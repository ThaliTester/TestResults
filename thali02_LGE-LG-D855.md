#### Test 82203060884b823_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-23 12:40:00.099  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 12:40:00.099  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 12:40:00.099  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 12:40:00.100  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-23 12:40:00.114  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 12:40:00.114  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-23 12:40:00.119  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-23 12:40:00.120  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 12:40:00.401  7087  7087 D AndroidRuntime: 
08-23 12:40:00.401  7087  7087 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 12:40:00.404  7087  7087 D AndroidRuntime: CheckJNI is OFF
08-23 12:40:00.529  7087  7087 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 12:40:00.534  1034  1050 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 12:40:00.544  1941  2942 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-23 12:40:00.548  1034  1050 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-23 12:40:00.549  1034  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{848e25 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 12:40:00.549  1034  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{848e25 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 12:40:00.550  1034  1050 D WindowStateEx: AppWindowTokenEx init.. 
08-23 12:40:00.551   347   352 E GBMv2   : DFP En is all cleared set to be enabled
08-23 12:40:00.582  1034  1050 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7106 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 12:40:00.585  7087  7087 D AndroidRuntime: Shutting down VM
08-23 12:40:00.664  1941  2942 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-23 12:40:00.664  1941  2942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{5706e2b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 12:40:00.665  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-23 12:40:00.666  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{32b23288 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 12:40:00.731  7106  7106 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-23 12:40:00.828  7106  7106 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-23 12:40:00.838  7106  7106 I LibraryLoader: Loading: webviewchromium
08-23 12:40:00.842  7106  7106 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8311-8315)
,08-23 12:40:00.842  7106  7106 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 12:40:00.860  7106  7106 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {358cf89b}
,08-23 12:40:00.862  7106  7106 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 12:40:00.862  7106  7106 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 12:40:00.874  7106  7106 I BrowserStartupController: Initializing chromium process, renderers=0
08-23 12:40:00.875  7106  7106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:40:00.890  7106  7106 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-23 12:40:00.891  7106  7106 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-23 12:40:00.892  7106  7106 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-23 12:40:00.898   326  2126 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-23 12:40:00.903  1034  1102 D BluetoothManagerService: Message: 20
08-23 12:40:00.903  1034  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3627f187:true
,08-23 12:40:00.912  7106  7106 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 12:40:00.912  7106  7106 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 12:40:00.912  7106  7106 I Adreno-EGL: Build Date: 12/12/14 금
08-23 12:40:00.912  7106  7106 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 12:40:00.912  7106  7106 I Adreno-EGL: Remote Branch: 
08-23 12:40:00.912  7106  7106 I Adreno-EGL: Local Patches: 
08-23 12:40:00.912  7106  7106 I Adreno-EGL: Reconstruct Branch: 
08-23 12:40:00.983  7106  7143 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-23 12:40:00.995  7106  7106 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-23 12:40:01.022  7106  7106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:40:01.028  7106  7106 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 12:40:01.030  7106  7106 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 12:40:01.033  7106  7106 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
,08-23 12:40:01.033  7106  7106 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-23 12:40:01.047  7106  7106 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-23 12:40:01.057  7106  7106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 12:40:01.057  7106  7106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:40:01.128  7106  7155 D OpenGLRenderer: Render dirty regions requested: true
,08-23 12:40:01.128  7106  7155 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 12:40:01.141  7106  7155 D OpenGLRenderer: Enabling debug mode 0
,08-23 12:40:01.150  7106  7106 D Atlas   : Validating map...
08-23 12:40:01.154  1034  1574 D SplitWindow: check instance of lgWin Window{16b3fb49 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 12:40:01.162  1034  1091 W ActivityManager: Activity pause timeout for ActivityRecord{315dfbfa u0 com.test.thalitest/.MainActivity t6}
,08-23 12:40:01.224  7106  7153 D LgDataFeature: LgDataFeature() Constructor: none
08-23 12:40:01.224  7106  7153 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 12:40:01.255  7106  7106 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4ea7426 time:178728
,08-23 12:40:01.279  1034  1103 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +617ms (total +727ms)
08-23 12:40:01.280  1034  1103 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{315dfbfa u0 com.test.thalitest/.MainActivity t6} time:178753
,08-23 12:40:01.474  7106  7106 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 12:40:01.541  7106  7153 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-23 12:40:01.541  7106  7153 I chromium: 
,08-23 12:40:01.705  7106  7169 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
,08-23 12:40:01.716  7106  7106 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-23 12:40:01.716  7106  7106 I chromium: 
08-23 12:40:01.726  7106  7169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 12:40:01.726  7106  7169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 12:40:01.726  7106  7169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 12:40:01.726  7106  7169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 12:40:01.726  7106  7169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 12:40:01.727  7106  7169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e6200a added. We now have 1 listener(s)
08-23 12:40:01.735  1034  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:01.741  7106  7169 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-23 12:40:01.745  7106  7169 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 12:40:01.747  7106  7169 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:01.747  7106  7169 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 12:40:01.756  7106  7169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d2226f1 added. We now have 1 listener(s)
,08-23 12:40:01.757  7106  7169 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:01.766  1034  1405 D WifiService: New client listening to asynchronous messages
08-23 12:40:01.771  7106  7169 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:40:01.771  7106  7169 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 12:40:01.773  7106  7169 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 12:40:01.774  7106  7169 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 12:40:01.774  7106  7169 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 12:40:01.778  7106  7169 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:01.778  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:01.779  7106  7169 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-23 12:40:01.790  7106  7169 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 12:40:01.790  7106  7169 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:01.790  7106  7169 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:01.790  7106  7169 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:01.790  7106  7169 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:01.790  7106  7169 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:01.790  7106  7169 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:01.790  7106  7169 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:01.790  7106  7169 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:01.790  7106  7169 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-23 12:40:01.792  7106  7169 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:40:01.795  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:01.795  7106  7169 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 12:40:01.798  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:01.841  7106  7106 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 12:40:02.409   347   354 E GBMv2   : DFP En is all cleared set to be enabled
,08-23 12:40:02.409   347   354 E GBMv2   : Set value is all cleared set the max
08-23 12:40:02.409   347   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-23 12:40:02.603  7106  7172 W jxcore-log: Initializing JXcore engine
08-23 12:40:02.603  7106  7172 W jxcore-log: JXcore engine is ready
,08-23 12:40:02.680  7172  7172 W Thread-832: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7772]" dev="sockfs" ino=7772 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-23 12:40:02.680  7172  7172 W Thread-832: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-23 12:40:02.680  7172  7172 W Thread-832: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7868]" dev="sockfs" ino=7868 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 12:40:02.680  7172  7172 W Thread-832: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-23 12:40:02.680  7172  7172 W Thread-832: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34852]" dev="sockfs" ino=34852 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-23 12:40:02.709  7106  7172 W jxcore-log: Starting JXcore engine
,08-23 12:40:02.831  7106  7172 W jxcore-log: Platform android
08-23 12:40:02.831  7106  7172 W jxcore-log: 
08-23 12:40:02.831  7106  7172 W jxcore-log: Process ARCH arm
08-23 12:40:02.831  7106  7172 W jxcore-log: 
,08-23 12:40:03.053  7106  7172 I jxcore-log: JXcore Cordova bridge is ready!
08-23 12:40:03.053  7106  7172 I jxcore-log: 
08-23 12:40:03.053  7106  7172 W jxcore-log: JXcore engine is started
,08-23 12:40:03.063  7106  7169 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-23 12:40:03.069  7106  7106 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 12:40:12.728  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 12:40:12.728  7106  7172 I jxcore-log: 
,08-23 12:40:12.731  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 12:40:12.731  7106  7172 I jxcore-log: 
08-23 12:40:12.735  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:12.735  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:12.735  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:12.735  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:12.735  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:12.735  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:12.735  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:12.735  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:12.737  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:12.739  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 12:40:12.739  7106  7172 I jxcore-log: 
08-23 12:40:12.741  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 12:40:12.741  7106  7172 I jxcore-log: 
,08-23 12:40:13.245  7106  7172 D ExecuteNativeTests: Running unit tests
,08-23 12:40:13.328  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:40:13.328  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a added. We now have 2 listener(s)
08-23 12:40:13.329  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:13.331  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 12:40:13.331  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:13.331  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:13.331  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:13.331  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b added. We now have 2 listener(s)
,08-23 12:40:13.331  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:13.332  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 12:40:13.334  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:13.337  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:13.337  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:13.337  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:13.337  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:13.337  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:13.337  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.337  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:13.337  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:13.338  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.338  7106  7172 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:40:13.339  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.340  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.343  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 12:40:13.343  7106  7172 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 12:40:13.343  7106  7172 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 12:40:13.347  7106  7172 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-23 12:40:13.348  7106  7172 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 12:40:13.348  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 12:40:13.348  7106  7172 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 12:40:13.348  7106  7172 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 12:40:13.348  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.349  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 12:40:13.349  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.349  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.349  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.349  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:40:13.349  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-23 12:40:13.350  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a removed from the list
08-23 12:40:13.350  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.350  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b removed from the list
08-23 12:40:13.350  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.350  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.350  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.350  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.351  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.351  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.351  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.351  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.352  7106  7172 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-23 12:40:13.352  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.353  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.353  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.353  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.353  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.353  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.353  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.353  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.353  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.353  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.353  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.353  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.353  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.353  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.354  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.354  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.354  7106  7,172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.354  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.358  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 12:40:13.358  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 12:40:13.358  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 12:40:13.358  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 12:40:13.358  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 12:40:13.358  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 12:40:13.358  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 12:40:1,3.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 12:40:13.359  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 12:40:13.359  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.359  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.359  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.359  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.359  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.360  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.360  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.360  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.360  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.360  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.360  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.360  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.360  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.360  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.362  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.362  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.362  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.362  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.363  7106  7172 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 12:40:13.364  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:13.366  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:13.366  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:13.366  7106,  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:13.366  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:13.366  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:13.366  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.366  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:13.366  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:40:13.369  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.369  7106  7172 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:40:13.373  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:40:13.373  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:40:13.373  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:40:13.373  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:13.373  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 12:40:13.375  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.376  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.378  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 12:40:13.378  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:13.381  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:40:13.385  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 12:40:13.387  7106  7172 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 12:40:13.387  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:40:13.387  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:13.388  7106  7172 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 12:40:13.388  7106  7172 I io.jxcore.node.ConnectionHelper: start: OK
08-23 12:40:13.390  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.390  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.391  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.391  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.391  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.391  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:13.391  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.391  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.391  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.391  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.391  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.391  7106  7172 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 12:40:13.392  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:13.394  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:13.394  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:13.394  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:13.394  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:13.394  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:13.394  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.394  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:13.394  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:40:13.395  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.395  7106  7172 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:40:13.396  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.397  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:40:13.397  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:40:13.397  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:40:13.397  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:13.397  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 12:40:13.397  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.401  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:40:13.401  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:13.402  7106  7172 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 12:40:13.402  7106  7172 I io.jxcore.node.ConnectionHelper: start: OK
08-23 12:40:13.404  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.404  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.404  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.404  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.404  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.404  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:13.404  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.404  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.404  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.404  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.404  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.404  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.404  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.405  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 12:40:13.405  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.406  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.406  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.406  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.406  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.407  7106  7172 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 12:40:13.408  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:13.410  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:13.410  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:13.410  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:13.410  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:13.410  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:13.410  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.410  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:13.410  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:13.411  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.411  7106  7172 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:40:13.412  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.412  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:40:13.412  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:40:13.412  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:40:13.412  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:13.412  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 12:40:13.413  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.415  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:40:13.415  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:13.416  7106  7172 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-23 12:40:13.416  7106  7172 I io.jxcore.node.ConnectionHelper: start: OK
08-23 12:40:13.416  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.416  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.416  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.417  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.417  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.417  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.417  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.417  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.417  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:13.418  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.418  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.418  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.418  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.418  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.418  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.418  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.419  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.419  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.419  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.419  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.419  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.419  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.419  7106  7172 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-23 12:40:13.420  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.420  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.420  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.420  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.420  7106  7172, W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.420  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.420  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.420  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.420  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.420  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.420  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.420  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.420  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.420  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.421  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.421  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.421  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.421  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.421  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.421  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.422  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 12:40:13.422  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.422  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.422  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.422  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.422  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.422  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.423  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.423  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.423  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.423  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.423  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.423  7106  7,172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.423  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.423  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.423  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.423  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.424  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.424  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.424  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.424  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.424  7106  7172 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-23 12:40:13.424  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.424  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.424  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.425  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.425  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.425  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.425  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.425  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.425  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.425  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.425  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.425  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.425  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.425  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.426  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.426  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.426  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.426  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.426  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.426  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2,c04228b not in the list
08-23 12:40:13.427  7106  7172 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-23 12:40:13.427  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.427  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.427  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.427  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.427  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.427  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.427  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.427  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.427  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.427  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.427  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.427  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.427  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.427  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.428  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.428  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.428  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.428  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.428  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.428  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.429  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 12:40:13.430  7106  7172 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 12:40:13.430  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 12:40:13.430  7106  7172 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 12:40:13.430  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 12:40:13.430  7106  7172 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 12:40:13.430  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.430  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.430  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.431  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.431  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.431  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.431  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.431  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.431  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.431  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.431  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.431  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.431  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.431  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.432  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.432  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.432  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.432  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.432  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.432  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.433  7106  7172 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:40:13.433  7106  7172 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 12:40:13.433  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 12:40:13.435  7106  7172 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:40:13.435  7106  7172 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 12:40:13.435  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 12:40:13.435  7106  7172 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-23 12:40:13.436  7106  7172 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 12:40:13.436  7106  7172 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-23 12:40:13.436  7106  7172 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:40:13.436  7106  7172 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 12:40:13.436  7106  7172 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-23 12:40:13.436  7106  7172 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:40:13.436  7106  7172 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 12:40:13.436  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-23 12:40:13.437  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-23 12:40:13.438  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-23 12:40:13.438  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-23 12:40:13.439  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-23 12:40:13.439  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-23 12:40:13.439  7106  7172 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-23 12:40:13.439  7106  7172 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:40:13.439  7106  7172 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-23 12:40:13.440  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.440  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.440  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.440  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.440  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.440  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.440  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-23 12:40:13.441  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.441  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.441  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.441  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.441  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.441  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.441  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.441  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.441  7106  7184 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 896)
08-23 12:40:13.442  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.442  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.442  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.442  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.442  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.442  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.443  7106  7172 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-23 12:40:13.443  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.443  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.443  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.443  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.443  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.443  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.443  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.443  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.443  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.443  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.443  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.443  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.443  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.443  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.444  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.444  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.445  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.445  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.445  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.445  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.445  7106  7172 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-23 12:40:13.446  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.446  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.446  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.447  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.447  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.447  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.447  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.447  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.447  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.447  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.447  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.447  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.447  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.447  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.447  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.447  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.448  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.448  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.448  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.448  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.449  7106  7172 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-23 12:40:13.449  7106  7172 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-23 12:40:13.449  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 12:40:13.449  7106  7172 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-23 12:40:13.451  7106  7172 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 12:40:13.451  7106  7172 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-23 12:40:13.451  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 12:40:13.451  7106  7172 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-23 12:40:13.452  7106  7172 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 12:40:13.452  7106  7172 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 12:40:13.452  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 12:40:13.452  7106  7172 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-23 12:40:13.452  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.452  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.452  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.454  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.454  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.454  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.454  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.454  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.454  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.454  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.454  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.455  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.455  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.456  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.457  7106  7185 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 896
08-23 12:40:13.457  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.457  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.457  7106  7185 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 896)
08-23 12:40:13.458  7106  7185 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 896)
08-23 12:40:13.466  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.466  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.466  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.466  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.467  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.467  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.467  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.467  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.467  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.467  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.467  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.467  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.467  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.468  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.468  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.468  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.468  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.468  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.468  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.468  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.468  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.468  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.468  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.468  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.468  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.468  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.468  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.468  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.468  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.468  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.468  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.468  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.468  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:40:13.473  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.473  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.474  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.474  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.475  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.475  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.477  7106  7172 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-23 12:40:13.477  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:13.478  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-23 12:40:13.479  7106  7172 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-23 12:40:13.479  7106  7172 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-23 12:40:13.479  7106  7106 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-23 12:40:13.480  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-23 12:40:13.480  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 12:40:13.481  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.481  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-23 12:40:13.481  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-23 12:40:13.481  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-23 12:40:13.481  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.481  7106  7172 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-23 12:40:13.481  7106  7106 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-23 12:40:13.483  7106  7186 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-23 12:40:13.483  7106  7186 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-23 12:40:13.484  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.484  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.484  7106  7106 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-23 12:40:13.484  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:40:13.484  7106  7172 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:40:13.484  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 12:40:13.486  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 12:40:13.487  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:13.487  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:13.487  7106  7172 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:40:13.487  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.487  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.488  7106  7172 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:40:13.488  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.488  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.488  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.488  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.489  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.489  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.489  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.489  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.489  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.489  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.489  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.489  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.489  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.489  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.489  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.490  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:40:13.490  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.490  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:40:13.490  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.490  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.490  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:40:13.490  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.491  7106  7172 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-23 12:40:13.492  7106  7172 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 12:40:13.492  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 12:40:13.492  7106  7172 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 12:40:13.492  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.492  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.492  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.492  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.492  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.492  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.492  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.492  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.493  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.493  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.493  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.493  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.493  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.493  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.493  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.493  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.493  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.493  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.495  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:13.495  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:13.497  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:13.497  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.497  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.497  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.497  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.497  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.497  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.497  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.497  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.497  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.497  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.497  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.497  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.497  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.497  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.498  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.498  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.498  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.498  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.499  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:13.499  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:13.499  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:13.499  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:13.500  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.500  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.500  7106  7172 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1641e05a not in the list
08-23 12:40:13.500  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:13.500  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.500  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:13.500  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.500  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.500  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:13.500  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:13.506  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:13.506  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:13.506  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 12:40:13.506  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c04228b not in the list
08-23 12:40:13.508  7106  7172 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-23 12:40:13.508  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 12:40:13.508  7106  7172 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-23 12:40:13.508  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 12:40:13.508  7106  7172 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-23 12:40:13.508  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 12:40:13.511  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 12:40:13.511  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-23 12:40:13.512  7106  7172 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-23 12:40:13.512  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 12:40:13.512  7106  7172 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-23 12:40:13.512  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 12:40:13.512  7106  7172 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-23 12:40:13.512  7106  7172 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-23 12:40:13.513  7106  7172 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-23 12:40:13.513  7106  7172 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-23 12:40:13.514  7106  7172 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-23 12:40:13.514  7106  7172 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-23 12:40:13.514  7106  7172 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-23 12:40:13.514  7106  7172 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-23 12:40:13.515  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:13.515  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a549380 added. We now have 2 listener(s)
08-23 12:40:13.515  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:13.516  7106  7172 D BluetoothAdapter: enable(): BT is already enabled..!
08-23 12:40:13.517  1034  1574 D WifiServiceImplEx: setWifiEnabled: true pid=7106, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 12:40:13.518  1034  1574 D WifiService: setWifiEnabled: true pid=7106, uid=10118
08-23 12:40:13.518  1034  1574 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 12:40:13.519  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:13.519  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ff3fdb9 added. We now have 3 listener(s)
08-23 12:40:13.519  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:13.523  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:13.523  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@84795fe added. We now have 4 listener(s)
08-23 12:40:13.523  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:13.525  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:13.525  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16a2715f added. We now have 5 listener(s)
08-23 12:40:13.525  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:13.527  1034  1772 D WifiServiceImplEx: setWifiEnabled: false pid=7106, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 12:40:13.527  1034  1772 D WifiService: setWifiEnabled: false pid=7106, uid=10118
08-23 12:40:13.527  1034  1772 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-23 12:40:13.529  7106  7184 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-23 12:40:13.529  7106  7184 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 896)
,08-23 12:40:13.536  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 12:40:13.537  1034  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:13.537  1034  1392 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-23 12:40:13.537  1034  1728 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@12e333b0 mBinding = false
08-23 12:40:13.537  1034  1392 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-23 12:40:13.538  1034  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-23 12:40:13.538  1034  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-23 12:40:13.538  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 12:40:13.538  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-23 12:40:13.539  1034  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-23 12:40:13.539  1034  1392 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-23 12:40:13.539  1034  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 12:40:13.539  1034  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 12:40:13.540  1034  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 12:40:13.540  1034  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-23 12:40:13.544  1034  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 12:40:13.544  1034  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.544  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.544  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 12:40:13.545  2742  2742 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 12:40:13.545  1034  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 12:40:13.545  1034  1392 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 12:40:13.546  1034  1392 D WifiNative-wlan0: SET ps 1: returned true
08-23 12:40:13.546  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 12:40:13.547  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 12:40:13.547  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-23 12:40:13.547  1034  2870 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.547   321   893 D CommandListener: Clearing all IP addresses on wlan0
08-23 12:40:13.547  1034  1102 D BluetoothManagerService: Message: 2
08-23 12:40:13.548  1034  1102 D BluetoothManagerService: Sending off request.
08-23 12:40:13.548  3909  3928 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-23 12:40:13.548  3909  3987 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-23 12:40:13.549  3909  3987 D BluetoothAdapterProperties: Setting state to 13
08-23 12:40:13.549  3909  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 12:40:13.549  3909  3987 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 12:40:13.549  3909  3987 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-23 12:40:13.550  1034  1102 D BluetoothManagerService: Message: 60
08-23 12:40:13.550  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-23 12:40:13.550  1034  1102 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-23 12:40:13.553  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:13.553  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 12:40:13.554  3909  3909 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:13.554  3909  3909 D BluetoothMapService: STATE_TURNING_OFF
08-23 12:40:13.554  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:13.556  3909  3909 V BtOppService: Receiver DISABLED_ACTION 
08-23 12:40:13.556  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:13.557  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:13.557  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:13.557  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:13.557  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:13.557  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:13.557  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.557  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:13.557  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:13.557  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:13.557  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.557  7106  7172 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:40:13.558  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.559  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.561  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:13.561  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:13.561  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:13.561  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:13.561  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:13.561  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:13.561  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.561  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:13.561  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:13.562  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check, when the Bluetooth is disabled - will return stored value
08-23 12:40:13.562  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:13.562  3909  3909 V BluetoothMapService: Handler(): got msg=4
08-23 12:40:13.562  3909  3909 D BluetoothMapService: MAP Service closeService in
08-23 12:40:13.562  3909  3909 D BluetoothMapMasInstance: MAP Service shutdown
08-23 12:40:13.564  3909  4230 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-23 12:40:13.564  3909  4230 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:40:13.564  3909  4230 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-23 12:40:13.564  3909  4230 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-23 12:40:13.564  3909  4230 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-23 12:40:13.564  3909  4230 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-23 12:40:13.564  3909  4230 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-23 12:40:13.564  3909  4230 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-23 12:40:13.564  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.565  3909  3909 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 12:40:13.565  3909  3909 V BluetoothMapService: MAP Service closeService out
08-23 12:40:13.565  3909  3909 I BtOppRfcommListener: stopping Accept Thread
08-23 12:40:13.565  3909  3909 V BtOppRfcommListener: close mBtServerSocket
08-23 12:40:13.565  3909  3909 V BtOppRfcommListener: waiting for thread to terminate
08-23 12:40:13.566  3909  4247 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:40:13.566  3909  4247 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 12:40:13.567  3909  3909 V BtOppRfcommListener: done waiting for thread to terminate
08-23 12:40:13.577  1034  1425 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-23 12:40:13.577  1034  1425 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-23 12:40:13.583  1034  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7192 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 12:40:13.585  1034  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:13.585  1034  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:13.586  1034  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:13.586  1034  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.586  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.586  1034  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2f1202b1
08-23 12:40:13.587  1034  1390 D LGWifiP2pService: P2pDisablingState
08-23 12:40:13.587  1034  1390 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.587  1034  1390 D LGWifiP2pService: p2p socket connection lost
08-23 12:40:13.587  1034  1390 D LGWifiP2pService: P2pDisabledState
08-23 12:40:13.589  3909  3990 D BluetoothAdapterProperties: Scan Mode:20
,08-23 12:40:13.589  3909  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-23 12:40:13.589  3909  3987 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 12:40:13.590  3909  4231 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:40:13.591  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-23 12:40:13.591  3909  4073 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-23 12:40:13.591  3909  3909 V BtOppService: onDestroy
08-23 12:40:13.591  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 12:40:13.591  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 12:40:13.591  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 12:40:13.592  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 12:40:13.592  3909  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:40:13.592  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 12:40:13.592  3909  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:40:13.592  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 12:40:13.592  3909  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 12:40:13.592  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-23 12:40:13.592  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-23 12:40:13.592  3909  4073 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-23 12:40:13.592  3909  4249 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:40:13.593  3909  4251 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:40:13.594  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-23 12:40:13.594  1034  1392 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 12:40:13.595  1034  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:13.595  1034  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:13.596  1034  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:13.597  1034  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-23 12:40:13.597  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.597  1034  1390 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.598  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 12:40:13.598  2742  2742 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 12:40:13.598  1034  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 12:40:13.598  1034  1392 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 12:40:13.599  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-23 12:40:13.600  1034  1392 D WifiNative-wlan0: SET ps 1: returned true
,08-23 12:40:13.603  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:13.603  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:13.603  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 12:40:13.603  1034  1958 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-23 12:40:13.604  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-23 12:40:13.604  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:13.604  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:13.604  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 12:40:13.604  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.604  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-23 12:40:13.604  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.604  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-23 12:40:13.604  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-23 12:40:13.604  1034  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.604  1034  1556 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.604  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.604  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-23 12:40:13.609  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 12:40:13.610  1941  1941 D WfdsService: WifiP2pState is changed : false
08-23 12:40:13.610  1941  2330 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-23 12:40:13.610  1941  2330 D WfdsService: Set the WFDS Monitor: false
08-23 12:40:13.611  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:13.611  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:13.611  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:13.611  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:13.611  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:13.611  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:13.611  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:13.611  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:13.611  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:13.612  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-2,3 12:40:13.612  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:40:13.613  1941  2330 D WfdsMonitor: WFDS Monitor is stopped
08-23 12:40:13.614  1941  2330 D WfdsService: STATE : WfdsDisabledState - enter
08-23 12:40:13.614   321   893 D CommandListener: Clearing all IP addresses on wlan0
08-23 12:40:13.614  1941  2332 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-23 12:40:13.614  1941  2782 D CtrlSupplicant: Received on exit socket, terminate
08-23 12:40:13.614  1941  2782 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-23 12:40:13.614  1941  2782 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-23 12:40:13.614  1941  2782 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-23 12:40:13.614  1034  1425 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-23 12:40:13.614  1034  1425 D DSQN    : disableDataServiceNotify
08-23 12:40:13.614  1034  1425 D DSQN    : stop dsqn bin
08-23 12:40:13.615  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:13.615  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:13.616  1941  2330 W WfdsService: DefaultState - msg [9445378] is not handled
08-23 12:40:13.617  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:13.617  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:13.617  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:13.617  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:13.617  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:13.617  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:13.617  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:13.617  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:13.617  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:13.617   321  7207 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-23 12:40:13.617  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:13.618  1034  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-23 12:40:13.618  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-23 12:40:13.618  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:13.618  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:40:13.619  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:13.619  1034  1425 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-23 12:40:13.619  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:13.619  1034  1425 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabili,ties: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:13.619  1034  1425 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 12:40:13.620  1034  1425 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 12:40:13.620  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:13.620  1034  1425 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-23 12:40:13.621  1034  1425 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-23 12:40:13.621  1034  1425 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-23 12:40:13.621  1034  1425 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 12:40:13.621  1602  1827 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-23 12:40:13.621  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.621  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.621  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-23 12:40:13.636  1034  1091 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7215 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-23 12:40:13.641  1034  1392 D WifiNative-p2p0: doBoolean: TERMINATE
08-23 12:40:13.641  1034  1392 D WifiNative-p2p0: TERMINATE: returned true
08-23 12:40:13.641  1034  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 12:40:13.641  1034  1392 E WifiStateMachine: useWiFiOffloading() : false
08-23 12:40:13.641  1034  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 12:40:13.642  1034  1425 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 12:40:13.642  1034  1425 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 12:40:13.642  1034  1425 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 12:40:13.642  1034  1425 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:13.642  1034  1425 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:13.642  3909  3909 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-23 12:40:13.642  1034  1425 D NetworkManagementService: Removing idletimer
08-23 12:40:13.643  1034  1425 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:13.643  1034  1425 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-23 12:40:13.644  1034  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-23 12:40:13.644  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-23 12:40:13.644  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:13.644  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:13.644  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 12:40:13.644  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-23 12:40:13.645  1034  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-23 12:40:13.646  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-23 12:40:13.646  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 12:40:13.646  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 12:40:13.646  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 12:40:13.646  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 12:40:13.646  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-23 12:40:13.646  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-23 12:40:13.646  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 12:40:13.646  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 12:40:13.646  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 12:40:13.647  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-23 12:40:13.647  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:13.647  1853  18,53 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 12:40:13.648  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:13.648  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:13.648  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:13.648  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:13.648  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:40:13.648  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:13.648  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:13.648  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:13.648  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:40:13.648  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:13.648  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:40:13.649  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-23 12:40:13.649  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:13.649  1034  1392 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:13.649  1034  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 12:40:13.651  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:13.651  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:13.651  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:13.651  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:13.651  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:40:13.651  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:13.651  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:13.651  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:13.651  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:40:13.651  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:13.651  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:40:13.652  1602  1602 D StatusBar.NetworkController: refreshViews: Data not conne,cted!! Set no data type icon / Roaming
08-23 12:40:13.665  7192  7192 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:40:13.666  7192  7192 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-23 12:40:13.666  7192  7192 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 12:40:13.666  7192  7192 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-23 12:40:13.669  7192  7192 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 12:40:13.670  7192  7192 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 12:40:13.682  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-23 12:40:13.683  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:13.683  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:13.684  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 12:40:13.704  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 12:40:13.706  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:13.706  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:13.725  7215  7215 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-23 12:40:13.725  7215  7215 W LG Account v2.2: No ProfileInfo entries
08-23 12:40:13.725  7215  7215 I LG Account v2.2: isEnabled: false
08-23 12:40:13.725  7215  7215 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-23 12:40:13.725  7215  7215 I Feature : [Lifetracker]Country: EU
08-23 12:40:13.725  7215  7215 I Feature : [Lifetracker]Operator: OPEN
08-23 12:40:13.725  7215  7215 I Feature : [Lifetracker]Ranking support: false
08-23 12:40:13.725  7215  7215 I Feature : [Lifetracker]Comfort support: false
08-23 12:40:13.725  7215  7215 I Feature : [Lifetracker]Accessory: true
08-23 12:40:13.726  7215  7215 I Feature : [Lifetracker]Health device: true
08-23 12:40:13.726  7215  7215 I Feature : [Lifetracker]Extra Pedometer: false
08-23 12:40:13.726  7215  7215 I Feature : [Lifetracker]Blood glucose device: false
08-23 12:40:13.726  7215  7215 I Feature : [Lifetracker]Device Number: 3
,08-23 12:40:13.732  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:13.760  2742  2742 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-23 12:40:13.760  2742  2742 I wpa_supplicant: monitor socket send errors count : 1
08-23 12:40:13.760  2742  2742 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
,08-23 12:40:13.761  1034  2870 D DhcpStateMachine: StoppedState
08-23 12:40:13.762  1034  2779 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-23 12:40:13.762  1034  2779 D WifiMonitor: Dropping event because (p2p0) is stopped
08-23 12:40:13.762  1034  2870 D DhcpStateMachine: StoppedState{ when=-161ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:13.763  1034  1904 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7237 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 12:40:13.764  7192  7192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 12:40:13.764  1034  1904 I ActivityManager: Killing 6709:com.qualcomm.timeservice/1000 (adj 15): empty #17
08-23 12:40:13.774   355   355 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 193us total 9.561ms
,08-23 12:40:13.784   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 212us total 9.333ms
08-23 12:40:13.795   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 9.885ms
,08-23 12:40:13.798  1034  1392 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-23 12:40:13.799  1034  1392 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-23 12:40:13.799  2742  2742 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 12:40:13.799  2742  2742 W wpa_supplicant: USIM:  scard_deinit function
08-23 12:40:13.799  1034  2779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-23 12:40:13.799  1034  2779 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 12:40:13.799  1034  2779 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-23 12:40:13.800  1034  2779 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-23 12:40:13.800  1034  2779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 12:40:13.800  1034  2779 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 12:40:13.800  1034  1392 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=191259
08-23 12:40:13.800  1034  1392 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=191259
08-23 12:40:13.800  1034  1102 D Tethering: InitialState.processMessage what=4
08-23 12:40:13.800  1034  1392 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=191260  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 12:40:13.801  1034  1392 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=191260  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 12:40:13.801  1034  1049 W libprocessgroup: failed to open /acct/uid_1000/pid_6709/cgroup.procs: No such file or directory
08-23 12:40:13.806  1034  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 12:40:13.806  1034  1102 D BluetoothManagerService: Message: 20
08-23 12:40:13.806  1034  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a4f756b:true
08-23 12:40:13.807  1034  1392 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:13.807  1034  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:13.807  3909  3909 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 12:40:13.807  3909  3909 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:13.808  3909  3909 V BluetoothPbapReceiver: ***********state = 13
08-23 12:40:13.809  3909  3909 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-23 12:40:13.810  3909  3909 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:13.810  3909  3909 V BluetoothPbapService: state: 13
08-23 12:40:13.810  3909  3909 V BluetoothPbapService: Pbap Service closeService in
08-23 12:40:13.812  3909  3909 V BluetoothPbapService: successfully stopped pbap service
08-23 12:40:13.812  3909  3909 V BluetoothPbapService: Pbap Service closeService out
08-23 12:40:13.812  3909  3909 V BluetoothPbapService: Pbap Service onDestroy
08-23 12:40:13.812  3909  3909 V BluetoothPbapService: Pbap Service closeService in
08-23 12:40:13.812  3909  3909 V BluetoothPbapService: Pbap Service closeService out
08-23 12:40:13.812  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 12:40:13.812  3909  3909 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-23 12:40:13.819  1034  1102 D BluetoothManagerService: Message: 30
08-23 12:40:13.822  1034  1102 D BluetoothManagerService: Message: 30
,08-23 12:40:13.824  7192  7192 D LocalBluetoothProfileManager: Adding local MAP profile
08-23 12:40:13.825  7192  7192 D BluetoothMap: Create BluetoothMap proxy object
08-23 12:40:13.825  1034  1102 D BluetoothManagerService: Message: 30
08-23 12:40:13.828  1034  1102 D BluetoothManagerService: Message: 30
08-23 12:40:13.830  7192  7192 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-23 12:40:13.830  7192  7192 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-23 12:40:13.839  7192  7192 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-23 12:40:13.840  7192  7192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-23 12:40:13.844  7237  7237 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 12:40:13.846  7192  7192 D DockEventReceiver: finishStartingService: stopping service
08-23 12:40:13.849  7237  7237 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 12:40:13.850  7237  7237 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 12:40:13.856  7192  7192 D BluetoothInputDevice: Proxy object connected
08-23 12:40:13.857  7192  7192 D HidProfile: Bluetooth service connected
,08-23 12:40:13.858  1034  1904 I ActivityManager: Killing 6729:com.android.calendar/u0a13 (adj 15): empty #17
08-23 12:40:13.858  7192  7192 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 12:40:13.858  7192  7192 D PanProfile: Bluetooth service connected
08-23 12:40:13.861  7192  7192 D BluetoothMap: Proxy object connected
08-23 12:40:13.862  7192  7192 D MapProfile: Bluetooth service connected
08-23 12:40:13.862  7192  7192 D BluetoothMap: getConnectedDevices()
08-23 12:40:13.862  7192  7192 D BluetoothMap: Bluetooth is Not enabled
08-23 12:40:13.863  7192  7192 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-23 12:40:13.877  2742  2742 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-23 12:40:13.878  1034  2779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-23 12:40:13.878  1034  2779 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-23 12:40:13.878  1034  2779 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-23 12:40:13.879  1034  1392 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-23 12:40:13.898  1034  1574 W libprocessgroup: failed to open /acct/uid_10013/pid_6729/cgroup.procs: No such file or directory
,08-23 12:40:13.907  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 12:40:13.946  7192  7192 D LgDataFeature: LgDataFeature() Constructor: none
08-23 12:40:13.946  7192  7192 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 12:40:13.959  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:13.963  7192  7192 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-23 12:40:13.973  7192  7192 D BluetoothPermissionRequest: onReceive
,08-23 12:40:13.978  7192  7192 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-23 12:40:13.980  1034  1392 D WifiOffDelayIfNotUsed: stopMonitoring
08-23 12:40:13.980  1034  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 12:40:13.980  1034  1392 E WifiStateMachine: useWiFiOffloading() : false
08-23 12:40:13.980  1034  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 12:40:13.983  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-23 12:40:13.983  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 12:40:13.984  1941  2330 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-23 12:40:13.984  1941  2330 D WfdsService: Set the WFDS Monitor: false
08-23 12:40:13.984  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:13.984  1941  2330 D WfdsMonitor: WFDS Monitor is stopped
08-23 12:40:13.986  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-23 12:40:13.987  1034  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-23 12:40:13.987  1034  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-23 12:40:13.987  6880  6880 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 12:40:13.991  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.991  2473  2473 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:13.994  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:13.995  7106  7106 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 12:40:14.008  1034  1958 I ActivityManager: Killing 6659:com.lge.clock/u0a10 (adj 15): empty #17
08-23 12:40:14.010  7192  7192 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 12:40:14.102  3909  3909 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-23 12:40:14.102  3909  3909 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-23 12:40:14.103  1034  1923 W libprocessgroup: failed to open /acct/uid_10010/pid_6659/cgroup.procs: No such file or directory
08-23 12:40:14.104  3909  3909 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-23 12:40:14.171  1034  2032 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7265 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-23 12:40:14.172  3909  3909 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:14.172  3909  3909 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-23 12:40:14.173  3909  3909 V BluetoothFtpService: Ftp Service onStartCommand
08-23 12:40:14.173  3909  3909 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:14.173  3909  3909 V BluetoothFtpService: Ftp Service closeService
08-23 12:40:14.174  3909  3909 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-23 12:40:14.177  3909  3909 V BluetoothFtpService: successfully stopped ftp service
08-23 12:40:14.177  3909  3909 V BluetoothFtpService: Ftp Service onDestroy
08-23 12:40:14.177  3909  3909 V BluetoothFtpService: Ftp Service closeService
08-23 12:40:14.183  3909  3909 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 12:40:14.183  3909  3909 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 12:40:14.183  3909  3909 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 12:40:14.183  3909  3909 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:14.183  3909  3909 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-23 12:40:14.183  3909  3909 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-23 12:40:14.188  3909  3909 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:14.188  3909  3909 V BluetoothSapService: state: 13
08-23 12:40:14.188  3909  3909 V BluetoothSapService: Stopping SAP server process
08-23 12:40:14.189  3909  3909 V BluetoothSapService: Sap Service closeSapService in
08-23 12:40:14.190  3909  3909 V BluetoothSapService: Close listen Socket : 
08-23 12:40:14.190  3909  3909 V BluetoothSapService: Close rfcomm Socket : 
08-23 12:40:14.190  3909  3909 V BluetoothSapService: Close sapd  Socket : 
08-23 12:40:14.248  1034  2033 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7282 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 12:40:14.249  3909  3909 V BluetoothSapService: Sap Service closeSapService out
08-23 12:40:14.250  3909  3909 V BluetoothSapService: Sap Service onDestroy
08-23 12:40:14.250  3909  3909 V BluetoothSapService: Sap Service closeSapService in
08-23 12:40:14.250  3909  3909 V BluetoothSapService: Close listen Socket : 
08-23 12:40:14.250  3909  3909 V BluetoothSapService: Close rfcomm Socket : 
08-23 12:40:14.250  3909  3909 V BluetoothSapService: Close sapd  Socket : 
08-23 12:40:14.259  3909  3909 V BluetoothSapService: Sap Service closeSapService out
08-23 12:40:14.280  7265  7265 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 12:40:14.311  7265  7265 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-23 12:40:14.312  7282  7282 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 12:40:14.330  1034  1974 I ActivityManager: Killing 6683:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-23 12:40:14.357  7265  7265 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-23 12:40:14.358  7265  7265 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-23 12:40:14.358  7265  7265 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-23 12:40:14.358  7265  7265 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-23 12:40:14.359  7265  7265 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-23 12:40:14.361  7265  7265 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-23 12:40:14.367  7265  7265 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-23 12:40:14.378  1034  1771 W libprocessgroup: failed to open /acct/uid_10085/pid_6683/cgroup.procs: No such file or directory
,08-23 12:40:14.390  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 12:40:14.398  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:14.424  7265  7265 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 12:40:14.426  7265  7265 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-23 12:40:14.429  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 12:40:14.432  7265  7265 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-23 12:40:14.435  7237  7237 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 12:40:14.435  7237  7237 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 12:40:14.435  7237  7237 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 12:40:14.444  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 12:40:14.451  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:14.461  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:14.461  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:14.463  7265  7265 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-23 12:40:14.466  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:14.473  7237  7237 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 12:40:14.473  7237  7237 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 12:40:14.474  7237  7237 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 12:40:14.477  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 12:40:14.486  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:14.501  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:14.501  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:14.503  7265  7265 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-23 12:40:14.581  1034  1574 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7305 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-23 12:40:14.597  3909  4073 W bt-btif : ag scb idx 1 not allocated
08-23 12:40:14.597  3909  3990 D bt_hci_bdroid: cleanup
08-23 12:40:14.597  3909  4073 E bt-btif : BTA AG is already disabled, ignoring ...
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 12:40:14.597  3909  4076 I bt_lpm  : LPM is already off!!!
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 12:40:14.597  3909  4192 I bt_userial_mct: exiting userial_read_thread
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:40:14.597  3909  4192 D bt_userial_mct: Leaving userial_evt_read_thread()
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 12:40:14.597  3909  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 12:40:14.597  3909  4073 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-23 12:40:14.597  3909  3990 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-23 12:40:14.597  3909  4076 I bt_vendor: hw_epilog_process
08-23 12:40:14.598  3909  3990 D bt_hci_bdroid: cleanup Finalizing cleanup
08-23 12:40:14.598  3909  3990 D bt_userial_mct: userial_close
08-23 12:40:14.598  3909  3990 E bt_userial_mct: pthread_join() FAILED result:3
08-23 12:40:14.598  3909  3990 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-23 12:40:14.667  7237  7237 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 12:40:14.676  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 12:40:14.683  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:14.690  3909  3990 D bt_hci_bdroid: set_power 0
08-23 12:40:14.690  3909  3990 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 12:40:14.690  3909  3990 I bt_vendor: bluetooth satus is on
08-23 12:40:14.690  3909  3990 I bt_vendor: bt-vendor : resetting BT status
08-23 12:40:14.690  3909  3990 I bt_vendor: Starting hciattach daemon
08-23 12:40:14.690  3909  3990 I bt_vendor: try to set false
08-23 12:40:14.690  3909  3990 I bt_vendor: Starting hciattach daemon
08-23 12:40:14.691  3909  3990 I bt_vendor: try to set false
08-23 12:40:14.691  3909  3990 I bt_vendor: cleanup
,08-23 12:40:14.692  3909  4073 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-23 12:40:14.693  3909  3990 I GKI_LINUX: GKI_exit_task 0 done
08-23 12:40:14.693  3909  3990 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-23 12:40:14.695  3909  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-23 12:40:14.698  3909  3909 D HeadsetService: Received stop request...Stopping profile...
08-23 12:40:14.700  3909  3909 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 12:40:14.700  3909  3909 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 12:40:14.700  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23a74438
08-23 12:40:14.701  3909  4017 D HeadsetStateMachine: Exit Disconnected: -1
08-23 12:40:14.702  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-23 12:40:14.702  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-23 12:40:14.703  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-23 12:40:14.703  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-23 12:40:14.703  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-23 12:40:14.706  3909  3909 D A2dpService: Received stop request...Stopping profile...
08-23 12:40:14.706  3909  4056 D A2dpStateMachine: Exit Disconnected: -1
08-23 12:40:14.706  3909  3909 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-23 12:40:14.709  3909  3909 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-23 12:40:14.709  3909  3909 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 12:40:14.709  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23a74438
08-23 12:40:14.710  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-23 12:40:14.711  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-23 12:40:14.711  3909  3987 D BluetoothAdapterState: Stopping profile services that were post enabled
08-23 12:40:14.712  3909  3909 D HidService: Received stop request...Stopping profile...
08-23 12:40:14.712  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23a74438
08-23 12:40:14.714  3909  3909 D HealthService: Received stop request...Stopping profile...
08-23 12:40:14.714  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23a74438
08-23 12:40:14.713  7192  7192 D BluetoothInputDevice: Proxy object disconnected
08-23 12:40:14.716  7305  7325 W FormManager: Network not available. Please check & try again.
08-23 12:40:14.716  7192  7192 D HidProfile: Bluetooth service disconnected
,08-23 12:40:14.719  3909  3909 D HeadsetStateMachine: Unbinding service...
08-23 12:40:14.719  3909  3909 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 12:40:14.719  3909  3909 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 12:40:14.719  3909  3909 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 12:40:14.719  3909  3909 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 12:40:14.720  3909  3909 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 12:40:14.720  3909  3909 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 12:40:14.720  3909  3909 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 12:40:14.720  3909  3909 D PanService: Received stop request...Stopping profile...
08-23 12:40:14.721  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23a74438
08-23 12:40:14.722  7305  7326 V FormManager: Network unavailable.
08-23 12:40:14.722  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 12:40:14.722  3909  3909 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 12:40:14.723  3909  3909 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 12:40:14.723  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 12:40:14.723  3909  3909 D BtGatt.GattService: stop()
08-23 12:40:14.723  3909  3909 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 12:40:14.723  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 12:40:14.723  7192  7192 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 12:40:14.724  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23a74438
08-23 12:40:14.725  3909  3909 D BluetoothMapService: Received stop request...Stopping profile...
08-23 12:40:14.725  3909  3909 D BluetoothMapService: stop()
08-23 12:40:14.725  7305  7326 V FormManager: Network unavailable.
08-23 12:40:14.725  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 12:40:14.725  3909  3909 D BluetoothMapEmailAppObserver: deinitObservers()
08-23 12:40:14.726  3909  3909 D BluetoothMapEmailAppObserver: removeReceiver()
08-23 12:40:14.726  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23a74438
08-23 12:40:14.727  3909  3909 I BluetoothA2dpServiceJni: cleanupNative
08-23 12:40:14.727  3909  4057 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-23 12:40:14.727  3909  3909 I GKI_LINUX: GKI_exit_task 2 done
08-23 12:40:14.728  3909  3909 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-23 12:40:14.728  3909  3909 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 12:40:14.728  3909  3909 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 12:40:14.728  3909  3909 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 12:40:14.729  3909  3909 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 12:40:14.729  3909  3909 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 12:40:14.729  3909  3909 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 12:40:14.729  3909  3909 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-23 12:40:14.730  3909  3909 V BluetoothMapService: Handler(): got msg=4
08-23 12:40:14.730  3909  3909 D BluetoothMapService: MAP Service closeService in
08-23 12:40:14.730  3909  3909 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 12:40:14.730  3909  3909 V BluetoothMapService: MAP Service closeService out
08-23 12:40:14.730  3909  3909 D BluetoothMapService: cleanup()
08-23 12:40:14.730  3909  3909 D BluetoothMapService: MAP Service closeService in
08-23 12:40:14.730  3909  3909 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 12:40:14.730  3909  3909 V BluetoothMapService: MAP Service closeService out
08-23 12:40:14.733  3909  3987 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-23 12:40:14.733  3909  3987 D BluetoothAdapterProperties: Setting state to 10
08-23 12:40:14.733  3909  3987 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-23 12:40:14.734  1034  1102 D BluetoothManagerService: Message: 60
08-23 12:40:14.734  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-23 12:40:14.734  1034  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-23 12:40:14.734  1034  1102 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:40:14.734  3909  3987 I BluetoothAdapterState: Entering OffState
08-23 12:40:14.734  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:40:14.735  1853  2671 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:40:14.735  1853  4467 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:40:14.736  7192  7213 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 12:40:14.736  1034  1102 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:40:14.737  7192  7228 D BluetoothMap: onBluetoothStateChange: up=false
08-23 12:40:14.737  7192  7214 D BluetoothPan: onBluetoothStateChange on: false
08-23 12:40:14.738  7192  7224 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 12:40:14.739  1034  1102 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-23 12:40:14.739  1034  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-23 12:40:14.741  1034  1102 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-23 12:40:14.742  1034  1102 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-23 12:40:14.742  1034  1102 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@12e333b0 mBinding = false
08-23 12:40:14.742  1034  1102 D BluetoothManagerService: Sending unbind request.
,08-23 12:40:14.747  1034  1102 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-23 12:40:14.750  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 12:40:14.752  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:14.752  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:14.753  1941  2149 D LGBluetoothAPIService: Message: 2
08-23 12:40:14.753  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:14.753  1941  2149 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3e752421 mBinding = false
08-23 12:40:14.753  1941  2149 D LGBluetoothAPIService: Sending unbind request.
08-23 12:40:14.755  1602  1602 D BluetoothAdapter: 253161107: getState() :  mService = null. Returning STATE_OFF
08-23 12:40:14.755  1602  1602 D BluetoothAdapter: 253161107: getState() :  mService = null. Returning STATE_OFF
,08-23 12:40:14.757  7192  7192 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 12:40:14.758  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-23 12:40:14.758  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 12:40:14.758  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 12:40:14.758  7192  7192 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 12:40:14.758  7192  7192 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 12:40:14.759  7192  7192 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 12:40:14.760  7192  7192 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-23 12:40:14.760  7192  7192 D LGBluetoothEventManager: [BTUI] clear device connection state
08-23 12:40:14.761  3909  3990 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-23 12:40:14.762  3909  3909 I GKI_LINUX: GKI_exit_task 1 done
08-23 12:40:14.763  3909  3909 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-23 12:40:14.763  3909  3909 I BluetoothServiceJni: cleanupNative: return from cleanup
08-23 12:40:14.763  3909  3909 I art     : --- WEIRD: removing null entry 246
08-23 12:40:14.763  3909  3909 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-23 12:40:14.763  1034  1771 I ActivityManager: Killing 6568:com.lge.bnr/1000 (adj 15): empty #17
08-23 12:40:14.764  3909  3909 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-23 12:40:14.765  7192  7192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 12:40:14.812  3909  3909 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-23 12:40:14.816  1034  1958 W libprocessgroup: failed to open /acct/uid_1000/pid_6568/cgroup.procs: No such file or directory
08-23 12:40:14.820  3909  3909 I art     : System.exit called, status: 0
08-23 12:40:14.820  3909  3909 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-23 12:40:14.827  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-23 12:40:14.827  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 12:40:14.832  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 12:40:14.833  7192  7192 D DockEventReceiver: finishStartingService: stopping service
08-23 12:40:14.839  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 12:40:14.850  4348  7337 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-23 12:40:14.851  7237  7237 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-23 12:40:14.851  7237  7237 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 12:40:14.851  7237  7237 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 12:40:14.855  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 12:40:14.857   326  1403 V AudioFlinger: 3909 died, releasing its sessions
08-23 12:40:14.857   326  1403 V AudioFlinger:  pid 1853 @ 0
08-23 12:40:14.857   326  1403 V AudioFlinger:  pid 3445 @ 1
08-23 12:40:14.857   326  1403 V AudioFlinger:  pid 3445 @ 2
08-23 12:40:14.859  4348  7338 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 12:40:14.860  4348  7338 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-23 12:40:14.867  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:14.867  7192  7192 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-23 12:40:14.876  1034  1974 I ActivityManager: Process com.android.bluetooth (pid 3909) has died
08-23 12:40:14.877  1034  1974 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-23 12:40:14.884  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 12:40:14.901  7305  7340 W FormManager: Network not available. Please check & try again.
,08-23 12:40:14.911  7305  7341 V FormManager: Network unavailable.
08-23 12:40:14.914  7192  7192 D BluetoothPermissionRequest: onReceive
,08-23 12:40:14.918  7305  7341 V FormManager: Network unavailable.
08-23 12:40:14.925  7192  7192 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-23 12:40:14.925  7192  7192 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-23 12:40:14.930  7192  7192 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 12:40:14.936  7265  7265 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-23 12:40:14.939  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-23 12:40:14.939  7265  7265 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-23 12:40:14.991  7265  7265 D LgDataFeature: LgDataFeature() Constructor: none
,08-23 12:40:14.991  7265  7265 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 12:40:15.002  7265  7265 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-23 12:40:15.007  7265  7265 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-23 12:40:15.007  7265  7265 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-23 12:40:15.007  7265  7265 V SoundPool: doLoad: loading sample sampleID=1
,08-23 12:40:15.010  7265  7265 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-23 12:40:15.011  1034  1574 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7344 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-23 12:40:15.011  7265  7345 V SoundPool: Start decode
08-23 12:40:15.011  7265  7345 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-23 12:40:15.016   326  2127 V MediaPlayerService: decode(23, 10857164, 17813)
08-23 12:40:15.016   326  2127 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-23 12:40:15.016   326  2127 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-23 12:40:15.016   326  2127 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-23 12:40:15.016   326  2127 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-23 12:40:15.016   326  2127 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-23 12:40:15.016   326  2127 V MediaPlayerService: player type = 3
08-23 12:40:15.016   326  2127 V AwesomePlayer: AwesomePlayer create()
08-23 12:40:15.017   326  2127 V AwesomePlayer: reset_l() 
08-23 12:40:15.017   326  2127 V AwesomePlayer: cancelPlayerEvents
08-23 12:40:15.017   326  2127 V AwesomePlayer: setAudioSink() 
08-23 12:40:15.017   326  2127 V AwesomePlayer: reset_l() 
08-23 12:40:15.017   326  2127 V AudioCache: notify(0xb1432480, 8, 0, 0)
08-23 12:40:15.018   326  2127 V AudioCache: ignored
08-23 12:40:15.018   326  2127 V AwesomePlayer: cancelPlayerEvents
08-23 12:40:15.018   326  2127 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-23 12:40:15.018   326  2127 V AwesomePlayer: setDataSource_l dataSource
08-23 12:40:15.018   326  2127 V LGParserOSAL: SniffLGParser start
08-23 12:40:15.018   326  2127 V LGParserOSAL: MainType:5, SubType=0
08-23 12:40:15.018   326  2127 V LGParserOSAL: #### check Mime : application/ogg
08-23 12:40:15.018   326  2127 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-23 12:40:15.019   326  2127 E MediaExtractor: Use LGExtractor :application/ogg 
08-23 12:40:15.067  1034  1958 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7362 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 12:40:15.068  7265  7265 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-23 12:40:15.073  7265  7265 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-23 12:40:15.074  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-23 12:40:15.079   326  2127 V LGParserOSAL: supported mime: application/ogg
08-23 12:40:15.080   326  2127 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-23 12:40:15.080   326  2127 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-23 12:40:15.080   326  2127 V AwesomePlayer: mBitrate = -1 bits/sec
08-23 12:40:15.080   326  2127 V AwesomePlayer: AudioTrack Setting
08-23 12:40:15.080   326  2127 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-23 12:40:15.080   326  2127 V AwesomePlayer: setAudioSource() 
08-23 12:40:15.080   326  2127 V MediaPlayerService: prepare
08-23 12:40:15.080   326  2127 V AwesomePlayer: prepareAsync_l() 
08-23 12:40:15.080   326  2127 V MediaPlayerService: wait for prepare
,08-23 12:40:15.086   326  7373 V AwesomePlayer: onPrepareAsyncEvent() 
08-23 12:40:15.087   326  7373 V AwesomePlayer: initAudioDecoder() 
08-23 12:40:15.087   326  7373 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-23 12:40:15.087   326  7373 V AudioSystem: isOffloadSupported()
08-23 12:40:15.087   326  7373 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-23 12:40:15.087   326  7373 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-23 12:40:15.087   326  7373 I AudioFlinger: isAudioPlaybackHookOn() false
08-23 12:40:15.087   326  7373 V AwesomePlayer: getUseOffload() = 0 
08-23 12:40:15.087   326  7373 V OMXCodec: OMXCodec::Create
08-23 12:40:15.087   326  7373 V OMXCodec: findMatchingCodecs()
08-23 12:40:15.087   326  7373 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-23 12:40:15.087   326  7373 V OMXCodec: matchingCodecs.size()=1
08-23 12:40:15.087   326  7373 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-23 12:40:15.089   326  7373 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-23 12:40:15.089   326  7373 V LGCodecAdapter: LG Codec Adapter start
08-23 12:40:15.089   326  7373 V OMXCodec: OMXCodec Createtor
08-23 12:40:15.089   326  7373 V OMXCodec: setComponentRole
08-23 12:40:15.089   326  7373 V OMXCodec: configureCodec protected=0
08-23 12:40:15.089   326  7373 V LGCodecAdapter: called getLGCodecSpecificData
08-23 12:40:15.089   326  7373 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-23 12:40:15.089   326  7373 V LGCodecOSAL: Called LGconfigureCodecMETA
08-23 12:40:15.090   326  7373 V LGCodecOSAL: Called LGconfigureCodecMSG
08-23 12:40:15.090   326  7373 V LGCodecOSAL: Not support LGCodec
08-23 12:40:15.090   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-23 12:40:15.090   326  7373 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-23 12:40:15.090   326  7373 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-23 12:40:15.090   326  7373 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-23 12:40:15.090   326  7373 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-23 12:40:15.090   326  7373 V AudioSystem: isOffloadSupported()
08-23 12:40:15.090   326  7373 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-23 12:40:15.090   326  7373 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-23 12:40:15.090   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-23 12:40:15.090   326  7373 V OMXCodec: init()
08-23 12:40:15.090   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-23 12:40:15.090   326  7373 V OMXCodec: allocateBuffers
08-23 12:40:15.090   326  7373 V OMXCodec: allocateBuffersOnPort portIndex=0
08-23 12:40:15.090   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-23 12:40:15.090   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-23 12:40:15.090   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-23 12:40:15.090   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-23 12:40:15.090   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-23 12:40:15.090   32,6  7373 V OMXCodec: allocateBuffersOnPort portIndex=1
08-23 12:40:15.090   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-23 12:40:15.091   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-23 12:40:15.091   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-23 12:40:15.091   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-23 12:40:15.091   326  7373 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-23 12:40:15.091   326  7373 V OMXCodec: init() mAsyncCompletion wait!!! 
08-23 12:40:15.093   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-23 12:40:15.093   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-23 12:40:15.093   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-23 12:40:15.094   326  7373 V OMXCodec: init() mAsyncCompletion wait!!! 
08-23 12:40:15.095   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-23 12:40:15.095   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-23 12:40:15.095   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-23 12:40:15.095   326  7373 V OMXCodec: init() mAsyncCompletion wait free! 
08-23 12:40:15.095   326  7373 V AwesomePlayer: finishAsyncPrepare_l() 
08-23 12:40:15.095   326  7373 V AudioCache: notify(0xb1432480, 5, 0, 0)
08-23 12:40:15.095   326  7373 V AudioCache: ignored
08-23 12:40:15.095   326  7373 V AudioCache: notify(0xb1432480, 1, 0, 0)
08-23 12:40:15.095   326  7373 V AudioCache: prepared
08-23 12:40:15.095   326  2127 V AudioCache: wait - success
08-23 12:40:15.095   326  2127 V MediaPlayerService: start
08-23 12:40:15.095   326  2127 V AwesomePlayer: play_l() 
08-23 12:40:15.095   326  2127 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-23 12:40:15.095   326  2127 V AwesomePlayer: createAudioPlayer_l
08-23 12:40:15.095   326  2127 V AwesomePlayer: seekAudioIfNecessary_l() 
08-23 12:40:15.095   326  2127 V AwesomePlayer: startAudioPlayer_l() 
08-23 12:40:15.095   326  2127 D AudioPlayer: start of Playback, useOffload 0
08-23 12:40:15.096   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-23 12:40:15.096   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-23 12:40:15.098   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-23 12:40:15.098   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-23 12:40:15.098   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-23 12:40:15.099  7344  7344 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-23 12:40:15.099  7344  7344 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 12:40:15.099   326  7378 V OMXCodec: allocateBuffersOnPort portIndex=1
08-23 12:40:15.099   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-23 12:40:15.100   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-23 12:40:15.100   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-23 12:40:15.100  7344  7344 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-23 12:40:15.100   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-23 12:40:15.100   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0410b50 on output port
08-23 12:40:15.100   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-23 12:40:15.100   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-23 12:40:15.100   326  2127 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-23 12:40:15.100  7344  7344 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 12:40:15.101   326  2127 V AudioCache: notify(0xb1432480, 6, 0, 0)
08-23 12:40:15.101   326  2127 V AudioCache: ignored
08-23 12:40:15.101   326  2127 V MediaPlayerService: wait for playback complete
08-23 12:40:15.102   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.102   326  7381 V AudioCache: memcpy(0xaf004000, 0xb178a000, 4096)
08-23 12:40:15.103   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.103   326  7381 V AudioCache: memcpy(0xaf005000, 0xb178a000, 4096)
08-23 12:40:15.104   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.104   326  7381 V AudioCache: memcpy(0xaf006000, 0xb178a000, 4096)
08-23 12:40:15.105   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.105   326  7381 V AudioCache: memcpy(0xaf007000, 0xb178a000, 4096)
08-23 12:40:15.106   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.106   326  7381 V AudioCache: memcpy(0xaf008000, 0xb178a000, 4096)
08-23 12:40:15.106   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.106   326  7381 V AudioCache: memcpy(0xaf009000, 0xb178a000, 4096)
08-23 12:40:15.107   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.107   326  7381 V AudioCache: memcpy(0xaf00a000, 0xb178a000, 4096)
08-23 12:40:15.108   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.108   326  7381 V AudioCache: memcpy(0xaf00b000, 0xb178a000, 4096)
08-23 12:40:15.108   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.108   326  7381 V AudioCache: memcpy(0xaf00c000, 0xb178a000, 4096)
08-23 12:40:15.109   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.109   326  7381 V AudioCache: memcpy(0xaf00d000, 0xb178a000, 4096)
08-23 12:40:15.110   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.110   326  7381 V AudioCache: memcpy(0xaf00e000, 0xb178a000, 4096)
08-23 12:40:15.111   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.111   326  7381 V AudioCache: memcpy(0xaf00f000, 0xb178a000, 4096)
08-23 12:40:15.112   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.112   326  7381 V AudioCache: memcpy(0xaf010000, 0xb178a000, 4096)
08-23 12:40:15.113   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.113   326  7381 V AudioCache: memcpy(0xaf011000, 0xb178a000, 4096)
,08-23 12:40:15.113   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.113   326  7381 V AudioCache: memcpy(0xaf012000, 0xb178a000, 4096)
08-23 12:40:15.114   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.114   326  7381 V AudioCache: memcpy(0xaf013000, 0xb178a000, 4096)
08-23 12:40:15.114   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.114   326  7381 V AudioCache: memcpy(0xaf014000, 0xb178a000, 4096)
08-23 12:40:15.115   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.115   326  7381 V AudioCache: memcpy(0xaf015000, 0xb178a000, 4096)
08-23 12:40:15.115   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.115   326  7381 V AudioCache: memcpy(0xaf016000, 0xb178a000, 4096)
08-23 12:40:15.116   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.116   326  7381 V AudioCache: memcpy(0xaf017000, 0xb178a000, 4096)
08-23 12:40:15.117   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.117   326  7381 V AudioCache: memcpy(0xaf018000, 0xb178a000, 4096)
08-23 12:40:15.118   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.118   326  7381 V AudioCache: memcpy(0xaf019000, 0xb178a000, 4096)
08-23 12:40:15.118  7265  7265 V LGMDMManager: Create singleton instance
08-23 12:40:15.119   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.119   326  7381 V AudioCache: memcpy(0xaf01a000, 0xb178a000, 4096)
08-23 12:40:15.119   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.119   326  7381 V AudioCache: memcpy(0xaf01b000, 0xb178a000, 4096)
08-23 12:40:15.120   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.120   326  7381 V AudioCache: memcpy(0xaf01c000, 0xb178a000, 4096)
08-23 12:40:15.120   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.120   326  7381 V AudioCache: memcpy(0xaf01d000, 0xb178a000, 4096)
08-23 12:40:15.121   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.121   326  7381 V AudioCache: memcpy(0xaf01e000, 0xb178a000, 4096)
08-23 12:40:15.121   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.121   326  7381 V AudioCache: memcpy(0xaf01f000, 0xb178a000, 4096)
08-23 12:40:15.122   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.122   326  7381 V AudioCache: memcpy(0xaf020000, 0xb178a000, 4096)
08-23 12:40:15.122   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.122   326  7381 V AudioCache: memcpy(0xaf021000, 0xb178a000, 4096)
08-23 12:40:15.123   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.123   326  7381 V AudioCache: memcpy(0xaf022000, 0xb178a000, 4096)
08-23 12:40:15.124   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.124   326  7381 V AudioCache: memcpy(0xaf023000, 0xb178a000, 4096)
08-23 12:40:15.124   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.124   326  7381 V AudioCache: memcpy(0xaf024000, 0xb178a000, 4096)
08-23 12:40:15.125   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.125   326  7381 V AudioCache: memcpy(0xaf025000, 0xb178a000, 4096)
08-23 12:40:15.125   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.125   326  7381 V AudioCache: memcpy(0xaf026000, 0xb178a000, 4096)
08-23 12:40:15.126   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.126   326  7381 V AudioCache: memcpy(0xaf027000, 0xb178a000, 4096)
08-23 12:40:15.126   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.126   326  7381 V AudioCache: memcpy(0xaf028000, 0xb178a000, 4096)
08-23 12:40:15.127   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.127   326  7381 V AudioCache: memcpy(0xaf029000, 0xb178a000, 4096)
08-23 12:40:15.127   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.127   326  7381 V AudioCache: memcpy(0xaf02a000, 0xb178a000, 4096)
08-23 12:40:15.128   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.128   326  7381 V AudioCache: memcpy(0xaf02b000, 0xb178a000, 4096)
08-23 12:40:15.128  7344  7344 D BluetoothAdapterApp: Loading JNI Library
08-23 12:40:15.128   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.128   326  7381 V AudioCache: memcpy(0xaf02c000, 0xb178a000, 4096)
08-23 12:40:15.129   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.129   326  7381 V AudioCache: memcpy(0xaf02d000, 0xb178a000, 4096)
08-23 12:40:15.129   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.129   326  7381 V AudioCache: memcpy(0xaf02e000, 0xb178a000, 4096)
08-23 12:40:15.130   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.130   326  7381 V AudioCache: memcpy(0xaf02f000, 0xb178a000, 4096)
08-23 12:40:15.130   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.130   326  7381 V AudioCache: memcpy(0xaf030000, 0xb178a000, 4096)
08-23 12:40:15.131   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.131   326  7381 V AudioCache: memcpy(0xaf031000, 0xb178a000, 4096)
08-23 12:40:15.131   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.131   326  7381 V AudioCache: memcpy(0xaf032000, 0xb178a000, 4096)
08-23 12:40:15.132   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.132   326  7381 V AudioCache: memcpy(0xaf033000, 0xb178a000, 4096)
08-23 12:40:15.132   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.132   326  7381 V AudioCache: memcpy(0xaf034000, 0xb178a000, 4096)
08-23 12:40:15.132   326  7381 V AudioCache: write(0xb178a000, 4096)
08-23 12:40:15.132   326  7381 V AudioCache: memcpy(0xaf035000, 0xb178a000, 4096)
08-23 12:40:15.133   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-23 12:40:15.133   326  7381 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-23 12:40:15.133   326  7381 V AwesomePlayer: postAudioEOS() 
08-23 12:40:15.133   326  7381 V AudioCache: write(0xb178a000, 280)
08-23 12:40:15.133   326  7381 V AudioCache: memcpy(0xaf036000, 0xb178a000, 280)
08-23 12:40:15.134   326  7373 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-23 12:40:15.134   326  7373 V AwesomePlayer: onStreamDone
08-23 12:40:15.134   326  7373 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-23 12:40:15.134   326  7373 V AudioCache: notify(0xb1432480, 2, 0, 0)
08-23 12:40:15.134   326  7373 V AudioCache: playback complete
08-23 12:40:15.134   326  7373 V AwesomePlayer: pause_l() 
08-23 12:40:15.134   326  7373 V AudioCache: notify(0xb1432480, 7, 0, 0)
08-23 12:40:15.134   326  7373 V AudioCache: ignored
08-23 12:40:15.134   326  7373 V AwesomePlayer: cancelPlayerEvents
08-23 12:40:15.134   326  7373 D AudioPlayer: Pause Playback at 1068125
08-23 12:40:15.135   326  2127 V AudioCache: wait - success
08-23 12:40:15.135   326  2127 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-23 12:40:15.135   326  2127 V AwesomePlayer: reset_l() 
08-23 12:40:15.135   326  2127 V AudioCache: notify(0xb1432480, 8, 0, 0)
08-23 12:40:15.135   326  2127 V AudioCache: ignored
08-23 12:40:15.135   326  2127 V AwesomePlayer: cancelPlayerEvents
08-23 12:40:15.135   326  2127 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-23 12:40:15.135   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-23 12:40:15.135   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-23 12:40:15.135   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-23 12:40:15.135   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0410b50 on port 1
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-23 12:40:15.135   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-23 12:40:15.136   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-23 12:40:15.136   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-23 12:40:15.136   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-23 12:40:15.136   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-23 12:40:15.136   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 12:40:15.136   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-23 12:40:15.136   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-23 12:40:15.136   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-23 12:40:15.136   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-23 12:40:15.136   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-23 12:40:15.136   326  7378 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-23 12:40:15.136   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-23 12:40:15.136   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-23 12:40:15.136   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-23 12:40:15.139   326  2127 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-23 12:40:15.139   326  2127 D AudioPlayer: AudioPlayer releasing audio source
08-23 12:40:15.139   326  2127 D AudioPlayer: AudioPlayer done releasing audio source
08-23 12:40:15.139   326  2127 V AwesomePlayer: reset_l() 
08-23 12:40:15.139   326  2127 V AwesomePlayer: cancelPlayerEvents
08-23 12:40:15.139   326  2127 V AwesomePlayer: ~AwesomePlayer call
08-23 12:40:15.139   326  2127 V AwesomePlayer: reset_l() 
08-23 12:40:15.139   326  2127 V AwesomePlayer: cancelPlayerEvents
08-23 12:40:15.139  7265  7345 V SoundPool: close(32)
08-23 12:40:15.139  7265  7345 V SoundPool: pointer = 0xa0045000, size = 205080, sampleRate = 48000, numChannels = 2
08-23 12:40:15.150  7362  7362 D UEI.SmartControl: Quickset Services start...
08-23 12:40:15.151  7362  7362 I UEI.SmartControl: Manufacture = LGE
08-23 12:40:15.151  7362  7362 D UEI.SmartControl: Id = LGNevo
08-23 12:40:15.152  7362  7362 D UEI.SmartControl: File observer start...
08-23 12:40:15.155  7344  7344 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@781ad9 Instance Count = 1
08-23 12:40:15.157  7362  7362 E UEI.SmartControl: IR Port is disabled: false
08-23 12:40:15.158  7362  7362 D UEI.SmartControl: Starting file observer...
08-23 12:40:15.158  7362  7362 D UEI.SmartControl: Extracting JNI libs...
08-23 12:40:15.158  7362  7362 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-23 12:40:15.158  7344  7344 D BluetoothAdapterApp: onCreate
,08-23 12:40:15.174  7344  7344 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-23 12:40:15.174  7344  7344 D ProfileConfigQcom: Adding HeadsetService
08-23 12:40:15.174  7344  7344 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-23 12:40:15.175  7344  7344 D ProfileConfigQcom: Adding A2dpService
08-23 12:40:15.175  7344  7344 D ProfileConfigQcom: [BTUI] HidService is supported
08-23 12:40:15.175  7344  7344 D ProfileConfigQcom: Adding HidService
08-23 12:40:15.175  7344  7344 D ProfileConfigQcom: [BTUI] HealthService is supported
08-23 12:40:15.175  7344  7344 D ProfileConfigQcom: Adding HealthService
08-23 12:40:15.175  7344  7344 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-23 12:40:15.176  7344  7344 D ProfileConfigQcom: [BTUI] PanService is supported
08-23 12:40:15.176  7344  7344 D ProfileConfigQcom: Adding PanService
08-23 12:40:15.176  7344  7344 D ProfileConfigQcom: [BTUI] GattService is supported
08-23 12:40:15.176  7344  7344 D ProfileConfigQcom: Adding GattService
08-23 12:40:15.177  7344  7344 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-23 12:40:15.177  7344  7344 D ProfileConfigQcom: Adding BluetoothMapService
08-23 12:40:15.177  7344  7344 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-23 12:40:15.178  7344  7344 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-23 12:40:15.182  7192  7192 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-23 12:40:15.184  7344  7344 V LGMDMManagerInternal: Create singleton instance
,08-23 12:40:15.193  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-23 12:40:15.195  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-23 12:40:15.197  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:802,
08-23 12:40:15.229  7362  7362 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-23 12:40:15.229  7362  7362 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-23 12:40:15.229  7362  7362 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip,
08-23 12:40:15.231  7344  7344 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:40:15.233  7344  7344 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 12:40:15.233  7344  7344 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 12:40:15.234  7344  7344 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 12:40:15.235  7344  7344 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:15.235  7344  7344 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-23 12:40:15.242  7282  7282 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-23 12:40:15.244  1034  1958 I ActivityManager: Killing 6750:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-23 12:40:15.253  7362  7362 I UEI.SmartControl: --- Selecting new region: 6
,08-23 12:40:15.255  7362  7362 I UEI.SmartControl: Model = LG-D855
,08-23 12:40:15.256  7362  7362 D UEI.SmartControl: QS Service created
,08-23 12:40:15.321  1034  2011 W libprocessgroup: failed to open /acct/uid_10046/pid_6750/cgroup.procs: No such file or directory
,08-23 12:40:15.356  7362  7362 I UEI.SmartControl: Service initServices...
,08-23 12:40:15.362  7362  7362 D UEI.SmartControl: QS start get config
08-23 12:40:15.416  7362  7362 D UEI.SmartControl: Loading JNI Libs...
,08-23 12:40:15.753  7362  7362 I UEI.SmartControl: Supports setup maps: true
,08-23 12:40:15.758  7362  7362 D UEI.SmartControl: QS start statue = true Error code = 0
08-23 12:40:15.758  7362  7362 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-23 12:40:15.758  7362  7362 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-23 12:40:15.758  7362  7362 I UEI.SmartControl: ### init IR Blaster...
08-23 12:40:15.764  7362  7362 D serial_port: Configuring serial port
08-23 12:40:15.768  7362  7362 E UEI.SmartControl: UEIBLaster setting for 616
08-23 12:40:15.768  7362  7362 I UEI.SmartControl: Setting serial record hearder size = 2
08-23 12:40:15.769  7362  7362 I UEI.SmartControl: configuring settings for MAXQ616
08-23 12:40:15.769  7362  7362 I UEI.SmartControl: Get version...
,08-23 12:40:15.785  7362  7392 D UEI.SmartControl: serial port data available: 21
,08-23 12:40:15.815  7362  7362 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-23 12:40:15.815  7362  7362 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-23 12:40:15.815  7362  7362 I UEI.SmartControl: QS saving settings...
08-23 12:40:15.818  7362  7362 D UEI.SmartControl: IR Blaster version: 25672567
,08-23 12:40:15.839  7362  7392 D UEI.SmartControl: serial port data available: 4
,08-23 12:40:15.875  7362  7362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-23 12:40:15.879  7362  7362 E UEI.SmartControl: Services init done
08-23 12:40:15.880  7362  7395 I UEI.SmartControl: Device manager: loading config....
08-23 12:40:15.881  7362  7362 D UEI.SmartControl: QS Service init finished
08-23 12:40:15.882  7362  7395 D UEI.SmartControl: ----------- loading internal config...
08-23 12:40:15.887  7362  7362 D UEI.SmartControl: QS Service version name: 2.1.91
08-23 12:40:15.888  7362  7362 D UEI.SmartControl: QS Service version code: 201091
08-23 12:40:15.888  7362  7362 D UEI.SmartControl: Service requested: Control
,08-23 12:40:15.898  7362  7395 E UEI.SmartControl: Loading SETTINGS...
08-23 12:40:15.899  7362  7362 D UEI.SmartControl: Request IControl service: devices are loaded...
08-23 12:40:15.901  7362  7362 D UEI.SmartControl: Internal service binding...
08-23 12:40:15.901  7265  7265 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-23 12:40:15.902  7362  7380 I UEI.SmartControl: ------ IControl API: 11
08-23 12:40:15.903  7362  7380 I UEI.SmartControl: Registering callback...
08-23 12:40:15.904  7362  7382 I UEI.SmartControl: ------ IControl API: 19
08-23 12:40:15.905  7362  7382 I UEI.SmartControl: Registering Services Ready callback...
08-23 12:40:15.909  7362  7395 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-23 12:40:15.932  7362  7394 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-23 12:40:15.932  7265  7281 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-23 12:40:15.933  7265  7342 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-23 12:40:15.933  7265  7342 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-23 12:40:15.934  7265  7265 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-23 12:40:15.935  7362  7394 D UEI.SmartControl: -----service ready thread exits
08-23 12:40:15.935  7265  7265 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-23 12:40:15.936  7362  7380 I UEI.SmartControl: ------ IControl API: 8
08-23 12:40:15.937  7265  7265 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-23 12:40:15.938  7265  7265 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-23 12:40:15.938  7265  7265 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-23 12:40:15.939  7265  7265 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-23 12:40:15.940  7265  7265 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-23 12:40:15.940  7265  7265 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-23 12:40:15.941  7265  7265 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-23 12:40:15.944  7265  7265 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-23 12:40:15.945  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-23 12:40:15.946  7265  7265 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-23 12:40:15.946  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-23 12:40:15.947  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-23 12:40:15.949  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-23 12:40:15.949  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-23 12:40:15.950  7265  7265 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471948815950]
08-23 12:40:15.953  7265  7265 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-23 12:40:15.955  1034  1923 I ActivityManager: Killing 6786:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-23 12:40:15.977  7265  7397 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-23 12:40:15.988  1034  1923 I ActivityManager: Killing 6834:com.android.providers.calendar/u0a14 (adj 15): empty #18
08-23 12:40:16.069  1034  1728 W libprocessgroup: failed to open /acct/uid_10005/pid_6786/cgroup.procs: No such file or directory
,08-23 12:40:16.078  1034  1049 W libprocessgroup: failed to open /acct/uid_10014/pid_6834/cgroup.procs: No such file or directory
,08-23 12:40:16.089  7265  7265 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-23 12:40:16.092  7265  7265 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-23 12:40:16.092  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-23 12:40:16.093  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-23 12:40:16.093  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-23 12:40:16.093  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-23 12:40:16.094  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-23 12:40:16.104  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-23 12:40:16.562  1034  1904 D WifiServiceImplEx: setWifiEnabled: true pid=7106, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 12:40:16.563  1034  1904 D WifiService: setWifiEnabled: true pid=7106, uid=10118
08-23 12:40:16.564  1034  1904 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 12:40:16.594  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 12:40:16.594  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 12:40:16.594  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-23 12:40:16.598  1034  1392 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-23 12:40:16.598  1034  1392 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-23 12:40:16.601  1034  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-23 12:40:16.601  1034  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-23 12:40:16.601  1034  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-23 12:40:16.601  1034  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-23 12:40:16.601  1034  1392 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-23 12:40:16.601  1034  1392 E WifiHW  : unknown target_country: EU , set to default
08-23 12:40:16.601  1034  1392 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-23 12:40:16.601  1034  1392 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-23 12:40:16.601  1034  1392 I WifiUtil: gEnableBmps=1
08-23 12:40:16.644  1034  1425 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:40:16.661  1034  1102 D Tethering: MasterInitialState.processMessage what=3
08-23 12:40:16.668  1034  1425 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:40:16.680  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:40:16.683  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:16.686  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-23 12:40:16.689  1034  1102 D Tethering: MasterInitialState.processMessage what=3
08-23 12:40:16.697  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:40:16.701  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:16.703  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-23 12:40:16.713  5298  5298 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-23 12:40:16.720  5298  5298 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-23 12:40:16.721  6378  7236 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-23 12:40:16.746  2198  2198 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:40:16.771  6929  6929 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-23 12:40:16.771  6929  6929 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:40:16.776  6929  6929 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-23 12:40:16.776  6929  6929 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-23 12:40:16.782  6929  6929 I AppUp4:CustModeStarterReceiver: onReceive
,08-23 12:40:16.795  6929  6929 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b9b7f4c
08-23 12:40:16.795  6929  6929 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 12:40:16.795  6929  6929 D AppUp4:CustFacade: isPhone : true
08-23 12:40:16.795  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-23 12:40:16.796  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:16.796  6929  6929 D AppUp4:CustModeStarterReceiver: begin check event
08-23 12:40:16.797  6929  6929 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-23 12:40:16.797  6929  6929 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-23 12:40:16.800  6929  6949 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-23 12:40:16.801  6929  6949 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-23 12:40:16.801  6929  6949 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-23 12:40:16.806  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-23 12:40:16.806  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 12:40:16.808  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 12:40:16.810  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 12:40:16.831  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 12:40:16.838  4348  7429 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 12:40:16.841  4348  7432 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 12:40:16.841  4348  7432 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 12:40:16.900  1034  1574 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7435 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-23 12:40:16.976  7435  7435 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:40:16.977  7435  7435 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 12:40:16.978  7435  7435 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 12:40:16.979  7435  7435 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-23 12:40:17.258  1034  1049 I art     : Explicit concurrent mark sweep GC freed 52645(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 3.015ms total 186.657ms
,08-23 12:40:17.261  7435  7435 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-23 12:40:17.276  7435  7435 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-23 12:40:17.309  1034  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-23 12:40:17.311  1034  1102 D Tethering: InitialState.processMessage what=4
08-23 12:40:17.312  1034  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 12:40:17.319  7435  7435 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:40:17.321   321   893 D SoftapController: Softap fwReload - Ok
,08-23 12:40:17.323  1034  1392 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (716ms)
08-23 12:40:17.324   321   893 D CommandListener: Setting iface cfg
08-23 12:40:17.324   321   893 D CommandListener: Trying to bring down wlan0
08-23 12:40:17.325   321   893 D CommandListener: Clearing all IP addresses on wlan0
08-23 12:40:17.328  1034  1392 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-23 12:40:17.329  1034  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 12:40:17.329  1034  1392 E WifiStateMachine: useWiFiOffloading() : false
08-23 12:40:17.329  1034  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 12:40:17.330  1034  1392 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-23 12:40:17.331  1034  1392 D WifiMonitor: connecting to supplicant
08-23 12:40:17.331  1034  1392 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-23 12:40:17.333  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-23 12:40:17.333  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-23 12:40:17.320  7462  7462 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:17.320  7462  7462 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 12:40:17.335  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:17.336  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:17.337  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:17.358  7462  7462 I wpa_supplicant: Successfully initialized wpa_supplicant
08-23 12:40:17.373  7435  7435 D LgDataFeature: LgDataFeature() Constructor: none
08-23 12:40:17.373  7435  7435 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 12:40:17.395  7462  7462 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-23 12:40:17.395  7462  7462 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-23 12:40:17.459  7462  7462 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-23 12:40:17.488  7435  7435 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-23 12:40:17.527  7462  7462 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-23 12:40:17.533  3445  3445 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-23 12:40:17.533  3445  3445 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-23 12:40:17.534  3445  3445 I LgeMiscReceiver: networkInfo.isConnected() = false
08-23 12:40:17.538  7435  7435 I HubEmail: JNI_OnLoad()
08-23 12:40:17.538  7435  7435 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-23 12:40:17.538  7435  7435 I HubEmail: registerNatives()
08-23 12:40:17.538  7435  7435 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-23 12:40:17.538  7435  7435 I HubEmail: registerNativeMethods()
08-23 12:40:17.538  7435  7435 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-23 12:40:17.538  7435  7435 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-23 12:40:17.548  7462  7462 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-23 12:40:17.548  7462  7462 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-23 12:40:17.618  1034  2011 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7471 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-23 12:40:17.625  7435  7470 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:17.628  7305  7467 W FormManager: Network not available. Please check & try again.
08-23 12:40:17.633  7305  7469 V FormManager: Network unavailable.
,08-23 12:40:17.638  7305  7469 V FormManager: Network unavailable.
08-23 12:40:17.644  1034  2011 I ActivityManager: Killing 6880:com.google.android.talk/u0a72 (adj 15): empty #17
08-23 12:40:17.687  1034  1995 W libprocessgroup: failed to open /acct/uid_10072/pid_6880/cgroup.procs: No such file or directory
,08-23 12:40:17.775  7471  7471 D LgDataFeature: LgDataFeature() Constructor: none
08-23 12:40:17.776  7471  7471 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 12:40:17.780  7471  7471 D PhoneMonitor: Register our PhoneStateListener
,08-23 12:40:17.798  7471  7471 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-23 12:40:17.799  7471  7471 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-23 12:40:17.823  7471  7471 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-23 12:40:17.824  7471  7471 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-23 12:40:17.826  7471  7471 D TelephonyAutoProfiling: [parse] Load xml
,08-23 12:40:17.833  7471  7471 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-23 12:40:17.833  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-23 12:40:17.833  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-23 12:40:17.833  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-23 12:40:17.833  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-23 12:40:17.833  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-23 12:40:17.834  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-23 12:40:17.834  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-23 12:40:17.834  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-23 12:40:17.834  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-23 12:40:17.834  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-23 12:40:17.834  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-23 12:40:17.834  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-23 12:40:17.834  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-23 12:40:17.834  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-23 12:40:17.834  7471  7471 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-23 12:40:17.835  7471  7471 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-23 12:40:17.846  7471  7471 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-23 12:40:17.878  1034  1905 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7490 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 12:40:17.879  1034  1905 I ActivityManager: Killing 6954:com.android.contacts/u0a19 (adj 15): empty #17
08-23 12:40:17.947  1034  1049 W libprocessgroup: failed to open /acct/uid_10019/pid_6954/cgroup.procs: No such file or directory
,08-23 12:40:18.108  7462  7462 E wpa_supplicant: USIM:  scard_init function
08-23 12:40:18.108  7462  7462 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-23 12:40:18.177  1034  1958 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7514 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-23 12:40:18.178  1034  1958 I ActivityManager: Killing 6976:com.android.gallery3d/u0a27 (adj 15): empty #17
08-23 12:40:18.220  7462  7462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 12:40:18.230  7462  7462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 12:40:18.231  7462  7462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 12:40:18.237  1034  1923 W libprocessgroup: failed to open /acct/uid_10027/pid_6976/cgroup.procs: No such file or directory
,08-23 12:40:18.241  1034  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 12:40:18.338  1034  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-23 12:40:18.339  1034  1392 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-23 12:40:18.340  1034  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-23 12:40:18.343  1034  1771 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7531 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 12:40:18.344  1034  1771 I ActivityManager: Killing 6068:com.android.vending/u0a44 (adj 15): empty #17
08-23 12:40:18.354  1034  1392 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-23 12:40:18.355  1034  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:18.357  1034  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:18.357  1034  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:18.358  1034  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:18.361  1034  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:18.362  1034  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:18.363  1034  1392 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-23 12:40:18.363  1034  1392 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-23 12:40:18.364  1034  1392 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-23 12:40:18.365  1034  1392 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-23 12:40:18.365  1034  1392 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-23 12:40:18.405  1034  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 12:40:18.405  1034  1392 E WifiStateMachine: useWiFiOffloading() : false
08-23 12:40:18.405  1034  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 12:40:18.405  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:18.405  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:18.405  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:18.405  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:18.405  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-23 12:40:18.406  1034  1392 D WifiNative-wlan0: doBoolean: SET update_config 1
08-23 12:40:18.406  1034  1050 W libprocessgroup: failed to open /acct/uid_10044/pid_6068/cgroup.procs: No such file or directory
08-23 12:40:18.409  1034  1392 D WifiNative-wlan0: SET update_config 1: returned true
08-23 12:40:18.409  1034  1392 D WifiConfigStore: Loading config and enabling all networks 
08-23 12:40:18.409  1034  1392 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-23 12:40:18.410  1034  1392 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-23 12:40:18.417  1034  1392 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-23 12:40:18.421  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-23 12:40:18.422  1034  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-23 12:40:18.424  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:18.425  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-23 12:40:18.427  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:18.427  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:18.427  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:18.427  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:18.427  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:18.427  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:18.427  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:18.427  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:18.427  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:40:18.427  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:18.427  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:40:18.428  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:18.428  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:18.428  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:18.428  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:18.428  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:18.428  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:18.428  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:18.428  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:18.428  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:40:18.428  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:18.428  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:40:18.443  1034  1392 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-23 12:40:18.444  1034  1392 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-23 12:40:18.446  1034  1392 D WifiStateMachine: enableVerboseLogging : level 2
08-23 12:40:18.446  1034  1392 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-23 12:40:18.446  1034  1392 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-23 12:40:18.447  1034  1392 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-23 12:40:18.447  1034  1392 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-23 12:40:18.447  1034  1392 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-23 12:40:18.448  1034  1392 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-23 12:40:18.448  1034  1392 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-23 12:40:18.451  1034  1392 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-23 12:40:18.451  1034  1392 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-23 12:40:18.452  1034  1392 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-23 12:40:18.452  1034  1392 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-23 12:40:18.452  1034  1392 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-23 12:40:18.452  1034  1392 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-23 12:40:18.452  1034  1392 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-23 12:40:18.454  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-23 12:40:18.454  1941  2330 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-23 12:40:18.454  1941  2330 D WfdsService: Set the WFDS Monitor: true
08-23 12:40:18.454  1941  2330 D WfdsMonitor: WfdsMonitorThread create
08-23 12:40:18.454  1034  1392 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 12:40:18.455  1941  2330 D WfdsMonitor: WFDS Monitor is created and started
08-23 12:40:18.455  1941  2330 D WfdsService: WiFi: Supplicant connection re-established
08-23 12:40:18.455  1034  1392 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-23 12:40:18.455  1034  1392 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-23 12:40:18.455  1034  1392 D WifiNative-HAL: Setting external_sim to 1
,08-23 12:40:18.455  1034  1392 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-23 12:40:18.456  1034  1392 D WifiNative-wlan0: SET external_sim 1: returned true
08-23 12:40:18.456  1034  1392 I WifiNative-HAL: startHal
08-23 12:40:18.456  1034  1392 D wifi    : setting scan oui 0xaf6769a0
08-23 12:40:18.456  7531  7531 I art     : Almond Protected OAT
08-23 12:40:18.456  1034  1392 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 12:40:18.457  1941  7559 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-23 12:40:18.458  1941  7559 E CtrlSupplicant: Succeed to open control connection
08-23 12:40:18.458  1941  7559 E CtrlSupplicant: Succeed to open monitor connection
08-23 12:40:18.458  1941  7559 D WfdsMonitor: Supplicant connection established
08-23 12:40:18.458  1941  2330 D WfdsService: Connected to the supplicant for wfds
08-23 12:40:18.459  1034  1392 I WifiNative-HAL: startHal
08-23 12:40:18.459  1034  1392 D wifi    : setting scan oui 0xaf6769a0
08-23 12:40:18.459  1034  1392 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-23 12:40:18.460  1034  1392 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-23 12:40:18.460  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-23 12:40:18.460  7462  7462 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-23 12:40:18.461  1034  1392 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-23 12:40:18.461  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-23 12:40:18.461  7462  7462 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-23 12:40:18.461  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 12:40:18.461  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-23 12:40:18.462  7462  7462 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-23 12:40:18.462  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-23 12:40:18.462  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 12:40:18.462  7462  7462 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-23 12:40:18.463  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-23 12:40:18.463  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-23 12:40:18.463  7462  7462 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-23 12:40:18.463  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 12:40:18.463  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-23 12:40:18.464  7462  7462 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-23 12:40:18.464  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-23 12:40:18.464  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 12:40:18.464  7462  7462 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-23 12:40:18.465  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-23 12:40:18.466  1034  1392 E WifiNative: : [195,924,289 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-23 12:40:18.466  1034  1392 D WifiNative-wlan0: doBoolean: RECONNECT
08-23 12:40:18.466  1034  1392 D WifiNative-wlan0: RECONNECT: returned true
08-23 12:40:18.466  1034  1392 D WifiNative-wlan0: doString: [STATUS]
08-23 12:40:18.467  1034  7532 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 12:40:18.467  1034  7532 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-23 12:40:18.470  1034  1392 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-23 12:40:18.470  1034  1392 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 12:40:18.471  1034  1392 D WifiNative-wlan0: SET ps 1: returned true
08-23 12:40:18.471  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.472  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-23 12:40:18.472  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-23 12:40:18.473  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.473  1034  1555 I WifiNative-HAL: startHal
08-23 12:40:18.473  1034  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6769a0
08-23 12:40:18.473  1034  1555 D wifi    : failed to get capabilities : -3
08-23 12:40:18.473  1034  1555 E WifiScanningService: could not get scan capabilities
08-23 12:40:18.473   321   893 D CommandListener: Setting iface cfg
08-23 12:40:18.473   321   893 D CommandListener: Trying to bring up p2p0
08-23 12:40:18.473  1034  1556 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.474  1034  1392 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-23 12:40:18.474  1034  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-23 12:40:18.474  1034  1390 D LGWifiP2pService: P2pEnablingState
08-23 12:40:18.474  1034  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.474  1034  1390 D LGWifiP2pService: P2p socket connection successful
08-23 12:40:18.474  1034  1390 D LGWifiP2pService: P2pEnabledState
08-23 12:40:18.474  1034  1392 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-23 12:40:18.474  1034  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-23 12:40:18.474  1034  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-23 12:40:18.474  1034  1392 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-23 12:40:18.475  1034  1392 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-23 12:40:18.475  1034  1392 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-23 12:40:18.476  1034  1392 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-23 12:40:18.476  1034  1392 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-23 12:40:18.476  1034  1392 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-23 12:40:18.477  7462  7462 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-23 12:40:18.477  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-23 12:40:18.477  1941  1941 D WfdsService: WifiP2pState is changed : true
08-23 12:40:18.477  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-23 12:40:18.478  1941  1941 D WfdsService: isConnected: false
08-23 12:40:18.478  1941  2330 D WfdsService: Receive the WFDS_ENABLE Method
08-23 12:40:18.478  1034  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-23 12:40:18.478  1941  2330 D WfdsService: Set the WFDS Monitor: true
08-23 12:40:18.478  1941  2330 D WfdsService: Connected to the supplicant for wfds
08-23 12:40:18.478  1941  2330 D WfdsJNI : doCommand: WFDS_SET TRUE
08-23 12:40:18.478  1034  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-23 12:40:18.478  7462  7462 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-23 12:40:18.478  1941  2330 D WfdsService: selectPreferredScanChannel [36]
08-23 12:40:18.478  1941  2330 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-23 12:40:18.480  1034  1390 D WifiNative-p2p0: SET de,vice_name G3: returned true
08-23 12:40:18.480  1034  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-23 12:40:18.480  1034  1390 D LGWifiP2pService: before postfix = G3
08-23 12:40:18.480  1034  1390 D WifiServerServiceExt: postfix byte check : 2
08-23 12:40:18.480  1034  1390 D LGWifiP2pService: after postfix = G3
08-23 12:40:18.480  1034  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-23 12:40:18.480  1034  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-23 12:40:18.480  1034  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-23 12:40:18.481  1034  1392 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-23 12:40:18.481  1034  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-23 12:40:18.481  1034  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-23 12:40:18.481  1034  1392 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,08-23 12:40:18.481  1034  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-23 12:40:18.481  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-23 12:40:18.481  1034  1392 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-23 12:40:18.481  1034  1392 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-23 12:40:18.482  7462  7462 E wpa_supplicant: disconnect_rssi_lvl: -100
08-23 12:40:18.482  1034  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-23 12:40:18.482  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-23 12:40:18.482  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-23 12:40:18.482  1034  1390 D LGWifiP2pService: DeviceAddress: 
08-23 12:40:18.482  1034  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-23 12:40:18.484  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-23 12:40:18.484  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-23 12:40:18.485  1941  1941 D WfdsService: Update P2p Interface State: 3
08-23 12:40:18.485  1034  1390 D WifiNative-p2p0: P2P_FLUSH: returned false
08-23 12:40:18.485  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-23 12:40:18.485  1034  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-23 12:40:18.485  1034  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-23 12:40:18.486  1034  1390 D WifiNative-p2p0:    returned OK
08-23 12:40:18.486  1034  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-23 12:40:18.487  1034  1392 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-23 12:40:18.488  1034  1392 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-23 12:40:18.489  1034  1392 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-23 12:40:18.489  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-23 12:40:18.497  1034  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-23 12:40:18.497  1034  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-23 12:40:18.497  1034  1390 D LGWifiP2pService: InactiveState
08-23 12:40:18.497  1034  1390 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.497  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.497  1034  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-23 12:40:18.498  7462  7462 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-23 12:40:18.498  7462  7462 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:18.499  7462  7462 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 12:40:18.499  7462  7462 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.500  7462  7462 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.500  1034  7532 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 12:40:18.500  1034  7532 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:18.500  1034  7532 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:18.500  1034  7532 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:18.500  1034  7532 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:18.500  1034  7532 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.500  1034  7532 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.500  1034  7532 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.500  1034  7532 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:18.500  1034  7532 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.500  1034  7532 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.500  1034  7532 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.501  1941  7559 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:18.501  1941  7559 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:18.502  1034  1392 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-23 12:40:18.502  7462  7462 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-23 12:40:18.503  7462  7462 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:18.503  1034  1392 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-23 12:40:18.503  7462  7462 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 12:40:18.504  7462  7462 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.504  1034  1392 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-23 12:40:18.504  1034  1392 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-23 12:40:18.504  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-23 12:40:18.504  7462  7462 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.505  1034  7532 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 12:40:18.505  1034  7532 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:18.505  1034  7532 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:18.505  1034  7532 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:18.505  1034  7532 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:18.505  1034  7532 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.505  1034  7532 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.505  1034  7532 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.505  1034  7532 D Wifi,Monitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:18.506  1034  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-23 12:40:18.506  1034  1390 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.506  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.506  1034  1390 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.506  1034  1390 D LGWifiP2pService: InactiveState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.506  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.506  1034  1390 D LGWifiP2pService: DefaultState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.507  1034  1390 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.507  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.507  1034  1390 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.507  1034  1390 D LGWifiP2pService: InactiveState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.507  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.507  1034  1390 D LGWifiP2pService: DefaultState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.507  1034  1390 D LGWifiP2pService: InactiveState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.507  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.507  1941  2330 W WfdsService: DefaultState - msg [9441285] is not handled
08-23 12:40:18.507  1034  7532 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.507  7462  7462 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-23 12:40:18.507  7462  7462 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 12:40:18.507  1034  7532 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.508  1034  7532 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:18.508  1034  7532 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-23 12:40:18.508  1034  7532 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 12:40:18.508  1034  7532 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 12:40:18.508  1034  7532 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-23 12:40:18.508  1941  7559 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 12:40:18.508  1941  7559 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:18.508  1034  1034 E WifiServerServiceExt: No p2p device connected
08-23 12:40:18.508  1941  7559 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:18.509  1034  1392 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-23 12:40:18.509  1034  1392 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-23 12:40:18.509  1034  1392 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-23 12:40:18.509  1034  1392 D WifiNative-wlan0: doBoolean: SCAN
08-23 12:40:18.510  7462  7462 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-23 12:40:18.511  1034  7532 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-23 12:40:18.512  1034  7532 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-23 12:40:18.512  1034  7532 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-23 12:40:18.512  1034  7532 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-23 12:40:18.512  1034  1392 D WifiNative-wlan0: SCAN: returned true
08-23 12:40:18.513  1034  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=195972  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 12:40:18.514  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:18.514  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:18.516  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:18.517  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:18.517  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:18.517  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-23 12:40:18.517  1034  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=195976  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 12:40:18.518  1034  1392 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 12:40:18.519  1034  1392 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 12:40:18.519  1034  1392 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 12:40:18.520  1034  1392 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 12:40:18.520  1034  1392 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 12:40:18.521  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 12:40:18.521  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-23 12:40:18.529  7531  7531 D WeatherApplication: removeAccount
,08-23 12:40:18.530  7531  7531 D WeatherApplication: Account.length = 0
08-23 12:40:18.531  7531  7531 E WeatherApplication: OPERATOR:OPEN
08-23 12:40:18.535  7531  7531 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:40:18
08-23 12:40:18.538  7531  7531 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 12:40:18.538  7531  7531 D Weather.Utils: 2 : All the weather widget is gone.
08-23 12:40:18.540  7531  7531 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 12:40:18.542  7531  7531 D WeatherAncestor: connectivity changed - connection : true
,08-23 12:40:18.543  7531  7531 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-23 12:40:18.556  7531  7531 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-23 12:40:18.557  7531  7531 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 12:40:18.557  7531  7531 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-23 12:40:18.580  7531  7531 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-23 12:40:18.580  7531  7531 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:40:18
08-23 12:40:18.587  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.587  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.587  1034  1390 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:18.642  1034  1392 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 12:40:18.643  1034  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 12:40:18.643  1034  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 12:40:18.643  1034  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 12:40:18.644  1034  1392 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-23 12:40:18.660  1034  1049 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7563 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 12:40:18.661  1034  1049 I ActivityManager: Killing 6999:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-23 12:40:18.684   355   355 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 420us total 21.086ms
,08-23 12:40:18.702   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 17.702ms
,08-23 12:40:18.717   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 284us total 14.280ms
,08-23 12:40:18.727  1034  1923 W libprocessgroup: failed to open /acct/uid_10080/pid_6999/cgroup.procs: No such file or directory
,08-23 12:40:18.840   281   328 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-23 12:40:18.840   281   328 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-23 12:40:18.840   281   328 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 12:40:18.841  7563  7581 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-23 12:40:18.845   281   328 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-23 12:40:18.845   281   328 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-23 12:40:18.845   281   328 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 12:40:18.846  7563  7581 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-23 12:40:18.858   281   328 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-23 12:40:18.858   281   328 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-23 12:40:18.858   281   328 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 12:40:18.858  7563  7583 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-23 12:40:18.862   281   328 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-23 12:40:18.862   281   328 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-23 12:40:18.862   281   328 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 12:40:18.862  7563  7583 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-23 12:40:19.114  7563  7563 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-23 12:40:19.126  7563  7563 I LibraryLoader: Loading: webviewchromium
08-23 12:40:19.130  7563  7563 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6599-6603)
,08-23 12:40:19.130  7563  7563 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 12:40:19.141  7563  7563 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2df09614}
08-23 12:40:19.144  7563  7563 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 12:40:19.145  7563  7563 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 12:40:19.165  7563  7563 I BrowserStartupController: Initializing chromium process, renderers=0
,08-23 12:40:19.167  7563  7563 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:40:19.191  7563  7563 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-23 12:40:19.191  7563  7563 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-23 12:40:19.192  7563  7563 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-23 12:40:19.205   326  2126 V AudioPolicyService: registerClient() client 0xb1003680, uid 10093
,08-23 12:40:19.215  7563  7608 W AudioManagerAndroid: Requires BLUETOOTH permission
08-23 12:40:19.217  7563  7563 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 12:40:19.217  7563  7563 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 12:40:19.217  7563  7563 I Adreno-EGL: Build Date: 12/12/14 금
08-23 12:40:19.217  7563  7563 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 12:40:19.217  7563  7563 I Adreno-EGL: Remote Branch: 
08-23 12:40:19.217  7563  7563 I Adreno-EGL: Local Patches: 
08-23 12:40:19.217  7563  7563 I Adreno-EGL: Reconstruct Branch: 
,08-23 12:40:19.313  7563  7563 I NSApplication: Starting up...
,08-23 12:40:19.361  1034  2011 I ActivityManager: Killing 7237:com.lge.sync/1000 (adj 15): empty #17
,08-23 12:40:19.395  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_7237/cgroup.procs: No such file or directory
,08-23 12:40:19.421  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-23 12:40:19.424  6378  7236 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-23 12:40:19.452  2198  2198 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:40:19.468  6929  6929 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-23 12:40:19.468  6929  6929 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:40:19.469  6929  6929 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-23 12:40:19.469  6929  6929 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-23 12:40:19.475  6929  6929 I AppUp4:CustModeStarterReceiver: onReceive
08-23 12:40:19.480  6929  6929 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b9b7f4c
08-23 12:40:19.480  6929  6929 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 12:40:19.480  6929  6929 D AppUp4:CustFacade: isPhone : true
08-23 12:40:19.481  6929  6929 D AppUp4:CustModeStarterReceiver: begin check event
08-23 12:40:19.482  6929  6929 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-23 12:40:19.488  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-23 12:40:19.489  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 12:40:19.492  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 12:40:19.495  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 12:40:19.503  4348  7622 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-23 12:40:19.508  7435  7435 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-23 12:40:19.512  4348  7623 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 12:40:19.512  4348  7623 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 12:40:19.539  7435  7625 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 12:40:19.549  3445  3445 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-23 12:40:19.549  3445  3445 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-23 12:40:19.550  3445  3445 I LgeMiscReceiver: networkInfo.isConnected() = false
08-23 12:40:19.551  7305  7626 W FormManager: Network not available. Please check & try again.
,08-23 12:40:19.557  7471  7471 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-23 12:40:19.557  7471  7471 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-23 12:40:19.560  7305  7628 V FormManager: Network unavailable.
08-23 12:40:19.567  7305  7628 V FormManager: Network unavailable.
08-23 12:40:19.575  7531  7531 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:40:19
,08-23 12:40:19.579  7531  7531 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 12:40:19.579  7531  7531 D Weather.Utils: 2 : All the weather widget is gone.
08-23 12:40:19.580  7531  7531 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 12:40:19.580  7531  7531 D WeatherAncestor: connectivity changed - connection : true
08-23 12:40:19.580  7531  7531 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@20514c11
08-23 12:40:19.581  7531  7531 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-23 12:40:19.581  7531  7531 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 12:40:19.581  7531  7531 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-23 12:40:19.581  7531  7531 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 12:40:19.581  7531  7531 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:40:19
08-23 12:40:19.601  1034  1905 D WifiServiceImplEx: setWifiEnabled: false pid=7106, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-23 12:40:19.601  1034  1905 D WifiService: setWifiEnabled: false pid=7106, uid=10118
08-23 12:40:19.601  1034  1905 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-23 12:40:19.615  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-23 12:40:19.615  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 12:40:19.616  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 12:40:19.616  7192  7192 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 12:40:19.618  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 12:40:19.619  7192  7192 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 12:40:19.619  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-23 12:40:19.619  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 12:40:19.619  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 12:40:19.619  7192  7192 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 12:40:19.620  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-23 12:40:19.620  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 12:40:19.620  7192  7192 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 12:40:19.620  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 12:40:19.620  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-23 12:40:19.622  1034  1392 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-23 12:40:19.623  1034  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-23 12:40:19.624  1034  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-23 12:40:19.625  1034  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-23 12:40:19.635  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:19.635  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-23 12:40:19.635  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:19.635  1034  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2f1202b1
,08-23 12:40:19.635  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-23 12:40:19.635  1034  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 12:40:19.635  1034  1390 D LGWifiP2pService: P2pDisablingState
08-23 12:40:19.635  1034  1556 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:19.635  1034  1390 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:19.635  1034  1390 D LGWifiP2pService: p2p socket connection lost
08-23 12:40:19.636  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 12:40:19.636  1941  1941 D WfdsService: WifiP2pState is changed : false
08-23 12:40:19.637  1941  2330 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-23 12:40:19.637  1941  2330 D WfdsService: Set the WFDS Monitor: false
08-23 12:40:19.638  1034  1390 D LGWifiP2pService: P2pDisabledState
08-23 12:40:19.639  1941  2330 D WfdsMonitor: WFDS Monitor is stopped
08-23 12:40:19.639  1941  2330 D WfdsService: STATE : WfdsDisabledState - enter
08-23 12:40:19.640  1941  2332 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-23 12:40:19.640  1941  7559 D CtrlSupplicant: Received on exit socket, terminate
08-23 12:40:19.640  1941  7559 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-23 12:40:19.640  1941  7559 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-23 12:40:19.640  1941  7559 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-23 12:40:19.640  1941  2330 W WfdsService: DefaultState - msg [9445378] is not handled
08-23 12:40:19.642  1034  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-23 12:40:19.643   321   893 D CommandListener: Clearing all IP addresses on wlan0
08-23 12:40:19.646  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-23 12:40:19.647  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-23 12:40:19.647  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:19.648  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:19.648  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:19.648  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 12:40:19.648  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:19.649  1034  1392 D WifiNative-p2p0: doBoolean: TERMINATE
08-23 12:40:19.649  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-23 12:40:19.650  1034  1392 D WifiNative-p2p0: TERMINATE: returned true
,08-23 12:40:19.650  1034  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 12:40:19.650  1034  1392 E WifiStateMachine: useWiFiOffloading() : false
08-23 12:40:19.650  1034  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 12:40:19.654  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:19.654  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:19.654  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 12:40:19.657  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-23 12:40:19.659  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:19.659  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:19.659  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:19.659  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:19.659  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:40:19.659  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:19.659  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:19.659  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:19.659  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:40:19.659  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:19.659  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:40:19.659  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-23 12:40:19.659  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 12:40:19.659  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-23 12:40:19.660  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:19.660  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:19.660  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:19.660  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:19.660  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:40:19.660  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:19.660  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:19.660  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:19.660  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:40:19.660  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:19.660  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular:, DO_NOT_CARE, BSSID name: null
08-23 12:40:19.672  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-23 12:40:19.672  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:19.673  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 12:40:19.676  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:19.717  1034  1923 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7633 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 12:40:19.720  7305  7631 W FormManager: Network not available. Please check & try again.
08-23 12:40:19.724  7305  7632 V FormManager: Network unavailable.
08-23 12:40:19.728  7305  7632 V FormManager: Network unavailable.
08-23 12:40:19.738  7462  7462 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-23 12:40:19.739  7462  7462 I wpa_supplicant: monitor socket send errors count : 1
08-23 12:40:19.739  7462  7462 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
08-23 12:40:19.740  1034  7532 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-23 12:40:19.740  1034  7532 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-23 12:40:19.760  7462  7462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 12:40:19.761  1034  7532 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-23 12:40:19.761  1034  7532 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 12:40:19.761  1034  7532 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 12:40:19.761  1034  7532 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-23 12:40:19.761  7462  7462 W wpa_supplicant: USIM:  scard_deinit function
08-23 12:40:19.762  1034  1392 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=197221
08-23 12:40:19.762  1034  1392 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=197222
08-23 12:40:19.763  1034  7532 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 12:40:19.763  1034  7532 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 12:40:19.764  1034  1392 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=197223  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 12:40:19.764  1034  1102 D Tethering: InitialState.processMessage what=4
08-23 12:40:19.764  1034  1392 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=197223  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 12:40:19.766  1034  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 12:40:19.766  1034  1392 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:19.767  1034  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-23 12:40:19.788  7462  7462 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-23 12:40:19.790  1034  7532 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-23 12:40:19.790  1034  7532 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-TERMINATING 
08-23 12:40:19.790  1034  7532 D WifiMonitor: Disconnecting from the supplicant, no more events
08-23 12:40:19.790  1034  1392 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 33 0
08-23 12:40:19.800  7633  7633 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 12:40:19.805  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:40:19.811  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:19.812  1034  1974 I ActivityManager: Killing 7215:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-23 12:40:19.846  1034  1771 W libprocessgroup: failed to open /acct/uid_10037/pid_7215/cgroup.procs: No such file or directory
,08-23 12:40:19.869  7633  7633 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 12:40:19.873  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:40:19.881  7305  7653 W FormManager: Network not available. Please check & try again.
,08-23 12:40:19.888  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:19.888  7305  7654 V FormManager: Network unavailable.
08-23 12:40:19.894  1034  1392 D WifiOffDelayIfNotUsed: stopMonitoring
08-23 12:40:19.894  1034  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 12:40:19.894  1034  1392 E WifiStateMachine: useWiFiOffloading() : false
08-23 12:40:19.894  1034  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-23 12:40:19.895  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-23 12:40:19.896  1941  2330 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-23 12:40:19.896  1941  2330 D WfdsService: Set the WFDS Monitor: false
08-23 12:40:19.896  1941  2330 D WfdsMonitor: WFDS Monitor is stopped
08-23 12:40:19.899  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:19.901  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 12:40:19.902  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-23 12:40:19.902  1034  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-23 12:40:19.902  1034  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-23 12:40:19.902  2473  2473 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:19.905  7305  7654 V FormManager: Network unavailable.
08-23 12:40:19.914  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 12:40:19.914  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-23 12:40:19.917  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:19.918  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:19.918  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 12:40:19.921  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 12:40:19.925  4348  7655 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 12:40:19.929  4348  7656 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 12:40:19.930  4348  7656 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-23 12:40:19.978  1034  1958 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7657 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-23 12:40:20.111  7657  7657 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 12:40:20.112  7657  7657 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-23 12:40:20.121  7657  7657 V [BNRBootReceiver]: Boot Receiver Return
08-23 12:40:20.123  7657  7657 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-23 12:40:20.124  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:20.144  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 12:40:20.150  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:20.163  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 12:40:20.163  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:20.164  7265  7265 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 12:40:20.169  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:20.176  7633  7633 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 12:40:20.179  7633  7633 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 12:40:20.180  7633  7633 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 12:40:20.183  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 12:40:20.191  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:20.203  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 12:40:20.203  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:20.205  1034  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=463326842, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
08-23 12:40:20.207  7265  7265 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 12:40:20.216  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 12:40:20.225  7633  7633 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 12:40:20.225  7633  7633 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 12:40:20.225  7633  7633 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 12:40:20.232  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 12:40:20.240  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:20.254  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:20.254  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 12:40:20.257  2615  2615 D [Concierge]Service: onStartCommand(). Type : 9
08-23 12:40:20.258  7265  7265 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 12:40:20.276  7633  7633 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 12:40:20.281  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 12:40:20.290  7305  7677 W FormManager: Network not available. Please check & try again.
,08-23 12:40:20.295  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:20.302  7305  7678 V FormManager: Network unavailable.
08-23 12:40:20.306  7305  7678 V FormManager: Network unavailable.
,08-23 12:40:20.313  1034  1771 I ActivityManager: Killing 7282:com.lge.settings.easy/1000 (adj 15): empty #17
08-23 12:40:20.340  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 12:40:20.340  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 12:40:20.340  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-23 12:40:20.340  7192  7192 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 12:40:20.341  1034  1049 W libprocessgroup: failed to open /acct/uid_1000/pid_7282/cgroup.procs: No such file or directory
08-23 12:40:20.342  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 12:40:20.343  7192  7192 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 12:40:20.343  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-23 12:40:20.343  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 12:40:20.343  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 12:40:20.344  7192  7192 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 12:40:20.344  7192  7192 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 12:40:20.348  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 12:40:20.348  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 12:40:20.350  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 12:40:20.352  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 12:40:20.360  4348  7679 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 12:40:20.361  7633  7633 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-23 12:40:20.361  7633  7633 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 12:40:20.361  7633  7633 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 12:40:20.365  4348  7681 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 12:40:20.365  4348  7681 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-23 12:40:20.368  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 12:40:20.376  7305  7682 W FormManager: Network not available. Please check & try again.
08-23 12:40:20.376  7305  7683 V FormManager: Network unavailable.
,08-23 12:40:20.381  7305  7683 V FormManager: Network unavailable.
,08-23 12:40:20.382  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:20.405  7265  7265 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-23 12:40:20.405  7265  7265 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:802
08-23 12:40:20.406  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=463326842 [*alarm*], flags=0x0
,08-23 12:40:20.874  7362  7396 D UEI.SmartControl: Internal timer expired: 1
08-23 12:40:20.874  7362  7396 D UEI.SmartControl: unbind internal service
,08-23 12:40:20.938  7362  7393 D serial_port: close(fd = 25)
,08-23 12:40:20.948  7362  7393 I UEI.SmartControl: Serial port is closed.
08-23 12:40:22.621  1034  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:22.622  1034  2011 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-23 12:40:22.650  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 12:40:22.650  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 12:40:22.650  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-23 12:40:22.651  1034  1102 D BluetoothManagerService: Message: 1
08-23 12:40:22.651  1034  1102 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-23 12:40:22.677  1034  1102 D BluetoothManagerService: Message: 20
08-23 12:40:22.677  1034  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee5eaf4:true
,08-23 12:40:22.682  7344  7344 D BluetoothAdapterState: make
08-23 12:40:22.688  7344  7344 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-23 12:40:22.688  7344  7344 I bluedroid-qcom: init
08-23 12:40:22.689  7344  7691 I BluetoothAdapterState: Entering OffState
08-23 12:40:22.689  7344  7344 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-23 12:40:22.690  7344  7344 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 12:40:22.690  7344  7344 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 12:40:22.690  7344  7344 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 12:40:22.690  7344  7344 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-23 12:40:22.693  7344  7344 I bluedroid-qcom: get_profile_interface socket
08-23 12:40:22.693  7344  7344 I bluedroid-qcom: get_profile_interface map_client
,08-23 12:40:22.697  7344  7695 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-23 12:40:22.690  7694  7694 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:22.700  7694  7694 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 12:40:22.719  7344  7695 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-23 12:40:22.722  7694  7694 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-23 12:40:22.722  7694  7694 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-23 12:40:22.722  7694  7694 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-23 12:40:22.725  7694  7694 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-23 12:40:22.728  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-23 12:40:22.728  1034  1102 D BluetoothManagerService: Message: 40
08-23 12:40:22.728  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-23 12:40:22.730  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-23 12:40:22.733  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-23 12:40:22.737  7344  7360 I bluedroid-qcom: config_hci_snoop_log
08-23 12:40:22.740  1034  1102 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-23 12:40:22.740  1034  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-23 12:40:22.746  7344  7691 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-23 12:40:22.749  7344  7695 D BluetoothAdapterProperties: Name is: G3
08-23 12:40:22.750  7344  7691 D BluetoothAdapterProperties: Setting state to 11
08-23 12:40:22.750  7344  7691 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-23 12:40:22.751  1034  1102 D BluetoothManagerService: Message: 60
08-23 12:40:22.751  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-23 12:40:22.751  1034  1102 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-23 12:40:22.752  7344  7691 I LGBluetoothServiceJni: classInitNative: succeeds
08-23 12:40:22.756  7694  7694 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-23 12:40:22.756  7694  7694 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-23 12:40:22.761  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 12:40:22.763  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:22.767  7192  7192 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-23 12:40:22.768  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:22.769  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:22.777  7344  7344 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-23 12:40:22.785  7344  7344 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:22.785  7344  7344 V BluetoothPbapReceiver: ***********state = 11
08-23 12:40:22.789  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 12:40:22.842  1034  2033 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7711 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-23 12:40:22.845  7344  7691 D BluetoothBondStateMachine: make
08-23 12:40:22.847  7344  7691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:22.847  7344  7691 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-23 12:40:22.847  7344  7691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:22.847  7344  7691 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-23 12:40:22.848  7344  7691 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-23 12:40:22.849  7344  7721 I BluetoothBondStateMachine: StableState(): Entering Off State
08-23 12:40:22.853  7344  7691 E BluetoothAdapterService: File transfer profiles supported!!
08-23 12:40:22.857  7344  7691 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 12:40:22.859  7344  7344 D HeadsetService: Received start request. Starting profile...
08-23 12:40:22.860  7344  7344 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 12:40:22.860  7344  7344 D LGBluetoothHfpAdapter: Version 1.6
08-23 12:40:22.862  7344  7344 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 12:40:22.863  7344  7691 E BluetoothAdapterService: File transfer profiles supported!!
08-23 12:40:22.863  7344  7344 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 12:40:22.863  7344  7344 D HeadsetStateMachine: make
08-23 12:40:22.873  7344  7691 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 12:40:22.885  7344  7691 E BluetoothAdapterService: File transfer profiles supported!!
08-23 12:40:22.890  7344  7691 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 12:40:22.892  7344  7344 D LgDataFeature: LgDataFeature() Constructor: none
08-23 12:40:22.892  7344  7344 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 12:40:22.895  7344  7344 D HeadsetStateMachine: max_hf_connections = 1
08-23 12:40:22.895  7344  7344 I bluedroid-qcom: get_profile_interface handsfree
08-23 12:40:22.897  7344  7691 E BluetoothAdapterService: File transfer profiles supported!!
08-23 12:40:22.897  7344  7344 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-23 12:40:22.897   326  2127 V AudioPolicyService: registerClient() client 0xb10037a0, uid 1002
08-23 12:40:22.897   326   326 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-23 12:40:22.897   326   326 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 12:40:22.897   326   326 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 12:40:22.898  7344  7344 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-23 12:40:22.898   326  2126 V AudioFlinger: registerClient() client 0xb5581820, pid 7344
08-23 12:40:22.898   326  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:40:22.898   326  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 12:40:22.898  1602  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:40:22.898  1602  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 12:40:22.898  7344  7344 V ToneGenerator: Create Track: 0xb4928a80
08-23 12:40:22.898  7344  7344 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-23 12:40:22.898  7344  7344 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-23 12:40:22.898  3445  3461 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:40:22.898  3445  3461 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 12:40:22.898   326  1397 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:22.898  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:40:22.898   326  1397 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 12:40:22.898  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 12:40:22.899   326   326 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 12:40:22.899   326   326 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-23 12:40:22.899   326   326 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 12:40:22.899   326   326 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 12:40:22.899  1853  2671 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:22.899  1853  2671 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 12:40:22.899  7344  7344 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-23 12:40:22.899  1602  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:22.899  1602  1618 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 12:40:22.899  3445  3460 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:22.899  3445  3460 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 12:40:22.899   326  2127 I AudioFlinger: isAudioPlaybackHookOn() false
08-23 12:40:22.899  1034  1772 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:40:22.899  1034  1772 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 12:40:22.899  1034  1772 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:22.899  1034  1772 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 12:40:22.899  7344  7361 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:,40:22.899  7344  7361 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-23 12:40:22.899  7344  7361 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:22.899  7344  7361 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-23 12:40:22.900   326   326 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 12:40:22.900   326   326 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-23 12:40:22.900   326   326 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 12:40:22.900   326   326 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 12:40:22.900  7344  7344 V AudioSystem: getLatency() output 2, latency 50
08-23 12:40:22.900  7344  7344 V AudioSystem: getFrameCount() output 2, frameCount 960
08-23 12:40:22.900  7344  7344 V AudioTrack: createTrack_l() output 2 afLatency 50
08-23 12:40:22.900   326  2126 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-23 12:40:22.900   326  2126 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 12:40:22.900   326  2126 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-23 12:40:22.900   326  2126 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 12:40:22.900   326  2126 V AudioFlinger: createTrack() lSessionId: 20
08-23 12:40:22.901  7344  7344 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-23 12:40:22.901   326  2126 V AudioFlinger: acquiring 20 from 7344, for 7344
08-23 12:40:22.901   326  2126 V AudioFlinger:  added new entry for 20
08-23 12:40:22.902  7344  7344 V ToneGenerator: ToneGenerator INIT OK, time: 200375
08-23 12:40:22.902  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:22.903  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:22.903  7344  7730 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-23 12:40:22.904  7344  7730 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 12:40:22.904  7344  7730 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 12:40:22.904  7344  7730 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-23 12:40:22.904   326  1403 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7344
,08-23 12:40:22.904   326  1403 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
,08-23 12:40:22.904   326  1403 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-23 12:40:22.904   326  1403 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-23 12:40:22.904   326  1403 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-23 12:40:22.904   326  1403 V voice   : voice_set_parameters: exit with code(0)
08-23 12:40:22.904   326  1403 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-23 12:40:22.904   326  1403 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-23 12:40:22.904   326  1403 V msm8974_platform: platform_set_parameters: exit with code(0)
08-23 12:40:22.904   326  1403 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-23 12:40:22.904   326  1403 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-23 12:40:22.904   326  1403 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-23 12:40:22.905  7344  7344 D A2dpService: Received start request. Starting profile...
08-23 12:40:22.906  7344  7344 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 12:40:22.907  7344  7344 V Avrcp   : make
08-23 12:40:22.907  7344  7344 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-23 12:40:22.907  7344  7344 I bluedroid-qcom: get_profile_interface avrcp
08-23 12:40:22.908  7344  7730 V ToneGenerator: ToneGenerator destructor
08-23 12:40:22.908  7344  7730 V ToneGenerator: stopTone
08-23 12:40:22.908  7344  7730 V ToneGenerator: Delete Track: 0xb4928a80
08-23 12:40:22.908  7344  7730 V AudioTrack: ~AudioTrack, releasing session id from 7344 on behalf of 7344
08-23 12:40:22.908   326  1402 V AudioFlinger: releasing 20 from 7344 for 7344
08-23 12:40:22.908   326  1402 V AudioFlinger:  decremented refcount to 0
08-23 12:40:22.908   326  1402 V AudioFlinger: purging stale effects
08-23 12:40:22.908   326  1402 V AudioPolicyService: AudioCommandThread() adding release output 2
08-23 12:40:22.908   326  1402 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-23 12:40:22.908   326  1402 V AudioFlinger: PlaybackThread::Track destructor
08-23 12:40:22.908   326  1121 V AudioPolicyService: AudioCommandThread() waking up
08-23 12:40:22.908   326  1402 V AudioFlinger: removeClient_l() pid 7344, calling pid 326
08-23 12:40:22.908   326  1121 V AudioPolicyService: AudioCommandThread() processing release output 2
08-23 12:40:22.908   326  1121 V AudioPolicyManager: releaseOutput() 2
08-23 12:40:22.908   326  1121 V AudioPolicyService: AudioCommandThread() going to sleep
08-23 12:40:22.909  1034  1574 W Process : Unable to open /proc/7732/status
08-23 12:40:22.915  7344  7691 V LGMDMManager: Create singleton instance
,08-23 12:40:22.917  7344  7344 V AudioManager: registerRemoteController: size of Media player list: 0
08-23 12:40:22.918  7344  7344 E AudioManager: No RCC entry present to update
08-23 12:40:22.918  7344  7344 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-23 12:40:22.921  7344  7344 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-23 12:40:22.922  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-23 12:40:22.922  7344  7344 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-23 12:40:22.923  7344  7691 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-23 12:40:22.925  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-23 12:40:22.961  7711  7711 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-23 12:40:22.962  7711  7711 W LG Account v2.2: No ProfileInfo entries
08-23 12:40:22.962  7711  7711 I LG Account v2.2: isEnabled: false
08-23 12:40:22.963  7711  7711 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-23 12:40:22.963  7711  7711 I Feature : [Lifetracker]Country: EU
08-23 12:40:22.963  7711  7711 I Feature : [Lifetracker]Operator: OPEN
08-23 12:40:22.963  7711  7711 I Feature : [Lifetracker]Ranking support: false
08-23 12:40:22.963  7711  7711 I Feature : [Lifetracker]Comfort support: false
08-23 12:40:22.963  7711  7711 I Feature : [Lifetracker]Accessory: true
08-23 12:40:22.963  7711  7711 I Feature : [Lifetracker]Health device: true
08-23 12:40:22.963  7711  7711 I Feature : [Lifetracker]Extra Pedometer: false
08-23 12:40:22.963  7711  7711 I Feature : [Lifetracker]Blood glucose device: false
08-23 12:40:22.963  7711  7711 I Feature : [Lifetracker]Device Number: 3
,08-23 12:40:22.979  7192  7192 D BluetoothPermissionRequest: onReceive
,08-23 12:40:22.983  7192  7192 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-23 12:40:23.017  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-23 12:40:23.017  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-23 12:40:23.141  1034  2033 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-23 12:40:23.149  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-23 12:40:23.154  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 12:40:23.155  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 12:40:23.155  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 12:40:23.155  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 12:40:23.155  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 12:40:23.155  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 12:40:23.155  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 12:40:23.155  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 12:40:23.155  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-23 12:40:23.155  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 12:40:23.156  7344  7344 I BluetoothA2dpServiceJni: classInitNative
08-23 12:40:23.156  7344  7344 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 12:40:23.156  7344  7344 D A2dpStateMachine: make
08-23 12:40:23.162  7344  7344 I bluedroid-qcom: get_profile_interface a2dp
08-23 12:40:23.163  7344  7739 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-23 12:40:23.165  7344  7344 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-23 12:40:23.165  7344  7344 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-23 12:40:23.166  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:23.167  7344  7738 D A2dpStateMachine: Enter Disconnected: -2
08-23 12:40:23.167  7344  7344 I BluetoothHidServiceJni: classInitNative: succeeds
08-23 12:40:23.169  7344  7344 D HidService: Received start request. Starting profile...
08-23 12:40:23.169  7344  7344 I bluedroid-qcom: get_profile_interface hidhost
08-23 12:40:23.169  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:23.170  7344  7344 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 12:40:23.171  7344  7344 D HealthService: Received start request. Starting profile...
,08-23 12:40:23.172  7344  7344 I bluedroid-qcom: get_profile_interface health
08-23 12:40:23.172  7344  7344 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-23 12:40:23.172  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:23.173  7344  7344 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-23 12:40:23.175  7344  7344 D PanService: Received start request. Starting profile...
08-23 12:40:23.175  7344  7344 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 12:40:23.175  7344  7344 I bluedroid-qcom: get_profile_interface pan
08-23 12:40:23.182  7344  7344 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-23 12:40:23.182  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
,08-23 12:40:23.183  7344  7344 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-23 12:40:23.187  7344  7344 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 12:40:23.187  7344  7344 D BtGatt.GattService: Received start request. Starting profile...
08-23 12:40:23.187  7344  7344 D BtGatt.GattService: start()
08-23 12:40:23.187  7344  7344 I bluedroid-qcom: get_profile_interface gatt
08-23 12:40:23.188  7344  7344 D BtGatt.AdvertiseManager: advertise manager created
08-23 12:40:23.196  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:23.196  7344  7344 D HeadsetStateMachine: Proxy object connected
08-23 12:40:23.196  7344  7344 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-23 12:40:23.197  7344  7344 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-23 12:40:23.198  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:23.198  7344  7344 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-23 12:40:23.199  7344  7344 V BluetoothMapService: BluetoothMapBinder()
,08-23 12:40:23.200  7344  7344 D BluetoothMapService: Received start request. Starting profile...
08-23 12:40:23.200  7344  7344 D BluetoothMapService: start()
08-23 12:40:23.203  7344  7344 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-23 12:40:23.203  7344  7344 D BluetoothMapEmailAppObserver: createReceiver()
08-23 12:40:23.204  7344  7344 D BluetoothMapEmailAppObserver: initObservers()
08-23 12:40:23.204  7344  7344 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-23 12:40:23.210  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
,08-23 12:40:23.215  7344  7344 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 12:40:23.215  7344  7730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 12:40:23.217  7344  7730 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 12:40:23.217  7344  7730 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-23 12:40:23.220  7344  7344 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 12:40:23.224  7344  7344 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 12:40:23.226  7344  7344 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-23 12:40:23.228  7344  7344 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 12:40:23.228  7344  7344 V PanService: [BTUI] SIM Extra State :ABSENT
,08-23 12:40:23.231  7344  7344 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-23 12:40:23.231  7344  7344 V BluetoothMapService: Handler(): got msg=1
08-23 12:40:23.232  7344  7691 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-23 12:40:23.232  7344  7691 I bluedroid-qcom: enable
08-23 12:40:23.233  7344  7344 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:23.233  7344  7746 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-23 12:40:23.233  7344  7746 I bt-btu  : btu_task pending for preload complete event
08-23 12:40:23.233  7344  7691 I bt_hci_bdroid: init
08-23 12:40:23.234  7344  7344 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 12:40:23.234  7344  7344 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 12:40:23.234  7344  7344 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 12:40:23.235  7344  7344 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:23.235  7344  7344 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-23 12:40:23.236  7344  7691 I bt_vendor: bt-vendor : init
08-23 12:40:23.236  7344  7691 I bt_vendor: bt-vendor : get_bt_soc_type
08-23 12:40:23.236  7344  7691 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-23 12:40:23.236  7344  7691 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-23 12:40:23.236  7344  7691 D bt_userial_mct: userial_init
08-23 12:40:23.237  7344  7691 D bt_hci_bdroid: set_power 1
08-23 12:40:23.237  7344  7691 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-23 12:40:23.237  7344  7691 I bt_vendor: Starting hciattach daemon
08-23 12:40:23.237  7344  7691 I bt_vendor: try to set true
,08-23 12:40:23.230  7749  7749 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:23.230  7749  7749 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:23.294  1034  1728 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7754 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 12:40:23.297  7753  7753 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-23 12:40:23.354  7754  7754 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 12:40:23.361  7776  7776 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-23 12:40:23.374  7777  7777 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-23 12:40:23.379  1034  1049 I ActivityManager: Killing 6929:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-23 12:40:23.397  7779  7779 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 12:40:23.408  7780  7780 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-23 12:40:23.420  7781  7781 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 12:40:23.428  1034  1772 W libprocessgroup: failed to open /acct/uid_10011/pid_6929/cgroup.procs: No such file or directory
08-23 12:40:23.430  7782  7782 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-23 12:40:23.449  7784  7784 I libmdmdetect: ESOC framework not supported
,08-23 12:40:23.451  7784  7784 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-23 12:40:23.458  7784  7784 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-23 12:40:23.459  7784  7784 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-23 12:40:23.459  7784  7784 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-23 12:40:23.459  7784  7784 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-23 12:40:23.459  7784  7784 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-23 12:40:23.459  7784  7784 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-23 12:40:23.459  7784  7784 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-23 12:40:23.493  7784  7785 E QC-QMI  : qmi_client [7784] 14: failed to locate client data
,08-23 12:40:23.494   485   485 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-23 12:40:23.494   485   485 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-23 12:40:23.539  7786  7786 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-23 12:40:23.559  7787  7787 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-23 12:40:23.598  7344  7691 I bt_vendor: bluetooth satus is on
08-23 12:40:23.598  7344  7691 D bt_hci_bdroid: preload
,08-23 12:40:23.602  7344  7748 D bt_userial_mct: userial_open(port:0)
08-23 12:40:23.602  7344  7748 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-23 12:40:23.607  7344  7748 I bt_vendor: Done intiailizing UART
08-23 12:40:23.611  7344  7748 I bt_vendor: Done intiailizing UART
08-23 12:40:23.611  7344  7748 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-23 12:40:23.612  7344  7748 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-23 12:40:23.612  7344  7789 D bt_userial_mct: Entering userial_read_thread()
08-23 12:40:23.612  7344  7746 I bt-btu  : btu_task received preload complete event
08-23 12:40:23.613  7344  7746 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-23 12:40:23.614  7344  7746 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-23 12:40:23.624  7344  7746 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_HCI
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_AVDT
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 12:40:23.632  7344  7746 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 12:40:23.633  7344  7746 I         : BTE_InitTraceLevels -- TRC_BTIF
08-23 12:40:23.646  1034  1425 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-23 12:40:23.690  7344  7746 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-23 12:40:23.690  7344  7746 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ce061 
08-23 12:40:23.690  7344  7746 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ce061 
,08-23 12:40:23.714  7344  7695 E bt-btif : Calling BTA_HhEnable
,08-23 12:40:23.714  7344  7746 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-23 12:40:23.714  7344  7695 E bt-btif : L2CAP - L2CA_Register() called for PSM: 0x0019
08-23 12:40:23.714  7344  7746 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-23 12:40:23.714  7344  7746 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-23 12:40:23.715  7344  7746 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-23 12:40:23.715  7344  7746 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-23 12:40:23.715  7344  7695 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-23 12:40:23.718  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-23 12:40:23.719  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-23 12:40:23.719  7344  7695 D BluetoothAdapterProperties: Name is: G3
08-23 12:40:23.722  7344  7695 D BluetoothAdapterProperties: Scan Mode:20
08-23 12:40:23.722  7344  7695 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 12:40:23.722  7344  7695 D bt_hci_bdroid: postload
08-23 12:40:23.723  7344  7748 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 12:40:23.723  7344  7748 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 12:40:23.723  7344  7748 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 12:40:23.724  7344  7746 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-23 12:40:23.725  7344  7748 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 12:40:23.725  7344  7748 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 12:40:23.725  7344  7695 D bte_conf: Device ID record 1 : primary
08-23 12:40:23.725  7344  7695 D bte_conf:   vendorId            = 00c4
08-23 12:40:23.725  7344  7695 D bte_conf:   vendorIdSource      = 0001
08-23 12:40:23.725  7344  7695 D bte_conf:   product             = 13a1
08-23 12:40:23.725  7344  7695 D bte_conf:   version             = 1000
08-23 12:40:23.725  7344  7695 D bte_conf:   clientExecutableURL = 
08-23 12:40:23.725  7344  7695 D bte_conf:   serviceDescription  = 
08-23 12:40:23.725  7344  7695 D bte_conf:   documentationURL    = 
08-23 12:40:23.725  7344  7695 D bte_conf: bte_load_did_conf no section named DID2.
08-23 12:40:23.731  7344  7746 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 12:40:23.732  7344  7746 W bt-smp  : Plain text(LSB ~ MSB) = eb fe 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 12:40:23.732  7344  7746 W bt-smp  : Encrypted text(LSB ~ MSB) = 69 bc 26 92 2a 32 59 fd 0e cd a7 24 29 9f f0 18 
08-23 12:40:23.732  7344  7746 W bt-btm  : Stopping oneshot timer
08-23 12:40:23.732  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:23.720  7791  7791 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:23.720  7791  7791 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 12:40:23.736  7344  7789 E bt_mct  : hci lib postload completed
08-23 12:40:23.737  7344  7691 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-23 12:40:23.737  7344  7691 D BluetoothAdapterProperties: ScanMode =  20
08-23 12:40:23.737  7344  7691 D BluetoothAdapterProperties: State =  11
08-23 12:40:23.738  7344  7691 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-23 12:40:23.738  7344  7691 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-23 12:40:23.738  7344  7691 D BluetoothAdapterProperties: Setting state to 12
08-23 12:40:23.738  7344  7691 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 12:40:23.739  1034  1102 D BluetoothManagerService: Message: 60
08-23 12:40:23.739  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-23 12:40:23.739  1034  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-23 12:40:23.739  1034  1102 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 12:40:23.740  7344  7691 I BluetoothAdapterState: Entering On State
08-23 12:40:23.740  7344  7695 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-23 12:40:23.741  7344  7695 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 12:40:23.745  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:40:23.748  7344  7691 D LGBluetoothServiceAdapter: [BTUI] OnState
08-23 12:40:23.749  7344  7691 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-23 12:40:23.749  7344  7691 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-23 12:40:23.752  1034  1034 D BluetoothA2dp: Proxy object connected
08-23 12:40:23.753  7344  7691 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-23 12:40:23.754  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:23.754  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:23.754  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:23.754  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:40:23.754  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:23.754  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:23.754  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:23.754  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:40:23.763  1853  1853 D BluetoothHeadset: Proxy object connected
08-23 12:40:23.764  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:40:23.764  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:40:23.767  7344  7695 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 12:40:23.768  7344  7695 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-23 12:40:23.769  1853  1853 D BluetoothHeadset: Proxy object connected
08-23 12:40:23.770  7344  7746 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 12:40:23.770  7344  7746 W bt-smp  : Plain text(LSB ~ MSB) = 01 58 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 12:40:23.770  7344  7746 W bt-smp  : Encrypted text(LSB ~ MSB) = ec ca 04 f7 62 9b 80 6a 92 a3 50 77 05 7b 45 b1 
08-23 12:40:23.770  7344  7746 W bt-btm  : Stopping oneshot timer
08-23 12:40:23.771  1853  4467 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:40:23.774  1853  1853 D BluetoothHeadset: Proxy object connected
08-23 12:40:23.775  7192  7214 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 12:40:23.778  7192  7192 D BluetoothInputDevice: Proxy object connected
08-23 12:40:23.779  7192  7192 D HidProfile: Bluetooth service connected
08-23 12:40:23.779  1034  1102 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 12:40:23.781  1034  1034 D BluetoothHeadset: Proxy object connected
08-23 12:40:23.784  7192  7224 D BluetoothMap: onBluetoothStateChange: up=true
08-23 12:40:23.788  7192  7224 D BluetoothPan: onBluetoothStateChange on: true
08-23 12:40:23.788  7192  7224 D BluetoothPan: onBluetoothStateChange call bindService
08-23 12:40:23.789  7344  7746 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 12:40:23.789  7344  7746 W bt-smp  : Plain text(LSB ~ MSB) = 98 4d 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 12:40:23.790  7344  7746 W bt-smp  : Encrypted text(LSB ~ MSB) = b8 ef ec 08 97 5a 6c 4c 95 87 b9 ba c6 81 46 0d 
08-23 12:40:23.790  7344  7746 W bt-btm  : Stopping oneshot timer
08-23 12:40:23.790  7344  7691 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-23 12:40:23.793  7192  7228 D BluetoothPbap: onBluetoothStateChange: up=true
,08-23 12:40:23.797  7192  7192 D BluetoothMap: Proxy object connected
08-23 12:40:23.797  7192  7192 D MapProfile: Bluetooth service connected
08-23 12:40:23.797  7192  7192 D BluetoothMap: getConnectedDevices()
08-23 12:40:23.798  7344  7792 V BluetoothMapService: getConnectedDevices()
08-23 12:40:23.798  7192  7192 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 12:40:23.799  7192  7192 D PanProfile: Bluetooth service connected
08-23 12:40:23.801  7344  7746 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 12:40:23.801  7344  7746 W bt-smp  : Plain text(LSB ~ MSB) = 33 11 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 12:40:23.801  7344  7746 W bt-smp  : Encrypted text(LSB ~ MSB) = f8 b7 f6 cd ee 94 ad e8 09 80 8e b7 b2 47 dd e8 
08-23 12:40:23.801  7344  7746 W bt-btm  : Stopping oneshot timer
08-23 12:40:23.802  1034  1102 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-23 12:40:23.802  1034  1102 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-23 12:40:23.809  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-23 12:40:23.810  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 12:40:23.812  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:23.812  1941  2149 D LGBluetoothAPIService: Message: 1
08-23 12:40:23.812  1941  2149 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-23 12:40:23.815  7106  7106 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 12:40:23.818  1034  1102 D BluetoothManagerService: Message: 40
08-23 12:40:23.818  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-23 12:40:23.819  7344  7344 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:23.819  7797  7797 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-23 12:40:23.819  7344  7344 D BluetoothMapService: STATE_ON
08-23 12:40:23.819  7344  7344 V BluetoothMapService: Handler(): got msg=1
08-23 12:40:23.822  7344  7746 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 12:40:23.822  7344  7746 W bt-smp  : Plain text(LSB ~ MSB) = ff 6a 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 12:40:23.822  7344  7746 W bt-smp  : Encrypted text(LSB ~ MSB) = 3b 10 2b bc 71 a8 2a 21 46 0d e1 fc fa 7f 55 3e 
08-23 12:40:23.822  7344  7746 W bt-btm  : Stopping oneshot timer
,08-23 12:40:23.823  7344  7344 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-23 12:40:23.825  7344  7802 D BluetoothMapMasInstance: MAS initSocket()
08-23 12:40:23.826  7344  7802 D BluetoothMapMasInstance:   masId = 00
08-23 12:40:23.826  7344  7802 D BluetoothMapMasInstance:   msgTypes = 0e
08-23 12:40:23.826  7344  7802 D BluetoothMapMasInstance:   masName = SMS/MMS
08-23 12:40:23.826  7344  7802 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-23 12:40:23.828  1034  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:23.828  1941  2149 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-23 12:40:23.829  7192  7192 D LocalBluetoothProfileManager: Adding local A2DP profile
08-23 12:40:23.829  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:23.829  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:23.829  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:23.829  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:40:23.829  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:23.829  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:23.829  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:23.829  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:40:23.831  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:40:23.832  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:23.833  1034  1102 D BluetoothManagerService: Message: 30
08-23 12:40:23.835  7344  7802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:40:23.838  7344  7802 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-23 12:40:23.838  7344  7802 V BluetoothMapMasInstance: Succeed to create listening socket 
08-23 12:40:23.839  7344  7802 D BluetoothMapMasInstance: Accepting socket connection...
08-23 12:40:23.840  7192  7192 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-23 12:40:23.840  7344  7695 D BluetoothAdapterProperties: Scan Mode:21
08-23 12:40:23.840  7344  7695 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-23 12:40:23.844  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:23.844  1034  1102 D BluetoothManagerService: Message: 30
08-23 12:40:23.846  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:23.846  7344  7344 V BluetoothPbapService: Pbap Service onCreate
08-23 12:40:23.846  7344  7344 V BluetoothPbapService: Starting PBAP service
08-23 12:40:23.848  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:23.848  7344  7344 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-23 12:40:23.849  7344  7344 V BluetoothPbapService: Pbap Service onBind
08-23 12:40:23.850  7344  7344 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:23.850  7344  7344 V BluetoothPbapService: state: 12
,08-23 12:40:23.851  7192  7192 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-23 12:40:23.852  7344  7344 D LGBluetoothAPIServer: [BTUI] onCreate()
08-23 12:40:23.852  7344  7344 D LGBluetoothAPIServer: [BTUI] onBind()
08-23 12:40:23.853  7344  7344 V BluetoothPbapService: Handler(): got msg=1
08-23 12:40:23.853  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-23 12:40:23.853  1941  2149 D LGBluetoothAPIService: Message: 100
08-23 12:40:23.853  1941  2149 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-23 12:40:23.853  7344  7344 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-23 12:40:23.855  7192  7192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 12:40:23.856  7344  7806 V BluetoothPbapService: Pbap Service initSocket
08-23 12:40:23.857  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:23.858  7192  7192 D BluetoothA2dp: Proxy object connected
08-23 12:40:23.858  7344  7806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:40:23.859  7192  7192 D A2dpProfile: Bluetooth service connected
08-23 12:40:23.860  7344  7806 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-23 12:40:23.860  7344  7344 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 12:40:23.860  7344  7344 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:23.860  7344  7344 V BluetoothPbapReceiver: ***********state = 12
08-23 12:40:23.860  7344  7806 V BluetoothPbapService: Succeed to create listening socket 
08-23 12:40:23.860  7344  7806 V BluetoothPbapService: Accepting socket connection...
,08-23 12:40:23.863  7192  7192 D BluetoothHeadset: Proxy object connected
08-23 12:40:23.864  7192  7192 D HeadsetProfile: Bluetooth service connected
08-23 12:40:23.864  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 12:40:23.865  2198  2198 D c       : Getting all permits...
08-23 12:40:23.865  2198  2198 D a       : Opening database...
08-23 12:40:23.866  7192  7192 D BluetoothPbap: Proxy object connected
08-23 12:40:23.867  7192  7192 D PbapServerProfile: Bluetooth service connected
08-23 12:40:23.869  2198  2198 D a       : Opening database auth.proximity.permit_store...
08-23 12:40:23.869  7192  7192 D DockEventReceiver: finishStartingService: stopping service
08-23 12:40:23.869  2198  2198 D a       : Closing database...
08-23 12:40:23.870  7563  7584 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-23 12:40:23.881  7192  7192 D BluetoothPermissionRequest: onReceive
,08-23 12:40:23.883  7192  7192 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-23 12:40:23.884  7192  7192 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 12:40:23.887  7344  7344 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-23 12:40:23.888  7344  7344 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-23 12:40:23.893  7344  7344 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-23 12:40:23.912  7344  7344 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-23 12:40:23.912  7344  7344 V BtOppService: onCreate
08-23 12:40:23.917  7344  7344 V BluetoothOppNotification: send message
08-23 12:40:23.921  7344  7344 V BtOppService: Starting RfcommListener
08-23 12:40:23.929  7344  7344 D BluetoothOppPreference: Dumping Names:  
08-23 12:40:23.929  7344  7344 D BluetoothOppPreference: {}
08-23 12:40:23.930  7344  7344 D BluetoothOppPreference: Dumping Channels:  
08-23 12:40:23.930  7344  7344 D BluetoothOppPreference: {}
08-23 12:40:23.930  7344  7344 V BtOppService: onStartCommand
,08-23 12:40:23.935  7344  7815 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 12:40:23.936  7344  7812 V BtOppService: Deleted complete outbound shares, number =  0
08-23 12:40:23.936  7344  7344 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:23.937  7344  7344 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-23 12:40:23.938  7344  7815 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 12:40:23.939  7344  7812 V BtOppService: Deleted complete inbound failed shares, number = 0
08-23 12:40:23.940  7344  7812 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-23 12:40:23.942  7344  7344 V BluetoothOppNotification: new notify threadi!
08-23 12:40:23.943  7344  7344 V BluetoothOppNotification: send delay message
,08-23 12:40:23.945  7344  7812 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16f56c12 on behalf of 
,08-23 12:40:23.947  7344  7344 V BtOppService: start RfcommListener
08-23 12:40:23.948  7344  7815 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3558afe3 on behalf of 
08-23 12:40:23.948  7344  7816 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-23 12:40:23.950  7344  7815 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 12:40:23.952  7344  7816 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28ec3de0 on behalf of 
08-23 12:40:23.953  7344  7816 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-23 12:40:23.955  7344  7816 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-23 12:40:23.956  7344  7344 V BtOppService: RfcommListener started
08-23 12:40:23.957  7344  7344 V BtOppService: ContentObserver received notification
08-23 12:40:23.958  7344  7816 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22b0c899 on behalf of 
08-23 12:40:23.958  7344  7344 V BtOppService: ContentObserver received notification
,08-23 12:40:23.960  7344  7816 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 12:40:23.962  7344  7818 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 12:40:23.962  7344  7818 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 12:40:23.963  7344  7816 V BluetoothOppNotification: outbound notification was removed.
08-23 12:40:23.963  7344  7816 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 12:40:23.964  7344  7817 V BtOppRfcommListener: Starting RFCOMM listener....
08-23 12:40:23.965  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:23.965  7344  7818 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21ba375e on behalf of 
08-23 12:40:23.967  7344  7817 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:40:23.967  7344  7816 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9dc673f on behalf of 
08-23 12:40:23.968  7344  7817 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
,08-23 12:40:23.971  7344  7818 V BluetoothOppNotification: update too frequent, put in queue
08-23 12:40:23.971  7344  7816 V BluetoothOppNotification: inbound: succ-0  fail-0
08-23 12:40:23.971  7344  7817 V BtOppRfcommListener: Started RFCOMM listener....
08-23 12:40:23.972  7344  7817 I BtOppRfcommListener: Accept thread started.
08-23 12:40:23.972  7344  7817 V BtOppRfcommListener: Accepting connection...
08-23 12:40:23.973  7344  7818 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 12:40:23.974  7344  7816 V BluetoothOppNotification: inbound notification was removed.
08-23 12:40:23.974  7344  7816 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-23 12:40:23.977  7344  7816 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3407580c on behalf of 
08-23 12:40:23.980  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:23.981  7344  7344 V BluetoothFtpService: Ftp Service onCreate
08-23 12:40:23.981  7344  7344 I BluetoothFtpService: Ftp Service onCreate
08-23 12:40:23.981  7344  7344 V BluetoothFtpService: Ftp Service onStartCommand
08-23 12:40:23.981  7344  7344 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:23.981  7344  7344 V BluetoothFtpService: Starting Listening on sockets
,08-23 12:40:23.982  7344  7344 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 12:40:23.982  7344  7344 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 12:40:23.982  7344  7344 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 12:40:23.982  7344  7344 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:23.982  7344  7344 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-23 12:40:23.982  7344  7344 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-23 12:40:23.986  7344  7344 V BluetoothFtpService: Handler(): got msg=1
08-23 12:40:23.988  7344  7344 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-23 12:40:23.988  7344  7344 V BluetoothFtpService: Ftp Service initSocket
08-23 12:40:23.992  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:23.993  7344  7344 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:40:23.996  7344  7344 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-23 12:40:23.999  7344  7819 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-23 12:40:24.024  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:24.024  7344  7344 V BluetoothSapService: Sap Service onCreate
,08-23 12:40:24.026  7344  7344 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:24.026  7344  7344 V BluetoothSapService: state: 12
08-23 12:40:24.026  7344  7344 V BluetoothSapService: Starting SAP server process
08-23 12:40:24.029  7344  7344 V BluetoothSapService: SAP Service startRfcommListenerThread
08-23 12:40:24.020  7820  7820 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:24.020  7820  7820 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:24.034  7344  7821 V BluetoothSapService: Sap Service initRfcommSocket
08-23 12:40:24.035  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:24.036  7344  7821 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:40:24.038  7344  7821 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-23 12:40:24.038  7344  7821 V BluetoothSapService: Succeed to create listening socket 
08-23 12:40:24.039  7344  7821 V BluetoothSapService: Accepting socket connection...
,08-23 12:40:24.052  7820  7820 V BT_SAP  : Event pipe created
,08-23 12:40:24.053  7820  7820 V BT_SAP  : create_server_socket qcom.sap.server
08-23 12:40:24.053  7820  7820 V BT_SAP  : created socket fd 6
,08-23 12:40:24.641  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 12:40:24.641  1034  1390 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 12:40:24.653  1034  1392 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-23 12:40:24.654  1034  1392 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-23 12:40:24.945  7344  7344 V BluetoothOppNotification: new notify threadi!
08-23 12:40:24.946  7344  7344 V BluetoothOppNotification: send delay message
,08-23 12:40:24.961  7344  7831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-23 12:40:24.967  7344  7831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27b9f1d1 on behalf of 
08-23 12:40:24.968  7344  7831 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-23 12:40:24.971  7344  7831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-23 12:40:24.972  7344  7831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a7fd436 on behalf of 
08-23 12:40:24.973  7344  7831 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 12:40:24.975  7344  7831 V BluetoothOppNotification: outbound notification was removed.
08-23 12:40:24.975  7344  7831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 12:40:24.976  7344  7831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22d9ff37 on behalf of 
08-23 12:40:24.977  7344  7831 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-23 12:40:24.981  7344  7831 V BluetoothOppNotification: inbound notification was removed.
,08-23 12:40:24.981  7344  7831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-23 12:40:24.983  7344  7831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e1e9ca4 on behalf of 
08-23 12:40:25.669  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:25.670  1034  2032 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@14954050 mBinding = false
,08-23 12:40:25.712  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 12:40:25.712  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 12:40:25.712  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-23 12:40:25.715  1034  1102 D BluetoothManagerService: Message: 2
08-23 12:40:25.716  1034  1102 D BluetoothManagerService: Sending off request.
08-23 12:40:25.717  7344  7361 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-23 12:40:25.718  7344  7691 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-23 12:40:25.718  7344  7691 D BluetoothAdapterProperties: Setting state to 13
08-23 12:40:25.718  7344  7691 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 12:40:25.719  7344  7691 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 12:40:25.719  7344  7691 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-23 12:40:25.721  7344  7695 D BluetoothAdapterProperties: Scan Mode:20
08-23 12:40:25.723  7344  7691 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-23 12:40:25.724  7344  7802 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-23 12:40:25.724  7344  7802 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:40:25.724  7344  7802 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-23 12:40:25.724  7344  7802 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-23 12:40:25.724  7344  7802 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-23 12:40:25.724  7344  7802 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-23 12:40:25.724  7344  7802 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-23 12:40:25.724  7344  7802 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-23 12:40:25.729  7344  7806 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:40:25.729  7344  7817 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:40:25.730  7344  7821 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:40:25.731  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-23 12:40:25.731  7344  7746 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-23 12:40:25.733  7344  7691 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 12:40:25.736  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 12:40:25.737  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 12:40:25.737  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 12:40:25.737  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 12:40:25.737  7344  7746 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:40:25.737  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 12:40:25.737  7344  7746 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:40:25.737  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 12:40:25.737  7344  7746 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 12:40:25.737  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-23 12:40:25.737  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-23 12:40:25.737  7344  7746 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-23 12:40:25.743  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:25.743  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:25.743  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:25.743  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:25.743  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:40:25.743  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:25.743  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:25.743  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:25.743  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:40:25.745  7344  7819 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:40:25.750  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:25.751  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:40:25.759  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:25.759  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:25.759  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:25.759  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:25.759  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:40:25.759  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:40:25.759  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:25.759  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:25.759  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:40:25.761  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:40:25.761  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:40:25.763  1034  1102 D BluetoothManagerService: Message: 60
08-23 12:40:25.763  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-23 12:40:25.763  1034  1102 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-23 12:40:25.766  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:40:25.770  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 12:40:25.775  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:25.777  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:40:25.780  7344  7344 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:25.780  7344  7344 D BluetoothMapService: STATE_TURNING_OFF
08-23 12:40:25.781  7344  7344 V BluetoothMapService: Handler(): got msg=4
08-23 12:40:25.781  7344  7344 D BluetoothMapService: MAP Service closeService in
08-23 12:40:25.781  7344  7344 D BluetoothMapMasInstance: MAP Service shutdown
08-23 12:40:25.781  7344  7344 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 12:40:25.781  7344  7344 V BluetoothMapService: MAP Service closeService out
08-23 12:40:25.782  7344  7344 V BtOppService: Receiver DISABLED_ACTION 
08-23 12:40:25.782  7344  7344 I BtOppRfcommListener: stopping Accept Thread
08-23 12:40:25.782  7344  7344 V BtOppRfcommListener: close mBtServerSocket
08-23 12:40:25.783  7344  7817 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 12:40:25.783  7344  7344 V BtOppRfcommListener: waiting for thread to terminate
08-23 12:40:25.783  7344  7344 V BtOppRfcommListener: done waiting for thread to terminate
08-23 12:40:25.787  7192  7192 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-23 12:40:25.801  7192  7192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 12:40:25.803  7344  7344 V BtOppService: onDestroy
08-23 12:40:25.804  7344  7344 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-23 12:40:25.809  7344  7344 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 12:40:25.809  7344  7344 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:25.809  7344  7344 V BluetoothPbapReceiver: ***********state = 13
,08-23 12:40:25.813  7344  7344 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-23 12:40:25.815  7344  7344 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:25.815  7344  7344 V BluetoothPbapService: state: 13
08-23 12:40:25.816  7344  7344 V BluetoothPbapService: Pbap Service closeService in
08-23 12:40:25.818  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 12:40:25.819  7344  7344 V BluetoothPbapService: successfully stopped pbap service
08-23 12:40:25.819  7344  7344 V BluetoothPbapService: Pbap Service closeService out
08-23 12:40:25.820  7344  7344 V BluetoothPbapService: Pbap Service onDestroy
08-23 12:40:25.820  7344  7344 V BluetoothPbapService: Pbap Service closeService in
08-23 12:40:25.820  7344  7344 V BluetoothPbapService: Pbap Service closeService out
08-23 12:40:25.820  7344  7344 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-23 12:40:25.843  7192  7192 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:40:25.846  7192  7192 D BluetoothPbap: Proxy object disconnected
08-23 12:40:25.846  7192  7192 D PbapServerProfile: Bluetooth service disconnected
08-23 12:40:25.850  7192  7192 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-23 12:40:25.853  7192  7192 D BluetoothPermissionRequest: onReceive
08-23 12:40:25.853  7192  7192 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-23 12:40:25.858  7192  7192 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-23 12:40:25.861  7344  7344 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-23 12:40:25.862  7344  7344 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-23 12:40:25.862  7344  7344 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-23 12:40:25.866  7344  7344 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:25.866  7344  7344 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-23 12:40:25.867  7344  7344 V BluetoothFtpService: Ftp Service onStartCommand
08-23 12:40:25.867  7344  7344 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:25.867  7344  7344 V BluetoothFtpService: Ftp Service closeService
08-23 12:40:25.868  7344  7344 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-23 12:40:25.869  7344  7344 V BluetoothFtpService: successfully stopped ftp service
08-23 12:40:25.869  7344  7344 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 12:40:25.869  7344  7344 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 12:40:25.869  7344  7344 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 12:40:25.869  7344  7344 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:25.869  7344  7344 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-23 12:40:25.869  7344  7344 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-23 12:40:25.871  7344  7344 V BluetoothFtpService: Ftp Service onDestroy
,08-23 12:40:25.871  7344  7344 V BluetoothFtpService: Ftp Service closeService
08-23 12:40:25.875  7344  7344 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:25.875  7344  7344 V BluetoothSapService: state: 13
08-23 12:40:25.875  7344  7344 V BluetoothSapService: Stopping SAP server process
08-23 12:40:25.876  7344  7344 V BluetoothSapService: Sap Service closeSapService in
08-23 12:40:25.877  7344  7344 V BluetoothSapService: Close listen Socket : 
08-23 12:40:25.877  7344  7344 V BluetoothSapService: Close rfcomm Socket : 
,08-23 12:40:25.877  7344  7344 V BluetoothSapService: Close sapd  Socket : ,
08-23 12:40:25.879  7344  7344 V BluetoothSapService: Sap Service closeSapService out
,08-23 12:40:25.879  7344  7344 V BluetoothSapService: Sap Service onDestroy
,08-23 12:40:25.879  7344  7344 V BluetoothSapService: Sap Service closeSapService in
08-23 12:40:25.879  7344  7344 V BluetoothSapService: Close listen Socket : ,
08-23 12:40:25.879  7344  7344 V BluetoothSapService: Close rfcomm Socket : 
,08-23 12:40:25.879  7344  7344 V BluetoothSapService: Close sapd  Socket : 
08-23 12:40:25.880  7344  7344 V BluetoothSapService: Sap Service closeSapService out
08-23 12:40:26.641  7344  7695 D bt_hci_bdroid: cleanup
,08-23 12:40:26.658  7344  7748 I bt_lpm  : LPM is already off!!!,
08-23 12:40:26.659  7344  7789 I bt_userial_mct: exiting userial_read_thread
08-23 12:40:26.659  7344  7789 D bt_userial_mct: Leaving userial_evt_read_thread()
08-23 12:40:26.660  7344  7746 W bt-btif : ag scb idx 1 not allocated
08-23 12:40:26.660  7344  7746 E bt-btif : BTA AG is already disabled, ignoring ...
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 12:40:26.660  7344  7746 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 12:40:26.660  7344  7746 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-23 12:40:26.661  7344  7695 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0,
08-23 12:40:26.661  7344  7748 I bt_vendor: hw_epilog_process
08-23 12:40:26.661  7344  7695 D bt_hci_bdroid: cleanup Finalizing cleanup
08-23 12:40:26.662  7344  7695 D bt_userial_mct: userial_close
,08-23 12:40:26.662  7344  7695 E bt_userial_mct: pthread_join() FAILED result:3
08-23 12:40:26.662  7344  7695 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-23 12:40:26.676  7344  7695 D bt_hci_bdroid: set_power 0,
08-23 12:40:26.676  7344  7695 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 12:40:26.677  7344  7695 I bt_vendor: bluetooth satus is on
08-23 12:40:26.677  7344  7695 I bt_vendor: bt-vendor : resetting BT status
08-23 12:40:26.677  7344  7695 I bt_vendor: Starting hciattach daemon
08-23 12:40:26.677  7344  7695 I bt_vendor: try to set false
,08-23 12:40:26.681  7344  7695 I bt_vendor: Starting hciattach daemon
08-23 12:40:26.681  7344  7695 I bt_vendor: try to set false
08-23 12:40:26.682  7344  7695 I bt_vendor: cleanup
08-23 12:40:26.682  7344  7746 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-23 12:40:26.683  7344  7695 I GKI_LINUX: GKI_exit_task 0 done
08-23 12:40:26.683  7344  7695 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-23 12:40:26.685  7344  7691 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-23 12:40:26.692  7344  7344 D HeadsetService: Received stop request...Stopping profile...
,08-23 12:40:26.697  7344  7344 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 12:40:26.697  7344  7344 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 12:40:26.697  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:26.698  7344  7730 D HeadsetStateMachine: Exit Disconnected: -1
08-23 12:40:26.699  7344  7691 D BluetoothAdapterState: Stopping profile services that were post enabled
08-23 12:40:26.700  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-23 12:40:26.701  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-23 12:40:26.701  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-23 12:40:26.701  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-23 12:40:26.702  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-23 12:40:26.703  7344  7344 D A2dpService: Received stop request...Stopping profile...
08-23 12:40:26.703  7344  7738 D A2dpStateMachine: Exit Disconnected: -1
08-23 12:40:26.705  7344  7344 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-23 12:40:26.711  7344  7344 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-23 12:40:26.711  7344  7344 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 12:40:26.711  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:26.712  7344  7344 D HidService: Received stop request...Stopping profile...
08-23 12:40:26.712  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:26.714  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-23 12:40:26.714  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-23 12:40:26.714  7344  7344 D HealthService: Received stop request...Stopping profile...
08-23 12:40:26.715  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:26.717  7344  7344 D PanService: Received stop request...Stopping profile...
08-23 12:40:26.719  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:26.723  7344  7344 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 12:40:26.724  7344  7344 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 12:40:26.724  7344  7344 D BtGatt.GattService: stop()
08-23 12:40:26.725  7344  7344 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 12:40:26.726  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:26.727  7344  7344 D BluetoothMapService: Received stop request...Stopping profile...
08-23 12:40:26.727  7344  7344 D BluetoothMapService: stop()
08-23 12:40:26.728  7344  7344 D BluetoothMapEmailAppObserver: deinitObservers()
08-23 12:40:26.728  7344  7344 D BluetoothMapEmailAppObserver: removeReceiver()
08-23 12:40:26.728  7344  7344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20514c11
08-23 12:40:26.731  7344  7344 D HeadsetStateMachine: Unbinding service...
,08-23 12:40:26.734  7344  7344 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 12:40:26.734  7344  7344 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 12:40:26.734  7344  7344 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 12:40:26.734  7344  7344 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 12:40:26.734  7344  7344 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 12:40:26.734  7344  7344 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 12:40:26.734  7344  7344 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 12:40:26.734  7344  7344 I BluetoothA2dpServiceJni: cleanupNative
08-23 12:40:26.735  7344  7739 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-23 12:40:26.735  7344  7344 I GKI_LINUX: GKI_exit_task 2 done
08-23 12:40:26.735  7344  7344 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-23 12:40:26.735  7344  7344 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 12:40:26.735  7344  7344 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 12:40:26.736  7344  7344 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 12:40:26.736  7344  7344 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 12:40:26.736  7344  7344 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 12:40:26.736  7344  7344 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 12:40:26.736  7344  7344 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 12:40:26.742  7344  7344 V BluetoothMapService: Handler(): got msg=4
08-23 12:40:26.742  7344  7344 D BluetoothMapService: MAP Service closeService in
08-23 12:40:26.742  7344  7344 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 12:40:26.742  7344  7344 V BluetoothMapService: MAP Service closeService out
08-23 12:40:26.747  7344  7691 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-23 12:40:26.747  7344  7691 D BluetoothAdapterProperties: Setting state to 10
08-23 12:40:26.747  7344  7691 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-23 12:40:26.747  7344  7344 D BluetoothMapService: cleanup()
08-23 12:40:26.747  7344  7344 D BluetoothMapService: MAP Service closeService in
08-23 12:40:26.747  7344  7344 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 12:40:26.747  7344  7344 V BluetoothMapService: MAP Service closeService out
08-23 12:40:26.748  1034  1102 D BluetoothManagerService: Message: 60
08-23 12:40:26.749  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-23 12:40:26.749  1034  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-23 12:40:26.749  1034  1102 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:40:26.749  7344  7691 I BluetoothAdapterState: Entering OffState
08-23 12:40:26.749  1853  2434 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:40:26.750  1853  2671 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:40:26.751  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:40:26.751  7192  7224 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:40:26.752  7192  7224 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 12:40:26.752  1034  1102 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:40:26.753  7192  7224 D BluetoothMap: onBluetoothStateChange: up=false
08-23 12:40:26.753  7192  7224 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:40:26.754  7192  7224 D BluetoothPan: onBluetoothStateChange on: false
08-23 12:40:26.754  7192  7224 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 12:40:26.756  1034  1102 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-23 12:40:26.757  1034  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-23 12:40:26.761  1034  1102 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-23 12:40:26.761  1034  1102 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-23 12:40:26.761  1034  1102 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@14954050 mBinding = false
08-23 12:40:26.762  1034  1102 D BluetoothManagerService: Sending unbind request.
08-23 12:40:26.767  7344  7695 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-23 12:40:26.768  7344  7344 I GKI_LINUX: GKI_exit_task 1 done
08-23 12:40:26.768  7344  7344 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-23 12:40:26.769  7344  7344 I BluetoothServiceJni: cleanupNative: return from cleanup
08-23 12:40:26.769  7344  7344 I art     : --- WEIRD: removing null entry 248
08-23 12:40:26.769  7344  7344 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-23 12:40:26.769  7344  7344 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-23 12:40:26.772  7344  7344 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-23 12:40:26.773  1034  1102 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-23 12:40:26.775  7344  7344 I art     : System.exit called, status: 0
08-23 12:40:26.775  7344  7344 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-23 12:40:26.794   326  1402 V AudioFlinger: 7344 died, releasing its sessions
08-23 12:40:26.794   326  1402 V AudioFlinger:  pid 1853 @ 0
08-23 12:40:26.794   326  1402 V AudioFlinger:  pid 3445 @ 1
08-23 12:40:26.794   326  1402 V AudioFlinger:  pid 3445 @ 2
,08-23 12:40:26.798  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-23 12:40:26.798  1941  2149 D LGBluetoothAPIService: Message: 101
08-23 12:40:26.798  1941  2149 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-23 12:40:26.798  1941  2149 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-23 12:40:26.799  1941  2149 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-23 12:40:26.800  7192  7192 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-23 12:40:26.806  1034  1728 I ActivityManager: Process com.android.bluetooth (pid 7344) has died
08-23 12:40:26.806  1034  1728 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-23 12:40:26.807  1034  1728 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-23 12:40:26.813  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:40:26.815  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 12:40:26.818  1941  2149 D LGBluetoothAPIService: Message: 2
08-23 12:40:26.818  1941  2149 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-23 12:40:26.823  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:26.824  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:26.832  7192  7192 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-23 12:40:26.832  7192  7192 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-23 12:40:26.837  1602  1602 D BluetoothAdapter: 253161107: getState() :  mService = null. Returning STATE_OFF
08-23 12:40:26.837  1602  1602 D BluetoothAdapter: 253161107: getState() :  mService = null. Returning STATE_OFF
08-23 12:40:26.980  1034  1050 I art     : Explicit concurrent mark sweep GC freed 69837(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.422ms total 142.232ms
08-23 12:40:26.981  7192  7192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-23 12:40:27.076  1034  1923 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7879 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-23 12:40:27.077  7192  7192 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:40:27.155  7879  7879 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-23 12:40:27.155  7879  7879 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 12:40:27.156  7879  7879 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-23 12:40:27.157  7879  7879 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 12:40:27.177  7879  7879 D BluetoothAdapterApp: Loading JNI Library
,08-23 12:40:27.214  7879  7879 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@781ad9 Instance Count = 1
,08-23 12:40:27.221  7879  7879 D BluetoothAdapterApp: onCreate
08-23 12:40:27.246  7879  7879 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-23 12:40:27.246  7879  7879 D ProfileConfigQcom: Adding HeadsetService
08-23 12:40:27.246  7879  7879 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-23 12:40:27.247  7879  7879 D ProfileConfigQcom: Adding A2dpService
08-23 12:40:27.247  7879  7879 D ProfileConfigQcom: [BTUI] HidService is supported
08-23 12:40:27.247  7879  7879 D ProfileConfigQcom: Adding HidService
08-23 12:40:27.247  7879  7879 D ProfileConfigQcom: [BTUI] HealthService is supported
08-23 12:40:27.248  7879  7879 D ProfileConfigQcom: Adding HealthService
08-23 12:40:27.248  7879  7879 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-23 12:40:27.249  7879  7879 D ProfileConfigQcom: [BTUI] PanService is supported
,08-23 12:40:27.249  7879  7879 D ProfileConfigQcom: Adding PanService
08-23 12:40:27.249  7879  7879 D ProfileConfigQcom: [BTUI] GattService is supported
08-23 12:40:27.249  7879  7879 D ProfileConfigQcom: Adding GattService
08-23 12:40:27.249  7879  7879 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-23 12:40:27.250  7879  7879 D ProfileConfigQcom: Adding BluetoothMapService
08-23 12:40:27.250  7879  7879 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-23 12:40:27.251  7879  7879 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 12:40:27.252  7879  7879 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:27.252  7879  7879 V BluetoothPbapReceiver: ***********state = 10
08-23 12:40:27.254  7879  7879 V LGMDMManagerInternal: Create singleton instance
08-23 12:40:27.343  7879  7879 D LGBluetoothAPIServer: [BTUI] onCreate()
08-23 12:40:27.343  7879  7879 D LGBluetoothAPIServer: [BTUI] onBind()
08-23 12:40:27.346  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 12:40:27.351  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-23 12:40:27.351  1941  2149 D LGBluetoothAPIService: Message: 100
08-23 12:40:27.351  1941  2149 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-23 12:40:27.361  7192  7192 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-23 12:40:27.369  7192  7192 D BluetoothPermissionRequest: onReceive
,08-23 12:40:27.371  7192  7192 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-23 12:40:27.371  7192  7192 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-23 12:40:27.374  7192  7192 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 12:40:27.383  7879  7879 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-23 12:40:27.388  7879  7879 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:27.392  7879  7879 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 12:40:27.393  7879  7879 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 12:40:27.393  7879  7879 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 12:40:27.394  7879  7879 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:40:27.394  7879  7879 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-23 12:40:27.404  7754  7754 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-23 12:40:27.439  1034  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{36d5606f type 2 when 204894 com.google.android.gms} when 204894
,08-23 12:40:27.449   321  7904 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-23 12:40:27.450  1034  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-23 12:40:28.794  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:40:28.794  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:40:31.810  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 12:40:31.811  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10cdbc75 added. We now have 6 listener(s)
08-23 12:40:31.811  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:40:31.820  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:31.820  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e83140a added. We now have 7 listener(s)
08-23 12:40:31.820  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:31.821  7106  7172 I System.out: IsBluetoothEnabled
08-23 12:40:31.822  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:31.822  1034  1995 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-23 12:40:31.822  1034  1102 D BluetoothManagerService: Message: 2
08-23 12:40:31.825  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:31.826  1034  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:31.826  1034  1772 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-23 12:40:31.853  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 12:40:31.853  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 12:40:31.853  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-23 12:40:31.854  1034  1102 D BluetoothManagerService: Message: 1
08-23 12:40:31.854  1034  1102 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-23 12:40:31.881  1034  1102 D BluetoothManagerService: Message: 20
08-23 12:40:31.882  1034  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c70c968:true
,08-23 12:40:31.886  7879  7879 D BluetoothAdapterState: make
08-23 12:40:31.891  7879  7879 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-23 12:40:31.891  7879  7879 I bluedroid-qcom: init
08-23 12:40:31.893  7879  7914 I BluetoothAdapterState: Entering OffState
08-23 12:40:31.893  7879  7879 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-23 12:40:31.893  7879  7879 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 12:40:31.894  7879  7879 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 12:40:31.894  7879  7879 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 12:40:31.894  7879  7879 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-23 12:40:31.896  7879  7879 I bluedroid-qcom: get_profile_interface socket
08-23 12:40:31.896  7879  7879 I bluedroid-qcom: get_profile_interface map_client
,08-23 12:40:31.901  7879  7918 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-23 12:40:31.903  7879  7918 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-23 12:40:31.891  7917  7917 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:31.891  7917  7917 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:31.913  7917  7917 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-23 12:40:31.913  7917  7917 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-23 12:40:31.913  7917  7917 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-23 12:40:31.919  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-23 12:40:31.919  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-23 12:40:31.920  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-23 12:40:31.921  1034  1102 D BluetoothManagerService: Message: 40
08-23 12:40:31.921  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-23 12:40:31.921  7879  7896 I bluedroid-qcom: config_hci_snoop_log
08-23 12:40:31.923  1034  1102 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-23 12:40:31.923  1034  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-23 12:40:31.924  7917  7917 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-23 12:40:31.926  7879  7918 D BluetoothAdapterProperties: Name is: G3
,08-23 12:40:31.933  7879  7914 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-23 12:40:31.933  7879  7914 D BluetoothAdapterProperties: Setting state to 11
08-23 12:40:31.933  7879  7914 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-23 12:40:31.936  7879  7914 I LGBluetoothServiceJni: classInitNative: succeeds
08-23 12:40:31.937  1034  1102 D BluetoothManagerService: Message: 60
08-23 12:40:31.937  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-23 12:40:31.937  1034  1102 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-23 12:40:31.941  7917  7917 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-23 12:40:31.941  7917  7917 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-23 12:40:31.944  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:31.946  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 12:40:31.951  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:40:31.954  7192  7192 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-23 12:40:31.979  7879  7879 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 12:40:31.979  7879  7879 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED,
08-23 12:40:31.979  7879  7879 V BluetoothPbapReceiver: ***********state = 11
,08-23 12:40:31.985  7879  7914 D BluetoothBondStateMachine: make
08-23 12:40:31.987  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 12:40:31.990  7879  7914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:31.990  7879  7914 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-23 12:40:31.990  7879  7914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:31.991  7879  7914 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-23 12:40:31.991  7879  7914 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-23 12:40:31.995  7879  7914 E BluetoothAdapterService: File transfer profiles supported!!
08-23 12:40:31.997  7879  7932 I BluetoothBondStateMachine: StableState(): Entering Off State
08-23 12:40:32.004  7879  7914 E BluetoothAdapterService: File transfer profiles supported!!
08-23 12:40:32.006  7879  7879 D HeadsetService: Received start request. Starting profile...
08-23 12:40:32.007  7879  7879 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 12:40:32.007  7879  7879 D LGBluetoothHfpAdapter: Version 1.6
,08-23 12:40:32.007  7192  7192 D BluetoothPermissionRequest: onReceive
08-23 12:40:32.010  7879  7879 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 12:40:32.012  7879  7879 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 12:40:32.012  7879  7879 D HeadsetStateMachine: make
08-23 12:40:32.013  7192  7192 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 12:40:32.018  7879  7914 E BluetoothAdapterService: File transfer profiles supported!!
08-23 12:40:32.023  7879  7914 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 12:40:32.028  7879  7914 E BluetoothAdapterService: File transfer profiles supported!!
08-23 12:40:32.034  7879  7914 E BluetoothAdapterService: File transfer profiles supported!!
08-23 12:40:32.039  7879  7914 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 12:40:32.048  7879  7879 D LgDataFeature: LgDataFeature() Constructor: none
08-23 12:40:32.048  7879  7879 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 12:40:32.053  7879  7879 D HeadsetStateMachine: max_hf_connections = 1
08-23 12:40:32.053  7879  7879 I bluedroid-qcom: get_profile_interface handsfree
08-23 12:40:32.054  7879  7914 V LGMDMManager: Create singleton instance
08-23 12:40:32.055  7879  7879 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-23 12:40:32.055   326  2127 V AudioPolicyService: registerClient() client 0xb10030c0, uid 1002
08-23 12:40:32.056   326   326 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-23 12:40:32.056   326   326 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 12:40:32.056   326   326 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 12:40:32.056  7879  7879 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-23 12:40:32.056   326  2126 V AudioFlinger: registerClient() client 0xb55814c0, pid 7879
08-23 12:40:32.056   326  1397 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:32.056   326  1397 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 12:40:32.057  3445  3460 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:32.057  7879  7896 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:32.057  3445  3460 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 12:40:32.057  1034  1923 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:32.057  1034  1923 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 12:40:32.057  1602  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:32.057  1602  1618 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 12:40:32.057  1853  2434 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 12:40:32.057  1853  2434 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 12:40:32.057   326  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:40:32.057   326  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 12:40:32.057  1034  1728 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:40:32.057  1034  1728 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 12:40:32.057  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:40:32.058  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 12:40:32.058  3445  3461 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:40:32.058  3445  3461 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 12:40:32.058  1602  2095 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:40:32.058  1602  2095 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 12:40:32.059  7879  7896 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-23 12:40:32.059  7879  7896 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 12:40:32.059  7879  7896 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-23 12:40:32.059  7879  7914 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-23 12:40:32.059  7879  7879 V ToneGenerator: Create Track: 0xb4928a80
08-23 12:40:32.059  7879  7879 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-23 12:40:32.059  7879  7879 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-23 12:40:32.060   326  1402 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 12:40:32.060   326  1402 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-23 12:40:32.060   326  1402 V AudioPolicyManagerEx: Aud,ioPolicyManagerEx: getOutputForDevice
08-23 12:40:32.060   326  1402 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 12:40:32.060   326  2127 I AudioFlinger: isAudioPlaybackHookOn() false
08-23 12:40:32.061   326   326 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 12:40:32.061   326   326 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-23 12:40:32.061   326   326 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 12:40:32.061   326   326 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 12:40:32.061  7879  7879 V AudioSystem: getLatency() output 2, latency 50
08-23 12:40:32.061  7879  7879 V AudioSystem: getFrameCount() output 2, frameCount 960
08-23 12:40:32.061  7879  7879 V AudioTrack: createTrack_l() output 2 afLatency 50
08-23 12:40:32.061   326  2126 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-23 12:40:32.061   326  2126 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 12:40:32.061   326  2126 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-23 12:40:32.061   326  2126 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 12:40:32.061   326  2126 V AudioFlinger: createTrack() lSessionId: 21
08-23 12:40:32.062  7879  7879 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-23 12:40:32.062   326  2126 V AudioFlinger: acquiring 21 from 7879, for 7879
08-23 12:40:32.062   326  2126 V AudioFlinger:  added new entry for 21
,08-23 12:40:32.062  7879  7879 V ToneGenerator: ToneGenerator INIT OK, time: 209536
08-23 12:40:32.062  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:32.063  7879  7936 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-23 12:40:32.063  7879  7936 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 12:40:32.064  7879  7936 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 12:40:32.064  7879  7936 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-23 12:40:32.065   326  1403 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7879
08-23 12:40:32.065   326  1403 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-23 12:40:32.065   326  1403 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-23 12:40:32.065   326  1403 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-23 12:40:32.065   326  1403 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-23 12:40:32.065   326  1403 V voice   : voice_set_parameters: exit with code(0)
08-23 12:40:32.065   326  1403 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-23 12:40:32.065   326  1403 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-23 12:40:32.066  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:32.066   326  1403 V msm8974_platform: platform_set_parameters: exit with code(0)
08-23 12:40:32.066   326  1403 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-23 12:40:32.066   326  1403 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-23 12:40:32.066   326  1403 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-23 12:40:32.066  7879  7936 V ToneGenerator: ToneGenerator destructor
08-23 12:40:32.066  7879  7936 V ToneGenerator: stopTone
08-23 12:40:32.066  7879  7936 V ToneGenerator: Delete Track: 0xb4928a80
08-23 12:40:32.067  7879  7936 V AudioTrack: ~AudioTrack, releasing session id from 7879 on behalf of 7879
08-23 12:40:32.067   326  1402 V AudioPolicyService: AudioCommandThread() adding release output 2
08-23 12:40:32.067   326  1402 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-23 12:40:32.067   326  1402 V AudioFlinger: PlaybackThread::Track destructor
08-23 12:40:32.067   326  1121 V AudioPolicyService: AudioCommandThread() waking up
08-23 12:40:32.067   326  1402 V AudioFlinger: removeClient_l() pid 7879, calling pid 326
08-23 12:40:32.067   326  1121 V AudioPolicyService: AudioCommandThread() processing release output 2
08-23 12:40:32.067   326  1121 V AudioPolicyManager: releaseOutput() 2
08-23 12:40:32.067   326  1121 V AudioPolicyService: AudioCommandThread() going to sleep
08-23 12:40:32.067   326  1403 V AudioFlinger: releasing 21 from 7879 for 7879
08-23 12:40:32.067   326  1403 V AudioFlinger:  decremented refcount to 0
08-23 12:40:32.067   326  1403 V AudioFlinger: purging stale effects
08-23 12:40:32.067  1034  1771 W Process : Unable to open /proc/7939/status
08-23 12:40:32.067  7879  7879 D A2dpService: Received start request. Starting profile...
08-23 12:40:32.068  7879  7879 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 12:40:32.069  7879  7879 V Avrcp   : make
08-23 12:40:32.069  7879  7879 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-23 12:40:32.069  7879  7879 I bluedroid-qcom: get_profile_interface avrcp
08-23 12:40:32.078  7879  7879 V AudioManager: registerRemoteController: size of Media player list: 0
,08-23 12:40:32.080  7879  7879 E AudioManager: No RCC entry present to update
08-23 12:40:32.080  7879  7879 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-23 12:40:32.085  7879  7879 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-23 12:40:32.086  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-23 12:40:32.086  7879  7879 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-23 12:40:32.089  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-23 12:40:32.178  1034  1574 V SIM_STK : Menu title from STK is T-Mobile
08-23 12:40:32.178  1034  1574 V SIM_STK : Menu title from STK is T-Mobile
,08-23 12:40:32.291  1034  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-23 12:40:32.302  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-23 12:40:32.308  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-23 12:40:32.308  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 12:40:32.308  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 12:40:32.309  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 12:40:32.309  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 12:40:32.309  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 12:40:32.309  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 12:40:32.309  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 12:40:32.309  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 12:40:32.309  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 12:40:32.309  7879  7879 I BluetoothA2dpServiceJni: classInitNative
08-23 12:40:32.311  7879  7879 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 12:40:32.311  7879  7879 D A2dpStateMachine: make
08-23 12:40:32.318  7879  7879 I bluedroid-qcom: get_profile_interface a2dp
08-23 12:40:32.318  7879  7946 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-23 12:40:32.325  7879  7879 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-23 12:40:32.326  7879  7879 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-23 12:40:32.331  7879  7945 D A2dpStateMachine: Enter Disconnected: -2
08-23 12:40:32.331  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:32.337  7879  7879 I BluetoothHidServiceJni: classInitNative: succeeds
08-23 12:40:32.343  7879  7879 D HidService: Received start request. Starting profile...
,08-23 12:40:32.343  7879  7879 I bluedroid-qcom: get_profile_interface hidhost
,08-23 12:40:32.343  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
,08-23 12:40:32.345  7879  7879 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 12:40:32.351  7879  7879 D HealthService: Received start request. Starting profile...
08-23 12:40:32.355  7879  7879 I bluedroid-qcom: get_profile_interface health
08-23 12:40:32.356  7879  7879 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-23 12:40:32.356  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:32.358  7879  7879 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-23 12:40:32.363  7879  7879 D PanService: Received start request. Starting profile...
08-23 12:40:32.363  7879  7879 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 12:40:32.363  7879  7879 I bluedroid-qcom: get_profile_interface pan
,08-23 12:40:32.373  7879  7879 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-23 12:40:32.373  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:32.375  7879  7879 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-23 12:40:32.381  7879  7879 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 12:40:32.382  7879  7879 D BtGatt.GattService: Received start request. Starting profile...
08-23 12:40:32.382  7879  7879 D BtGatt.GattService: start()
08-23 12:40:32.382  7879  7879 I bluedroid-qcom: get_profile_interface gatt
08-23 12:40:32.382  7879  7879 D BtGatt.AdvertiseManager: advertise manager created
,08-23 12:40:32.391  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:32.393  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:32.394  7879  7879 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-23 12:40:32.395  7879  7879 V BluetoothMapService: BluetoothMapBinder()
08-23 12:40:32.396  7879  7879 D BluetoothMapService: Received start request. Starting profile...
08-23 12:40:32.396  7879  7879 D BluetoothMapService: start()
,08-23 12:40:32.400  7879  7879 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-23 12:40:32.400  7879  7879 D BluetoothMapEmailAppObserver: createReceiver()
08-23 12:40:32.401  7879  7879 D BluetoothMapEmailAppObserver: initObservers()
,08-23 12:40:32.401  7879  7879 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-23 12:40:32.411  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:32.412  7879  7879 D HeadsetStateMachine: Proxy object connected
08-23 12:40:32.413  7879  7879 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-23 12:40:32.413  7879  7879 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-23 12:40:32.417  7879  7936 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 12:40:32.418  7879  7936 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 12:40:32.419  7879  7936 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-23 12:40:32.420  7879  7879 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 12:40:32.424  7879  7879 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 12:40:32.426  7879  7879 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:40:32.434  7879  7879 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 12:40:32.437  7879  7879 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 12:40:32.437  7879  7879 V PanService: [BTUI] SIM Extra State :ABSENT
08-23 12:40:32.441  7879  7879 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-23 12:40:32.444  7879  7879 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-23 12:40:32.444  7879  7879 V BluetoothMapService: Handler(): got msg=1
08-23 12:40:32.445  7879  7879 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 12:40:32.446  7879  7879 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 12:40:32.446  7879  7879 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 12:40:32.446  7879  7879 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:32.446  7879  7914 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-23 12:40:32.446  7879  7879 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-23 12:40:32.446  7879  7914 I bluedroid-qcom: enable
08-23 12:40:32.447  7879  7914 I bt_hci_bdroid: init
08-23 12:40:32.450  7879  7914 I bt_vendor: bt-vendor : init
08-23 12:40:32.450  7879  7914 I bt_vendor: bt-vendor : get_bt_soc_type
08-23 12:40:32.450  7879  7914 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-23 12:40:32.450  7879  7914 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-23 12:40:32.450  7879  7914 D bt_userial_mct: userial_init
08-23 12:40:32.451  7879  7953 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-23 12:40:32.452  7879  7914 D bt_hci_bdroid: set_power 1
08-23 12:40:32.452  7879  7914 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-23 12:40:32.452  7879  7914 I bt_vendor: Starting hciattach daemon
08-23 12:40:32.452  7879  7914 I bt_vendor: try to set true
08-23 12:40:32.453  7879  7953 I bt-btu  : btu_task pending for preload complete event
08-23 12:40:32.450  7956  7956 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:32.450  7956  7956 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 12:40:32.497  7957  7957 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-23 12:40:32.632  7963  7963 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-23 12:40:32.648  7964  7964 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-23 12:40:32.679  7966  7966 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 12:40:32.691  7970  7970 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-23 12:40:32.704  7971  7971 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 12:40:32.718  7972  7972 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-23 12:40:32.754  7974  7974 I libmdmdetect: ESOC framework not supported
,08-23 12:40:32.754  7974  7974 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-23 12:40:32.763  7974  7974 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-23 12:40:32.763  7974  7974 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-23 12:40:32.763  7974  7974 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-23 12:40:32.763  7974  7974 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-23 12:40:32.763  7974  7974 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-23 12:40:32.763  7974  7974 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-23 12:40:32.763  7974  7974 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-23 12:40:32.808  7974  7975 E QC-QMI  : qmi_client [7974] 15: failed to locate client data
08-23 12:40:32.809   485   485 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-23 12:40:32.809   485   485 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-23 12:40:32.869  7976  7976 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-23 12:40:32.886  7977  7977 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-23 12:40:32.957  7879  7914 I bt_vendor: bluetooth satus is on
08-23 12:40:32.958  7879  7914 D bt_hci_bdroid: preload
08-23 12:40:32.958  7879  7955 D bt_userial_mct: userial_open(port:0)
08-23 12:40:32.958  7879  7955 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-23 12:40:32.965  7879  7955 I bt_vendor: Done intiailizing UART
08-23 12:40:32.969  7879  7955 I bt_vendor: Done intiailizing UART
08-23 12:40:32.969  7879  7955 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-23 12:40:32.970  7879  7955 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-23 12:40:32.970  7879  7953 I bt-btu  : btu_task received preload complete event
08-23 12:40:32.971  7879  7979 D bt_userial_mct: Entering userial_read_thread()
,08-23 12:40:32.972  7879  7953 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-23 12:40:32.972  7879  7953 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-23 12:40:32.990  7879  7953 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_HCI
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_AVDT
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 12:40:32.996  7879  7953 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 12:40:32.997  7879  7953 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 12:40:32.997  7879  7953 I         : BTE_InitTraceLevels -- TRC_BTIF
08-23 12:40:33.053  7879  7953 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-23 12:40:33.053  7879  7953 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ce061 
08-23 12:40:33.053  7879  7953 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ce061 
,08-23 12:40:33.080  7879  7918 E bt-btif : Calling BTA_HhEnable
08-23 12:40:33.081  7879  7918 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-23 12:40:33.081  7879  7918 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-23 12:40:33.086  7879  7918 D BluetoothAdapterProperties: Name is: G3
08-23 12:40:33.087  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-23 12:40:33.088  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-23 12:40:33.090  7879  7918 D BluetoothAdapterProperties: Scan Mode:20
08-23 12:40:33.090  7879  7918 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 12:40:33.090  7879  7918 D bt_hci_bdroid: postload
08-23 12:40:33.092  7879  7918 D bte_conf: Device ID record 1 : primary
08-23 12:40:33.092  7879  7918 D bte_conf:   vendorId            = 00c4
08-23 12:40:33.092  7879  7918 D bte_conf:   vendorIdSource      = 0001
08-23 12:40:33.092  7879  7918 D bte_conf:   product             = 13a1
08-23 12:40:33.092  7879  7918 D bte_conf:   version             = 1000
08-23 12:40:33.092  7879  7918 D bte_conf:   clientExecutableURL = 
08-23 12:40:33.092  7879  7918 D bte_conf:   serviceDescription  = 
08-23 12:40:33.092  7879  7918 D bte_conf:   documentationURL    = 
08-23 12:40:33.093  7879  7955 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 12:40:33.093  7879  7918 D bte_conf: bte_load_did_conf no section named DID2.
08-23 12:40:33.096  7879  7955 D bt_hci_bdroid: Used up Tx Cmd credits
,08-23 12:40:33.101  7879  7979 E bt_mct  : hci lib postload completed
08-23 12:40:33.105  7879  7914 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-23 12:40:33.105  7879  7914 D BluetoothAdapterProperties: ScanMode =  20
08-23 12:40:33.105  7879  7914 D BluetoothAdapterProperties: State =  11
08-23 12:40:33.106  7879  7914 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-23 12:40:33.107  7879  7914 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-23 12:40:33.107  7879  7914 D BluetoothAdapterProperties: Setting state to 12
08-23 12:40:33.107  7879  7914 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 12:40:33.100  7984  7984 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 12:40:33.113  7879  7918 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 12:40:33.100  7984  7984 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:33.117  1034  1102 D BluetoothManagerService: Message: 60
08-23 12:40:33.117  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-23 12:40:33.117  1034  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-23 12:40:33.117  1034  1102 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 12:40:33.130  7879  7914 I BluetoothAdapterState: Entering On State
,08-23 12:40:33.147  7879  7914 D LGBluetoothServiceAdapter: [BTUI] OnState
08-23 12:40:33.147  7879  7914 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-23 12:40:33.147  7879  7914 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-23 12:40:33.151  7879  7914 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-23 12:40:33.136  1853  4467 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:40:33.160  1034  1034 D BluetoothA2dp: Proxy object connected
,08-23 12:40:33.165  7879  7918 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 12:40:33.165  7879  7918 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-23 12:40:33.175  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:33.175  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:33.175  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:33.175  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:40:33.175  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:33.175  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:33.175  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:33.175  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:40:33.181  7879  7914 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-23 12:40:33.195  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:40:33.200  1853  1853 D BluetoothHeadset: Proxy object connected
08-23 12:40:33.201  1853  2434 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:40:33.209  7879  7953 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-23 12:40:33.209  7879  7953 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-23 12:40:33.209  7879  7953 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-23 12:40:33.211  7879  7953 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-23 12:40:33.211  7879  7953 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-23 12:40:33.211  7879  7953 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-23 12:40:33.212  7879  7918 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-23 12:40:33.230  7990  7990 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-23 12:40:33.234  7879  7953 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 12:40:33.235  7879  7953 W bt-smp  : Plain text(LSB ~ MSB) = 40 ac 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 12:40:33.235  7879  7953 W bt-smp  : Encrypted text(LSB ~ MSB) = 61 e6 0e 63 0f 05 32 39 f8 40 a3 27 d4 3a ef 4c 
08-23 12:40:33.235  7879  7953 W bt-btm  : Stopping oneshot timer
08-23 12:40:33.235  1853  1853 D BluetoothHeadset: Proxy object connected
08-23 12:40:33.236  1853  2671 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:40:33.238  1853  1853 D BluetoothHeadset: Proxy object connected
08-23 12:40:33.240  7192  7224 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:40:33.242  7192  7224 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 12:40:33.246  1034  1102 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 12:40:33.249  7879  7953 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 12:40:33.249  7879  7953 W bt-smp  : Plain text(LSB ~ MSB) = 9c 91 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 12:40:33.249  7879  7953 W bt-smp  : Encrypted text(LSB ~ MSB) = d3 9e 59 39 ee e7 2e 91 19 b0 f2 b7 22 d4 d0 c3 
08-23 12:40:33.249  7879  7953 W bt-btm  : Stopping oneshot timer
08-23 12:40:33.250  1034  1034 D BluetoothHeadset: Proxy object connected
08-23 12:40:33.252  7192  7214 D BluetoothMap: onBluetoothStateChange: up=true
08-23 12:40:33.256  7192  7228 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 12:40:33.258  7192  7228 D BluetoothPan: onBluetoothStateChange on: true
08-23 12:40:33.258  7192  7228 D BluetoothPan: onBluetoothStateChange call bindService
,08-23 12:40:33.261  7879  7953 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 12:40:33.261  7879  7953 W bt-smp  : Plain text(LSB ~ MSB) = a6 be 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 12:40:33.261  7879  7953 W bt-smp  : Encrypted text(LSB ~ MSB) = fc d7 f7 44 28 34 c3 44 95 af 54 72 72 81 26 c1 
08-23 12:40:33.261  7879  7953 W bt-btm  : Stopping oneshot timer
08-23 12:40:33.265  7192  7214 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 12:40:33.266  7192  7192 D BluetoothHeadset: Proxy object connected
08-23 12:40:33.266  7192  7192 D HeadsetProfile: Bluetooth service connected
08-23 12:40:33.272  7879  7953 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 12:40:33.272  7879  7953 W bt-smp  : Plain text(LSB ~ MSB) = e7 68 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 12:40:33.272  7879  7953 W bt-smp  : Encrypted text(LSB ~ MSB) = 44 c8 cf a5 91 c3 45 fa a2 08 a9 84 13 31 8c 01 
,08-23 12:40:33.273  7879  7953 W bt-btm  : Stopping oneshot timer
,08-23 12:40:33.278  1034  1102 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-23 12:40:33.278  1034  1102 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-23 12:40:33.278  7192  7192 D BluetoothInputDevice: Proxy object connected
08-23 12:40:33.279  7192  7192 D HidProfile: Bluetooth service connected
08-23 12:40:33.281  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:33.282  1941  2149 D LGBluetoothAPIService: Message: 1
08-23 12:40:33.282  1941  2149 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-23 12:40:33.282  1941  2149 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-23 12:40:33.282  1941  2149 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-23 12:40:33.283  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 12:40:33.289  7879  7953 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 12:40:33.289  7879  7953 W bt-smp  : Plain text(LSB ~ MSB) = 8a 88 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 12:40:33.289  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-23 12:40:33.289  1034  1102 D BluetoothManagerService: Message: 40
08-23 12:40:33.289  7879  7953 W bt-smp  : Encrypted text(LSB ~ MSB) = 47 12 f4 fd 71 51 86 2d a2 83 18 2e ce f9 5f 78 
08-23 12:40:33.289  1034  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-23 12:40:33.289  7879  7953 W bt-btm  : Stopping oneshot timer
08-23 12:40:33.292  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:40:33.292  7192  7192 D BluetoothMap: Proxy object connected
08-23 12:40:33.292  7192  7192 D MapProfile: Bluetooth service connected
08-23 12:40:33.292  7192  7192 D BluetoothMap: getConnectedDevices()
08-23 12:40:33.293  7879  7987 V BluetoothMapService: getConnectedDevices()
08-23 12:40:33.296  7879  7879 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:33.296  7879  7879 D BluetoothMapService: STATE_ON
08-23 12:40:33.296  7192  7192 D BluetoothA2dp: Proxy object connected
08-23 12:40:33.296  7192  7192 D A2dpProfile: Bluetooth service connected
08-23 12:40:33.298  7192  7192 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 12:40:33.298  7192  7192 D PanProfile: Bluetooth service connected
08-23 12:40:33.302  7192  7192 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-23 12:40:33.303  7192  7192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 12:40:33.310  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:33.311  7879  7879 V BluetoothPbapService: Pbap Service onCreate
08-23 12:40:33.311  7879  7879 V BluetoothPbapService: Starting PBAP service
08-23 12:40:33.312  7879  7879 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-23 12:40:33.312  7879  7879 V BluetoothMapService: Handler(): got msg=1
08-23 12:40:33.313  7879  7879 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-23 12:40:33.314  7879  7879 V BluetoothPbapService: Pbap Service onBind
08-23 12:40:33.315  7879  8006 D BluetoothMapMasInstance: MAS initSocket()
08-23 12:40:33.315  7879  8006 D BluetoothMapMasInstance:   masId = 00
08-23 12:40:33.315  7879  8006 D BluetoothMapMasInstance:   msgTypes = 0e
08-23 12:40:33.315  7879  8006 D BluetoothMapMasInstance:   masName = SMS/MMS
08-23 12:40:33.315  7879  8006 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-23 12:40:33.318  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:33.318  7879  7879 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:33.319  7879  7879 V BluetoothPbapService: state: 12
08-23 12:40:33.319  7879  7879 V BluetoothPbapService: Handler(): got msg=1
08-23 12:40:33.319  7879  7879 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-23 12:40:33.320  7879  8008 V BluetoothPbapService: Pbap Service initSocket
08-23 12:40:33.321  1034  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:33.321  7879  7879 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 12:40:33.321  7879  7879 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:33.321  7879  7879 V BluetoothPbapReceiver: ***********state = 12
08-23 12:40:33.323  7879  8006 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:40:33.324  7192  7192 D DockEventReceiver: finishStartingService: stopping service
08-23 12:40:33.325  7879  8006 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-23 12:40:33.326  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 12:40:33.326  7879  8006 V BluetoothMapMasInstance: Succeed to create listening socket 
08-23 12:40:33.327  7879  8006 D BluetoothMapMasInstance: Accepting socket connection...
08-23 12:40:33.328  7879  7918 D BluetoothAdapterProperties: Scan Mode:21
08-23 12:40:33.328  7879  7918 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-23 12:40:33.329  7192  7192 D BluetoothPbap: Proxy object connected
08-23 12:40:33.330  7192  7192 D PbapServerProfile: Bluetooth service connected
08-23 12:40:33.330  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:33.332  2198  2198 D c       : Getting all permits...
08-23 12:40:33.332  2198  2198 D a       : Opening database...
08-23 12:40:33.336  7879  8008 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:40:33.339  2198  2198 D a       : Opening database auth.proximity.permit_store...
08-23 12:40:33.339  7879  8008 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,08-23 12:40:33.340  7879  8008 V BluetoothPbapService: Succeed to create listening socket 
08-23 12:40:33.340  7879  8008 V BluetoothPbapService: Accepting socket connection...
08-23 12:40:33.340  2198  2198 D a       : Closing database...
08-23 12:40:33.350  7192  7192 D BluetoothPermissionRequest: onReceive
08-23 12:40:33.352  7192  7192 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-23 12:40:33.353  7192  7192 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 12:40:33.357  7879  7879 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-23 12:40:33.358  7879  7879 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-23 12:40:33.363  7879  7879 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-23 12:40:33.383  7879  7879 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-23 12:40:33.383  7879  7879 V BtOppService: onCreate
08-23 12:40:33.388  7879  7879 V BluetoothOppNotification: send message
08-23 12:40:33.391  7879  7879 V BtOppService: Starting RfcommListener
08-23 12:40:33.397  7879  7879 D BluetoothOppPreference: Dumping Names:  
08-23 12:40:33.397  7879  7879 D BluetoothOppPreference: {}
08-23 12:40:33.397  7879  7879 D BluetoothOppPreference: Dumping Channels:  
08-23 12:40:33.397  7879  7879 D BluetoothOppPreference: {}
08-23 12:40:33.397  7879  7879 V BtOppService: onStartCommand
08-23 12:40:33.398  7879  8013 V BtOppService: Deleted complete outbound shares, number =  0
08-23 12:40:33.400  7879  8013 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-23 12:40:33.401  7879  8013 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-23 12:40:33.402  7879  8016 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 12:40:33.402  7879  8016 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 12:40:33.403  7879  8013 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16f56c12 on behalf of 
08-23 12:40:33.404  7879  7879 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:33.404  7879  8016 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3558afe3 on behalf of 
08-23 12:40:33.404  7879  7879 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-23 12:40:33.406  7879  8016 V BluetoothOppNotification: update too frequent, put in queue
08-23 12:40:33.407  7879  8016 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 12:40:33.407  7879  7879 V BluetoothOppNotification: new notify threadi!
08-23 12:40:33.408  7879  7879 V BluetoothOppNotification: send delay message
08-23 12:40:33.408  7879  7879 V BtOppService: start RfcommListener
08-23 12:40:33.414  7879  7879 V BtOppService: RfcommListener started
08-23 12:40:33.414  7879  7879 V BtOppService: ContentObserver received notification
,08-23 12:40:33.416  7879  7879 V BtOppService: ContentObserver received notification
08-23 12:40:33.426  7879  8018 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-23 12:40:33.427  7879  8019 V BtOppRfcommListener: Starting RFCOMM listener....
08-23 12:40:33.428  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:33.429  7879  8019 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:40:33.430  7879  8019 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-23 12:40:33.431  7879  8019 V BtOppRfcommListener: Started RFCOMM listener....
08-23 12:40:33.431  7879  8019 I BtOppRfcommListener: Accept thread started.
08-23 12:40:33.431  7879  8019 V BtOppRfcommListener: Accepting connection...
08-23 12:40:33.433  7879  8018 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28ec3de0 on behalf of 
08-23 12:40:33.436  7879  8020 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 12:40:33.436  7879  8020 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 12:40:33.437  7879  8018 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-23 12:40:33.438  7879  8020 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22b0c899 on behalf of 
08-23 12:40:33.438  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:33.439  7879  7879 V BluetoothFtpService: Ftp Service onCreate
08-23 12:40:33.439  7879  7879 I BluetoothFtpService: Ftp Service onCreate
,08-23 12:40:33.439  7879  7879 V BluetoothFtpService: Ftp Service onStartCommand
08-23 12:40:33.439  7879  8018 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-23 12:40:33.439  7879  7879 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:33.439  7879  7879 V BluetoothFtpService: Starting Listening on sockets
08-23 12:40:33.439  7879  7879 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 12:40:33.440  7879  7879 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 12:40:33.440  7879  7879 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 12:40:33.440  7879  7879 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:33.440  7879  7879 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-23 12:40:33.440  7879  7879 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-23 12:40:33.441  7879  8018 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9dc673f on behalf of 
08-23 12:40:33.442  7879  7879 V BluetoothFtpService: Handler(): got msg=1
08-23 12:40:33.442  7879  8020 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 12:40:33.443  7879  7879 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-23 12:40:33.443  7879  7879 V BluetoothFtpService: Ftp Service initSocket
08-23 12:40:33.445  7879  8018 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 12:40:33.446  1034  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:33.447  7879  7879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:40:33.447  7879  8018 V BluetoothOppNotification: outbound notification was removed.
08-23 12:40:33.448  7879  8018 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 12:40:33.449  7879  8018 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3407580c on behalf of 
08-23 12:40:33.450  7879  8018 V BluetoothOppNotification: inbound: succ-0  fail-0
08-23 12:40:33.452  7879  7879 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
,08-23 12:40:33.452  7879  7879 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-23 12:40:33.454  7879  8021 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-23 12:40:33.457  7879  8018 V BluetoothOppNotification: inbound notification was removed.
08-23 12:40:33.457  7879  8018 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-23 12:40:33.458  7879  8018 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@93c5555 on behalf of 
08-23 12:40:33.468  7879  7879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df0c176
08-23 12:40:33.469  7879  7879 V BluetoothSapService: Sap Service onCreate
,08-23 12:40:33.471  7879  7879 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:40:33.471  7879  7879 V BluetoothSapService: state: 12
08-23 12:40:33.471  7879  7879 V BluetoothSapService: Starting SAP server process
08-23 12:40:33.472  7879  7879 V BluetoothSapService: SAP Service startRfcommListenerThread
08-23 12:40:33.460  8022  8022 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:33.460  8022  8022 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:33.474  7879  8023 V BluetoothSapService: Sap Service initRfcommSocket
08-23 12:40:33.475  1034  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:33.475  7879  8023 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:40:33.477  7879  8023 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-23 12:40:33.478  7879  8023 V BluetoothSapService: Succeed to create listening socket 
08-23 12:40:33.478  7879  8023 V BluetoothSapService: Accepting socket connection...
08-23 12:40:33.488  8022  8022 V BT_SAP  : Event pipe created
,08-23 12:40:33.488  8022  8022 V BT_SAP  : create_server_socket qcom.sap.server
,08-23 12:40:33.488  8022  8022 V BT_SAP  : created socket fd 6
08-23 12:40:33.886  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:33.886  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:33.886  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:33.886  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:40:33.886  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:33.886  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:33.886  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:33.886  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:40:33.907  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:40:33.911  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:33.911  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27a6c47b added. We now have 8 listener(s)
08-23 12:40:33.911  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:33.915  1034  1771 D WifiServiceImplEx: setWifiEnabled: false pid=7106, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 12:40:33.916  1034  1771 D WifiService: setWifiEnabled: false pid=7106, uid=10118
08-23 12:40:33.916  1034  1771 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-23 12:40:33.920  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:40:33.925  1034  1728 D WifiServiceImplEx: setWifiEnabled: true pid=7106, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 12:40:33.925  1034  1728 D WifiService: setWifiEnabled: true pid=7106, uid=10118
08-23 12:40:33.925  1034  1728 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 12:40:33.953  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 12:40:33.954  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 12:40:33.954  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-23 12:40:33.955  1034  1392 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-23 12:40:33.955  1034  1392 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-23 12:40:33.964  1034  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-23 12:40:33.964  1034  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-23 12:40:33.964  1034  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-23 12:40:33.964  1034  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-23 12:40:33.964  1034  1392 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-23 12:40:33.964  1034  1392 E WifiHW  : unknown target_country: EU , set to default
08-23 12:40:33.965  1034  1392 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-23 12:40:33.965  1034  1392 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-23 12:40:33.965  1034  1392 I WifiUtil: gEnableBmps=1
,08-23 12:40:34.410  7879  7879 V BluetoothOppNotification: new notify threadi!
08-23 12:40:34.411  7879  7879 V BluetoothOppNotification: send delay message
,08-23 12:40:34.414  7879  8042 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-23 12:40:34.416  7879  8042 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27b9f1d1 on behalf of 
08-23 12:40:34.417  7879  8042 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-23 12:40:34.418  7879  8042 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-23 12:40:34.419  7879  8042 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a7fd436 on behalf of 
08-23 12:40:34.419  7879  8042 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 12:40:34.421  7879  8042 V BluetoothOppNotification: outbound notification was removed.
08-23 12:40:34.421  7879  8042 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 12:40:34.422  7879  8042 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22d9ff37 on behalf of 
08-23 12:40:34.422  7879  8042 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-23 12:40:34.427  7879  8042 V BluetoothOppNotification: inbound notification was removed.
08-23 12:40:34.427  7879  8042 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-23 12:40:34.428  7879  8042 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e1e9ca4 on behalf of 
08-23 12:40:34.568   321   893 D SoftapController: Softap fwReload - Ok
,08-23 12:40:34.578  1034  1392 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (604ms)
08-23 12:40:34.580   321   893 D CommandListener: Setting iface cfg
08-23 12:40:34.580   321   893 D CommandListener: Trying to bring down wlan0
08-23 12:40:34.587   321   893 D CommandListener: Clearing all IP addresses on wlan0
,08-23 12:40:34.611  1034  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 12:40:34.628  1034  1392 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-23 12:40:34.620  8044  8044 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:34.636  1034  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 12:40:34.636  1034  1392 E WifiStateMachine: useWiFiOffloading() : false
08-23 12:40:34.636  1034  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 12:40:34.630  8044  8044 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 12:40:34.649  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-23 12:40:34.652  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 12:40:34.680  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:40:34.685  1034  1392 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-23 12:40:34.685  1034  1392 D WifiMonitor: connecting to supplicant
08-23 12:40:34.690  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-23 12:40:34.690  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 12:40:34.691  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 12:40:34.691  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 12:40:34.691  7192  7192 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 12:40:34.693  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 12:40:34.694  7192  7192 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-23 12:40:34.694  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
,08-23 12:40:34.695  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 12:40:34.695  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 12:40:34.695  7192  7192 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 12:40:34.695  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-23 12:40:34.695  7192  7192 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 12:40:34.704  8044  8044 I wpa_supplicant: Successfully initialized wpa_supplicant
08-23 12:40:34.710  7633  7633 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 12:40:34.714  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 12:40:34.720  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:34.728  7305  8063 W FormManager: Network not available. Please check & try again.
,08-23 12:40:34.736  7305  8064 V FormManager: Network unavailable.
08-23 12:40:34.738  8044  8044 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-23 12:40:34.738  7305  8064 V FormManager: Network unavailable.
08-23 12:40:34.738  8044  8044 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-23 12:40:34.742  1034  1102 D Tethering: InitialState.processMessage what=4
08-23 12:40:34.742  1034  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-23 12:40:34.749  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 12:40:34.749  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 12:40:34.749  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 12:40:34.749  7192  7192 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 12:40:34.750  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 12:40:34.750  7192  7192 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 12:40:34.750  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-23 12:40:34.750  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 12:40:34.750  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 12:40:34.750  7192  7192 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 12:40:34.751  7192  7192 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 12:40:34.812  8044  8044 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-23 12:40:34.832  8044  8044 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-23 12:40:34.842  1034  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-23 12:40:34.843  1034  1392 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-23 12:40:34.844  1034  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-23 12:40:34.844  1034  1392 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-23 12:40:34.845  1034  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:34.846  1034  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:34.847  1034  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:34.847  1034  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:34.848  1034  1392 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-23 12:40:34.848  1034  1392 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-23 12:40:34.848  1034  1392 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-23 12:40:34.849  1034  1392 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-23 12:40:34.849  1034  1392 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-23 12:40:34.849  1034  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 12:40:34.849  1034  1392 E WifiStateMachine: useWiFiOffloading() : false
08-23 12:40:34.849  1034  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-23 12:40:34.850  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:34.850  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:34.850  1034  1392 D WifiNative-wlan0: doBoolean: SET update_config 1
08-23 12:40:34.850  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:34.851  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:34.851  1034  1392 D WifiNative-wlan0: SET update_config 1: returned true
08-23 12:40:34.851  1034  1392 D WifiConfigStore: Loading config and enabling all networks 
08-23 12:40:34.851  1034  1392 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-23 12:40:34.851  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 12:40:34.852  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-23 12:40:34.852  1034  1392 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-23 12:40:34.852  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:34.858  8044  8044 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-23 12:40:34.861  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-23 12:40:34.862  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-23 12:40:34.862  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-23 12:40:34.862  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-23 12:40:34.862  1034  8065 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-23 12:40:34.862  1034  8065 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-23 12:40:34.863  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-23 12:40:34.864  1034  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-23 12:40:34.866  1034  1392 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-23 12:40:34.868  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:34.868  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:34.868  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:34.868  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:34.868  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:34.868  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:34.868  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:34.868  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:40:34.872  7633  7633 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 12:40:34.875  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:40:34.877  1034  1392 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-23 12:40:34.877  1034  1392 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-23 12:40:34.879  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 12:40:34.881  1034  1392 D WifiStateMachine: enableVerboseLogging : level 2
08-23 12:40:34.881  1034  1392 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-23 12:40:34.881  1034  1392 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-23 12:40:34.881  1034  1392 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-23 12:40:34.882  1034  1392 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-23 12:40:34.882  1034  1392 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-23 12:40:34.882  1034  1392 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-23 12:40:34.883  1034  1392 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-23 12:40:34.883  1034  1392 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-23 12:40:34.883  1034  1392 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-23 12:40:34.883  7305  8067 W FormManager: Network not available. Please check & try again.
08-23 12:40:34.884  1034  1392 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-23 12:40:34.884  1034  1392 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-23 12:40:34.884  1034  1392 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-23 12:40:34.884  1034  1392 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-23 12:40:34.885  1034  1392 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-23 12:40:34.885  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:34.886  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-23 12:40:34.886  1941  2330 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-23 12:40:34.886  1941  2330 D WfdsService: Set the WFDS Monitor: true
08-23 12:40:34.886  1941  2330 D WfdsMonitor: WfdsMonitorThread create
08-23 12:40:34.886  1941  2330 D WfdsMonitor: WFDS Monitor is created and started
08-23 12:40:34.886  1034  1392 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 12:40:34.886  1034  1392 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-23 12:40:34.887  1941  2330 D WfdsService: WiFi: Supplicant connection re-established
08-23 12:40:34.887  1034  1392 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-23 12:40:34.887  1034  1392 D WifiNative-HAL: Setting external_sim to 1
08-23 12:40:34.887  1034  1392 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-23 12:40:34.888  1941  8069 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-23 12:40:34.888  1034  1392 D WifiNative-wlan0: SET external_sim 1: returned true
08-23 12:40:34.888  1034  1392 I WifiNative-HAL: startHal
08-23 12:40:34.888  1034  1392 D wifi    : setting scan oui 0xaf6769a0
08-23 12:40:34.888  1941  8069 E CtrlSupplicant: Succeed to open control connection
08-23 12:40:34.888  1941  8069 E CtrlSupplicant: Succeed to open monitor connection
08-23 12:40:34.888  1034  1392 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 12:40:34.888  1034  1392 I WifiNative-HAL: startHal
08-23 12:40:34.889  1034  1392 D wifi    : setting scan oui 0xaf6769a0
08-23 12:40:34.889  1941  8069 D WfdsMonitor: Supplicant connection established
08-23 12:40:34.889  1034  1392 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-23 12:40:34.889  1941  2330 D WfdsService: Connected to the supplicant for wfds
08-23 12:40:34.890  1034  1392 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-23 12:40:34.890  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-23 12:40:34.890  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-23 12:40:34.890  1034  1392 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-23 12:40:34.890  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-23 12:40:34.891  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-23 12:40:34.891  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 12:40:34.891  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-23 12:40:34.892  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-23 12:40:34.892  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-23 12:40:34.892  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 12:40:34.892  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-23 12:40:34.893  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-23 12:40:34.893  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,08-23 12:40:34.893  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-23 12:40:34.893  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 12:40:34.893  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-23 12:40:34.893  8044  8044 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-23 12:40:34.894  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-23 12:40:34.894  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 12:40:34.894  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-23 12:40:34.894  1034  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-23 12:40:34.895  1034  1392 E WifiNative: : [212,354,152 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-23 12:40:34.895  1034  1392 D WifiNative-wlan0: doBoolean: RECONNECT
08-23 12:40:34.896  1034  1392 D WifiNative-wlan0: RECONNECT: returned true
08-23 12:40:34.896  1034  1392 D WifiNative-wlan0: doString: [STATUS]
08-23 12:40:34.897  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-23 12:40:34.897  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-23 12:40:34.897  1034  1392 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-23 12:40:34.897  1034  1392 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 12:40:34.898  1034  1392 D WifiNative-wlan0: SET ps 1: returned true
08-23 12:40:34.898  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.899  7305  8068 V FormManager: Network unavailable.
08-23 12:40:34.899  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-23 12:40:34.899  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-23 12:40:34.899   321   893 D CommandListener: Setting iface cfg
08-23 12:40:34.899   321   893 D CommandListener: Trying to bring up p2p0
08-23 12:40:34.900  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.900  1034  1555 I WifiNative-HAL: startHal
08-23 12:40:34.900  1034  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-23 12:40:34.900  1034  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6769a0
08-23 12:40:34.900  1034  1555 D wifi    : failed to get capabilities : -3
08-23 12:40:34.900  1034  1390 D LGWifiP2pService: P2pEnablingState
08-23 12:40:34.900  1034  1555 E WifiScanningService: could not get scan capabilities
08-23 12:40:34.900  1034  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.900  1034  1390 D LGWifiP2pService: P2p socket connection successful
08-23 12:40:34.900  1034  1390 D LGWifiP2pService: P2pEnabledState
08-23 12:40:34.900  1034  1556 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.900  1034  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-23 12:40:34.901  1034  1392 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-23 12:40:34.902  1034  1392 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-23 12:40:34.902  1034  1392 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-23 12:40:34.903  1034  1392 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-23 12:40:34.903  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-23 12:40:34.903  1941  1941 D WfdsService: WifiP2pState is changed : true
08-23 12:40:34.903  1941  2330 D WfdsService: Receive the WFDS_ENABLE Method
08-23 12:40:34.903  1941  2330 D WfdsService: Set t,he WFDS Monitor: true
08-23 12:40:34.903  1941  2330 D WfdsService: Connected to the supplicant for wfds
08-23 12:40:34.903  1941  2330 D WfdsJNI : doCommand: WFDS_SET TRUE
08-23 12:40:34.903  1034  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=212362  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 12:40:34.903  8044  8044 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-23 12:40:34.903  1941  2330 D WfdsService: selectPreferredScanChannel [36]
08-23 12:40:34.903  1941  2330 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,08-23 12:40:34.905  1034  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=212365  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 12:40:34.906  1034  1392 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-23 12:40:34.907  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:34.907  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:34.907  1034  1392 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-23 12:40:34.908  1034  1392 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-23 12:40:34.908  1034  1392 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-23 12:40:34.908  8044  8044 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-23 12:40:34.908  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:34.908  7305  8068 V FormManager: Network unavailable.
08-23 12:40:34.908  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:34.908  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-23 12:40:34.909  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:34.911  1034  1392 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-23 12:40:34.911  1034  1392 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-23 12:40:34.912  1034  1392 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-23 12:40:34.912  1034  1392 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-23 12:40:34.912  8044  8044 E wpa_supplicant: disconnect_rssi_lvl: -100
08-23 12:40:34.912  1034  1392 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-23 12:40:34.913  1034  1392 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-23 12:40:34.913  1034  1392 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-23 12:40:34.913  1034  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-23 12:40:34.913  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-23 12:40:34.914  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 12:40:34.914  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-23 12:40:34.914  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 12:40:34.914  8044  8044 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:34.914  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 12:40:34.914  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:34.915  1034  8065 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:34.915  1034  8065 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:34.915  8044  8044 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 12:40:34.915  8044  8044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.915  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-23 12:40:34.915  1034  1392 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-23 12:40:34.916  8044  8044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.916  1941  1941 D WfdsService: isConnected: false
08-23 12:40,:34.916  1034  1392 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-23 12:40:34.916  1034  1392 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-23 12:40:34.917  1034  1392 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-23 12:40:34.917  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-23 12:40:34.917  1941  8069 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-23 12:40:34.917  1941  8069 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:34.917  1034  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-23 12:40:34.917  1034  8065 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:34.917  1034  8065 E WifiMonitor: WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.917  1034  8065 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.917  1034  8065 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.917  1034  8065 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:34.917  1034  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-23 12:40:34.917  1034  8065 E WifiMonitor: WifiMonitor:p2p0 cnt=38 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.917  1034  8065 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.917  1034  8065 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.918  1034  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-23 12:40:34.918  1034  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-23 12:40:34.918  1034  1390 D LGWifiP2pService: before postfix = G3
08-23 12:40:34.918  1034  1390 D WifiServerServiceExt: postfix byte check : 2
08-23 12:40:34.918  1034  1390 D LGWifiP2pService: after postfix = G3
08-23 12:40:34.918  1034  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-23 12:40:34.918  1034  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-23 12:40:34.918  1034  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-23 12:40:34.919  1034  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-23 12:40:34.919  1034  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-23 12:40:34.919  1034  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-23 12:40:34.919  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-23 12:40:34.919  1034  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-23 12:40:34.919  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-23 12:40:34.920  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-23 12:40:34.920  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-23 12:40:34.920  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 12:40:34.920  8044  8044 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 12:40:34.921  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-23 12:40:34.921  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 12:40:34.921  1034  8065 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 12:40:34.921  1034  8065 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 12:40:34.921  1034  1392 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-23 12:40:34.921  1034  1392 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-23 12:40:34.922  1034  1392 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-23 12:40:34.922  1034  1392 D WifiNative-wlan0: doBoolean: SCAN
08-23 12:40:34.923  1034  1392 D WifiNative-wlan0: SCAN: returned false
08-23 12:40:34.92,3  1034  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=212382  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 12:40:34.925  1034  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-23 12:40:34.925  1034  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-23 12:40:34.925  1034  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-23 12:40:34.925  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-23 12:40:34.925  1034  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-23 12:40:34.926  1034  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-23 12:40:34.926  1034  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-23 12:40:34.926  1034  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-23 12:40:34.928  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 12:40:34.928  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-23 12:40:34.928  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-23 12:40:34.928  1941  1941 D WfdsService: Update P2p Interface State: 3
08-23 12:40:34.929  1034  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=212388  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-23 12:40:34.930  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:34.931  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:34.931  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-23 12:40:34.931  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:34.931  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:34.934  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 12:40:34.934  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-23 12:40:34.934  1034  1392 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 12:40:34.934  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:34.934  1034  1392 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 12:40:34.935  1034  1392 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 12:40:34.935  1034  1392 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 12:40:34.935  1034  1392 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 12:40:34.936  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 12:40:34.936  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-23 12:40:34.938  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:34.938  1034  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-23 12:40:34.939  1034  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-23 12:40:34.940  4348  8071 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 12:40:34.941  1034  1390 D LGWifiP2pService: InactiveState
08-23 12:40:34.941  1034  1390 D LGWifiP2pService: InactiveState{ when=-26ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.942  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-26ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.942  1034  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-23 12:40:34.943  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-23 12:40:34.943  8044  8044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:34.944  8044  8044 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 12:40:34.944  8044  8044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.945  8044  8044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.945  4348  8072 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 12:40:34.945  4348  8072 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 12:40:34.946  1941  8069 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 12:40:34.946  1941  8069 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:34.946  1941  8069 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:34.946  1034  8065 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 12:40:34.947  1034  8065 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:34.947  1034  8065 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:34.947  1034  8065 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 12:40:34.947  1034  8065 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:34.947  1034  8065 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.947  1034  8065 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.947  1034  8065 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.947  1034  8065 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 12:40:34.947  1034  8065 E WifiMonitor: WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.947  1034  8065 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.947  1034  8065 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 12:40:34.947  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 12:40:34.947  1034  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-23 12:40:34.948  1034  1390 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.948  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.948  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.948  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.948  1034  1390 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.948  1034  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.948  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.948  1034  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.948  1034  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=13928,7 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.948  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.948  1034  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.949  1034  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.949  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.949  1034  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:34.949  1941  2330 W WfdsService: DefaultState - msg [9441285] is not handled
08-23 12:40:34.949  1034  1034 E WifiServerServiceExt: No p2p device connected
,08-23 12:40:34.956  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:34.961  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:34.962  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:34.963  7265  7265 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 12:40:34.965  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:40:34.965  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:34.965  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:34.965  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:34.965  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:34.965  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:40:34.965  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:40:34.965  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:40:34.966  7657  7657 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-23 12:40:34.966  7657  7657 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-23 12:40:34.966  7657  7657 V [BNRBootReceiver]: Boot Receiver Return
08-23 12:40:34.966  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:40:34.972  7106  7172 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-23 12:40:34.972  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:34.973  7106  7172 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-23 12:40:34.974  7106  7172 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6e28405 Bundle[{}]
08-23 12:40:34.975  7106  7172 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 12:40:34.976  7106  7172 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-23 12:40:34.976  7106  7172 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-23 12:40:34.977  7106  7172 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 12:40:34.978  7106  7172 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 12:40:34.979  7106  7172 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-23 12:40:34.979  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 12:40:34.986  7106  7172 I System.out: Running OutgoingSocketThread
08-23 12:40:34.987  7106  8073 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 926)
08-23 12:40:34.989  7106  8073 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46604
08-23 12:40:34.989  7106  8073 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-23 12:40:34.991  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 12:40:34.998  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:34.998  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:34.999  7265  7265 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 12:40:35.542  8044  8044 E wpa_supplicant: USIM:  scard_init function
08-23 12:40:35.544  8044  8044 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-23 12:40:35.550  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-23 12:40:35.551  1034  8065 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-23 12:40:35.551  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-23 12:40:35.551  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: WPS-AP-AVAILABLE 
08-23 12:40:35.551  1034  8065 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-23 12:40:35.551  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-23 12:40:35.551  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-23 12:40:35.552  1034  1392 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-23 12:40:35.553  1034  1392 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-23 12:40:35.553  1034  1392 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-23 12:40:35.553  1034  1392 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-23 12:40:35.554  1034  1392 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-23 12:40:35.577  1034  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=213036  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-23 12:40:35.585  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:35.585  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:35.588  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:35.590  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.590  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.590  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-23 12:40:35.595  1034  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=213054  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-23 12:40:35.596  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 12:40:35.596  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-23 12:40:35.602  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-23 12:40:35.614  7192  7192 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-23 12:40:35.619  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:35.629  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 12:40:35.637  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:35.645  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:35.646  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:35.646  7265  7265 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 12:40:35.671  8044  8044 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 12:40:35.680  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-23 12:40:35.680  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-23 12:40:35.680  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-23 12:40:35.680  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-23 12:40:35.680  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 12:40:35.680  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 12:40:35.686  1034  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=213145  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-23 12:40:35.687  1034  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=213146  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-23 12:40:35.687  1034  1392 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213147
08-23 12:40:35.688  1034  1392 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213147
08-23 12:40:35.688  1034  1392 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213147
08-23 12:40:35.689  1034  1392 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213148
08-23 12:40:35.689  1034  1392 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213148
,08-23 12:40:35.694  8044  8044 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 12:40:35.694  8044  8044 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 12:40:35.697  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 12:40:35.697  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 12:40:35.697  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-23 12:40:35.697  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 12:40:35.697  1034  8065 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 12:40:35.697  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-23 12:40:35.697  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 12:40:35.697  1034  8065 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 12:40:35.698  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 12:40:35.698  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 12:40:35.700  1034  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-23 12:40:35.714  1034  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=213173  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-23 12:40:35.719  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.719  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.719  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-23 12:40:35.722  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 12:40:35.722  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:35.725  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:35.736  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 12:40:35.736  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 12:40:35.736  7192  7192 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 12:40:35.736  7192  7192 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-23 12:40:35.742  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 12:40:35.746  1034  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=213205  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-23 12:40:35.747  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.747  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.747  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:35.747  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:35.748  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-23 12:40:35.748  7192  7192 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 12:40:35.748  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-23 12:40:35.748  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 12:40:35.748  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 12:40:35.748  7192  7192 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 12:40:35.748  7192  7192 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-23 12:40:35.748  7192  7192 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 12:40:35.749  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:35.753  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 12:40:35.754  1034  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=213213  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-23 12:40:35.755  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 12:40:35.755  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-23 12:40:35.757  1034  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=213215  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-23 12:40:35.758  1034  1392 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=213217
08-23 12:40:35.758  1034  1392 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=213217
08-23 12:40:35.759  1034  1392 D WifiNative-wlan0: doString: [STATUS]
08-23 12:40:35.759  1034  8065 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 12:40:35.759  1034  8065 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 12:40:35.759  1034  1392 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-23 12:40:35.761  1034  1392 I WifiServiceExtension: setVHTCapabilityType  : false
08-23 12:40:35.763  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 12:40:35.772  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:35.774  1034  1392 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-23 12:40:35.774  1034  1392 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-23 12:40:35.778  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:35.778  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-23 12:40:35.779  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.779  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.779  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-23 12:40:35.782  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.782  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.783  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-23 12:40:35.786  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:35.787  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:35.787  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:35.787  7265  7265 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 12:40:35.788  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:35.788  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:35.788  1034  1392 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-23 12:40:35.789  1034  1425 D ConnectivityService: Got NetworkAgent Messenger
08-23 12:40:35.789  1034  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 12:40:35.789  1034  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 12:40:35.789  1034  1425 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-23 12:40:35.789  1034  1425 D ConnectivityService: NetworkAgent connected
08-23 12:40:35.789  1034  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 12:40:35.789  1034  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 12:40:35.791  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 12:40:35.794  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:35.798  1034  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 12:40:35.798  1034  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 12:40:35.798  1034  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 12:40:35.799  1034  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 12:40:35.799  1034  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 12:40:35.802  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 12:40:35.805  1034  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 12:40:35.806   321   893 D CommandListener: Setting iface cfg
08-23 12:40:35.809  1034  1392 E WifiStateMachine: Start Dhcp Watchdog 2
08-23 12:40:35.809  1034  8100 D DhcpStateMachine: StoppedState
08-23 12:40:35.809  1034  8100 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:35.809  1034  8100 D DhcpStateMachine: WaitBeforeStartState
08-23 12:40:35.810  1034  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=213269  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 12:40:35.810  1034  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=213269  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 12:40:35.810  1034  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=213269  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 12:40:35.811  1034  1392 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:35.811  1034  1392 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:35.811  1034  1392 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:35.811  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:35.812  1034  1392 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:35.812  1034  1392 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:35.812  1034  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 12:40:35.814  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-23 12:40:35.814  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-23 12:40:35.818  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:35.818  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:35.818  7265  7265 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 12:40:35.820  1034  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=213279  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 12:40:35.820  1034  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=213279  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 12:40:35.820  1034  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=213280  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 12:40:35.821  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 12:40:35.821  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-23 12:40:35.822  1034  1392 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:166711] from screen [on:0 period:-1224946706] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-23 12:40:35.823  1034  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1224946705] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-23 12:40:35.823  1034  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-23 12:40:35.824  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:35.828  1034  1425 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-23 12:40:35.829  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 12:40:35.829  1034  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.829  1034  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.829  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 12:40:35.830  1034  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.830  1034  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.830  1034  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.831  1034  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.831  1034  1425 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-23 12:40:35.831  1034  1392 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=110,0,0
,08-23 12:40:35.832  1034  1392 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=110,0,0
08-23 12:40:35.832  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-23 12:40:35.832  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-23 12:40:35.833  1034  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-23 12:40:35.833  1034  1392 D WifiNative-wlan0: doBoolean: SET ps 0
08-23 12:40:35.833  1034  1392 D WifiNative-wlan0: SET ps 0: returned true
08-23 12:40:35.833  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-23 12:40:35.833  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-23 12:40:35.833  1034  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-23 12:40:35.833  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:35.834  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24376a82 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:35.834  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24376a82 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:35.834  1034  8100 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:35.834  1034  8100 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-23 12:40:35.835  1034  1392 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-23 12:40:35.835  1034  1392 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-23 12:40:35.835  1034  1392 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-23 12:40:35.835   321   893 D CommandListener: Setting iface cfg
08-23 12:40:35.836   321   893 D CommandListener: Trying to bring up wlan0
08-23 12:40:35.837  1034  1392 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-23 12:40:35.837  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 12:40:35.837  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-23 12:40:35.840  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:35.840  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:35.840  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 12:40:35.840  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-23 12:40:35.841  7265  7265 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 12:40:35.841  1034  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.842  1034  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.842  1034  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.843  1034  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.843  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 12:40:35.843  1034  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.843  1034  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 12:40:35.844  1034  1425 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-23 12:40:35.844  1034  1392 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-23 12:40:35.845  1034  1392 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-23 12:40:35.845  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 12:40:35.845  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 12:40:35.845  1034  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:35.845  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:35.845  1034  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 12:40:35.845  1034  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-23 12:40:35.845  8044  8044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-23 12:40:35.846  1034  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-23 12:40:35.846  1034  1392 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 12:40:35.849  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 12:40:35.852  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 12:40:35.856  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:35.857  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:35.857  7265  7265 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 12:40:35.862  1034  1392 D WifiNative-wlan0: SET ps 1: returned true
08-23 12:40:35.862  1034  1425 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-23 12:40:35.862  1034  1392 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-23 12:40:35.862  1034  1392 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-23 12:40:35.862  1034  1392 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-23 12:40:35.863  1034  1425 D ConnectivityService: ignoring duplicate network state non-change
08-23 12:40:35.865  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:35.865  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-23 12:40:35.866  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:35.867  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.867  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.867  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-23 12:40:35.869  1034  1425 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-23 12:40:35.870  1034  1392 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-23 12:40:35.870  1034  1425 D ConnectivityService: Adding iface wlan0 to network 101
08-23 12:40:35.872  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:35.877  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.877  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 12:40:35.877  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-23 12:40:35.879  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-23 12:40:35.882  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-23 12:40:35.882  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.882  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.883  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-23 12:40:35.884  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-23 12:40:35.886  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:35.886  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 12:40:35.888  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 12:40:35.890  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:35.890  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-23 12:40:35.891  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:35.893  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.893  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:40:35.893  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-23 12:40:35.897  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:40:35.897  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-23 12:40:35.898  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:35.898  1034  1425 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 12:40:35.898  1034  1425 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-23 12:40:35.899  1034  1425 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-23 12:40:35.901   321   893 E Netd    : netlink response contains error (File exists)
08-23 12:40:35.901  1034  1425 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-23 12:40:35.902  1034  1425 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-23 12:40:35.902  1034  1425 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-23 12:40:35.902  1034  1425 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-23 12:40:35.903  1034  1425 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-23 12:40:35.903  1034  1425 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-23 12:40:35.903  1034  1425 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-23 12:40:35.903  1034  1425 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-23 12:40:35.903  1034  1425 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 12:40:35.903  1034  1425 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 12:40:35.903  1034  1425 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-23 12:40:35.904  1034  1425 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:35.904  1034  8099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:35.904  1034  1425 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-23 12:40:35.904  1034  8099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-23 12:40:35.904  1034  1425 D ConnectivityService: currentScore = 0, newScore = 20
08-23 12:40:35.904  1034  1425 D ConnectivityService:    accepting network in place of null
08-23 12:40:35.904  1034  8099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:40:35.904  1034  1425 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:35.904  1034  8099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-23 12:40:35.904  1034  1392 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:35.904  1034  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 12:40:35.905  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:35.906  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 12:40:35.906  1034  1425 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.,1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-23 12:40:35.906  1034  1425 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-23 12:40:35.907  1034  1425 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 12:40:35.907  1034  1425 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 12:40:35.907  1034  1425 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-23 12:40:35.907   321  8106 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-23 12:40:35.907  1034  1425 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-23 12:40:35.909  1034  1425 D ConnectivityService: validation of new default Network = false
08-23 12:40:35.909  1034  1425 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-23 12:40:35.909  1034  1425 D DSQN    : enableDataServiceNotify 
08-23 12:40:35.909  1034  1425 D DSQN    : start dsqn bin
08-23 12:40:35.910  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-23 12:40:35.910  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 12:40:35.910  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 12:40:35.910  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-23 12:40:35.918  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 12:40:35.921  1034  1425 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-23 12:40:35.921  1034  1425 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:35.921  1034  1425 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 12:40:35.921  1034  1425 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 12:40:35.922  1602  1827 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 12:40:35.910  8107  8107 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:35.910  8107  8107 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:35.923  1034  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-23 12:40:35.934  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:35.934  8107  8107 E DSQN    : DSQN ssw
,08-23 12:40:35.943  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:35.943  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:35.944  1817  8111 I CheckinService: active receiver: enabled
08-23 12:40:35.946  7265  7265 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 12:40:35.960  1817  8111 I CheckinService: Preparing to send checkin request
08-23 12:40:35.960  1817  8111 I EventLogService: Accumulating logs since 1471948736263
08-23 12:40:35.961   321  8106 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-23 12:40:35.962  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:35.969  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 12:40:35.973  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 12:40:35.974  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:35.974  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:35.975  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:35.979  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 12:40:35.979  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:35.980  7265  7265 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 12:40:35.983  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:35.985  7633  7633 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-23 12:40:35.988  7633  7633 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-23 12:40:35.990  7106  7172 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 927)
08-23 12:40:35.990  7106  7172 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 927)
08-23 12:40:35.991  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 12:40:35.992   321  8106 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-23 12:40:35.993  7106  7172 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 932)
08-23 12:40:35.994  7106  7172 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-23 12:40:35.994  7106  7172 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 933)
08-23 12:40:35.997  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:40:35.997  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24015298 added. We now have 2 listener(s)
08-23 12:40:35.998  1034  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:35.998  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:35.999  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 12:40:35.999  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:35.999  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:36.000  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:36.000  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@354aaaf1 added. We now have 9 listener(s)
08-23 12:40:36.000  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:36.000  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 12:40:36.001  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:36.002  1817  8111 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-23 12:40:36.005  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:36.005  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:36.006  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:36.006  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:36.006  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:36.006  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:36.006  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:36.006  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:36.006  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:36.006  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:36.006  7265  7265 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-23 12:40:36.007  7265  7265 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-23 12:40:36.007  7265  7265 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-23 12:40:36.008  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:36.008  7106  7172 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:40:36.009  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:40:36.009  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28d32d57 added. We now have 3 listener(s)
08-23 12:40:36.010  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:36.010  1034  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:36.012  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 12:40:36.012  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:36.014  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-23 12:40:36.014  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:36.014  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:36.014  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:36.014  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22050044 added. We now have 10 listener(s)
08-23 12:40:36.014  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:40:36.014  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:36.014  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:36.014  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:36.014  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 12:40:36.014  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.014  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:36.015  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:40:36.015  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24015298 removed from the list
08-23 12:40:36.015  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.015  7633  7633 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-23 12:40:36.015  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@354aaaf1 removed from the list
08-23 12:40:36.015  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:36.015  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.015  7633  7633 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-23 12:40:36.017   321   892 D LGDataListener: argv[0]=dsqncommand
08-23 12:40:36.017   321   892 D LGDataListener: argv[1]=wlan0
08-23 12:40:36.017   321   892 D LGDataListener: argv[2]=1
08-23 12:40:36.017   321   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-23 12:40:36.018  1034  1100 D DSQN    : DSQM DsqnNotification wlan0  1
08-23 12:40:36.018  1034  1100 D DSQN    : start to monitor internet connection
08-23 12:40:36.022  7192  7192 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 12:40:36.022  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.022  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.023  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:36.023  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:36.023  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.023  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@354aaaf1 not in the list
08-23 12:40:36.023  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.023  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.024  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:36.024  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:36.024  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.024  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22050044 removed from the list
08-23 12:40:36.024  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:36.024  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.024  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.024  7106  7172 I org.thaliproject.p2p.btconnec,torlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:40:36.024  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28d32d57 removed from the list
08-23 12:40:36.025  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:40:36.025  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ace052d added. We now have 2 listener(s)
08-23 12:40:36.025  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:36.027  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 12:40:36.027  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:36.027  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:36.027  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:36.027  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d1a1a62 added. We now have 9 listener(s)
08-23 12:40:36.027  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:36.027  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:40:36.030  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:36.031  7192  7192 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 12:40:36.035  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:36.035  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:36.035  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:36.035  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:36.035  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:36.035  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:36.035  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:36.035  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:36.035  1034  8100 D DhcpStateMachine: DHCPV4 request on wlan0
08-23 12:40:36.036  1034  8100 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-23 12:40:36.036  1034  8100 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-23 12:40:36.030  8115  8115 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 12:40:36.030  8115  8115 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 12:40:36.039  7265  7265 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 12:40:36.040  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:36.040  7265  7265 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 12:40:36.040  7106  7172 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:40:36.040  7265  7265 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-23 12:40:36.041  7265  7265 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-23 12:40:36.041  7265  7265 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-23 12:40:36.041  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:40:36.041  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d73dcb0 added. We now have 3 listener(s)
08-23 12:40:36.042  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:36.042  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:36.045  8115  8115 I dhcpcd  : version 5.5.6 starting
08-23 12:40:36.046  1034  8099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 10:40:36 GMT], X-Android-Received-Millis=[1471948836045], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471948836016]}
08-23 12:40:36.046  1034  8099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-23 12:40:36.046  1034  8099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-23 12:40:36.047  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-23 12:40:36.047  8115  8115 E dhcpcd  : get_duid: m
08-23 12:40:36.047  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:36.047  8115  8115 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-23 12:40:36.047  8115  8115 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-23 12:40:36.047  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:36.048  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:36.048  1034  1425 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-23 12:40:36.048  1034  1425 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-23 12:40:36.048  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27b2c729 added. We now have 10 listener(s)
08-23 12:40:36.048  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:36.048  1034  1425 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 12:40:36.048  1034  1425 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 12:40:36.048  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:40:36.048  1034  1425 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-23 12:40:36.048  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:40:36.048  1034  1425 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-23 12:40:36.048  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:40:36.048  1034  1425 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-23 12:40:36.048  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:36.048  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 12:40:36.048  1034  1425 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:36.048  1034  1425 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 12:40:36.048  1034  1425 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 12:40:36.050  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:36.050  1034  1425 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:36.050  1034  1392 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:36.050  1034  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 12:40:36.050  1034  1425 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_AC,TION
08-23 12:40:36.051  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:36.051  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 12:40:36.051  1602  1827 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-23 12:40:36.053  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 12:40:36.054  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:36.064  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 12:40:36.065  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 12:40:36.069  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:40:36.069  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:36.070  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 12:40:36.071  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:36.072  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 12:40:36.072  7106  7172 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 12:40:36.072  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:36.072  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:36.074  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:36.074  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:36.074  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:36.074  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:36.074  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.074  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:36.074  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:40:36.074  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ace052d removed from the list
08-23 12:40:36.074  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.074  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d1a1a62 removed from the list
08-23 12:40:36.075  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:36.075  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.075  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.075  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:40:36.075  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:36.076  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:36.076  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.076  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d1a1a62 not in the list
08-23 12:40:36.076  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.076  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.076  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:36.077  7106  7172 D BluetoothLeScanner: could not find callback wrapper
,08-23 12:40:36.077  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:36.077  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:36.077  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.077  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27b2c729 removed from the list
08-23 12:40:36.077  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:36.077  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.077  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.077  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:40:36.077  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d73dcb0 removed from the list
08-23 12:40:36.078  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:40:36.078  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b213dc added. We now have 2 listener(s)
08-23 12:40:36.079  1034  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:36.080  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 12:40:36.080  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:36.080  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:36.081  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:36.081  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3307ace5 added. We now have 9 listener(s)
08-23 12:40:36.081  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:36.084  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 12:40:36.086  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:36.088  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:36.088  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:36.088  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:36.088  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:36.088  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:36.088  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:36.088  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:36.088  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:36.089  7106  7172 D io.jxcore.node.JXcoreExtension: no,tifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:36.089  7106  7172 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:40:36.089  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:40:36.089  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12edc26b added. We now have 3 listener(s)
08-23 12:40:36.090  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 12:40:36.091  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:36.094  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:36.094  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 12:40:36.094  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:36.094  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:36.094  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:36.094  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a91c8 added. We now have 10 listener(s)
08-23 12:40:36.094  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:36.094  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:40:36.095  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:40:36.095  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:40:36.095  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:40:36.095  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:36.095  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 12:40:36.097  8115  8115 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-23 12:40:36.097  8115  8115 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-23 12:40:36.097  8115  8115 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-23 12:40:36.097  8115  8115 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-23 12:40:36.097  8115  8115 D dhcpcd  : wlan0: sending REQUEST (xid 0x726b5543), next in 3.78 seconds
08-23 12:40:36.137  8115  8115 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-23 12:40:36.139  1034  1728 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8122 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-23 12:40:36.142  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 12:40:36.142  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:36.146  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 12:40:36.147  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 12:40:36.149  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 12:40:36.149  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:36.151  7106  7172 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 12:40:36.152  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 12:40:36.152  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:36.152  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:36.152  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:36.152  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.152  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:36.152  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:40:36.152  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b213dc removed from the list
08-23 12:40:36.152  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.152  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3307ace5 removed from the list
08-23 12:40:36.152  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:36.152  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:40:36.153  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.153  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.153  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:36.153  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:36.154  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.154  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3307ace5 not in the list
08-23 12:40:36.154  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.154  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.154  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:36.155  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:36.155  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:36.155  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:36.155  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.155  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a91c8 removed from the list
08-23 12:40:36.155  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:36.155  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.155  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.155  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:40:36.155  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12edc26b removed from the list
08-23 12:40:36.156  8115  8115 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-23 12:40:36.156  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:40:36.156  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14241a47 added. We now have 2 listener(s)
08-23 12:40:36.157  8115  8115 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-23 12:40:36.157  8115  8115 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-23 12:40:36.158  8115  8115 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-23 12:40:36.158  1034  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:36.158  8115  8115 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-23 12:40:36.158  8115  8115 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-23 12:40:36.159  8115  8115 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-23 12:40:36.159  8115  8115 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-23 12:40:36.161  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address,: "58:3F:54:73:BA:17"
08-23 12:40:36.161  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:36.161  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:36.161  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:36.161  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d4b0274 added. We now have 9 listener(s)
08-23 12:40:36.161  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:40:36.167  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 12:40:36.170  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:36.175  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:36.175  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:36.175  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:36.175  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:36.175  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:36.175  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:36.175  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:36.175  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:40:36.177  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:36.177  7106  7172 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:40:36.178  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-23 12:40:36.179  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c81e012 added. We now have 3 listener(s)
08-23 12:40:36.179  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:36.180  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:36.181  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:36.183  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 12:40:36.183  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:36.183  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:36.183  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:36.183  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@357e13e3 added. We now have 10 listener(s)
08-23 12:40:36.183  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:36.184  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:40:36.184  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:40:36.184  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:40:36.184  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:36.184  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 12:40:36.187  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:40:36.187  1034  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 12:40:36.191  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 12:40:36.191  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 12:40:36.193  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:40:36.194  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:36.195  7106  7172 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 12:40:36.197  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:36.197  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:36.197  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:36.199  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:36.199  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.199  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:36.199  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:40:36.199  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14241a47 removed from the list
08-23 12:40:36.199  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.199  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d4b0274 removed from the list
08-23 12:40:36.199  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:36.199  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.200  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.200  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.201  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:36.201  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:36.201  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.201  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d4b0274 not in the list
08-23 12:40:36.201  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.201  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.202  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:36.203  7106  7172 D BluetoothLeScanner: could not find callback wrapper
08-23 12:40:36.204  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:40:36.204  7106  7172 I, org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:36.204  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.204  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@357e13e3 removed from the list
08-23 12:40:36.204  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:36.204  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:40:36.204  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.204  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:40:36.204  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c81e012 removed from the list
08-23 12:40:36.204  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:40:36.205  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@599eb5e added. We now have 2 listener(s)
08-23 12:40:36.205  1034  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:36.208  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 12:40:36.208  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:36.208  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:36.208  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:36.208  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f40b3f added. We now have 9 listener(s)
08-23 12:40:36.208  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:36.209  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 12:40:36.211  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:40:36.214  7106  7172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:40:36.214  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:40:36.214  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:40:36.214  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:40:36.214  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:40:36.214  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:40:36.214  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:40:36.214  7106  7172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:40:36.216  7106  7172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:40:36.216  7106  7172 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:40:36.216  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:40:36.216  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12969955 added. We now have 3 listener(s)
08-23 12:40:36.218  1034  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:40:36.219  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:36.220  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:40:36.221  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 12:40:36.221  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:40:36.221  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:40:36.222  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:40:36.222  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39955f6a added. We now have 10 listener(s)
08-23 12:40:36.222  7106  7172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:40:36.222  7106  7172 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:40:36.222  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:36.222  7106  7172 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:40:36.223  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:36.223  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.223  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:40:36.223  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:40:36.223  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@599eb5e removed from the list
08-23 12:40:36.223  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.223  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f40b3f removed from the list
08-23 12:40:36.223  7106  7172 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:40:36.223  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.223  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.223  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.224  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:36.224  7106  7172 I org.thaliproject.p2p.btconnect,orlib.DiscoveryManager: stopDiscovery
08-23 12:40:36.224  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.224  7106  7172 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f40b3f not in the list
08-23 12:40:36.224  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.224  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.225  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:40:36.225  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:40:36.225  7106  7172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:40:36.225  7106  7172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39955f6a removed from the list
08-23 12:40:36.225  7106  7172 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:40:36.225  7106  7172 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:40:36.225  7106  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:40:36.225  7106  7172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:40:36.225  7106  7172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12969955 removed from the list
08-23 12:40:36.226  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-23 12:40:36.226  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-23 12:40:36.226  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-23 12:40:36.226  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:40:36.227  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-23 12:40:36.227  7106  7172 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 12:40:36.231  8122  8122 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-23 12:40:36.231  8122  8122 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 12:40:36.236  7106  8146 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 940, name: My test thread name)
08-23 12:40:36.236  7106  8146 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 940, thread name: My test thread name)
08-23 12:40:36.237  7106  8146 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 940, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 12:40:36.239  7106  8148 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 942, name: My test thread name)
08-23 12:40:36.239  7106  8148 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 942, thread name: My test thread name)
08-23 12:40:36.239  7106  8148 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 942, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 12:40:36.240  7106  7172 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-23 12:40:36.241  7106  7172 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-23 12:40:36.241  7106  7172 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-23 12:40:36.241  7106  7172 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-23 12:40:36.241  7106  7172 D com.test.thalitest.ThaliTestRunner: Total duration: 22915 ms
08-23 12:40:36.242  7106  7172 I jxcore-log: Total number of executed tests:  80
08-23 12:40:36.242  7106  7172 I jxcore-log: 
08-23 12:40:36.242  7106  7172 I jxcore-log: Number of passed tests:  80
08-23 12:40:36.242  7106  7172 I jxcore-log: 
08-23 12:40:36.242  7106  7172 I jxcore-log: Number of failed tests:  0
08-23 12:40:36.242  7106  7172 I jxcore-log: 
08-23 12:40:36.242  7106  7172 I jxcore-log: Number of ignored tests:  0
08-23 12:40:36.242  7106  7172 I jxcore-log: 
08-23 12:40:36.242  7106  7172 I jxcore-log: Total duration:  22915
08-23 12:40:36.242  7106  7172 I jxcore-log: 
08-23 12:40:36.243  7106  7172 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-23 12:40:36.243  7106  7172 I jxcore-log: 
08-23 12:40:36.248  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.248  7106  7172 I jxcore-log: 
,08-23 12:40:36.251  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.251  7106  7172 I jxcore-log: 
08-23 12:40:36.252  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.252  7106  7172 I jxcore-log: 
08-23 12:40:36.253  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.253  7106  7172 I jxcore-log: 
08-23 12:40:36.254  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.254  7106  7172 I jxcore-log: 
08-23 12:40:36.257  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.257  7106  7172 I jxcore-log: 
08-23 12:40:36.259  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.259  7106  7172 I jxcore-log: 
08-23 12:40:36.259  8122  8122 I MultiDex: VM with version 2.1.0 has multidex support
08-23 12:40:36.260  8122  8122 I MultiDex: install
08-23 12:40:36.260  8122  8122 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-23 12:40:36.261  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 12:40:36.261  7106  7172 I jxcore-log: 
08-23 12:40:36.262  7106  7106 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-23 12:40:36.262  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 12:40:36.262  7106  7172 I jxcore-log: 
08-23 12:40:36.263  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:40:36.263  7106  7172 I jxcore-log: 
08-23 12:40:36.264  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:40:36.264  7106  7172 I jxcore-log: 
,08-23 12:40:36.266  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 12:40:36.266  7106  7172 I jxcore-log: 
08-23 12:40:36.268  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 12:40:36.268  7106  7172 I jxcore-log: 
08-23 12:40:36.268  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 12:40:36.268  7106  7172 I jxcore-log: 
,08-23 12:40:36.269  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:40:36.269  7106  7172 I jxcore-log: 
08-23 12:40:36.270  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:40:36.270  7106  7172 I jxcore-log: 
08-23 12:40:36.271  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:40:36.271  7106  7172 I jxcore-log: 
08-23 12:40:36.271  8122  8122 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-23 12:40:36.273  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:40:36.273  7106  7172 I jxcore-log: 
08-23 12:40:36.274  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:40:36.274  7106  7172 I jxcore-log: 
08-23 12:40:36.274  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:40:36.274  7106  7172 I jxcore-log: 
08-23 12:40:36.275  2198  2198 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-23 12:40:36.275  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:40:36.275  7106  7172 I jxcore-log: 
08-23 12:40:36.276  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:40:36.276  7106  7172 I jxcore-log: 
08-23 12:40:36.277  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 12:40:36.277  7106  7172 I jxcore-log: 
,08-23 12:40:36.278  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 12:40:36.278  7106  7172 I jxcore-log: 
08-23 12:40:36.278  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.278  7106  7172 I jxcore-log: 
08-23 12:40:36.279  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.279  7106  7172 I jxcore-log: 
08-23 12:40:36.279  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.279  7106  7172 I jxcore-log: 
,08-23 12:40:36.280  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.280  7106  7172 I jxcore-log: 
08-23 12:40:36.281  7106  7172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:40:36.281  7106  7172 I jxcore-log: 
08-23 12:40:36.286  2198  2198 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-23 12:40:36.287  2198  2198 D c       : Getting all permits...
08-23 12:40:36.287  2198  2198 D a       : Opening database...
08-23 12:40:36.291  2198  2198 D a       : Opening database auth.proximity.permit_store...
08-23 12:40:36.291  2198  2198 D a       : Closing database...
08-23 12:40:36.438  1034  8100 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-23 12:40:36.440  1034  8100 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-23 12:40:36.441  1034  8100 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-23 12:40:36.441  1034  8100 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-23 12:40:36.441  1034  8100 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-23 12:40:36.441  1034  8100 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-23 12:40:36.442  1034  8100 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-23 12:40:36.442  1034  8100 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-23 12:40:36.444  1034  8100 D DhcpStateMachine: RunningState
08-23 12:40:36.535  8160  8160 D AndroidRuntime: 
08-23 12:40:36.535  8160  8160 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 12:40:36.538  8160  8160 D AndroidRuntime: CheckJNI is OFF
08-23 12:40:36.577  8166  8166 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-23 12:40:36.647  8166  8166 I dex2oat : dex2oat took 69.558ms (threads: 4)
,08-23 12:40:36.662  8122  8141 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 12:40:36.662  8122  8141 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 12:40:36.662  8122  8141 I Adreno-EGL: Build Date: 12/12/14 금
08-23 12:40:36.662  8122  8141 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 12:40:36.662  8122  8141 I Adreno-EGL: Remote Branch: 
08-23 12:40:36.662  8122  8141 I Adreno-EGL: Local Patches: 
08-23 12:40:36.662  8122  8141 I Adreno-EGL: Reconstruct Branch: 
,08-23 12:40:36.720  8160  8160 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 12:40:36.735  1034  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-23 12:40:36.735  1034  1091 I ActivityManager: Killing 7106:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-23 12:40:36.798  8122  8141 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 12:40:36.798  8122  8141 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 12:40:36.798  8122  8141 I Adreno-EGL: Build Date: 12/12/14 금
08-23 12:40:36.798  8122  8141 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 12:40:36.798  8122  8141 I Adreno-EGL: Remote Branch: 
08-23 12:40:36.798  8122  8141 I Adreno-EGL: Local Patches: 
08-23 12:40:36.798  8122  8141 I Adreno-EGL: Reconstruct Branch: 
,08-23 12:40:36.807  1034  1995 I WindowState: WIN DEATH: Window{16b3fb49 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 12:40:36.807  1034  1405 D WifiService: Client connection lost with reason: 4
08-23 12:40:36.815  1034  1995 D InputDispatcher: Window went away: Window{16b3fb49 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 12:40:36.943  1034  1091 E libprocessgroup: failed to kill 1 processes for processgroup 7106
,08-23 12:40:36.945  1034  1091 I ActivityManager:   Force finishing activity ActivityRecord{315dfbfa u0 com.test.thalitest/.MainActivity t6}
,08-23 12:40:36.974   347   352 E GBMv2   : DFP En is all cleared set to be enabled
08-23 12:40:36.976  1034  1574 W ActivityManager: Spurious death for ProcessRecord{152fe973 7106:com.test.thalitest/u0a118}, curProc for 7106: null
08-23 12:40:36.976  1034  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-23 12:40:36.978  1034  1126 I ActivityManager:   Force finishing activity ActivityRecord{315dfbfa u0 com.test.thalitest/.MainActivity t6 f}
08-23 12:40:36.978  1034  1126 W ActivityManager: Duplicate finish request for ActivityRecord{315dfbfa u0 com.test.thalitest/.MainActivity t6 f}
,08-23 12:40:36.995  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-23 12:40:36.995  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b68a046 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 12:40:36.997  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-23 12:40:36.998  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{885c207 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-23 12:40:37.017  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-23 12:40:37.023  1034  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 12:40:37.032  3861  3861 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-23 12:40:37.032  2473  2598 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-23 12:40:37.033  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 12:40:37.037  7879  7879 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-23 12:40:37.037  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-23 12:40:37.085  4632  4632 I art     : Explicit concurrent mark sweep GC freed 8055(463KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 405us total 38.853ms
08-23 12:40:37.103  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-23 12:40:37.104  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-23 12:40:37.105  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-23 12:40:37.114  4529  4529 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 12:40:37.114  4529  4529 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-23 12:40:37.114  4529  4529 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-23 12:40:37.114  4529  4529 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-23 12:40:37.114  4529  4529 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 12:40:37.114  4529  4529 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 12:40:37.114  4529  4529 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 12:40:37.114  4529  4529 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 12:40:37.115  4529  4529 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:40:37.115  4529  4529 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:40:37.115  4529  4529 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 12:40:37.115  4529  4529 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 12:40:37.124  1034  1905 V SIM_STK : Menu title from STK is T-Mobile
08-23 12:40:37.154  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-23 12:40:37.155  1870  1870 D SplitUIService: removed split : 
,08-23 12:40:37.172  1034  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-23 12:40:37.173  1034  1923 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8194 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-23 12:40:37.175  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-23 12:40:37.176  2034  2125 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-23 12:40:37.178  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-23 12:40:37.181  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-23 12:40:37.181  1034  1034 I art     : Explicit concurrent mark sweep GC freed 78960(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.844ms total 188.677ms
08-23 12:40:37.182  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-23 12:40:37.182  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-23 12:40:37.183  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-23 12:40:37.185  8122  8141 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 12:40:37.185  8122  8141 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 12:40:37.185  8122  8141 I Adreno-EGL: Build Date: 12/12/14 금
08-23 12:40:37.185  8122  8141 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 12:40:37.185  8122  8141 I Adreno-EGL: Remote Branch: 
08-23 12:40:37.185  8122  8141 I Adreno-EGL: Local Patches: 
08-23 12:40:37.185  8122  8141 I Adreno-EGL: Reconstruct Branch: 
08-23 12:40:37.186  1906  1906 D ActionManagerService: notifyUserLog: 1000003
08-23 12:40:37.187  3861  4523 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-23 12:40:37.190  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-23 12:40:37.194  1034  1126 I art     : WaitForGcToComplete blocked for 199.848ms for cause Explicit
08-23 12:40:37.208  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-23 12:40:37.209  1906  1906 D ActionManagerService: notifyUserLog: 1000004
08-23 12:40:37.210  3861  4523 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-23 12:40:37.210  2198  2198 I ConfigService: onCreate
08-23 12:40:37.211  2198  2198 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-23 12:40:37.217  3861  3876 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , display: false
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , animation: false }
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , display: false
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , animation: false }
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , create_time: 1471602816196
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , display: false
08-23 12:40:37.219  2034  2034 I GBoardWebViewUtils: , animation: false }
08-23 12:40:37.223  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-23 12:40:37.223  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-23 12:40:37.226  2198  2198 I ConfigService: onBind returning update interface
,08-23 12:40:37.229  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-23 12:40:37.229  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-23 12:40:37.230  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-23 12:40:37.230  2034  8212 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-23 12:40:37.230  2198  2198 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-23 12:40:37.231  2198  2198 I ConfigService: onBind returning config service
08-23 12:40:37.237  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-23 12:40:37.237  1870  1870 I SplitUIService: split app #11
,08-23 12:40:37.244  1817  1817 I ConfigFetchService: service connected
08-23 12:40:37.244  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 12:40:37.245  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-23 12:40:37.246  2198  2198 I ConfigService: onDestroy
08-23 12:40:37.254  1034  1958 V SIM_STK : Menu title from STK is T-Mobile
,08-23 12:40:37.271  8194  8194 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-23 12:40:37.273  1034  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-23 12:40:37.273  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-23 12:40:37.273  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 12:40:37.273  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 12:40:37.273  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-23 12:40:37.273  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 12:40:37.273  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 12:40:37.273  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 12:40:37.273  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 12:40:37.273  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 12:40:37.274  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 12:40:37.274  7879  7879 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 12:40:37.278  1817  8214 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-23 12:40:37.305  2034  2048 I art     : Background sticky concurrent mark sweep GC freed 2113(118KB) AllocSpace objects, 2(32KB) LOS objects, 0% free, 79MB/79MB, paused 11.164ms total 17.750ms
08-23 12:40:37.306   340   422 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-23 12:40:37.307  3203  8217 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-23 12:40:37.312  1034  2033 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8218 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-23 12:40:37.319  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-23 12:40:37.325  1034  1034 D administrator: Handling package changes for user 0
08-23 12:40:37.329  1602  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 12:40:37.329  1602  1651 D KeyguardModel: createShortcutInfo...
08-23 12:40:37.332  1602  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 12:40:37.332  1602  1651 D KeyguardModel: createShortcutInfo...
08-23 12:40:37.336  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-23 12:40:37.336  1602  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:40:37.336  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-23 12:40:37.347  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 12:40:37.347  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:40:37.347  1602  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 12:40:37.348  1602  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 12:40:37.348  1602  1651 D KeyguardModel: createShortcutInfo...
,08-23 12:40:37.368  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 12:40:37.368  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 12:40:37.370  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-23 12:40:37.370  1602  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 12:40:37.371  8122  8141 D LgDataFeature: LgDataFeature() Constructor: none
08-23 12:40:37.371  8122  8141 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 12:40:37.373  1602  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 12:40:37.373  1602  1651 D KeyguardModel: createShortcutInfo...
08-23 12:40:37.377  1602  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:40:37.377  1602  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 12:40:37.377  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 12:40:37.378  1602  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 12:40:37.378  1817  4800 I Icing   : doRemovePackageData com.test.thalitest
08-23 12:40:37.381  1817  8239 I PeopleContactsSync: CP2 sync disabled
08-23 12:40:37.381  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:40:37.381  1602  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 12:40:37.383  5929  8230 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-23 12:40:37.397  2198  2223 I art     : Explicit concurrent mark sweep GC freed 6813(433KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 1.140ms total 21.544ms
08-23 12:40:37.409  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-23 12:40:37.409  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 12:40:37.409  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 12:40:37.411  1034  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-23 12:40:37.411  1602  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 12:40:37.411  1602  1651 D KeyguardModel: createShortcutInfo...
08-23 12:40:37.412  1817  8237 W GmsApplication: Using Auth Proxy for data requests.
08-23 12:40:37.414  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-23 12:40:37.414  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 12:40:37.417  1602  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 12:40:37.417  1602  1651 D KeyguardModel: createShortcutInfo...
08-23 12:40:37.421  1817  8237 W GmsApplication: Using Auth Proxy for data requests.
,08-23 12:40:37.427  1602  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 12:40:37.427  1602  1651 D KeyguardModel: createShortcutInfo...
08-23 12:40:37.428  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:40:37.428  1602  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 12:40:37.429  1602  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 12:40:37.429  1602  1651 D KeyguardModel: createShortcutInfo...
08-23 12:40:37.430  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:40:37.431  1602  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 12:40:37.435  1602  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 12:40:37.435  1602  1651 D KeyguardModel: createShortcutInfo...
08-23 12:40:37.436  1602  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:40:37.436  1602  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-23 12:40:37.439  1602  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 12:40:37.440  1602  1651 D KeyguardModel: createShortcutInfo...
08-23 12:40:37.447  1034  1392 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-23 12:40:37.453  1034  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 12:40:37.453  1034  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 12:40:37.453  1034  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 12:40:37.454  1034  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 12:40:37.454  1034  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 12:40:37.454  1034  1425 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-23 12:40:37.454  1034  1425 D ConnectivityService: identical MTU - not setting
08-23 12:40:37.454  1034  1425 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-23 12:40:37.454  1034  1425 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-23 12:40:37.454  1034  1425 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:40:37.454  1034  1425 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 12:40:37.455  1034  1425 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 12:40:37.455  1602  1827 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-23 12:40:37.463  1034  1574 I ActivityManager: Killing 7435:com.lge.email/u0a23 (adj 15): empty #17
,08-23 12:40:37.469  8218  8218 I AppUp4:AppBoxCP: onCreate
08-23 12:40:37.470  8218  8218 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-23 12:40:37.475  8218  8218 I AppUp4:DB:  setFingerPrint start
08-23 12:40:37.475  8218  8218 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-23 12:40:37.481  8218  8218 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-23 12:40:37.481  8218  8218 I AppUp4:DB:  SDK version = 21
08-23 12:40:37.481  8218  8218 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-23 12:40:37.483  1034  1126 I art     : Explicit concurrent mark sweep GC freed 10757(686KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 5.525ms total 287.778ms
08-23 12:40:37.503  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-23 12:40:37.506  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:40:37.508  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-23 12:40:37.509  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-23 12:40:37.510  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-23 12:40:37.511  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-23 12:40:37.526  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-23 12:40:37.527  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:40:37.534  2034  2191 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-23 12:40:37.534  2034  2191 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-23 12:40:37.540  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-23 12:40:37.541  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 12:40:37.541  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:40:37.548  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-23 12:40:37.553  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-23 12:40:37.553  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-23 12:40:37.554  1034  1905 W libprocessgroup: failed to open /acct/uid_10023/pid_7435/cgroup.procs: No such file or directory
,08-23 12:40:37.556  8160  8160 D AndroidRuntime: Shutting down VM
08-23 12:40:37.557  8218  8218 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-23 12:40:37.558  2615  2615 D [Concierge]Service: onStartCommand(). Type : 8
08-23 12:40:37.558  2615  2615 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-23 12:40:37.559  1034  1103 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ff403a6 u0 com.lge.launcher2/.Launcher t5} time:215032
08-23 12:40:37.559  2615  2615 D [Concierge]Service: Update widget ID : 11
08-23 12:40:37.562  2034  2034 D [Concierge]WidgetView: change position of spinner
08-23 12:40:37.575  8218  8218 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-23 12:40:37.592  1034  1126 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8246 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-23 12:40:37.593  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1471948837593
08-23 12:40:37.594  2615  2615 D [Concierge]Service: onStartCommand(). Type : 0
08-23 12:40:37.600  1034  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:40:37.603  1034  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-23 12:40:37.622  1034  1974 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8263 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-23 12:40:37.623  1034  1974 I ActivityManager: Killing 7471:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-23 12:40:37.660  1034  1995 W libprocessgroup: failed to open /acct/uid_10046/pid_7471/cgroup.procs: No such file or directory
08-23 12:40:37.676  8263  8263 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:40:37.677  8263  8263 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 12:40:37.677  8263  8263 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-23 12:40:37.678  8263  8263 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-23 12:40:37.678  8263  8263 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 12:40:37.679  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 595994526
08-23 12:40:37.679  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-23 12:40:37.679  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 12:40:37.682  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@5c46d59
08-23 12:40:37.682  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-23 12:40:37.683  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 12:40:37.683  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:40:37.686   321  8282 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-23 12:40:37.686   321  8282 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-23 12:40:37.688  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-23 12:40:37.689  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-23 12:40:37.689  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-23 12:40:37.690  1034  1050 I ActivityManager: Killing 7490:com.android.chrome/u0a57 (adj 15): empty #17
08-23 12:40:37.690  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-23 12:40:37.717  1034  2011 W libprocessgroup: failed to open /acct/uid_10057/pid_7490/cgroup.procs: No such file or directory
,08-23 12:40:37.717  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471948651257, New one : 1471948837593
,08-23 12:40:37.717  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-23 12:40:37.717   321  8282 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-23 12:40:37.717  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 12:40:37.719  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:40:37.720  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-23 12:40:37.721  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-23 12:40:37.722  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-23 12:40:37.723  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-23 12:40:37.724  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-23 12:40:37.725  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:40:37.725  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:40:37.741  8263  8263 I SystemConfig: BUILD Country: EU
08-23 12:40:37.741  8263  8263 I SystemConfig: BUILD Operator: OPEN
,08-23 12:40:37.764  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-23 12:40:37.772  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-23 12:40:37.772  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-23 12:40:37.774  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-23 12:40:37.793  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@535ee4b time:215266
,08-23 12:40:37.798  1034  1995 I ActivityManager: Killing 7514:com.lge.drmservice/u0a62 (adj 15): empty #17
08-23 12:40:37.805  1817  8111 I CheckinTask: Sending checkin request (8016 bytes)
,08-23 12:40:37.868  1034  2011 W libprocessgroup: failed to open /acct/uid_10062/pid_7514/cgroup.procs: No such file or directory
,08-23 12:40:37.873  2372  2494 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 12:40:37.873  2372  8288 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-23 12:40:37.874  8263  8284 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-23 12:40:37.874  8263  8284 I SystemConfig: existFile = false
08-23 12:40:37.874  8263  8284 I SystemConfig: canReadFile = false
08-23 12:40:37.875  8263  8284 I SystemConfig: systemFeature RCS result false
08-23 12:40:37.875  8263  8284 D SystemConfig: refreshRcsSupport() :false
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-23 12:40:37.875  2372  2494 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:40:37.880  2372  8288 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
08-23 12:40:37.880  2372  8288 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-23 12:40:37.880  2372  8288 E AndroidRuntime: Process: android.process.acore, PID: 2372
08-23 12:40:37.880  2372  8288 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-23 12:40:,37.880  2372  8288 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-23 12:40:37.880  2372  8288 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:40:37.901  1034  1905 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8289 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-23 12:40:37.904  2372  8288 I Process : Sending signal. PID: 2372 SIG: 9
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:40:37.907  1034  8295 E DropBoxManagerService: 	... 5 more
08-23 12:40:37.911   355   355 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 197us total 9.515ms
08-23 12:40:37.915  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-23 12:40:37.919  4529  4576 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: Error inserting f004=13 f005=8289 f002=1471948837903 f003=com.lge.email f006=10023
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-23 12:40:37.920  4529  4576 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
08-23 12:40:37.921   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.990ms

```
