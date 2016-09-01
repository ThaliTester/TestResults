#### Test 835917643a9a586_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
,09-01 11:33:00.108  1595  1595 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-01 11:33:00.108  1595  1595 I KeyguardUpdateMonitor: called onTimeUpdated()
09-01 11:33:00.108  1595  1595 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-01 11:33:00.109  1595  1595 I [SystemUI]Clock: called onTimeUpdated()
09-01 11:33:00.122  1595  1595 I LgeClockWidgetControlView: called onTimeUpdated()
09-01 11:33:00.122  1595  1595 I [SystemUI]DateView: called onTimeUpdated()
09-01 11:33:00.128  1595  1595 I [SystemUI]DateView: called onTimeUpdated()
09-01 11:33:00.129  1595  1595 D KeyguardUpdateMonitor: handleTimeUpdate
09-01 11:33:00.433  6817  6817 D AndroidRuntime: 
09-01 11:33:00.433  6817  6817 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-01 11:33:00.440  6817  6817 D AndroidRuntime: CheckJNI is OFF
09-01 11:33:00.640  6817  6817 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-01 11:33:00.651  1026  1568 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-01 11:33:00.667  1936  3305 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-01 11:33:00.674  1026  1568 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-01 11:33:00.676  1026  1568 D ActivityManager: setTaskToReturnTo : TaskRecord{2e00022 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-01 11:33:00.676  1026  1568 D ActivityManager: setTaskToReturnTo : TaskRecord{2e00022 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-01 11:33:00.678  1026  1568 D WindowStateEx: AppWindowTokenEx init.. 
09-01 11:33:00.678   338   400 E GBMv2   : DFP En is all cleared set to be enabled
09-01 11:33:00.706  1026  1568 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6832 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-01 11:33:00.709  6817  6817 D AndroidRuntime: Shutting down VM
09-01 11:33:00.764  1936  1952 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-01 11:33:00.764  1936  1952 D SplitWindowPolicy: topRunningActivity=ActivityInfo{37ec1db5 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-01 11:33:00.765  1936  1951 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-01 11:33:00.765  1936  1951 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f93fc4a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-01 11:33:00.837  6832  6832 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-01 11:33:00.906  6832  6832 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-01 11:33:00.930  6832  6832 I LibraryLoader: Loading: webviewchromium
,09-01 11:33:00.937  6832  6832 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 8472-8481)
,09-01 11:33:00.937  6832  6832 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 11:33:00.965  6832  6832 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {366a6aa5}
,09-01 11:33:00.967  6832  6832 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 11:33:00.967  6832  6832 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-01 11:33:00.980  6832  6832 I BrowserStartupController: Initializing chromium process, renderers=0
,09-01 11:33:00.981  6832  6832 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 11:33:00.998  6832  6832 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-01 11:33:00.999  6832  6832 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-01 11:33:01.000  6832  6832 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-01 11:33:01.008   321  1376 V AudioPolicyService: registerClient() client 0xb1023c80, uid 10118
09-01 11:33:01.013  1026  1088 D BluetoothManagerService: Message: 20
09-01 11:33:01.013  1026  1088 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1142cb9c:true
,09-01 11:33:01.026  6832  6832 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:33:01.026  6832  6832 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:33:01.026  6832  6832 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:33:01.026  6832  6832 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:33:01.026  6832  6832 I Adreno-EGL: Remote Branch: 
09-01 11:33:01.026  6832  6832 I Adreno-EGL: Local Patches: 
09-01 11:33:01.026  6832  6832 I Adreno-EGL: Reconstruct Branch: 
,09-01 11:33:01.114  6832  6876 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-01 11:33:01.124  6832  6832 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-01 11:33:01.155  6832  6832 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 11:33:01.160  6832  6832 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-01 11:33:01.164  6832  6832 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-01 11:33:01.167  6832  6832 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-01 11:33:01.167  6832  6832 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-01 11:33:01.185  6832  6832 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-01 11:33:01.201  6832  6832 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-01 11:33:01.201  6832  6832 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 11:33:01.240  6832  6892 D OpenGLRenderer: Render dirty regions requested: true
09-01 11:33:01.240  6832  6892 I OpenGLRenderer: Initialized EGL, version 1.4
09-01 11:33:01.257  6832  6892 D OpenGLRenderer: Enabling debug mode 0
,09-01 11:33:01.264  1026  1084 W ActivityManager: Activity pause timeout for ActivityRecord{35b69ab3 u0 com.test.thalitest/.MainActivity t6}
09-01 11:33:01.267  6832  6832 D Atlas   : Validating map...
09-01 11:33:01.271  1026  1917 D SplitWindow: check instance of lgWin Window{2668f1f6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-01 11:33:01.314  6832  6890 D LgDataFeature: LgDataFeature() Constructor: none
,09-01 11:33:01.314  6832  6890 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:33:01.392  1026  1089 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +629ms (total +713ms)
09-01 11:33:01.393  1026  1089 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{35b69ab3 u0 com.test.thalitest/.MainActivity t6} time:188938
09-01 11:33:01.394  6832  6832 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@297ed5b8 time:188938
,09-01 11:33:01.526  6832  6832 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-01 11:33:01.526  6832  6832 I chromium: 
,09-01 11:33:01.579  6832  6832 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-01 11:33:01.639  6832  6890 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-01 11:33:01.639  6832  6890 I chromium: 
,09-01 11:33:01.797  6832  6906 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
,09-01 11:33:01.814  6832  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-01 11:33:01.814  6832  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-01 11:33:01.814  6832  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-01 11:33:01.814  6832  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-01 11:33:01.814  6832  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-01 11:33:01.815  6832  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ae2cfc added. We now have 1 listener(s)
,09-01 11:33:01.821  1026  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:01.825  6832  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-01 11:33:01.833  6832  6906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-01 11:33:01.839  6832  6906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:01.839  6832  6906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-01 11:33:01.849  6832  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@303f060b added. We now have 1 listener(s)
09-01 11:33:01.849  6832  6906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:33:01.854  1026  1536 D WifiService: New client listening to asynchronous messages
09-01 11:33:01.859  6832  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:33:01.859  6832  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-01 11:33:01.861  6832  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-01 11:33:01.861  6832  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-01 11:33:01.861  6832  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-01 11:33:01.868  6832  6906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:01.868  1026  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:01.869  6832  6906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-01 11:33:01.884  6832  6906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-01 11:33:01.885  6832  6906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:01.885  6832  6906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:01.885  6832  6906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:01.885  6832  6906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:01.885  6832  6906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:01.885  6832  6906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:01.885  6832  6906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:01.885  6832  6906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:33:01.886  6832  6906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-01 11:33:01.886  6832  6906 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:33:01.890  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:01.893  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:01.895  6832  6906 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 11:33:01.932  6832  6832 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-01 11:33:02.332   338   402 E GBMv2   : DFP En is all cleared set to be enabled
,09-01 11:33:02.333   338   402 E GBMv2   : Set value is all cleared set the max
09-01 11:33:02.333   338   402 I GBMv2   : DFP Enabled. Ignore VFP set
09-01 11:33:02.917  6832  6909 W jxcore-log: Initializing JXcore engine
09-01 11:33:02.918  6832  6909 W jxcore-log: JXcore engine is ready
,09-01 11:33:02.977  6909  6909 W Thread-797: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10312]" dev="sockfs" ino=10312 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-01 11:33:02.977  6909  6909 W Thread-797: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-01 11:33:02.977  6909  6909 W Thread-797: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8641]" dev="sockfs" ino=8641 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-01 11:33:02.977  6909  6909 W Thread-797: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-01 11:33:02.977  6909  6909 W Thread-797: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31514]" dev="sockfs" ino=31514 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-01 11:33:03.017  6832  6909 W jxcore-log: Starting JXcore engine
,09-01 11:33:03.173  6832  6909 W jxcore-log: Platform android
09-01 11:33:03.173  6832  6909 W jxcore-log: 
09-01 11:33:03.174  6832  6909 W jxcore-log: Process ARCH arm
09-01 11:33:03.174  6832  6909 W jxcore-log: 
,09-01 11:33:03.560  6832  6909 I jxcore-log: JXcore Cordova bridge is ready!
09-01 11:33:03.560  6832  6909 I jxcore-log: 
09-01 11:33:03.561  6832  6909 W jxcore-log: JXcore engine is started
,09-01 11:33:03.568  6832  6906 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-01 11:33:03.575  6832  6832 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-01 11:33:14.343  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-01 11:33:14.343  6832  6909 I jxcore-log: 
09-01 11:33:14.346  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-01 11:33:14.346  6832  6909 I jxcore-log: 
,09-01 11:33:14.349  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:14.349  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:14.349  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:14.349  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:14.349  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:14.349  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:14.349  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:14.349  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:33:14.351  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:14.353  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-01 11:33:14.353  6832  6909 I jxcore-log: 
09-01 11:33:14.355  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-01 11:33:14.355  6832  6909 I jxcore-log: 
09-01 11:33:14.858  6832  6909 D executeNativeTests: Running unit tests
,09-01 11:33:14.940  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:33:14.940  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc added. We now have 2 listener(s)
09-01 11:33:14.940  1026  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-01 11:33:14.942  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:33:14.942  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:14.942  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:33:14.942  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:14.942  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 added. We now have 2 listener(s)
09-01 11:33:14.942  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:14.942  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:33:14.944  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:14.949  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:14.949  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:14.949  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:14.949  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:14.949  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:14.949  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:14.949  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:14.949  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:33:14.950  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:14.951  6832  6909 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:33:14.952  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:14.953  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:33:14.959  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 11:33:14.963  6832  6909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:33:14.963  6832  6909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:33:14.969  6832  6909 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-01 11:33:14.971  6832  6909 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:33:14.971  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:33:14.971  6832  6909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:33:14.971  6832  6909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:33:14.973  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:14.976  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:14.976  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:14.976  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:14.976  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:14.977  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:14.977  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:33:14.977  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc removed from the list
09-01 11:33:14.977  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:14.977  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 removed from the list
09-01 11:33:14.977  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:14.977  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:14.978  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:14.978  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:14.978  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:14.978  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:14.978  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:14.978  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:14.981  6832  6909 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-01 11:33:14.981  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:14.981  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:14.981  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:14.981  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:14.981  6832  6909 W org.thaliprojec,t.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:14.982  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:14.982  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:14.982  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:14.982  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:14.982  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:14.982  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:14.982  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:14.982  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:14.982  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:33:14.985  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:14.985  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:14.985  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:14.985  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 11:33:14.989  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:33:14.989  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:14.990  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:14.990  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:14.990  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:14.990  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:14.990  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:14.990  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:14.990  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:14.990  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:14.990  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:14.990  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:14.990  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:14.990  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:14.990  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:14.990  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:14.991  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:14.991  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:14.991  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:14.991  6832  6909 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:33:14.993  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:14,.994  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:14.994  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:14.994  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:14.994  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:14.994  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:14.994  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:14.994  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:14.994  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:33:14.997  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:14.997  6832  6909 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:33:14.997  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:33:14.998  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:33:14.998  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:33:14.998  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:14.998  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:33:14.998  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:14.999  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:15.002  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:33:15.002  1026  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:15.005  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:33:15.010  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:33:15.011  6832  6909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-01 11:33:15.012  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:33:15.012  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:15.013  6832  6909 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:33:15.013  6832  6909 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:33:15.015  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.015  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.015  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.016  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.016  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.016  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:15.016  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.016  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.016  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.016  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.016  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.016  6832  6909 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:33:15.017  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:33:15.019  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:15.019  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:15.019  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:15.019  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:15.019  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:15.019  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:15.019  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:15.019  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:33:15.020  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:15.021  6832  6909 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:33:15.021  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:33:15.021  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:33:15.021  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:33:15.021  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:15.021  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:33:15.023  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:15.024  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:15.026  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:33:15.026  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:15.027  6832  6909 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:33:15.027  6832  6909 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:33:15.028  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.028  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.028  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.028  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.028  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.028  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:15.029  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.029  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.029  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryMana,gerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.029  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.029  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.029  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:33:15.029  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.030  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.030  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.031  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.031  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.031  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.031  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.032  6832  6909 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:33:15.033  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:15.035  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:15.035  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:15.035  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:15.035  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:15.035  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:15.035  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:15.035  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:15.035  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:33:15.036  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:15.036  6832  6909 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:33:15.037  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:15.038  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:15.038  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:33:15.038  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:33:15.038  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:33:15.038  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:15.038  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:33:15.041  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:33:15.042  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:33:15.043  6832  6909 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:33:15.043  6832  6909 I io.jxcore.node.ConnectionHelper: start: OK
09-01 11:33:15.043  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.043  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.043  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.044  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.044  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.044  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.044  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.044  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.044  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:15.044  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.044  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.044  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.044  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.044  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.045  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.045  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.045  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.045  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.045  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.045  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.045  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.046  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.046  6832  6909 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-01 11:33:15.046  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.046  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.046  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, s,kipping...
09-01 11:33:15.047  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.047  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.047  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.047  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.047  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.047  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.047  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.047  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.047  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.047  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.047  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.047  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.047  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.048  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.048  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.048  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.048  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list,
09-01 11:33:15.049  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:33:15.049  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.049  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.049  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.049  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.049  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.049  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.049  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.049  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.049  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.049  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:33:15.049  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-01 11:33:15.049  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.049  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.049  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.050  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.050  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.050  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.050  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.050  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:33:15.050  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.051  6832  6909 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-01 11:33:15.051  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.051  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.051  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.051  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.051  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.051  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.051  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
,09-01 11:33:15.051  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.052  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.052  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.052  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.052  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.052  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.052  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.052  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.052  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.053  6832  6909 D BluetoothLeScanner: could not find callback wrapper
,09-01 11:33:15.053  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.053  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.053  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.053  6832  6909 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-01 11:33:15.053  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.053  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.053  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.055  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.055  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.055  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:33:15.055  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.055  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.055  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.055  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.055  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.055  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.055  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.055  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.056  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.056  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,09-01 11:33:15.056  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.056  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.056  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.056  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.057  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 11:33:15.057  6832  6909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:33:15.057  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:33:15.057  6832  6909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:33:15.057  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 11:33:15.057  6832  6909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:33:15.057  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.057  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.057  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.057  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.057  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.057  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.057  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.057  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.057  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.057  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.057  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.057  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.058  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.058  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.058  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.058  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.059  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.059  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.059  6832  6909 I org.thaliproject.p2p.btconne,ctorlib.DiscoveryManager: dispose
09-01 11:33:15.059  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.059  6832  6909 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:33:15.059  6832  6909 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 11:33:15.059  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 11:33:15.061  6832  6909 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:33:15.061  6832  6909 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:33:15.061  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 11:33:15.062  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:33:15.062  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 11:33:15.062  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 11:33:15.062  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:33:15.062  6832  6909 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-01 11:33:15.062  6832  6909 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:33:15.062  6832  6909 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-01 11:33:15.062  6832  6909 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:33:15.062  6832  6909 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:33:15.062  6832  6909 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-01 11:33:15.062  6832  6909 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:33:15.062  6832  6909 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:33:15.062  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-01 11:33:15.064  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-01 11:33:15.065  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-01 11:33:15.065  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-01 11:33:15.065  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-01 11:33:15.065  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-01 11:33:15.066  6832  6909 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-01 11:33:15.066  6832  6909 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:33:15.066  6832  6909 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-01 11:33:15.066  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.066  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.066  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.068  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.068  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.068  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.068  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-01 11:33:15.068  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.068  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.069  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.069  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.069  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.069  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.069  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.069  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.069  6832  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 861)
09-01 11:33:15.075  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.075  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.076  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.076  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.076  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.076  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.076  6832  6909 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-01 11:33:15.076  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.077  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.077  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.077  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.077  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.077  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.077  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.077  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.077  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.077  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.077  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.077  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.077  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.077  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.078  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.078  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.079  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.079  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.079  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.079  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.079  6832  6909 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-01 11:33:15.080  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.080  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.080  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.080  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.080  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.080  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.080  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.080  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.080  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.080  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.080  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.080  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.080  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:1,5.080  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.081  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.081  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.082  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.082  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.082  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.082  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.082  6832  6909 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-01 11:33:15.082  6832  6909 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-01 11:33:15.082  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:33:15.082  6832  6909 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-01 11:33:15.082  6832  6909 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 11:33:15.083  6832  6909 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-01 11:33:15.083  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:33:15.083  6832  6909 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-01 11:33:15.083  6832  6909 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 11:33:15.083  6832  6909 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 11:33:15.083  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:33:15.083  6832  6909 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-01 11:33:15.083  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.083  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.083  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.084  6832  6921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 861
09-01 11:33:15.084  6832  6921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 861)
09-01 11:33:15.084  6832  6921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 861)
09-01 11:33:15.084  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.085  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.085  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.085  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.085  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.085  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.085  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.085  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.085  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.085  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.085  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:33:15.085  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.086  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.086  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.086  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.086  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.086  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.086  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.086  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.086  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.086  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.086  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.086  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.086  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.086  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.086  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.087  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.087  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.087  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.087  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.087  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.087  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.087  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.087  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.087  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.088  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.088  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.088  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.088  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.088  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.088  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.088  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.088  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.088  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.088  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.088  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.089  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.089  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.090  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.090  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.090  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.090  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.092  6832  6909 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-01 11:33:15.096  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:15.096  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-01 11:33:15.097  6832  6909 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-01 11:33:15.097  6832  6909 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-01 11:33:15.097  6832  6832 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-01 11:33:15.097  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-01 11:33:15.097  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:33:15.098  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.098  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-01 11:33:15.098  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-01 11:33:15.098  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-01 11:33:15.098  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.098  6832  6909 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-01 11:33:15.105  6832  6922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-01 11:33:15.106  6832  6922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-01 11:33:15.106  6832  6832 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-01 11:33:15.107  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.107  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.107  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:33:15.107  6832  6909 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:33:15.107  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:33:15.107  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:33:15.108  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:15.108  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:15.108  6832  6909 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:33:15.108  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.108  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.109  6832  6909 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:33:15.109  6832  6832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:33:15.109  6832  6832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:33:15.109  6832  6832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:33:15.110  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.110  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.110  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.110  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.110  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.110  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.110  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.110  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.110  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.110  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.110  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.110  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.110  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.110  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.110  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.111  6832  6832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-01 11:33:15.111  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.111  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.111  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.111  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.112  6832  6909 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-01 11:33:15.112  6832  6909 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:33:15.112  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:33:15.113  6832  6909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:33:15.113  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.113  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.113  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.113  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.113  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.113  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.113  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.113  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.113  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.113  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.113  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.113  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.113  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.113  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.114  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.114  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.114  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.114  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.115  1026  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:15.118  1026  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:15.118  1026  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:15.119  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.119  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.119  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.119  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.119  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.119  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.119  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.119  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.119  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.119  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.120  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.120  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.120  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.120  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.122  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.122  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.122  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.122  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.125  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:15.125  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:15.125  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:15.126  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:15.127  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.127  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.127  6832  6909 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2511cccc not in the list
09-01 11:33:15.127  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.127  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.127  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:15.127  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.127  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.128  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:15.128  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:15.129  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:15.129  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:15.129  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:15.129  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26c28b15 not in the list
09-01 11:33:15.130  6832  6909 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-01 11:33:15.130  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:33:15.130  6832  6909 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-01 11:33:15.130  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:33:15.130  6832  6909 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-01 11:33:15.131  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:33:15.132  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:33:15.132  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-01 11:33:15.132  6832  6909 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-01 11:33:15.132  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 11:33:15.133  6832  6909 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-01 11:33:15.133  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 11:33:15.133  6832  6909 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-01 11:33:15.133  6832  6909 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-01 11:33:15.133  6832  6909 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-01 11:33:15.133  6832  6909 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-01 11:33:15.134  6832  6909 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-01 11:33:15.134  6832  6909 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-01 11:33:15.134  6832  6909 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-01 11:33:15.134  6832  6909 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-01 11:33:15.136  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:33:15.136  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ae3f882 added. We now have 2 listener(s)
09-01 11:33:15.136  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:15.143  6832  6909 D BluetoothAdapter: enable(): BT is already enabled..!
09-01 11:33:15.144  1026  1935 D WifiServiceImplEx: setWifiEnabled: true pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:33:15.145  1026  1935 D WifiService: setWifiEnabled: true pid=6832, uid=10118
09-01 11:33:15.145  1026  1935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:33:15.146  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:15.146  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f549b93 added. We now have 3 listener(s)
09-01 11:33:15.146  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:15.150  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:15.150  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@51f37d0 added. We now have 4 listener(s)
09-01 11:33:15.150  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:15.152  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:15.152  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c2c53c9 added. We now have 5 listener(s)
09-01 11:33:15.152  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:15.154  1026  1041 D WifiServiceImplEx: setWifiEnabled: false pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:33:15.154  1026  1041 D WifiService: setWifiEnabled: false pid=6832, uid=10118
09-01 11:33:15.154  1026  1041 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:33:15.181  6832  6920 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-01 11:33:15.182  6832  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 861)
,09-01 11:33:15.220  1026  1729 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:15.220  1026  1531 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-01 11:33:15.221  1026  1729 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@d960971 mBinding = false
09-01 11:33:15.221  1026  1531 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-01 11:33:15.221  1026  1531 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-01 11:33:15.222  1026  1531 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-01 11:33:15.222  1026  1531 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-01 11:33:15.222  1026  1531 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-01 11:33:15.222  1026  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:33:15.222  1026  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:33:15.223  1026  1026 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:33:15.223  1026  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:33:15.223  1026  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:33:15.223  1026  1026 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:33:15.223  1026  1026 D Ulp_jni : JNI:system_update. Event-4
09-01 11:33:15.229  1026  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:33:15.229  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:33:15.229  1026  1529 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.229  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.229  2707  2707 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-01 11:33:15.231  1026  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:33:15.231  1026  1531 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:33:15.231  1026  1531 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:33:15.232  1026  2857 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.234  1026  1026 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:33:15.234  1026  1026 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:33:15.234  1026  1026 D Ulp_jni : JNI:system_update. Event-4
09-01 11:33:15.235  1026  1088 D BluetoothManagerService: Message: 2
09-01 11:33:15.237  1026  1088 D BluetoothManagerService: Sending off request.
09-01 11:33:15.237  3830  3852 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-01 11:33:15.238  3830  3927 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-01 11:33:15.238  3830  3927 D BluetoothAdapterProperties: Setting state to 13
09-01 11:33:15.238  3830  3927 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 11:33:15.239  3830  3927 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 11:33:15.240  3830  3927 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-01 11:33:15.240  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:15.242   317   883 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:33:15.243  1026  1088 D BluetoothManagerService: Message: 60
09-01 11:33:15.243  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-01 11:33:15.243  1026  1088 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-01 11:33:15.256  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:15.256  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:15.256  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:15.256  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:15.256  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:15.256  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:33:15.256  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:15.256  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:15.256  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:33:15.266  3830  3931 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:33:15.266  3830  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-01 11:33:15.267  3830  3927 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-01 11:33:15.269  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:15.269  3830  4222 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:33:15.269  3830  4223 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:33:15.272  3830  4235 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:33:15.281  3830  4177 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-01 11:33:15.281  3830  4177 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:33:15.281  3830  4177 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-01 11:33:15.281  3830  4177 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-01 11:33:15.281  3830  4177 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-01 11:33:15.281  3830  4177 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-01 11:33:15.281  3830  4177 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-01 11:33:15.281  3830  4177 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-01 11:33:15.282  3830  4182 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-01 11:33:15.285  3830  3830 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:15.285  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-01 11:33:15.285  3830  4021 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-01 11:33:15.285  3830  3830 D BluetoothMapService: STATE_TURNING_OFF
09-01 11:33:15.286  3830  3830 V BtOppService: Receiver DISABLED_ACTION 
09-01 11:33:15.286  3830  3830 V BluetoothMapService: Handler(): got msg=4
09-01 11:33:15.286  3830  3830 D BluetoothMapService: MAP Service closeService in
09-01 11:33:15.286  3830  3830 D BluetoothMapMasInstance: MAP Service shutdown
09-01 11:33:15.286  3830  3830 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:33:15.286  3830  3830 V BluetoothMapService: MAP Service closeService out
09-01 11:33:15.286  3830  3830 I BtOppRfcommListener: stopping Accept Thread
09-01 11:33:15.286  3830  3830 V BtOppRfcommListener: close mBtServerSocket
09-01 11:33:15.287  3830  3830 V BtOppRfcommListener: waiting for thread to terminate
09-01 11:33:15.287  3830  4222 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 11:33:15.288  1026  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 11:33:15.289  1026  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-01 11:33:15.295  3830  3830 V BtOppRfcommListener: done waiting for thread to terminate
09-01 11:33:15.296  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:33:15.296  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:33:15.296  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:33:15.296  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:33:15.297  3830  4021 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:33:15.297  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:33:15.297  3830  4021 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:33:15.297  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:33:15.297  3830  4021 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:33:15.297  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-01 11:33:15.297  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-01 11:33:15.297  3830  4021 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:33:15.305  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:33:15.319  1026  1729 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,09-01 11:33:15.319  1026  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.319  1026  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.319  1026  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-01 11:33:15.319  1026  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.319  1026  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-01 11:33:15.321  1026  1084 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6933 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-01 11:33:15.323  3830  3830 V BtOppService: onDestroy
09-01 11:33:15.324  1026  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:15.325  1026  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:15.325  1026  1529 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.325  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.325  1026  1529 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@31659bcb
09-01 11:33:15.326  1026  1529 D LGWifiP2pService: P2pDisablingState
09-01 11:33:15.326  1026  1529 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.326  1026  1529 D LGWifiP2pService: p2p socket connection lost
09-01 11:33:15.326  1026  1529 D LGWifiP2pService: P2pDisabledState
09-01 11:33:15.326  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:15.326  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:15.326  6832  6909 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:33:15.329  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:15.329  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:15.329  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:15.329  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:15.329  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:15.329  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:33:15.329  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:15.329  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:15.329  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:33:15.329  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:15.,330  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:15.331  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:15.331  1026  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:15.332  1026  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:15.333  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:15.333  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:15.333  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:15.333  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:15.333  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:15.333  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:33:15.333  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:15.333  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:15.333  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:33:15.333  1026  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:15.335  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:15.335  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:33:15.337  1026  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:15.337  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:15.339  1026  1026 D WifiHS20: hidePasspointNotification off =false
09-01 11:33:15.340  1026  1531 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 11:33:15.341  1026  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:15.342  1026  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:15.343  1936  1936 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-01 11:33:15.345  1026  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:15.346  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:15.347  1026  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-01 11:33:15.347  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:33:15.347  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:33:15.347  2707  2707 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:33:15.348  1026  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:33:15.348  1026  1531 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:33:15.349  1026  1531 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:33:15.349   317   883 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:33:15.350   317  6947 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-01 11:33:15.350  1026  1537 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-01 11:33:15.350  1026  1537 D DSQN    : disableDataServiceNotify
09-01 11:33:15.350  1026  1537 D DSQN    : stop dsqn bin
09-01 11:33:15.350  1026  1086 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-01 11:33:15.351  1026  1529 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.351  1026  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-01 11:33:15.352  1026  1529 D LGWifiP2pService: DefaultState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.352  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:15.352  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:15.352  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:33:15.355  1026  1026 D WifiHS20: hidePasspointNotification off =false
09-01 11:33:15.357  1026  1537 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-01 11:33:15.357  1026  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:15.357  1026  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:33:15.357  1026  1537 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:33:15.357  1026  1537 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-01 11:33:15.358  1026  1537 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-01 11:33:15.358  1026  1537 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-01 11:33:15.358  1026  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:33:15.359  1595  1824 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-01 11:33:15.360  1026  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.360  1026  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.360  1026  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-01 11:33:15.364  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:15.364  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:15.364  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:33:15.365  1026  1026 D WifiScanningService: SCAN_AVAILABLE : 1
09-01 11:33:15.365  1026  1549 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.365  1026  1026 D RttService: SCAN_AVAILABLE : 1
09-01 11:33:15.366  1026  1550 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:15.368  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-01 11:33:15.368  1936  1936 D WfdsService: WifiP2pState is changed : false
09-01 11:33:15.368  1936  2300 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-01 11:33:15.369  1936  2300 D WfdsService: Set the WFDS Monitor: false
09-01 11:33:15.369  1936  2300 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:33:15.370  1936  2737 D CtrlSupplicant: Received on exit socket, terminate
09-01 11:33:15.370  1936  2300 D WfdsService: STATE : WfdsDisabledState - enter
09-01 11:33:15.370  1936  2737 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-01 11:33:15.370  1936  2737 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-01 11:33:15.370  1936  2737 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-01 11:33:15.370  1936  2300 W WfdsService: DefaultState - msg [9445378] is not handled
09-01 11:33:15.370  1936  2301 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-01 11:33:15.391  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:15.391  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:15.392  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:15.394  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:15.394  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-01 11:33:15.395  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:15.418  1026  1084 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6959 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-01 11:33:15.419  1026  1531 D WifiNative-p2p0: doBoolean: TERMINATE
09-01 11:33:15.419  1026  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:15.419  1026  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:33:15.419  1026  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:15.419  1026  1531 D WifiNative-p2p0: TERMINATE: returned true
09-01 11:33:15.419  1026  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:33:15.419  1026  1531 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:33:15.419  1026  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:33:15.419  1026  1537 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:15.419  1026  1537 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:15.420  1026  1537 D NetworkManagementService: Removing idletimer
09-01 11:33:15.420  1026  1531 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:15.420  1026  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:33:15.420  1026  1537 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:15.420  1026  1026 D WifiHS20: hidePasspointNotification off =false
09-01 11:33:15.421  1848  1848 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:15.421  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:15.421  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:15.421  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:33:15.422  1026  1026 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-01 11:33:15.422  1026  1528 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-01 11:33:15.422  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:33:15.423  1026  1528 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-01 11:33:15.423  1026  1537 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-01 11:33:15.425  1026  1026 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-01 11:33:15.426  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-01 11:33:15.428  1026  1026 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:33:15.429  1026  1026 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:33:15.429  1026  1026 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:33:15.429  1026  1026 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-01 11:33:15.429  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 11:33:15.429  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:15.429  1026  1026 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:33:15.429  1026  1026 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:33:15.429  1026  1026 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-01 11:33:15.430  1026  1026 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:33:15.430  1026  1026 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-01 11:33:15.430  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:33:15.430  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:15.430  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:15.430  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:15.430  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:33:15.430  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:33:15.430  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:15.430  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:15.430  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:33:15.430  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:15.430  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:15.430  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:15.431  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:15.431  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:15.431  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:15.431  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:15.431  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:33:15.431  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:33:15.431  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:15.431  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:15.431  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:33:15.432  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:15.432  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:15.441  1026  2857 D DhcpStateMachine: StoppedState
09-01 11:33:15.441  1026  2857 D DhcpStateMachine: StoppedState{ when=-93ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:33:15.445  1026  1531 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-01 11:33:15.446  1026  1531 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-01 11:33:15.470  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:33:15.471  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:15.472  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:15.474  1026  1041 I art     : Explicit concurrent mark sweep GC freed 48369(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.502ms total 217.398ms
09-01 11:33:15.487  3830  3830 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-01 11:33:15.497  6933  6933 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:33:15.497  6933  6933 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-01 11:33:15.497  6933  6933 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-01 11:33:15.497  6933  6933 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-01 11:33:15.498  6933  6933 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-01 11:33:15.499  6933  6933 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-01 11:33:15.502  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:33:15.503  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:15.503  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:15.504  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:15.536  2707  2707 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-01 11:33:15.536  2707  2707 I wpa_supplicant: monitor socket send errors count : 1
09-01 11:33:15.536  2707  2707 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1936-2\x00 that cannot receive messages
,09-01 11:33:15.536  1026  2722 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-01 11:33:15.536  1026  2722 D WifiMonitor: Dropping event because (p2p0) is stopped
09-01 11:33:15.559  6959  6959 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-01 11:33:15.559  6959  6959 W LG Account v2.2: No ProfileInfo entries
09-01 11:33:15.559  6959  6959 I LG Account v2.2: isEnabled: false
09-01 11:33:15.559  6959  6959 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-01 11:33:15.559  6959  6959 I Feature : [Lifetracker]Country: EU
09-01 11:33:15.559  6959  6959 I Feature : [Lifetracker]Operator: OPEN
09-01 11:33:15.559  6959  6959 I Feature : [Lifetracker]Ranking support: false
09-01 11:33:15.559  6959  6959 I Feature : [Lifetracker]Comfort support: false
09-01 11:33:15.559  6959  6959 I Feature : [Lifetracker]Accessory: true
09-01 11:33:15.559  6959  6959 I Feature : [Lifetracker]Health device: true
09-01 11:33:15.559  6959  6959 I Feature : [Lifetracker]Extra Pedometer: false
09-01 11:33:15.559  6959  6959 I Feature : [Lifetracker]Blood glucose device: false
09-01 11:33:15.559  6959  6959 I Feature : [Lifetracker]Device Number: 3
,09-01 11:33:15.566  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:15.585  2707  2707 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-01 11:33:15.587  2707  2707 W wpa_supplicant: USIM:  scard_deinit function
09-01 11:33:15.587  1026  1088 D Tethering: InitialState.processMessage what=4
09-01 11:33:15.590  1026  2722 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-01 11:33:15.590  1026  2722 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:33:15.590  1026  2722 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:33:15.591  1026  2722 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-01 11:33:15.591  1026  2722 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:33:15.591  1026  2722 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:33:15.592  1026  1531 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=203125
09-01 11:33:15.593  1026  1531 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=203126
09-01 11:33:15.594  6933  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-01 11:33:15.594  1026  1531 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=203127  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:33:15.595  1026  1531 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=203128  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:33:15.609  6832  6832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 11:33:15.628  1026  1767 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6981 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-01 11:33:15.629  1026  1767 I ActivityManager: Killing 6392:com.lge.email/u0a23 (adj 15): empty #17
09-01 11:33:15.738  2707  2707 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-01 11:33:15.740  1026  2722 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-01 11:33:15.740  1026  2722 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-01 11:33:15.740  1026  2722 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-01 11:33:15.743  1026  1531 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-01 11:33:15.753  1026  1088 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 11:33:15.767  1026  1088 D BluetoothManagerService: Message: 20
09-01 11:33:15.767  1026  1088 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7103530:true
09-01 11:33:15.776  3830  3830 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:33:15.776  3830  3830 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:15.776  3830  3830 V BluetoothPbapReceiver: ***********state = 13
,09-01 11:33:15.776  1026  1041 W libprocessgroup: failed to open /acct/uid_10023/pid_6392/cgroup.procs: No such file or directory
09-01 11:33:15.779  3830  3830 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-01 11:33:15.783  3830  3830 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:15.784  3830  3830 V BluetoothPbapService: state: 13
09-01 11:33:15.784  3830  3830 V BluetoothPbapService: Pbap Service closeService in
09-01 11:33:15.785  3830  3830 V BluetoothPbapService: successfully stopped pbap service
,09-01 11:33:15.785  3830  3830 V BluetoothPbapService: Pbap Service closeService out
09-01 11:33:15.785  3830  3830 V BluetoothPbapService: Pbap Service onDestroy
09-01 11:33:15.785  3830  3830 V BluetoothPbapService: Pbap Service closeService in
09-01 11:33:15.785  3830  3830 V BluetoothPbapService: Pbap Service closeService out
,09-01 11:33:15.786  3830  3830 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-01 11:33:15.788  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:33:15.789  1026  1088 D BluetoothManagerService: Message: 30
,09-01 11:33:15.801  1026  1088 D BluetoothManagerService: Message: 30
09-01 11:33:15.803  6933  6933 D LocalBluetoothProfileManager: Adding local MAP profile
,09-01 11:33:15.805  6933  6933 D BluetoothMap: Create BluetoothMap proxy object
09-01 11:33:15.806  1026  1088 D BluetoothManagerService: Message: 30
09-01 11:33:15.810  1026  1088 D BluetoothManagerService: Message: 30
09-01 11:33:15.813  6933  6933 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-01 11:33:15.814  6933  6933 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-01 11:33:15.834  6933  6933 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-01 11:33:15.840  6933  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-01 11:33:15.851  6981  6981 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-01 11:33:15.852  6933  6933 D DockEventReceiver: finishStartingService: stopping service
09-01 11:33:15.852  1026  1531 D WifiOffDelayIfNotUsed: stopMonitoring
09-01 11:33:15.852  1026  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:33:15.852  1026  1531 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:33:15.852  1026  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:33:15.856  1936  1936 D WfdsService: Supplicant Connection state is changed : false
09-01 11:33:15.856  1936  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-01 11:33:15.856  1936  2300 D WfdsService: Set the WFDS Monitor: false
09-01 11:33:15.856  1936  2300 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:33:15.858  2503  2503 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:15.858  1026  1026 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-01 11:33:15.859  1026  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-01 11:33:15.859  1026  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-01 11:33:15.859  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:15.860  6737  6737 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:15.860  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-01 11:33:15.866  6981  6981 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:33:15.867  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:33:15.869  6933  6933 D BluetoothInputDevice: Proxy object connected
09-01 11:33:15.870  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:15.871  6933  6933 D HidProfile: Bluetooth service connected
09-01 11:33:15.871  1026  1776 I ActivityManager: Killing 6485:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-01 11:33:15.873  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:15.873  6933  6933 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:33:15.874  6933  6933 D PanProfile: Bluetooth service connected
09-01 11:33:15.875  6933  6933 D BluetoothMap: Proxy object connected
09-01 11:33:15.877  6933  6933 D MapProfile: Bluetooth service connected
09-01 11:33:15.877  6933  6933 D BluetoothMap: getConnectedDevices()
09-01 11:33:15.879  6933  6933 D BluetoothMap: Bluetooth is Not enabled
09-01 11:33:15.880  6933  6933 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-01 11:33:15.908  1026  2025 W libprocessgroup: failed to open /acct/uid_10061/pid_6485/cgroup.procs: No such file or directory
,09-01 11:33:15.926  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:33:15.966  6933  6933 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:33:15.966  6933  6933 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:33:15.980  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:15.981  6933  6933 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-01 11:33:15.989  6933  6933 D BluetoothPermissionRequest: onReceive
09-01 11:33:15.995  6933  6933 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-01 11:33:16.009  6933  6933 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-01 11:33:16.009  1026  2036 I ActivityManager: Killing 6567:com.lge.eula/1000 (adj 15): empty #17
09-01 11:33:16.056  1026  1531 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:16.057  1026  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-01 11:33:16.068  3830  3830 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-01 11:33:16.069  3830  3830 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-01 11:33:16.069  1026  1568 W libprocessgroup: failed to open /acct/uid_1000/pid_6567/cgroup.procs: No such file or directory
09-01 11:33:16.070  3830  3830 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-01 11:33:16.087  3830  3830 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:16.088  3830  3830 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-01 11:33:16.089  3830  3830 V BluetoothFtpService: Ftp Service onStartCommand
09-01 11:33:16.090  3830  3830 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:33:16.090  3830  3830 V BluetoothFtpService: Ftp Service closeService
09-01 11:33:16.090  3830  3830 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-01 11:33:16.099  3830  3830 V BluetoothFtpService: successfully stopped ftp service
09-01 11:33:16.100  3830  3830 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:33:16.100  3830  3830 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:33:16.100  3830  3830 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:33:16.100  3830  3830 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:16.100  3830  3830 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-01 11:33:16.100  3830  3830 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-01 11:33:16.179  1026  1953 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7012 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-01 11:33:16.184  3830  3830 V BluetoothFtpService: Ftp Service onDestroy
09-01 11:33:16.184  3830  3830 V BluetoothFtpService: Ftp Service closeService
09-01 11:33:16.247  1026  1568 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7029 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-01 11:33:16.254  3830  3830 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:16.254  3830  3830 V BluetoothSapService: state: 13
09-01 11:33:16.254  3830  3830 V BluetoothSapService: Stopping SAP server process
09-01 11:33:16.255  3830  3830 V BluetoothSapService: Sap Service closeSapService in
09-01 11:33:16.255  3830  3830 V BluetoothSapService: Close listen Socket : 
09-01 11:33:16.256  3830  3830 V BluetoothSapService: Close rfcomm Socket : 
09-01 11:33:16.256  3830  3830 V BluetoothSapService: Close sapd  Socket : 
09-01 11:33:16.257  3830  3830 V BluetoothSapService: Sap Service closeSapService out
09-01 11:33:16.257  3830  3830 V BluetoothSapService: Sap Service onDestroy
09-01 11:33:16.257  3830  3830 V BluetoothSapService: Sap Service closeSapService in
09-01 11:33:16.257  3830  3830 V BluetoothSapService: Close listen Socket : 
09-01 11:33:16.257  3830  3830 V BluetoothSapService: Close rfcomm Socket : 
09-01 11:33:16.257  3830  3830 V BluetoothSapService: Close sapd  Socket : 
09-01 11:33:16.258  3830  3830 V BluetoothSapService: Sap Service closeSapService out
,09-01 11:33:16.293  7012  7012 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-01 11:33:16.298  3830  3931 D bt_hci_bdroid: cleanup
09-01 11:33:16.298  3830  4023 I bt_lpm  : LPM is already off!!!
09-01 11:33:16.299  3830  4164 I bt_userial_mct: exiting userial_read_thread
09-01 11:33:16.299  3830  4021 W bt-btif : ag scb idx 1 not allocated
09-01 11:33:16.299  3830  4164 D bt_userial_mct: Leaving userial_evt_read_thread()
09-01 11:33:16.299  3830  4021 E bt-btif : BTA AG is already disabled, ignoring ...
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:33:16.299  7029  7029 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:33:16.299  3830  4021 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:33:16.299  3830  4021 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:33:16.299  3830  3931 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-01 11:33:16.299  3830  4023 I bt_vendor: hw_epilog_process
09-01 11:33:16.300  3830  3931 D bt_hci_bdroid: cleanup Finalizing cleanup
09-01 11:33:16.300  3830  3931 D bt_userial_mct: userial_close
09-01 11:33:16.300  3830  3931 E bt_userial_mct: pthread_join() FAILED result:3
09-01 11:33:16.300  3830  3931 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-01 11:33:16.314  1026  1917 I ActivityManager: Killing 5130:com.lge.bnr/1000 (adj 15): empty #17
,09-01 11:33:16.349  1026  1766 W libprocessgroup: failed to open /acct/uid_1000/pid_5130/cgroup.procs: No such file or directory
,09-01 11:33:16.352  7012  7012 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-01 11:33:16.365  3830  3931 D bt_hci_bdroid: set_power 0
09-01 11:33:16.365  3830  3931 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-01 11:33:16.365  3830  3931 I bt_vendor: bluetooth satus is on
09-01 11:33:16.366  3830  3931 I bt_vendor: bt-vendor : resetting BT status
09-01 11:33:16.366  3830  3931 I bt_vendor: Starting hciattach daemon
09-01 11:33:16.366  3830  3931 I bt_vendor: try to set false
,09-01 11:33:16.367  3830  3931 I bt_vendor: Starting hciattach daemon
09-01 11:33:16.367  3830  3931 I bt_vendor: try to set false
,09-01 11:33:16.368  3830  3931 I bt_vendor: cleanup
09-01 11:33:16.370  3830  4021 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-01 11:33:16.371  3830  3931 I GKI_LINUX: GKI_exit_task 0 done
09-01 11:33:16.371  3830  3931 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-01 11:33:16.373  3830  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-01 11:33:16.381  3830  3830 D HeadsetService: Received stop request...Stopping profile...
,09-01 11:33:16.385  3830  3830 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:33:16.386  3830  3830 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:33:16.386  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@386bde7a
09-01 11:33:16.386  3830  3959 D HeadsetStateMachine: Exit Disconnected: -1
09-01 11:33:16.387  1026  1026 D BluetoothHeadset: Proxy object disconnected
09-01 11:33:16.387  1026  1026 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-01 11:33:16.389  1848  1848 D BluetoothHeadset: Proxy object disconnected
09-01 11:33:16.389  1848  1848 D BluetoothHeadset: Proxy object disconnected
09-01 11:33:16.389  3830  3830 D A2dpService: Received stop request...Stopping profile...
09-01 11:33:16.389  1848  1848 D BluetoothHeadset: Proxy object disconnected
09-01 11:33:16.390  3830  4006 D A2dpStateMachine: Exit Disconnected: -1
09-01 11:33:16.391  3830  3830 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-01 11:33:16.395  3830  3927 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-01 11:33:16.399  3830  3830 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-01 11:33:16.400  3830  3830 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:33:16.400  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@386bde7a
09-01 11:33:16.400  1026  1026 D BluetoothA2dp: Proxy object disconnected
09-01 11:33:16.400  1026  1026 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-01 11:33:16.402  3830  3830 D HidService: Received stop request...Stopping profile...
09-01 11:33:16.402  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@386bde7a
09-01 11:33:16.404  6933  6933 D BluetoothInputDevice: Proxy object disconnected
09-01 11:33:16.404  6933  6933 D HidProfile: Bluetooth service disconnected
09-01 11:33:16.404  3830  3830 D HealthService: Received stop request...Stopping profile...
09-01 11:33:16.405  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@386bde7a
09-01 11:33:16.407  3830  3830 D PanService: Received stop request...Stopping profile...
09-01 11:33:16.407  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@386bde7a
,09-01 11:33:16.408  3830  3830 D HeadsetStateMachine: Unbinding service...
09-01 11:33:16.410  3830  3830 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:33:16.410  3830  3830 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:33:16.410  3830  3830 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:33:16.410  3830  3830 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:33:16.410  3830  3830 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 11:33:16.410  3830  3830 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:33:16.410  3830  3830 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:33:16.410  3830  3830 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:33:16.411  3830  3830 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 11:33:16.411  3830  3830 D BtGatt.GattService: stop()
09-01 11:33:16.412  3830  3830 D BtGatt.AdvertiseManager: advertise clients cleared
09-01 11:33:16.412  6933  6933 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 11:33:16.413  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@386bde7a
09-01 11:33:16.413  6933  6933 D PanProfile: Bluetooth service disconnected
09-01 11:33:16.414  3830  3830 D BluetoothMapService: Received stop request...Stopping profile...
09-01 11:33:16.414  3830  3830 D BluetoothMapService: stop()
09-01 11:33:16.415  3830  3830 D BluetoothMapEmailAppObserver: deinitObservers()
09-01 11:33:16.415  3830  3830 D BluetoothMapEmailAppObserver: removeReceiver()
09-01 11:33:16.416  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@386bde7a
09-01 11:33:16.417  7012  7012 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-01 11:33:16.417  3830  3830 I BluetoothA2dpServiceJni: cleanupNative
09-01 11:33:16.417  3830  4007 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-01 11:33:16.417  7012  7012 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-01 11:33:16.418  7012  7012 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-01 11:33:16.418  3830  3830 I GKI_LINUX: GKI_exit_task 2 done
09-01 11:33:16.418  3830  3830 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-01 11:33:16.418  7012  7012 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-01 11:33:16.418  3830  3830 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 11:33:16.418  3830  3830 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:33:16.418  7012  7012 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-01 11:33:16.419  3830  3830 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 11:33:16.418  6933  6933 D BluetoothMap: Proxy object disconnected
09-01 11:33:16.419  6933  6933 D MapProfile: Bluetooth service disconnected
09-01 11:33:16.419  3830  3830 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:33:16.419  3830  3830 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:33:16.419  3830  3830 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-01 11:33:16.419  3830  3830 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 11:33:16.420  7012  7012 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-01 11:33:16.420  3830  3830 V BluetoothMapService: Handler(): got msg=4
09-01 11:33:16.420  3830  3830 D BluetoothMapService: MAP Service closeService in
09-01 11:33:16.420  3830  3830 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
,09-01 11:33:16.420  3830  3830 V BluetoothMapService: MAP Service closeService out
09-01 11:33:16.421  3830  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-01 11:33:16.421  3830  3927 D BluetoothAdapterProperties: Setting state to 10
09-01 11:33:16.421  3830  3927 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-01 11:33:16.422  3830  3830 D BluetoothMapService: cleanup()
09-01 11:33:16.422  3830  3830 D BluetoothMapService: MAP Service closeService in
09-01 11:33:16.422  3830  3830 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:33:16.422  3830  3830 V BluetoothMapService: MAP Service closeService out
,09-01 11:33:16.423  1026  1088 D BluetoothManagerService: Message: 60
09-01 11:33:16.423  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-01 11:33:16.423  1026  1088 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-01 11:33:16.423  1026  1088 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 11:33:16.424  3830  3927 I BluetoothAdapterState: Entering OffState
09-01 11:33:16.425  6933  6957 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:33:16.426  6933  6958 D BluetoothPan: onBluetoothStateChange on: false
09-01 11:33:16.426  1026  1088 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:33:16.427  1848  2430 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:33:16.428  1848  2711 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:33:16.428  7012  7012 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-01 11:33:16.429  6933  6957 D BluetoothMap: onBluetoothStateChange: up=false
09-01 11:33:16.429  1848  1863 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:33:16.430  6933  6958 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 11:33:16.432  1026  1088 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-01 11:33:16.433  1026  1088 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-01 11:33:16.435  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:33:16.435  1026  1088 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
,09-01 11:33:16.435  1026  1088 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-01 11:33:16.436  1026  1088 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@d960971 mBinding = false
09-01 11:33:16.437  1026  1088 D BluetoothManagerService: Sending unbind request.
09-01 11:33:16.438  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:16.439  1026  1088 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-01 11:33:16.443  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:33:16.445  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:16.446  1936  2121 D LGBluetoothAPIService: Message: 2
09-01 11:33:16.446  1936  2121 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@41d27bb mBinding = false
09-01 11:33:16.446  1936  2121 D LGBluetoothAPIService: Sending unbind request.
09-01 11:33:16.447  6933  6933 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-01 11:33:16.448  6933  6933 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-01 11:33:16.448  6933  6933 D LGBluetoothEventManager: [BTUI] clear device connection state
09-01 11:33:16.448  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:16.449  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:16.450  3830  3931 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-01 11:33:16.452  3830  3830 I GKI_LINUX: GKI_exit_task 1 done
09-01 11:33:16.452  3830  3830 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-01 11:33:16.453  3830  3830 I BluetoothServiceJni: cleanupNative: return from cleanup
09-01 11:33:16.453  3830  3830 I art     : --- WEIRD: removing null entry 246
09-01 11:33:16.453  3830  3830 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-01 11:33:16.453  3830  3830 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-01 11:33:16.454  6933  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-01 11:33:16.454  3830  3830 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-01 11:33:16.457  3830  3830 I art     : System.exit called, status: 0
09-01 11:33:16.457  3830  3830 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-01 11:33:16.458  1595  1595 D BluetoothAdapter: 946697181: getState() :  mService = null. Returning STATE_OFF
09-01 11:33:16.458  1595  1595 D BluetoothAdapter: 946697181: getState() :  mService = null. Returning STATE_OFF
09-01 11:33:16.468  6933  6933 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:33:16.479  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:33:16.482  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:16.482  7012  7012 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-01 11:33:16.484  6981  6981 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:33:16.484  6981  6981 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:33:16.484  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:33:16.487   321  1376 V AudioFlinger: 3830 died, releasing its sessions
,09-01 11:33:16.487   321  1376 V AudioFlinger:  pid 1848 @ 0
09-01 11:33:16.487   321  1376 V AudioFlinger:  pid 3450 @ 1
09-01 11:33:16.487   321  1376 V AudioFlinger:  pid 3450 @ 2
09-01 11:33:16.487  6933  6933 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-01 11:33:16.488  7012  7012 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-01 11:33:16.489  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:33:16.498  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:16.525  1026  2025 I ActivityManager: Process com.android.bluetooth (pid 3830) has died
09-01 11:33:16.525  1026  2025 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-01 11:33:16.532  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:33:16.538  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-01 11:33:16.539  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:16.543  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:33:16.547  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:16.555  6981  6981 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:33:16.555  6981  6981 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:33:16.555  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:33:16.558  6933  6933 D BluetoothPermissionRequest: onReceive
09-01 11:33:16.565  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:33:16.571  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:16.573  6933  6933 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-01 11:33:16.573  6933  6933 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-01 11:33:16.574  6933  6933 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:33:16.632  1026  1041 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7058 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-01 11:33:16.643  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:16.644  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:16.646  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:33:16.703  1026  1916 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7075 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-01 11:33:16.726  7058  7058 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-01 11:33:16.727  7058  7058 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-01 11:33:16.727  7058  7058 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-01 11:33:16.728  7058  7058 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-01 11:33:16.747  7058  7058 D BluetoothAdapterApp: Loading JNI Library
,09-01 11:33:16.783  7058  7058 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@26f8e3b3 Instance Count = 1
,09-01 11:33:16.789  7058  7058 D BluetoothAdapterApp: onCreate
,09-01 11:33:16.805  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:33:16.811  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:33:16.812  7058  7058 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-01 11:33:16.812  7058  7058 D ProfileConfigQcom: Adding HeadsetService
09-01 11:33:16.812  7058  7058 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-01 11:33:16.813  7058  7058 D ProfileConfigQcom: Adding A2dpService
09-01 11:33:16.813  7058  7058 D ProfileConfigQcom: [BTUI] HidService is supported
09-01 11:33:16.813  7058  7058 D ProfileConfigQcom: Adding HidService
09-01 11:33:16.813  7058  7058 D ProfileConfigQcom: [BTUI] HealthService is supported
,09-01 11:33:16.813  7058  7058 D ProfileConfigQcom: Adding HealthService
09-01 11:33:16.814  7058  7058 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-01 11:33:16.815  7058  7058 D ProfileConfigQcom: [BTUI] PanService is supported
09-01 11:33:16.815  7058  7058 D ProfileConfigQcom: Adding PanService
09-01 11:33:16.815  7058  7058 D ProfileConfigQcom: [BTUI] GattService is supported
09-01 11:33:16.816  7058  7058 D ProfileConfigQcom: Adding GattService
,09-01 11:33:16.816  7058  7058 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-01 11:33:16.816  7058  7058 D ProfileConfigQcom: Adding BluetoothMapService
09-01 11:33:16.816  7058  7058 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-01 11:33:16.818  7058  7058 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-01 11:33:16.818  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:16.827  6933  6933 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-01 11:33:16.829  7058  7058 V LGMDMManagerInternal: Create singleton instance
09-01 11:33:16.832  7075  7095 W FormManager: Network not available. Please check & try again.
,09-01 11:33:16.842  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:33:16.842  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:33:16.842  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:33:16.842  6933  6933 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:33:16.843  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:33:16.855  6933  6933 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:33:16.856  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-01 11:33:16.857  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,09-01 11:33:16.857  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:33:16.857  6933  6933 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:33:16.857  6933  6933 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-01 11:33:16.860  7075  7096 V FormManager: Network unavailable.
09-01 11:33:16.860  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:33:16.860  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:33:16.862  7075  7096 V FormManager: Network unavailable.
09-01 11:33:16.862  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:33:16.865  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:33:16.872  6981  6981 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-01 11:33:16.872  6981  6981 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:33:16.872  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:33:16.875  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:33:16.877  4323  7099 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-01 11:33:16.878  4323  7100 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:33:16.880  4323  7100 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:33:16.883  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:16.895  7075  7101 W FormManager: Network not available. Please check & try again.
,09-01 11:33:16.898  7012  7012 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-01 11:33:16.899  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-01 11:33:16.899  7012  7012 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-01 11:33:16.901  7075  7102 V FormManager: Network unavailable.
09-01 11:33:16.903  7075  7102 V FormManager: Network unavailable.
09-01 11:33:16.908  1026  1042 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
,09-01 11:33:16.922   321  2144 V AudioFlinger: 2127 died, releasing its sessions
09-01 11:33:16.922   321  2144 V AudioFlinger:  pid 1848 @ 0
,09-01 11:33:16.923   321  2144 V AudioFlinger:  pid 3450 @ 1
09-01 11:33:16.923   321  2144 V AudioFlinger:  pid 3450 @ 2
,09-01 11:33:16.938  7012  7012 D LgDataFeature: LgDataFeature() Constructor: none
,09-01 11:33:16.938  7012  7012 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:33:16.945  7012  7012 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-01 11:33:16.946  7012  7012 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-01 11:33:16.946  7012  7012 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-01 11:33:16.946  7012  7012 V SoundPool: doLoad: loading sample sampleID=1
09-01 11:33:16.947  7012  7105 V SoundPool: Start decode
09-01 11:33:16.947  7012  7105 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-01 11:33:16.948   321  1375 V MediaPlayerService: decode(23, 10857164, 17813)
09-01 11:33:16.948   321  1375 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-01 11:33:16.948  7012  7012 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-01 11:33:16.948   321  1375 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-01 11:33:16.948   321  1375 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-01 11:33:16.949   321  1375 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-01 11:33:16.949   321  1375 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-01 11:33:16.949   321  1375 V MediaPlayerService: player type = 3
09-01 11:33:16.949   321  1375 V AwesomePlayer: AwesomePlayer create()
,09-01 11:33:16.950   321  1375 V AwesomePlayer: reset_l() 
09-01 11:33:16.950   321  1375 V AwesomePlayer: cancelPlayerEvents
09-01 11:33:16.950   321  1375 V AwesomePlayer: setAudioSink() 
09-01 11:33:16.950   321  1375 V AwesomePlayer: reset_l() 
09-01 11:33:16.950   321  1375 V AudioCache: notify(0xb1003300, 8, 0, 0)
09-01 11:33:16.950   321  1375 V AudioCache: ignored
09-01 11:33:16.950   321  1375 V AwesomePlayer: cancelPlayerEvents
09-01 11:33:16.951   321  1375 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-01 11:33:16.951   321  1375 V AwesomePlayer: setDataSource_l dataSource
09-01 11:33:16.951   321  1375 V LGParserOSAL: SniffLGParser start
09-01 11:33:16.951   321  1375 V LGParserOSAL: MainType:5, SubType=0
09-01 11:33:16.951   321  1375 V LGParserOSAL: #### check Mime : application/ogg
09-01 11:33:16.951   321  1375 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-01 11:33:16.951   321  1375 E MediaExtractor: Use LGExtractor :application/ogg 
09-01 11:33:16.967  1026  1917 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
09-01 11:33:16.968  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:33:16.977  7012  7012 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-01 11:33:16.978  6601  6601 D UEI.SmartControl: QS Service created
09-01 11:33:16.979  7012  7012 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-01 11:33:16.980  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-01 11:33:16.983  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:33:16.984  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:33:16.984  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:33:16.988  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:16.988  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-01 11:33:16.994  7012  7012 V LGMDMManager: Create singleton instance
,09-01 11:33:16.999  7029  7029 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-01 11:33:17.004  6601  6601 I UEI.SmartControl: Service initServices...
09-01 11:33:17.005  6601  6601 D UEI.SmartControl: QS start get config
,09-01 11:33:17.035   321  1375 V LGParserOSAL: supported mime: application/ogg
09-01 11:33:17.035   321  1375 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,09-01 11:33:17.036   321  1375 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-01 11:33:17.036   321  1375 V AwesomePlayer: mBitrate = -1 bits/sec
09-01 11:33:17.036   321  1375 V AwesomePlayer: AudioTrack Setting
09-01 11:33:17.036   321  1375 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-01 11:33:17.036   321  1375 V AwesomePlayer: setAudioSource() 
09-01 11:33:17.036   321  1375 V MediaPlayerService: prepare
09-01 11:33:17.036   321  1375 V AwesomePlayer: prepareAsync_l() 
09-01 11:33:17.036   321  1375 V MediaPlayerService: wait for prepare
09-01 11:33:17.037   321  7107 V AwesomePlayer: onPrepareAsyncEvent() 
09-01 11:33:17.037   321  7107 V AwesomePlayer: initAudioDecoder() 
09-01 11:33:17.037   321  7107 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-01 11:33:17.037   321  7107 V AudioSystem: isOffloadSupported()
09-01 11:33:17.037   321  7107 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-01 11:33:17.037   321  7107 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-01 11:33:17.037   321  7107 I AudioFlinger: isAudioPlaybackHookOn() false
09-01 11:33:17.037   321  7107 V AwesomePlayer: getUseOffload() = 0 
09-01 11:33:17.037   321  7107 V OMXCodec: OMXCodec::Create
09-01 11:33:17.037   321  7107 V OMXCodec: findMatchingCodecs()
09-01 11:33:17.037   321  7107 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-01 11:33:17.037   321  7107 V OMXCodec: matchingCodecs.size()=1
09-01 11:33:17.037   321  7107 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-01 11:33:17.039   321  7107 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-01 11:33:17.039   321  7107 V LGCodecAdapter: LG Codec Adapter start
09-01 11:33:17.039   321  7107 V OMXCodec: OMXCodec Createtor
09-01 11:33:17.039   321  7107 V OMXCodec: setComponentRole
09-01 11:33:17.039   321  7107 V OMXCodec: configureCodec protected=0
09-01 11:33:17.039   321  7107 V LGCodecAdapter: called getLGCodecSpecificData
09-01 11:33:17.039   321  7107 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-01 11:33:17.039   321  7107 V LGCodecOSAL: Called LGconfigureCodecMETA
09-01 11:33:17.039   321  7107 V LGCodecOSAL: Called LGconfigureCodecMSG
09-01 11:33:17.039   321  7107 V LGCodecOSAL: Not support LGCodec
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-01 11:33:17.040   321  7107 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-01 11:33:17.040   321  7107 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-01 11:33:17.040   321  7107 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-01 11:33:17.040   321  7107 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-01 11:33:17.040   321  7107 V AudioSystem: isOffloadSupported()
09-01 11:33:17.040   321  7107 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-01 11:33:17.040   321  7107 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-01 11:33:17.040   321  7107 V OMXCodec: init()
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-01 11:33:17.040   321  7107 V OMXCodec: allocateBuffers
09-01 11:33:17.040   321  7107 V OMXCodec: allocateBuffersOnPort portIndex=0
09-0,1 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
09-01 11:33:17.040   321  7107 V OMXCodec: allocateBuffersOnPort portIndex=1
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
09-01 11:33:17.040   321  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
09-01 11:33:17.040   321  7107 V OMXCodec: init() mAsyncCompletion wait!!! 
09-01 11:33:17.041   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-01 11:33:17.041   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-01 11:33:17.041   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-01 11:33:17.041   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-01 11:33:17.041   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-01 11:33:17.041   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-01 11:33:17.041   321  7107 V OMXCodec: init() mAsyncCompletion wait free! 
09-01 11:33:17.041   321  7107 V AwesomePlayer: finishAsyncPrepare_l() 
09-01 11:33:17.041   321  7107 V AudioCache: notify(0xb1003300, 5, 0, 0)
09-01 11:33:17.041   321  7107 V AudioCache: ignored
09-01 11:33:17.041   321  7107 V AudioCache: notify(0xb1003300, 1, 0, 0)
09-01 11:33:17.041   321  7107 V AudioCache: prepared
09-01 11:33:17.041   321  1375 V AudioCache: wait - success
09-01 11:33:17.041   321  1375 V MediaPlayerService: start
09-01 11:33:17.041   321  1375 V AwesomePlayer: play_l() 
,09-01 11:33:17.041   321  1375 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-01 11:33:17.041   321  1375 V AwesomePlayer: createAudioPlayer_l
09-01 11:33:17.041   321  1375 V AwesomePlayer: seekAudioIfNecessary_l() 
09-01 11:33:17.041   321  1375 V AwesomePlayer: startAudioPlayer_l() 
09-01 11:33:17.041   321  1375 D AudioPlayer: start of Playback, useOffload 0
09-01 11:33:17.041   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-01 11:33:17.041   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-01 11:33:17.044   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-01 11:33:17.044   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1),
09-01 11:33:17.044   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-01 11:33:17.044   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,09-01 11:33:17.044   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1),
09-01 11:33:17.044   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-01 11:33:17.044   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
,09-01 11:33:17.044   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:33:17.044   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
09-01 11:33:17.044   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568,
,09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-01 11:33:17.045   321  7109 V OMXCodec: allocateBuffersOnPort portIndex=1
09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-01 11:33:17.045   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57be7e0 on output port
,09-01 11:33:17.046   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-01 11:33:17.046   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-01 11:33:17.046   321  1375 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-01 11:33:17.047   321  1375 V AudioCache: notify(0xb1003300, 6, 0, 0)
09-01 11:33:17.047   321  1375 V AudioCache: ignored
09-01 11:33:17.047   321  1375 V MediaPlayerService: wait for playback complete
09-01 11:33:17.050   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.050   321  7110 V AudioCache: memcpy(0xac300000, 0xb1507000, 4096)
,09-01 11:33:17.051   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.051   321  7110 V AudioCache: memcpy(0xac301000, 0xb1507000, 4096)
09-01 11:33:17.051   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.051   321  7110 V AudioCache: memcpy(0xac302000, 0xb1507000, 4096)
09-01 11:33:17.051   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.051   321  7110 V AudioCache: memcpy(0xac303000, 0xb1507000, 4096)
09-01 11:33:17.052   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.052   321  7110 V AudioCache: memcpy(0xac304000, 0xb1507000, 4096)
09-01 11:33:17.052   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.052   321  7110 V AudioCache: memcpy(0xac305000, 0xb1507000, 4096)
09-01 11:33:17.053   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.053   321  7110 V AudioCache: memcpy(0xac306000, 0xb1507000, 4096)
,09-01 11:33:17.053   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.053   321  7110 V AudioCache: memcpy(0xac307000, 0xb1507000, 4096)
09-01 11:33:17.054   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.054   321  7110 V AudioCache: memcpy(0xac308000, 0xb1507000, 4096)
09-01 11:33:17.054   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.054   321  7110 V AudioCache: memcpy(0xac309000, 0xb1507000, 4096)
09-01 11:33:17.055   321  7110 V AudioCache: write(0xb1507000, 4096)
,09-01 11:33:17.055   321  7110 V AudioCache: memcpy(0xac30a000, 0xb1507000, 4096)
,09-01 11:33:17.055   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.055   321  7110 V AudioCache: memcpy(0xac30b000, 0xb1507000, 4096)
09-01 11:33:17.056   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.056   321  7110 V AudioCache: memcpy(0xac30c000, 0xb1507000, 4096)
09-01 11:33:17.056  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-01 11:33:17.057   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.057   321  7110 V AudioCache: memcpy(0xac30d000, 0xb1507000, 4096)
09-01 11:33:17.057  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-01 11:33:17.057   321  7110 V AudioCache: write(0xb1507000, 4096)
,09-01 11:33:17.057   321  7110 V AudioCache: memcpy(0xac30e000, 0xb1507000, 4096)
09-01 11:33:17.058   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.058   321  7110 V AudioCache: memcpy(0xac30f000, 0xb1507000, 4096)
09-01 11:33:17.058   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.058   321  7110 V AudioCache: memcpy(0xac310000, 0xb1507000, 4096)
09-01 11:33:17.058   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.058   321  7110 V AudioCache: memcpy(0xac311000, 0xb1507000, 4096)
09-01 11:33:17.059  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8374
09-01 11:33:17.059   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.059   321  7110 V AudioCache: memcpy(0xac312000, 0xb1507000, 4096)
,09-01 11:33:17.059   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.059   321  7110 V AudioCache: memcpy(0xac313000, 0xb1507000, 4096)
09-01 11:33:17.060   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.060   321  7110 V AudioCache: memcpy(0xac314000, 0xb1507000, 4096)
09-01 11:33:17.061   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.061   321  7110 V AudioCache: memcpy(0xac315000, 0xb1507000, 4096)
09-01 11:33:17.061   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.061   321  7110 V AudioCache: memcpy(0xac316000, 0xb1507000, 4096)
09-01 11:33:17.062   321  7110 V AudioCache: write(0xb1507000, 4096)
,09-01 11:33:17.062   321  7110 V AudioCache: memcpy(0xac317000, 0xb1507000, 4096)
09-01 11:33:17.062   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.062   321  7110 V AudioCache: memcpy(0xac318000, 0xb1507000, 4096)
09-01 11:33:17.063   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.063   321  7110 V AudioCache: memcpy(0xac319000, 0xb1507000, 4096)
09-01 11:33:17.063   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.063   321  7110 V AudioCache: memcpy(0xac31a000, 0xb1507000, 4096)
09-01 11:33:17.063   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.063   321  7110 V AudioCache: memcpy(0xac31b000, 0xb1507000, 4096)
,09-01 11:33:17.064   321  7110 V AudioCache: write(0xb1507000, 4096)
,09-01 11:33:17.064   321  7110 V AudioCache: memcpy(0xac31c000, 0xb1507000, 4096)
09-01 11:33:17.064   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.064   321  7110 V AudioCache: memcpy(0xac31d000, 0xb1507000, 4096)
09-01 11:33:17.065   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.065   321  7110 V AudioCache: memcpy(0xac31e000, 0xb1507000, 4096)
,09-01 11:33:17.065   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.065   321  7110 V AudioCache: memcpy(0xac31f000, 0xb1507000, 4096)
09-01 11:33:17.066   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.066   321  7110 V AudioCache: memcpy(0xac320000, 0xb1507000, 4096)
09-01 11:33:17.066   321  7110 V AudioCache: write(0xb1507000, 4096)
,09-01 11:33:17.066   321  7110 V AudioCache: memcpy(0xac321000, 0xb1507000, 4096)
09-01 11:33:17.067   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.067   321  7110 V AudioCache: memcpy(0xac322000, 0xb1507000, 4096)
09-01 11:33:17.067   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.067   321  7110 V AudioCache: memcpy(0xac323000, 0xb1507000, 4096)
,09-01 11:33:17.068   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.068   321  7110 V AudioCache: memcpy(0xac324000, 0xb1507000, 4096)
09-01 11:33:17.068   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.068   321  7110 V AudioCache: memcpy(0xac325000, 0xb1507000, 4096)
09-01 11:33:17.068   321  7110 V AudioCache: write(0xb1507000, 4096)
,09-01 11:33:17.068   321  7110 V AudioCache: memcpy(0xac326000, 0xb1507000, 4096)
09-01 11:33:17.069   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.069   321  7110 V AudioCache: memcpy(0xac327000, 0xb1507000, 4096)
,09-01 11:33:17.069   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.069   321  7110 V AudioCache: memcpy(0xac328000, 0xb1507000, 4096)
09-01 11:33:17.070   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.070   321  7110 V AudioCache: memcpy(0xac329000, 0xb1507000, 4096)
09-01 11:33:17.070   321  7110 V AudioCache: write(0xb1507000, 4096)
,09-01 11:33:17.070   321  7110 V AudioCache: memcpy(0xac32a000, 0xb1507000, 4096)
09-01 11:33:17.071   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.071   321  7110 V AudioCache: memcpy(0xac32b000, 0xb1507000, 4096)
09-01 11:33:17.071   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.071   321  7110 V AudioCache: memcpy(0xac32c000, 0xb1507000, 4096)
,09-01 11:33:17.071   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.071   321  7110 V AudioCache: memcpy(0xac32d000, 0xb1507000, 4096)
09-01 11:33:17.072   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.072   321  7110 V AudioCache: memcpy(0xac32e000, 0xb1507000, 4096)
09-01 11:33:17.072   321  7110 V AudioCache: write(0xb1507000, 4096)
,09-01 11:33:17.072   321  7110 V AudioCache: memcpy(0xac32f000, 0xb1507000, 4096)
09-01 11:33:17.073   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.073   321  7110 V AudioCache: memcpy(0xac330000, 0xb1507000, 4096)
09-01 11:33:17.073   321  7110 V AudioCache: write(0xb1507000, 4096)
09-01 11:33:17.073   321  7110 V AudioCache: memcpy(0xac331000, 0xb1507000, 4096)
,09-01 11:33:17.073   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-01 11:33:17.073   321  7110 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-01 11:33:17.073   321  7110 V AwesomePlayer: postAudioEOS() 
09-01 11:33:17.073   321  7110 V AudioCache: write(0xb1507000, 280)
,09-01 11:33:17.073   321  7110 V AudioCache: memcpy(0xac332000, 0xb1507000, 280)
09-01 11:33:17.075   321  7107 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-01 11:33:17.075   321  7107 V AwesomePlayer: onStreamDone
09-01 11:33:17.075   321  7107 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-01 11:33:17.075   321  7107 V AudioCache: notify(0xb1003300, 2, 0, 0)
,09-01 11:33:17.075   321  7107 V AudioCache: playback complete
09-01 11:33:17.075   321  1375 V AudioCache: wait - success
09-01 11:33:17.075   321  7107 V AwesomePlayer: pause_l() 
,09-01 11:33:17.075   321  1375 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-01 11:33:17.075   321  7107 V AudioCache: notify(0xb1003300, 7, 0, 0)
09-01 11:33:17.075   321  7107 V AudioCache: ignored
,09-01 11:33:17.075   321  7107 V AwesomePlayer: cancelPlayerEvents
09-01 11:33:17.076   321  7107 D AudioPlayer: Pause Playback at 1068125
09-01 11:33:17.076   321  1375 V AwesomePlayer: reset_l() 
09-01 11:33:17.076   321  1375 V AudioCache: notify(0xb1003300, 8, 0, 0)
09-01 11:33:17.076   321  1375 V AudioCache: ignored
09-01 11:33:17.076   321  1375 V AwesomePlayer: cancelPlayerEvents
09-01 11:33:17.076   321  1375 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,09-01 11:33:17.076   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-01 11:33:17.076   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-01 11:33:17.076   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-01 11:33:17.076   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
,09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
,09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
,09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57be7e0 on port 1
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
09-01 11:33:17.076   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1,
09-01 11:33:17.077   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
09-01 11:33:17.077   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-01 11:33:17.077   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-01 11:33:17.077   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-01 11:33:17.077   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-01 11:33:17.077   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
,09-01 11:33:17.077   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-01 11:33:17.077   321  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-01 11:33:17.077   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-01 11:33:17.077   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-01 11:33:17.077   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,09-01 11:33:17.077   321  1375 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-01 11:33:17.077   321  1375 D AudioPlayer: AudioPlayer releasing audio source
09-01 11:33:17.077   321  1375 D AudioPlayer: AudioPlayer done releasing audio source
09-01 11:33:17.077   321  1375 V AwesomePlayer: reset_l() 
09-01 11:33:17.077   321  1375 V AwesomePlayer: cancelPlayerEvents
09-01 11:33:17.077   321  1375 V AwesomePlayer: ~AwesomePlayer call
09-01 11:33:17.078   321  1375 V AwesomePlayer: reset_l() ,
09-01 11:33:17.078   321  1375 V AwesomePlayer: cancelPlayerEvents
09-01 11:33:17.078  7012  7105 V SoundPool: close(31)
09-01 11:33:17.078  7012  7105 V SoundPool: pointer = 0x9fea1000, size = 205080, sampleRate = 48000, numChannels = 2
,09-01 11:33:17.280  6601  6601 I UEI.SmartControl: Supports setup maps: true,
,09-01 11:33:17.283  6601  6601 D UEI.SmartControl: QS start statue = true Error code = 0
09-01 11:33:17.283  6601  6601 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-01 11:33:17.283  6601  6601 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-01 11:33:17.284  6601  6601 I UEI.SmartControl: ### init IR Blaster...
,09-01 11:33:17.287  6601  6601 D serial_port: Configuring serial port
,09-01 11:33:17.287  6601  6601 E UEI.SmartControl: UEIBLaster setting for 616
09-01 11:33:17.287  6601  6601 I UEI.SmartControl: Setting serial record hearder size = 2
09-01 11:33:17.287  6601  6601 I UEI.SmartControl: configuring settings for MAXQ616
09-01 11:33:17.287  6601  6601 I UEI.SmartControl: Get version...
09-01 11:33:17.306  6601  7111 D UEI.SmartControl: serial port data available: 21
,09-01 11:33:17.332  6601  6601 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-01 11:33:17.332  6601  6601 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-01 11:33:17.332  6601  6601 I UEI.SmartControl: QS saving settings...
,09-01 11:33:17.334  6601  6601 D UEI.SmartControl: IR Blaster version: 25672567
,09-01 11:33:17.357  6601  7111 D UEI.SmartControl: serial port data available: 4
,09-01 11:33:17.388  6601  7117 I UEI.SmartControl: Device manager: loading config....
09-01 11:33:17.389  6601  7117 D UEI.SmartControl: ----------- loading internal config...
09-01 11:33:17.390  6601  6601 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-01 11:33:17.394  6601  6601 E UEI.SmartControl: Services init done
09-01 11:33:17.394  6601  6601 D UEI.SmartControl: QS Service init finished
09-01 11:33:17.396  6601  6601 D UEI.SmartControl: QS Service version name: 2.1.91
09-01 11:33:17.397  6601  6601 D UEI.SmartControl: QS Service version code: 201091
09-01 11:33:17.398  6601  7117 E UEI.SmartControl: Loading SETTINGS...
09-01 11:33:17.400  6601  6601 D UEI.SmartControl: Service requested: Control
09-01 11:33:17.402  7012  7012 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,09-01 11:33:17.404  6601  6601 D UEI.SmartControl: Internal service binding...
09-01 11:33:17.404  6601  6617 I UEI.SmartControl: ------ IControl API: 11
09-01 11:33:17.404  6601  6617 D UEI.SmartControl: File observer start...
09-01 11:33:17.405  6601  6617 E UEI.SmartControl: IR Port is disabled: false
09-01 11:33:17.405  6601  6617 D UEI.SmartControl: Starting file observer...
09-01 11:33:17.405  6601  6617 I UEI.SmartControl: Registering callback...
09-01 11:33:17.406  6601  6616 I UEI.SmartControl: ------ IControl API: 19
09-01 11:33:17.406  6601  6616 I UEI.SmartControl: Registering Services Ready callback...
09-01 11:33:17.410  6601  7117 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-01 11:33:17.426  6601  7116 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-01 11:33:17.427  7012  7028 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-01 11:33:17.428  6601  7116 D UEI.SmartControl: -----service ready thread exits
09-01 11:33:17.428  7012  7103 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-01 11:33:17.429  7012  7103 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-01 11:33:17.429  7012  7012 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-01 11:33:17.430  7012  7012 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-01 11:33:17.430  6601  6617 I UEI.SmartControl: ------ IControl API: 8
,09-01 11:33:17.432  7012  7012 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-01 11:33:17.432  7012  7012 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-01 11:33:17.432  7012  7012 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-01 11:33:17.433  7012  7012 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-01 11:33:17.434  7012  7012 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-01 11:33:17.434  7012  7012 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-01 11:33:17.436  7012  7012 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-01 11:33:17.442  7012  7012 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-01 11:33:17.443  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-01 11:33:17.445  7012  7012 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0,
09-01 11:33:17.446  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true,
09-01 11:33:17.448  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-01 11:33:17.450  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,09-01 11:33:17.452  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,09-01 11:33:17.454  7012  7012 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472722397453]
,09-01 11:33:17.462  7012  7012 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-01 11:33:17.466  1026  1729 I ActivityManager: Killing 6645:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-01 11:33:17.492  7012  7119 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-01 11:33:17.505  1026  1729 I ActivityManager: Killing 6694:com.google.android.setupwizard/u0a46 (adj 15): empty #18
,09-01 11:33:17.535  1026  2025 W libprocessgroup: failed to open /acct/uid_10005/pid_6645/cgroup.procs: No such file or directory
,09-01 11:33:17.539  1026  1767 W libprocessgroup: failed to open /acct/uid_10046/pid_6694/cgroup.procs: No such file or directory
09-01 11:33:17.547  7012  7012 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-01 11:33:17.548  7012  7012 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-01 11:33:17.549  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-01 11:33:17.549  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-01 11:33:17.549  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-01 11:33:17.550  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-01 11:33:17.550  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-01 11:33:17.562  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-01 11:33:18.349  1026  1916 D WifiServiceImplEx: setWifiEnabled: true pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:33:18.351  1026  1916 D WifiService: setWifiEnabled: true pid=6832, uid=10118
09-01 11:33:18.351  1026  1916 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:33:18.379  1026  1026 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:33:18.380  1026  1026 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:33:18.380  1026  1026 D Ulp_jni : JNI:system_update. Event-4
09-01 11:33:18.381  1026  1531 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-01 11:33:18.381  1026  1531 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-01 11:33:18.384  1026  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1026] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-01 11:33:18.384  1026  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:33:18.384  1026  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1026] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-01 11:33:18.384  1026  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:33:18.384  1026  1531 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-01 11:33:18.384  1026  1531 E WifiHW  : unknown target_country: EU , set to default
09-01 11:33:18.384  1026  1531 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-01 11:33:18.385  1026  1531 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-01 11:33:18.385  1026  1531 I WifiUtil: gEnableBmps=1
09-01 11:33:18.422  1026  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:33:18.440  1026  1088 D Tethering: MasterInitialState.processMessage what=3
,09-01 11:33:18.454  1026  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:33:18.460  1026  1083 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:18.463  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:18.464  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:18.469  1026  1088 D Tethering: MasterInitialState.processMessage what=3
,09-01 11:33:18.480  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:18.483  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:33:18.486  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-01 11:33:18.489  6258  6980 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-01 11:33:18.501  5710  5710 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-01 11:33:18.510  5710  5710 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-01 11:33:18.526  2209  2209 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:33:18.550  6345  6345 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:33:18.551  6345  6345 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:18.553  6345  6345 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-01 11:33:18.553  6345  6345 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-01 11:33:18.562  6345  6345 I AppUp4:CustModeStarterReceiver: onReceive
,09-01 11:33:18.567  6345  6345 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2a9b996e
09-01 11:33:18.567  6345  6345 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:33:18.567  6345  6345 D AppUp4:CustFacade: isPhone : true
09-01 11:33:18.574  6345  6345 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:33:18.574  6345  6345 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-01 11:33:18.575  1026  1083 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:18.576  1026  1083 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:18.576  1026  1083 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:18.575  6345  6345 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,09-01 11:33:18.580  6345  6791 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-01 11:33:18.580  6345  6791 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-01 11:33:18.580  6345  6791 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-01 11:33:18.585  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:18.585  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:33:18.587  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:33:18.590  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-01 11:33:18.618  4323  7139 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:33:18.622  4323  7140 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:18.622  4323  7140 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:33:18.646  1026  1776 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7144 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-01 11:33:18.708  7144  7144 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:33:18.708  7144  7144 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:33:18.710  7144  7144 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-01 11:33:18.710  7144  7144 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-01 11:33:18.805  7144  7144 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-01 11:33:18.834  7144  7144 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-01 11:33:18.880  7144  7144 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-01 11:33:18.936  7144  7144 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:33:18.937  7144  7144 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:33:19.054  7144  7144 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-01 11:33:19.093  1026  1088 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-01 11:33:19.094  1026  1088 D Tethering: InitialState.processMessage what=4
09-01 11:33:19.095  1026  1088 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 11:33:19.101   317   883 D SoftapController: Softap fwReload - Ok
09-01 11:33:19.104  1026  1531 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (714ms)
09-01 11:33:19.106   317   883 D CommandListener: Setting iface cfg
09-01 11:33:19.106   317   883 D CommandListener: Trying to bring down wlan0
09-01 11:33:19.106   317   883 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:33:19.109  1026  1531 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-01 11:33:19.111  1026  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:33:19.111  1026  1531 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:33:19.111  1026  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:33:19.111  1026  1531 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-01 11:33:19.111  1026  1531 D WifiMonitor: connecting to supplicant
09-01 11:33:19.112  1026  1531 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
09-01 11:33:19.097  7179  7179 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:19.097  7179  7179 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:19.117  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:19.122  1026  1026 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-01 11:33:19.126  3450  3450 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-01 11:33:19.126  3450  3450 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:19.126  3450  3450 I LgeMiscReceiver: networkInfo.isConnected() = false
09-01 11:33:19.128  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-01 11:33:19.130  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:19.131  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:19.140  7179  7179 I wpa_supplicant: Successfully initialized wpa_supplicant
09-01 11:33:19.143  7144  7144 I HubEmail: JNI_OnLoad()
09-01 11:33:19.143  7144  7144 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-01 11:33:19.143  7144  7144 I HubEmail: registerNatives()
09-01 11:33:19.143  7144  7144 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-01 11:33:19.143  7144  7144 I HubEmail: registerNativeMethods()
09-01 11:33:19.143  7144  7144 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-01 11:33:19.143  7144  7144 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-01 11:33:19.182  7179  7179 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-01 11:33:19.182  7179  7179 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-01 11:33:19.194  1026  1917 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7188 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-01 11:33:19.203  7075  7180 W FormManager: Network not available. Please check & try again.
,09-01 11:33:19.206  7075  7181 V FormManager: Network unavailable.
09-01 11:33:19.207  7144  7182 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:19.209  7075  7181 V FormManager: Network unavailable.
09-01 11:33:19.215  1026  2025 I ActivityManager: Killing 6737:com.google.android.talk/u0a72 (adj 15): empty #17
,09-01 11:33:19.255  7179  7179 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 11:33:19.268  1026  1953 W libprocessgroup: failed to open /acct/uid_10072/pid_6737/cgroup.procs: No such file or directory
,09-01 11:33:19.288  7179  7179 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-01 11:33:19.301  7179  7179 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-01 11:33:19.327  7179  7179 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-01 11:33:19.338  7188  7188 D LgDataFeature: LgDataFeature() Constructor: none
,09-01 11:33:19.338  7188  7188 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:33:19.342  7188  7188 D PhoneMonitor: Register our PhoneStateListener
,09-01 11:33:19.368  7188  7188 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-01 11:33:19.373  7188  7188 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-01 11:33:19.414  7188  7188 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-01 11:33:19.415  7188  7188 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-01 11:33:19.417  7188  7188 D TelephonyAutoProfiling: [parse] Load xml
09-01 11:33:19.425  7188  7188 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-01 11:33:19.426  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-01 11:33:19.426  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-01 11:33:19.426  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-01 11:33:19.426  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-01 11:33:19.426  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-01 11:33:19.426  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-01 11:33:19.426  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-01 11:33:19.426  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-01 11:33:19.426  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-01 11:33:19.427  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-01 11:33:19.427  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-01 11:33:19.427  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-01 11:33:19.427  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-01 11:33:19.427  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-01 11:33:19.427  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-01 11:33:19.427  7188  7188 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-01 11:33:19.439  7188  7188 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-01 11:33:19.450  1026  1766 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7208 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 11:33:19.452  1026  1766 I ActivityManager: Killing 6367:com.android.contacts/u0a19 (adj 15): empty #17
,09-01 11:33:19.475   381   381 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 470us total 21.067ms
,09-01 11:33:19.496   381   381 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 20.041ms
,09-01 11:33:19.515   381   381 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 369us total 18.211ms
,09-01 11:33:19.527  1026  1767 W libprocessgroup: failed to open /acct/uid_10019/pid_6367/cgroup.procs: No such file or directory
,09-01 11:33:19.784  1026  1917 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7229 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-01 11:33:19.785  1026  1917 I ActivityManager: Killing 6422:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-01 11:33:19.846  1026  2036 W libprocessgroup: failed to open /acct/uid_10027/pid_6422/cgroup.procs: No such file or directory
,09-01 11:33:19.917  7179  7179 E wpa_supplicant: USIM:  scard_init function
09-01 11:33:19.918  7179  7179 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-01 11:33:19.971  1026  1917 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7249 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 11:33:19.972  1026  1917 I ActivityManager: Killing 6524:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-01 11:33:20.026  1026  1935 W libprocessgroup: failed to open /acct/uid_10080/pid_6524/cgroup.procs: No such file or directory
,09-01 11:33:20.030  7179  7179 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-01 11:33:20.036  1026  1088 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-01 11:33:20.043  7179  7179 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:33:20.043  7179  7179 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:33:20.078  7249  7249 I art     : Almond Protected OAT
,09-01 11:33:20.115  1026  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-01 11:33:20.116  1026  1531 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-01 11:33:20.116  1026  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-01 11:33:20.116  1026  1531 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,09-01 11:33:20.117  1026  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-01 11:33:20.118  1026  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:20.118  1026  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:20.118  1026  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:20.119  1026  1531 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-01 11:33:20.119  1026  1531 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-01 11:33:20.120  1026  1531 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-01 11:33:20.120  1026  1531 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-01 11:33:20.120  1026  1531 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-01 11:33:20.120  1026  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:33:20.120  1026  1531 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:33:20.120  1026  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:33:20.121  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:20.121  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:20.121  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:20.121  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:20.121  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:33:20.122  1026  1531 D WifiNative-wlan0: doBoolean: SET update_config 1
09-01 11:33:20.123  1026  1531 D WifiNative-wlan0: SET update_config 1: returned true
09-01 11:33:20.123  1026  1531 D WifiConfigStore: Loading config and enabling all networks 
09-01 11:33:20.123  1026  1531 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-01 11:33:20.124  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:20.124  1026  1026 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-01 11:33:20.125  1936  1936 D WfdService: Waiting for WifiP2p enabling
09-01 11:33:20.125  1026  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-01 11:33:20.127  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:20.127  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:20.127  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:20.127  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:20.127  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:20.127  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:33:20.127  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:20.127  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:20.127  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:33:20.127  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:20.127  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-,01 11:33:20.127  1026  1531 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
09-01 11:33:20.128  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:20.128  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:20.128  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:20.128  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:20.128  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:20.128  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:33:20.128  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:20.128  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:20.128  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:33:20.128  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:20.129  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:20.137  1026  1531 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-01 11:33:20.144  7249  7249 D WeatherApplication: removeAccount
09-01 11:33:20.147  7249  7249 D WeatherApplication: Account.length = 0
09-01 11:33:20.148  7249  7249 E WeatherApplication: OPERATOR:OPEN
09-01 11:33:20.153  7249  7249 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:33:20
09-01 11:33:20.153  1026  1531 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-01 11:33:20.154  1026  1531 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-01 11:33:20.155  1026  1531 D WifiStateMachine: enableVerboseLogging : level 2
09-01 11:33:20.155  1026  1531 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,09-01 11:33:20.156  1026  1531 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-01 11:33:20.156  1026  1531 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-01 11:33:20.158  1026  1531 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-01 11:33:20.158  1026  1531 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-01 11:33:20.158  1026  1531 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-01 11:33:20.158  1026  1531 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-01 11:33:20.159  1026  1531 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-01 11:33:20.159  1026  1531 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-01 11:33:20.159  7249  7249 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-01 11:33:20.159  7249  7249 D Weather.Utils: 2 : All the weather widget is gone.
09-01 11:33:20.159  1026  1531 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-01 11:33:20.159  1026  1531 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-01 11:33:20.160  1026  1531 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-01 11:33:20.160  1026  1531 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-01 11:33:20.160  1026  1531 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-01 11:33:20.161  7249  7249 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-01 11:33:20.162  1936  1936 D WfdsService: Supplicant Connection state is changed : true
09-01 11:33:20.162  1936  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-01 11:33:20.162  1936  2300 D WfdsService: Set the WFDS Monitor: true
09-01 11:33:20.162  1936  2300 D WfdsMonitor: WfdsMonitorThread create
09-01 11:33:20.162  1936  2300 D WfdsMonitor: WFDS Monitor is created and started
09-01 11:33:20.162  1936  2300 D WfdsService: WiFi: Supplicant connection re-established
09-01 11:33:20.163  1026  1531 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:33:20.163  1026  1531 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-01 11:33:20.163  7249  7249 D WeatherAncestor: connectivity changed - connection : true
09-01 11:33:20.163  1936  7277 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-01 11:33:20.164  1026  1531 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-01 11:33:20.164  1026  1531 D WifiNative-HAL: Setting external_sim to 1
09-01 11:33:20.164  1026  1531 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-01 11:33:20.164  1936  7277 E CtrlSupplicant: Succeed to open control connection
09-01 11:33:20.164  1936  7277 E CtrlSupplicant: Succeed to open monitor connection
09-01 11:33:20.164  7249  7249 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-01 11:33:20.164  1026  1531 D WifiNative-wlan0: SET external_sim 1: returned true
09-01 11:33:20.164  1026  1531 I WifiNative-HAL: startHal
09-01 11:33:20.164  1936  7277 D WfdsMonitor: Supplicant connection established
09-01 11:33:20.164  1026  1531 D wifi    : setting scan oui 0x95360f40
09-01 11:33:20.165  1936  2300 D WfdsService: Connected to the supplicant for wfds
09-01 11:33:20.165  1026  1531 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:33:20.165  1026  1531 I WifiNative-HAL: startHal
09-01 11:33:20.165  1026  1531 D wifi    : setting scan oui 0x95360f40
09-01 11:33:20.165  1026  1531 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-01 11:33:20.165  1026  1531 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-01 11:33:20.165  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-01 11:33:20.166  7179  7179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-01 11:33:20.166  1026  1531 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-01 11:33:20.166  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-01 11:33:20.166  7179  7179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:33:20.,166  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:33:20.166  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-01 11:33:20.167  7179  7179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-01 11:33:20.167  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-01 11:33:20.167  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:33:20.167  7179  7179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:33:20.167  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-01 11:33:20.167  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-01 11:33:20.167  7179  7179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:33:20.168  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:33:20.168  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-01 11:33:20.168  7179  7179 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-01 11:33:20.168  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,09-01 11:33:20.168  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:33:20.169  7179  7179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:33:20.169  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-01 11:33:20.172  7249  7249 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-01 11:33:20.172  7249  7249 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-01 11:33:20.172  7249  7249 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-01 11:33:20.174  1026  1531 E WifiNative: : [207,702,771 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-01 11:33:20.174  1026  1531 D WifiNative-wlan0: doBoolean: RECONNECT
09-01 11:33:20.174  1026  1531 D WifiNative-wlan0: RECONNECT: returned true
09-01 11:33:20.174  1026  1531 D WifiNative-wlan0: doString: [STATUS]
09-01 11:33:20.175  1026  1531 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-01 11:33:20.175  1026  1531 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:33:20.175  1026  7272 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:33:20.175  1026  7272 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:33:20.176  1026  1531 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:33:20.176  1026  1529 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.176  1026  1026 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 11:33:20.177  1026  1026 D RttService: SCAN_AVAILABLE : 3
09-01 11:33:20.177  1026  1550 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.177  1026  1549 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.177  1026  1549 I WifiNative-HAL: startHal
09-01 11:33:20.177  1026  1549 D wifi    : getting scan capabilities on interface[1] = 0x95360f40
09-01 11:33:20.177  1026  1549 D wifi    : failed to get capabilities : -3
09-01 11:33:20.177  1026  1549 E WifiScanningService: could not get scan capabilities
09-01 11:33:20.177   317   883 D CommandListener: Setting iface cfg
09-01 11:33:20.177   317   883 D CommandListener: Trying to bring up p2p0
09-01 11:33:20.177  1026  1531 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-01 11:33:20.178  1026  1529 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-01 11:33:20.178  1026  1529 D LGWifiP2pService: P2pEnablingState
09-01 11:33:20.178  1026  1529 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.178  1026  1531 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-01 11:33:20.178  1026  1529 D LGWifiP2pService: P2p socket connection successful
,09-01 11:33:20.178  1026  1529 D LGWifiP2pService: P2pEnabledState
09-01 11:33:20.178  1026  1529 D LGWifiP2pService: sending p2p connection changed broadcast
09-01 11:33:20.179  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,09-01 11:33:20.179  1936  1936 D WfdsService: WifiP2pState is changed : true
09-01 11:33:20.179  1936  2300 D WfdsService: Receive the WFDS_ENABLE Method
09-01 11:33:20.180  1936  2300 D WfdsService: Set the WFDS Monitor: true
09-01 11:33:20.180  1936  2300 D WfdsService: Connected to the supplicant for wfds
09-01 11:33:20.180  1936  2300 D WfdsJNI : doCommand: WFDS_SET TRUE
,09-01 11:33:20.180  7179  7179 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-01 11:33:20.180  1936  2300 D WfdsService: selectPreferredScanChannel [36]
09-01 11:33:20.180  1936  2300 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-01 11:33:20.182  1026  1529 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-01 11:33:20.184  1936  1936 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
,09-01 11:33:20.184  1026  1529 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-01 11:33:20.184  1936  1936 D WfdsService: isConnected: false
09-01 11:33:20.184  1026  1529 D WifiNative-p2p0: doBoolean: SET device_name G3
09-01 11:33:20.185  1026  1529 D WifiNative-p2p0: SET device_name G3: returned true
09-01 11:33:20.185  1026  1529 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-01 11:33:20.185  1026  1529 D LGWifiP2pService: before postfix = G3
,09-01 11:33:20.185  1026  1529 D WifiServerServiceExt: postfix byte check : 2
09-01 11:33:20.185  1026  1529 D LGWifiP2pService: after postfix = G3
09-01 11:33:20.185  1026  1529 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-01 11:33:20.185  1026  1529 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-01 11:33:20.186  1026  1529 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-01 11:33:20.186  1026  1529 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-01 11:33:20.186  1026  1529 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-01 11:33:20.187  1026  1529 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-01 11:33:20.187  1026  1531 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-01 11:33:20.187  1026  1529 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-01 11:33:20.187  1026  1529 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-01 11:33:20.187  1026  1529 D WifiNative-HAL: p2pGetDeviceAddress
09-01 11:33:20.187  1026  1531 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-01 11:33:20.188  1026  1529 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-01 11:33:20.188  1026  1531 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-01 11:33:20.188  1026  1531 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-01 11:33:20.189  1026  1531 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-01 11:33:20.189  1026  1531 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-01 11:33:20.189  7179  7179 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-01 11:33:20.189  1026  1529 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-01 11:33:20.189  1026  1529 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-01 11:33:20.189  1026  1529 D WifiNative-p2p0: P2P_FLUSH: returned true
09-01 11:33:20.189  1026  1529 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-01 11:33:20.190  1026  1529 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-01 11:33:20.190  1026  1529 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-01 11:33:20.190  1026  1529 D WifiNative-p2p0:    returned OK
09-01 11:33:20.190  1936  1936 I WfdStateTracker: handleP2pThisDeviceChanged
09-01 11:33:20.190  1026  1529 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-01 11:33:20.191  1936  1936 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-01 11:33:20.191  1936  1936 D WfdsService: Update P2p Interface State: 3
09-01 11:33:20.191  1026  1529 D WifiNative-p2p0: SAVE_CONFIG: returned false
09-01 11:33:20.191  1026  1529 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-01 11:33:20.192  1026  1529 D LGWifiP2pService: InactiveState
09-01 11:33:20.192  1026  1529 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.192  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.192  1026  1529 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-01 11:33:20.194  7249  7249 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:33:20.194  7249  7249 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:33:20
09-01 11:33:20.202  7179  7179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-01 11:33:20.202  7179  7179 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:20.203  1026  7272 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:33:20.203  1026  7272 E WifiMonitor: WifiMonitor:p2p0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:20.203  1026  7272 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:20.203  1026  7272 E ,WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:20.203  7179  7179 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:33:20.203  7179  7179 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.204  7179  7179 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-01 11:33:20.206  1936  7277 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:33:20.206  1936  7277 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:20.206  1936  7277 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:20.207  1026  1531 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-01 11:33:20.207  1026  1531 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-01 11:33:20.208  1026  7272 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:20.208  1026  7272 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.208  1026  7272 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.208  1026  7272 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.208  1026  7272 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:20.208  1026  7272 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.208  1026  7272 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.208  1026  7272 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.208  1026  1531 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-01 11:33:20.209  1026  1531 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-01 11:33:20.209  7179  7179 E wpa_supplicant: disconnect_rssi_lvl: -100
09-01 11:33:20.209  1026  1529 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-01 11:33:20.209  1026  1529 D LGWifiP2pService: InactiveState{ when=-18ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.209  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.209  1026  1529 D LGWifiP2pService: DefaultState{ when=-18ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.209  1026  1529 D LGWifiP2pService: InactiveState{ when=-18ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.210  1026  1531 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-01 11:33:20.210  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.210  1026  1529 D LGWifiP2pService: DefaultState{ when=-19ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.210  1026  1531 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-01 11:33:20.210  1026  1529 D LGWifiP2pService: InactiveState{ when=-19ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.210  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.210  1026  1529 D LGWifiP2pService: DefaultState{ when=-19ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.210  1026  1529 D LGWifiP2pService: InactiveState{ when=-19ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.210  1936  2300 W WfdsService: DefaultState - msg [9441285] is not handled
09-01 11:33:20.210  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.211  1026  1529 D LGWifiP2pService: DefaultState{ when=-19ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.211  1026  1531 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-01 11:33:20.211  1026  1026 E WifiServerS,erviceExt: No p2p device connected
09-01 11:33:20.211  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-01 11:33:20.212  7179  7179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-01 11:33:20.212  7179  7179 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:20.212  1026  7272 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:33:20.212  1026  7272 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:20.212  1026  7272 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:20.212  1026  7272 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:20.213  7179  7179 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:33:20.213  7179  7179 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.213  1936  7277 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:20.213  1026  7272 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:20.213  1026  7272 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.213  1026  7272 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.213  1026  7272 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.215  7179  7179 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.215  1936  7277 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:20.215  1026  7272 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:20.215  1026  7272 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.215  1026  7272 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.215  1026  7272 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:20.216  1026  1531 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-01 11:33:20.216  1026  1529 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.216  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.217  1026  1531 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:33:20.218  1026  1531 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:33:20.219  1026  1531 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:33:20.220  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,09-01 11:33:20.220  7179  7179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-01 11:33:20.220  7179  7179 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-01 11:33:20.222  1026  7272 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-01 11:33:20.222  1026  7272 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:33:20.222  1026  7272 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:33:20.222  1026  7272 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:33:20.223  1026  1531 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-01 11:33:20.223  1026  1531 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-01 11:33:20.223  1026  1531 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-01 11:33:20.224  1026  1531 D WifiNative-wlan0: doBoolean: SCAN
09-01 11:33:20.225  1026  1531 D WifiNative-wlan0: SCAN: returned true
09-01 11:33:20.225  7179  7179 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-01 11:33:20.225  1026  7272 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-01 11:33:20.225  1026  7272 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-01 11:33:20.226  1026  7272 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-01 11:33:20.226  1026  7272 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-01 11:33:20.226  1026  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=207759  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-01 11:33:20.236  1026  1568 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7281 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 11:33:20.238  1026  1568 I ActivityManager: Killing 6542:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-01 11:33:20.295  1026  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=207828  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-01 11:33:20.295  1026  1935 W libprocessgroup: failed to open /acct/uid_10097/pid_6542/cgroup.procs: No such file or directory
,09-01 11:33:20.301  1026  1531 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-01 11:33:20.302  1026  1531 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:33:20.302  1026  1531 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:33:20.302  1026  1531 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:33:20.303  1026  1531 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:33:20.325  1026  1529 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.326  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:20.326  1026  1529 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:33:20.357  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 11:33:20.357  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:20.358  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:20.359  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:20.359  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:20.359  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-01 11:33:20.359  1026  1026 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:33:20.359  1026  1026 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-01 11:33:20.419   278   420 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-01 11:33:20.419   278   420 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-01 11:33:20.419   278   420 W Vold    : Returning OperationFailed - no handler for errno 0
09-01 11:33:20.420  7281  7299 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-01 11:33:20.421  1026  1531 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:33:20.421  1026  1531 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:33:20.422  1026  1531 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:33:20.422  1026  1531 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:33:20.422  1026  1531 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-01 11:33:20.424   278   420 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-01 11:33:20.424   278   420 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-01 11:33:20.424   278   420 W Vold    : Returning OperationFailed - no handler for errno 0
09-01 11:33:20.425  7281  7299 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-01 11:33:20.439   278   420 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-01 11:33:20.439   278   420 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-01 11:33:20.439   278   420 W Vold    : Returning OperationFailed - no handler for errno 0
09-01 11:33:20.440  7281  7303 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-01 11:33:20.445   278   420 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-01 11:33:20.445   278   420 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-01 11:33:20.445   278   420 W Vold    : Returning OperationFailed - no handler for errno 0
09-01 11:33:20.446  7281  7303 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-01 11:33:20.730  7281  7281 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-01 11:33:20.743  7281  7281 I LibraryLoader: Loading: webviewchromium
,09-01 11:33:20.749  7281  7281 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 8287-8293)
,09-01 11:33:20.749  7281  7281 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 11:33:20.760  7281  7281 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {13e26ef6}
,09-01 11:33:20.764  7281  7281 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 11:33:20.766  7281  7281 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-01 11:33:20.792  7281  7281 I BrowserStartupController: Initializing chromium process, renderers=0
,09-01 11:33:20.794  7281  7281 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 11:33:20.816   321  2145 V AudioPolicyService: registerClient() client 0xb1023c20, uid 10093
,09-01 11:33:20.819  7281  7326 W AudioManagerAndroid: Requires BLUETOOTH permission
09-01 11:33:20.821  7281  7281 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-01 11:33:20.822  7281  7281 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-01 11:33:20.823  7281  7281 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-01 11:33:20.849  7281  7281 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:33:20.849  7281  7281 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:33:20.849  7281  7281 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:33:20.849  7281  7281 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:33:20.849  7281  7281 I Adreno-EGL: Remote Branch: 
09-01 11:33:20.849  7281  7281 I Adreno-EGL: Local Patches: 
09-01 11:33:20.849  7281  7281 I Adreno-EGL: Reconstruct Branch: 
,09-01 11:33:20.938  7281  7281 I NSApplication: Starting up...
,09-01 11:33:21.003  1026  2025 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7339 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-01 11:33:21.006  1026  2025 I ActivityManager: Killing 6442:com.android.vending/u0a44 (adj 15): empty #17
09-01 11:33:21.064  1026  1953 W libprocessgroup: failed to open /acct/uid_10044/pid_6442/cgroup.procs: No such file or directory
,09-01 11:33:21.100  7339  7339 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:33:21.383  1026  2036 D WifiServiceImplEx: setWifiEnabled: false pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:33:21.384  1026  2036 D WifiService: setWifiEnabled: false pid=6832, uid=10118
09-01 11:33:21.384  1026  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:33:21.397  1026  1531 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
09-01 11:33:21.397  1026  1531 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-01 11:33:21.398  1026  1531 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-01 11:33:21.398  1026  1531 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
,09-01 11:33:21.406  1026  1026 D WifiScanningService: SCAN_AVAILABLE : 1
09-01 11:33:21.406  1026  1529 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:21.406  1026  1026 D RttService: SCAN_AVAILABLE : 1
09-01 11:33:21.406  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:21.406  1026  1529 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@31659bcb
09-01 11:33:21.406  1026  1026 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:33:21.406  1026  1529 D LGWifiP2pService: P2pDisablingState
09-01 11:33:21.406  1026  1026 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:33:21.406  1026  1026 D Ulp_jni : JNI:system_update. Event-4
09-01 11:33:21.406  1026  1529 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:21.406  1026  1529 D LGWifiP2pService: p2p socket connection lost
09-01 11:33:21.406  1026  1529 D LGWifiP2pService: P2pDisabledState
09-01 11:33:21.406  1026  1549 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:21.407  1026  1550 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:21.408  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-01 11:33:21.408  1936  1936 D WfdsService: WifiP2pState is changed : false
09-01 11:33:21.408  1936  2300 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-01 11:33:21.408  1936  2300 D WfdsService: Set the WFDS Monitor: false
09-01 11:33:21.410  1936  2300 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:33:21.410  1936  2300 D WfdsService: STATE : WfdsDisabledState - enter
09-01 11:33:21.411  1936  2301 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-01 11:33:21.411  1936  7277 D CtrlSupplicant: Received on exit socket, terminate
09-01 11:33:21.411  1936  7277 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-01 11:33:21.411  1936  7277 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-01 11:33:21.411  1936  7277 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-01 11:33:21.415  1936  2300 W WfdsService: DefaultState - msg [9445378] is not handled
,09-01 11:33:21.417  1026  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-01 11:33:21.418   317   883 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:33:21.421  1026  1026 D WifiHS20: hidePasspointNotification off =false
09-01 11:33:21.422  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:21.422  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:21.422  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:33:21.423  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 11:33:21.423  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:21.424  1026  1531 D WifiNative-p2p0: doBoolean: TERMINATE
09-01 11:33:21.426  1026  1026 D WifiHS20: hidePasspointNotification off =false
09-01 11:33:21.427  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:21.427  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:21.427  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:33:21.424  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:21.427  1026  1531 D WifiNative-p2p0: TERMINATE: returned true
09-01 11:33:21.427  1026  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:33:21.427  1026  1531 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:33:21.427  1026  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:33:21.429  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 11:33:21.429  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:21.429  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,09-01 11:33:21.436  1026  1026 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-01 11:33:21.436  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:21.438  1026  1026 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:33:21.438  1026  1026 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-01 11:33:21.438  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:21.438  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:21.438  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:21.438  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:21.438  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:33:21.438  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:33:21.438  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:21.438  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:21.438  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:33:21.439  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:21.439  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:21.440  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:21.440  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:21.440  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:21.440  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:21.440  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:33:21.440  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:33:21.440  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:21.440  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:21.440  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:33:21.440  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:21.440  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:21.450  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-01 11:33:21.452  6258  6980 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-01 11:33:21.452  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:21.476  2209  2209 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:33:21.493  6345  6345 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-01 11:33:21.493  6345  6345 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:21.494  6345  6345 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-01 11:33:21.494  6345  6345 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-01 11:33:21.496  6345  6345 I AppUp4:CustModeStarterReceiver: onReceive
09-01 11:33:21.500  6345  6345 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2a9b996e
09-01 11:33:21.500  6345  6345 D AppUp4:CustFacade: isCustomizationCompleted : false
09-01 11:33:21.500  6345  6345 D AppUp4:CustFacade: isPhone : true
09-01 11:33:21.501  6345  6345 D AppUp4:CustModeStarterReceiver: begin check event
09-01 11:33:21.501  6345  6345 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-01 11:33:21.504  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:21.505  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:33:21.507  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-01 11:33:21.512  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:33:21.519  4323  7381 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:33:21.519  7144  7144 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-01 11:33:21.520  4323  7382 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:21.520  4323  7382 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:33:21.537  7179  7179 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-01 11:33:21.537  7179  7179 I wpa_supplicant: monitor socket send errors count : 1
09-01 11:33:21.537  7179  7179 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1936-4\x00 that cannot receive messages
,09-01 11:33:21.538  1026  7272 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-01 11:33:21.538  1026  7272 D WifiMonitor: Dropping event because (p2p0) is stopped
09-01 11:33:21.539  7144  7384 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:21.551  7075  7389 W FormManager: Network not available. Please check & try again.
,09-01 11:33:21.553  3450  3450 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-01 11:33:21.553  3450  3450 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:21.553  3450  3450 I LgeMiscReceiver: networkInfo.isConnected() = false
09-01 11:33:21.558  7075  7390 V FormManager: Network unavailable.
09-01 11:33:21.559  7188  7188 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-01 11:33:21.559  7188  7188 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-01 11:33:21.572  7249  7249 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:33:21
,09-01 11:33:21.573  7075  7390 V FormManager: Network unavailable.
09-01 11:33:21.574  7249  7249 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-01 11:33:21.574  7249  7249 D Weather.Utils: 2 : All the weather widget is gone.
09-01 11:33:21.574  7249  7249 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-01 11:33:21.574  7249  7249 D WeatherAncestor: connectivity changed - connection : true
09-01 11:33:21.574  7249  7249 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3013162b
09-01 11:33:21.575  7249  7249 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-01 11:33:21.575  7249  7249 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-01 11:33:21.575  7249  7249 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-01 11:33:21.575  7249  7249 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-01 11:33:21.576  7249  7249 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:33:21
09-01 11:33:21.599  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:33:21.599  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:33:21.599  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:33:21.599  6933  6933 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-01 11:33:21.602  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:33:21.603  6933  6933 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:33:21.603  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-01 11:33:21.603  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:33:21.603  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:33:21.603  6933  6933 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:33:21.603  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-01 11:33:21.604  6933  6933 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:33:21.612  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:33:21.615  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:33:21.621  7075  7393 W FormManager: Network not available. Please check & try again.
,09-01 11:33:21.623  7075  7394 V FormManager: Network unavailable.
,09-01 11:33:21.624  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:21.627  7179  7179 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:33:21.627  7179  7179 W wpa_supplicant: USIM:  scard_deinit function
09-01 11:33:21.627  1026  7272 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-01 11:33:21.627  1026  7272 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:33:21.627  1026  7272 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-01 11:33:21.628  1026  7272 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-01 11:33:21.628  1026  7272 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:33:21.628  1026  7272 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:33:21.628  1026  1531 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=209161
09-01 11:33:21.629  1026  1531 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=209162
09-01 11:33:21.629  1026  1088 D Tethering: InitialState.processMessage what=4
09-01 11:33:21.629  1026  1531 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=209162  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:33:21.629  1026  1088 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 11:33:21.630  1026  1531 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=209163  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-01 11:33:21.631  1026  1531 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:21.631  1026  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:21.633  7075  7394 V FormManager: Network unavailable.
09-01 11:33:21.648  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:33:21.651  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:33:21.654  7075  7396 W FormManager: Network not available. Please check & try again.
09-01 11:33:21.656  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:21.660  7075  7397 V FormManager: Network unavailable.
,09-01 11:33:21.663  7075  7397 V FormManager: Network unavailable.
09-01 11:33:21.671  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:33:21.671  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-01 11:33:21.673  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:33:21.675  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:33:21.681  4323  7398 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-01 11:33:21.683  4323  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:33:21.683  4323  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:33:21.686  7179  7179 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-01 11:33:21.687  1026  7272 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-01 11:33:21.687  1026  7272 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-TERMINATING 
09-01 11:33:21.687  1026  7272 D WifiMonitor: Disconnecting from the supplicant, no more events
09-01 11:33:21.687  1026  1531 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 33 0
,09-01 11:33:21.715  1026  2036 I art     : Explicit concurrent mark sweep GC freed 80345(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.735ms total 157.166ms
,09-01 11:33:21.729  1026  1989 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7401 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-01 11:33:21.789  1026  1531 D WifiOffDelayIfNotUsed: stopMonitoring
09-01 11:33:21.789  1936  1936 D WfdsService: Supplicant Connection state is changed : false
,09-01 11:33:21.789  1026  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:33:21.789  1026  1531 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:33:21.789  1026  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:33:21.789  1936  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-01 11:33:21.790  1936  2300 D WfdsService: Set the WFDS Monitor: false
09-01 11:33:21.790  1936  2300 D WfdsMonitor: WFDS Monitor is stopped
09-01 11:33:21.792  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:21.792  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-01 11:33:21.794  1026  1026 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-01 11:33:21.795  1026  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-01 11:33:21.795  1026  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-01 11:33:21.795  2503  2503 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:21.796  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:21.797  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:21.833  7401  7401 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-01 11:33:21.833  7401  7401 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-01 11:33:21.840  7401  7401 V [BNRBootReceiver]: Boot Receiver Return
09-01 11:33:21.842  7401  7401 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-01 11:33:21.843  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:21.850  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:33:21.856  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:21.868  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:21.869  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:21.870  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:33:21.874  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:33:21.879  6981  6981 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:33:21.879  6981  6981 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:33:21.879  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:33:21.883  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:33:21.891  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:21.901  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:21.902  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-01 11:33:21.904  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:33:21.911  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:21.918  6981  6981 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-01 11:33:21.918  6981  6981 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-01 11:33:21.918  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:33:21.925  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:33:21.934  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:21.944  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:21.945  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:21.947  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-01 11:33:21.962  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:33:21.968  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:33:21.975  7075  7420 W FormManager: Network not available. Please check & try again.
,09-01 11:33:21.979  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:21.990  7075  7421 V FormManager: Network unavailable.
,09-01 11:33:21.996  7075  7421 V FormManager: Network unavailable.
09-01 11:33:22.006  1026  1776 I ActivityManager: Killing 6959:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-01 11:33:22.038  1026  1042 W libprocessgroup: failed to open /acct/uid_10037/pid_6959/cgroup.procs: No such file or directory
,09-01 11:33:22.052  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:33:22.052  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-01 11:33:22.052  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,09-01 11:33:22.052  6933  6933 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:33:22.053  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:33:22.053  6933  6933 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:33:22.054  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-01 11:33:22.054  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:33:22.054  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:33:22.054  6933  6933 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:33:22.054  6933  6933 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:33:22.061  1026  1415 D PowerManagerServiceEx: acquireWakeLockInternal: lock=126597223, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1026
,09-01 11:33:22.062  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:33:22.063  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:33:22.068  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:33:22.072  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-01 11:33:22.084  4323  7422 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:33:22.084  4323  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:33:22.085  4323  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-01 11:33:22.090  6981  6981 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-01 11:33:22.092  6981  6981 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-01 11:33:22.092  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:33:22.102  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:33:22.113  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:22.118  7075  7425 W FormManager: Network not available. Please check & try again.
,09-01 11:33:22.126  7075  7426 V FormManager: Network unavailable.
09-01 11:33:22.127  2573  2573 D [Concierge]Service: onStartCommand(). Type : 9
09-01 11:33:22.145  7075  7426 V FormManager: Network unavailable.
,09-01 11:33:22.152  7012  7012 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-01 11:33:22.155  7012  7012 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8374
09-01 11:33:22.165  1026  1026 D PowerManagerServiceEx: releaseWakeLockInternal: lock=126597223 [*alarm*], flags=0x0
,09-01 11:33:22.389  6601  7118 D UEI.SmartControl: Internal timer expired: 2
09-01 11:33:22.389  6601  7118 D UEI.SmartControl: unbind internal service
,09-01 11:33:22.454  6601  7112 D serial_port: close(fd = 24)
,09-01 11:33:22.462  6601  7112 I UEI.SmartControl: Serial port is closed.
,09-01 11:33:24.409  1026  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:24.410  1026  2025 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-01 11:33:24.437  1026  1026 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:33:24.437  1026  1026 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:33:24.437  1026  1026 D Ulp_jni : JNI:system_update. Event-4
09-01 11:33:24.438  1026  1088 D BluetoothManagerService: Message: 1
09-01 11:33:24.438  1026  1088 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-01 11:33:24.465  1026  1088 D BluetoothManagerService: Message: 20
09-01 11:33:24.465  1026  1088 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37989cae:true
,09-01 11:33:24.469  7058  7058 D BluetoothAdapterState: make
09-01 11:33:24.474  7058  7058 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-01 11:33:24.474  7058  7058 I bluedroid-qcom: init
09-01 11:33:24.475  7058  7437 I BluetoothAdapterState: Entering OffState
09-01 11:33:24.476  7058  7058 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-01 11:33:24.476  7058  7058 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 11:33:24.476  7058  7058 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 11:33:24.476  7058  7058 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 11:33:24.476  7058  7058 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-01 11:33:24.478  7058  7058 I bluedroid-qcom: get_profile_interface socket
09-01 11:33:24.478  7058  7058 I bluedroid-qcom: get_profile_interface map_client
,09-01 11:33:24.482  7058  7441 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-01 11:33:24.467  7440  7440 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:24.487  7058  7441 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-01 11:33:24.477  7440  7440 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:24.498  1026  1026 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-01 11:33:24.500  1026  1088 D BluetoothManagerService: Message: 40
09-01 11:33:24.500  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-01 11:33:24.501  7058  7073 I bluedroid-qcom: config_hci_snoop_log
09-01 11:33:24.502  1026  1088 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-01 11:33:24.502  1026  1088 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-01 11:33:24.504  7440  7440 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-01 11:33:24.504  7440  7440 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-01 11:33:24.505  7440  7440 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-01 11:33:24.507  7440  7440 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-01 11:33:24.511  7440  7440 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-01 11:33:24.512  7440  7440 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-01 11:33:24.517  7058  7437 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-01 11:33:24.518  1026  1026 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:33:24.519  1026  1026 D BluetoothManagerService: Stored Bluetooth name: G3
09-01 11:33:24.519  7058  7441 D BluetoothAdapterProperties: Name is: G3
09-01 11:33:24.519  7058  7437 D BluetoothAdapterProperties: Setting state to 11
09-01 11:33:24.519  7058  7437 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-01 11:33:24.520  1026  1088 D BluetoothManagerService: Message: 60
09-01 11:33:24.520  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-01 11:33:24.520  1026  1088 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-01 11:33:24.522  7058  7437 I LGBluetoothServiceJni: classInitNative: succeeds
09-01 11:33:24.528  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:33:24.531  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:33:24.534  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:24.536  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:24.537  6933  6933 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-01 11:33:24.545  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:33:24.546  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:24.546  7058  7058 V BluetoothPbapReceiver: ***********state = 11
,09-01 11:33:24.572  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:33:24.572  7058  7437 D BluetoothBondStateMachine: make
,09-01 11:33:24.583  7058  7437 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:24.584  7058  7437 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-01 11:33:24.584  7058  7437 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:24.584  7058  7437 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-01 11:33:24.586  7058  7437 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,09-01 11:33:24.588  7058  7454 I BluetoothBondStateMachine: StableState(): Entering Off State
09-01 11:33:24.592  7058  7437 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:33:24.626  1026  1042 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7459 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-01 11:33:24.631  7058  7437 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:33:24.634  7058  7058 D HeadsetService: Received start request. Starting profile...
09-01 11:33:24.634  7058  7058 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:33:24.634  7058  7058 D LGBluetoothHfpAdapter: Version 1.6
09-01 11:33:24.637  7058  7437 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:33:24.638  7058  7058 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-01 11:33:24.639  7058  7058 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:33:24.639  7058  7058 D HeadsetStateMachine: make
09-01 11:33:24.645  7058  7437 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:33:24.654  7058  7437 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:33:24.660  7058  7437 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:33:24.666  7058  7437 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:33:24.677  7058  7058 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:33:24.677  7058  7058 D LgDataFeature: LgDataFeature() Constructor Done, null
09-01 11:33:24.678  7058  7437 V LGMDMManager: Create singleton instance
09-01 11:33:24.681  7058  7437 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-01 11:33:24.681  7058  7058 D HeadsetStateMachine: max_hf_connections = 1
09-01 11:33:24.681  7058  7058 I bluedroid-qcom: get_profile_interface handsfree
09-01 11:33:24.683  7058  7058 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-01 11:33:24.684   321  1375 V AudioPolicyService: registerClient() client 0xb1023e60, uid 1002
,09-01 11:33:24.684   321   321 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-01 11:33:24.684   321   321 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:33:24.684   321   321 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:33:24.684  7058  7058 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-01 11:33:24.684   321  2145 V AudioFlinger: registerClient() client 0xb1433868, pid 7058
09-01 11:33:24.685  7058  7058 V ToneGenerator: Create Track: 0xb4928080
09-01 11:33:24.685  7058  7058 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-01 11:33:24.685  7058  7058 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-01 11:33:24.684   321  1370 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:24.685   321  1370 V AudioSystem: ioConfigChanged() opening already existing output! 2
,09-01 11:33:24.685   321   321 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:33:24.685   321   321 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-01 11:33:24.685   321   321 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:33:24.685   321   321 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:33:24.685  1848  1864 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:24.685  7058  7058 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-01 11:33:24.685  1848  1864 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:33:24.685  1595  1613 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:24.685  1595  1613 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:33:24.685   321  2144 I AudioFlinger: isAudioPlaybackHookOn() false
09-01 11:33:24.685  3450  3465 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:24.685  3450  3465 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:33:24.686   321  1371 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:33:24.686   321  1371 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:33:24.686  1026  1729 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:24.686  1026  1729 V AudioSystem: ioConfigChanged() opening already existing output! 2
,09-01 11:33:24.686   321  1376 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:33:24.686   321  1376 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-01 11:33:24.686   321  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:33:24.686   321  1376 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:33:24.687  1848  2710 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:33:24.687  3450  3466 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:33:24.687  1848  2710 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:33:24.687  3450  3466 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:33:24.687  1595  2532 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:33:24.687  1595  2532 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:33:24.687  1026  1935 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:33:24.687  1026  1935 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:33:24.687  7058  7073 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:24.687  7058  7073 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-01 11:33:24.687  7058  7073 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:33:24.687  7058  7073 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-01 11:33:24.687  7058  7058 V AudioSystem: getLatency() output 2, latency 50
09-01 11:33:24.687  7058  7058 V AudioSystem: getFrameCount() output 2, frameCount 960
09-01 11:33:24.687  7058  7058 V AudioTrack: createTrack_l() output 2 afLatency 50
09-01 11:33:24.687   321   321 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:33:24.687   321   321 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:33:24.688   321   321 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:33:24.688   321   321 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:33:24.688   321   321 V AudioFlinger: createTrack() lSessionId: 22
09-01 11:33:24.688  7058  7058 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-01 11:33:24.689   321  2145 V AudioFlinger: acquiring 22 from 7058, for 7058
09-01 11:33:24.689   321  2145 V AudioFlinger:  added new entry for 22
,09-01 11:33:24.689  7058  7058 V ToneGenerator: ToneGenerator INIT OK, time: 212233
09-01 11:33:24.689  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:24.689  7058  7470 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-01 11:33:24.689  7058  7470 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:33:24.689  7058  7470 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:33:24.689  7058  7470 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-01 11:33:24.690   321  2144 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7058
09-01 11:33:24.690   321  2144 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-01 11:33:24.690   321  2144 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-01 11:33:24.690   321  2144 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-01 11:33:24.690   321  2144 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-01 11:33:24.690   321  2144 V voice   : voice_set_parameters: exit with code(0)
09-01 11:33:24.690   321  2144 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-01 11:33:24.690  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
,09-01 11:33:24.690   321  2144 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-01 11:33:24.690   321  2144 V msm8974_platform: platform_set_parameters: exit with code(0)
09-01 11:33:24.690   321  2144 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-01 11:33:24.690   321  2144 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-01 11:33:24.690   321  2144 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-01 11:33:24.690  7058  7470 V ToneGenerator: ToneGenerator destructor
09-01 11:33:24.691  7058  7470 V ToneGenerator: stopTone
09-01 11:33:24.691  7058  7470 V ToneGenerator: Delete Track: 0xb4928080
09-01 11:33:24.691  7058  7470 V AudioTrack: ~AudioTrack, releasing session id from 7058 on behalf of 7058
,09-01 11:33:24.691   321  1375 V AudioFlinger: releasing 22 from 7058 for 7058
09-01 11:33:24.691   321  1375 V AudioFlinger:  decremented refcount to 0
09-01 11:33:24.691   321  1375 V AudioFlinger: purging stale effects
09-01 11:33:24.691   321  1375 V AudioPolicyService: AudioCommandThread() adding release output 2
09-01 11:33:24.691   321  1375 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-01 11:33:24.691   321  1375 V AudioFlinger: PlaybackThread::Track destructor
09-01 11:33:24.691   321  1251 V AudioPolicyService: AudioCommandThread() waking up
09-01 11:33:24.691   321  1375 V AudioFlinger: removeClient_l() pid 7058, calling pid 321
09-01 11:33:24.691   321  1251 V AudioPolicyService: AudioCommandThread() processing release output 2
,09-01 11:33:24.691   321  1251 V AudioPolicyManager: releaseOutput() 2
09-01 11:33:24.691   321  1251 V AudioPolicyService: AudioCommandThread() going to sleep
09-01 11:33:24.692  7058  7058 D A2dpService: Received start request. Starting profile...
09-01 11:33:24.692  7058  7058 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 11:33:24.693  7058  7058 V Avrcp   : make
09-01 11:33:24.694  7058  7058 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-01 11:33:24.694  7058  7058 I bluedroid-qcom: get_profile_interface avrcp
09-01 11:33:24.696  1026  1989 W Process : Unable to open /proc/7478/status
09-01 11:33:24.702  7058  7058 V AudioManager: registerRemoteController: size of Media player list: 0
09-01 11:33:24.703  7058  7058 E AudioManager: No RCC entry present to update
09-01 11:33:24.703  7058  7058 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-01 11:33:24.707  7058  7058 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,09-01 11:33:24.708  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-01 11:33:24.708  7058  7058 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-01 11:33:24.711  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-01 11:33:24.797  7459  7459 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-01 11:33:24.797  7459  7459 W LG Account v2.2: No ProfileInfo entries
09-01 11:33:24.798  7459  7459 I LG Account v2.2: isEnabled: false
09-01 11:33:24.798  7459  7459 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-01 11:33:24.798  7459  7459 I Feature : [Lifetracker]Country: EU
09-01 11:33:24.798  7459  7459 I Feature : [Lifetracker]Operator: OPEN
09-01 11:33:24.798  7459  7459 I Feature : [Lifetracker]Ranking support: false
09-01 11:33:24.798  7459  7459 I Feature : [Lifetracker]Comfort support: false
09-01 11:33:24.798  7459  7459 I Feature : [Lifetracker]Accessory: true
09-01 11:33:24.798  7459  7459 I Feature : [Lifetracker]Health device: true
09-01 11:33:24.798  7459  7459 I Feature : [Lifetracker]Extra Pedometer: false
09-01 11:33:24.798  7459  7459 I Feature : [Lifetracker]Blood glucose device: false
09-01 11:33:24.798  7459  7459 I Feature : [Lifetracker]Device Number: 3
,09-01 11:33:24.809  6933  6933 D BluetoothPermissionRequest: onReceive
09-01 11:33:24.812  1026  1767 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:33:24.812  1026  1767 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:33:24.813  6933  6933 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-01 11:33:24.885  1026  1766 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-01 11:33:24.892  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-01 11:33:24.895  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-01 11:33:24.896  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-01 11:33:24.896  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-01 11:33:24.896  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-01 11:33:24.896  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:33:24.896  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-01 11:33:24.896  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-01 11:33:24.896  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-01 11:33:24.896  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:33:24.896  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-01 11:33:24.897  7058  7058 I BluetoothA2dpServiceJni: classInitNative
09-01 11:33:24.897  7058  7058 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:33:24.897  7058  7058 D A2dpStateMachine: make
09-01 11:33:24.899  7058  7058 I bluedroid-qcom: get_profile_interface a2dp
09-01 11:33:24.900  7058  7485 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-01 11:33:24.902  7058  7058 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:33:24.902  7058  7058 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,09-01 11:33:24.903  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:24.904  7058  7484 D A2dpStateMachine: Enter Disconnected: -2
09-01 11:33:24.904  7058  7058 I BluetoothHidServiceJni: classInitNative: succeeds
09-01 11:33:24.905  7058  7058 D HidService: Received start request. Starting profile...
09-01 11:33:24.905  7058  7058 I bluedroid-qcom: get_profile_interface hidhost
09-01 11:33:24.905  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:24.906  7058  7058 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:33:24.907  7058  7058 D HealthService: Received start request. Starting profile...
09-01 11:33:24.910  7058  7058 I bluedroid-qcom: get_profile_interface health
09-01 11:33:24.910  7058  7058 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:33:24.910  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:24.911  7058  7058 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-01 11:33:24.912  7058  7058 D PanService: Received start request. Starting profile...
09-01 11:33:24.912  7058  7058 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 11:33:24.912  7058  7058 I bluedroid-qcom: get_profile_interface pan
09-01 11:33:24.920  7058  7058 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,09-01 11:33:24.920  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:24.922  7058  7058 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-01 11:33:24.934  7058  7058 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:33:24.935  7058  7058 D BtGatt.GattService: Received start request. Starting profile...
09-01 11:33:24.935  7058  7058 D BtGatt.GattService: start()
09-01 11:33:24.935  7058  7058 I bluedroid-qcom: get_profile_interface gatt
,09-01 11:33:24.936  7058  7058 D BtGatt.AdvertiseManager: advertise manager created
09-01 11:33:24.947  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
,09-01 11:33:24.951  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:24.952  7058  7058 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-01 11:33:24.954  7058  7058 V BluetoothMapService: BluetoothMapBinder()
09-01 11:33:24.956  7058  7058 D BluetoothMapService: Received start request. Starting profile...
09-01 11:33:24.956  7058  7058 D BluetoothMapService: start()
09-01 11:33:24.967  7058  7058 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-01 11:33:24.967  7058  7058 D BluetoothMapEmailAppObserver: createReceiver()
,09-01 11:33:24.969  7058  7058 D BluetoothMapEmailAppObserver: initObservers()
09-01 11:33:24.970  7058  7058 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-01 11:33:24.993  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:24.993  7058  7058 D HeadsetStateMachine: Proxy object connected
,09-01 11:33:24.995  7058  7058 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-01 11:33:24.996  7058  7058 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-01 11:33:25.001  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:33:25.001  7058  7470 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-01 11:33:25.002  7058  7470 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 11:33:25.003  7058  7470 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-01 11:33:25.005  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-01 11:33:25.009  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-01 11:33:25.012  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-01 11:33:25.013  7058  7058 V PanService: [BTUI] SIM Extra State :ABSENT
09-01 11:33:25.016  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:33:25.019  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-01 11:33:25.020  7058  7058 V BluetoothMapService: Handler(): got msg=1
,09-01 11:33:25.021  7058  7437 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-01 11:33:25.021  7058  7437 I bluedroid-qcom: enable
09-01 11:33:25.021  7058  7437 I bt_hci_bdroid: init
09-01 11:33:25.023  7058  7495 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-01 11:33:25.023  7058  7495 I bt-btu  : btu_task pending for preload complete event
09-01 11:33:25.023  7058  7437 I bt_vendor: bt-vendor : init
09-01 11:33:25.023  7058  7437 I bt_vendor: bt-vendor : get_bt_soc_type
09-01 11:33:25.023  7058  7437 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-01 11:33:25.023  7058  7437 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-01 11:33:25.023  7058  7437 D bt_userial_mct: userial_init
09-01 11:33:25.024  7058  7437 D bt_hci_bdroid: set_power 1
09-01 11:33:25.024  7058  7437 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-01 11:33:25.024  7058  7437 I bt_vendor: Starting hciattach daemon
09-01 11:33:25.024  7058  7437 I bt_vendor: try to set true
09-01 11:33:25.025  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:25.027  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:33:25.027  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:33:25.027  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:33:25.027  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:25.027  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-01 11:33:25.017  7498  7498 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:25.017  7498  7498 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:25.071  7499  7499 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-01 11:33:25.209  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-01 11:33:25.224  7506  7506 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-01 11:33:25.264  7508  7508 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 11:33:25.277  7509  7509 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-01 11:33:25.291  7510  7510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 11:33:25.307  7511  7511 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-01 11:33:25.333  7513  7513 I libmdmdetect: ESOC framework not supported
,09-01 11:33:25.334  7513  7513 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-01 11:33:25.342  7513  7513 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-01 11:33:25.342  7513  7513 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-01 11:33:25.342  7513  7513 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-01 11:33:25.342  7513  7513 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-01 11:33:25.342  7513  7513 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-01 11:33:25.342  7513  7513 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-01 11:33:25.342  7513  7513 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-01 11:33:25.379  7513  7514 E QC-QMI  : qmi_client [7513] 14: failed to locate client data
09-01 11:33:25.380   473   473 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-01 11:33:25.380   473   473 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-01 11:33:25.422  7515  7515 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-01 11:33:25.434  1026  1537 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
09-01 11:33:25.438  7516  7516 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-01 11:33:25.443  7281  7301 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-01 11:33:25.477  7058  7437 I bt_vendor: bluetooth satus is on
,09-01 11:33:25.477  7058  7437 D bt_hci_bdroid: preload
09-01 11:33:25.477  7058  7497 D bt_userial_mct: userial_open(port:0)
09-01 11:33:25.477  7058  7497 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-01 11:33:25.481  7058  7497 I bt_vendor: Done intiailizing UART
09-01 11:33:25.482  7058  7497 I bt_vendor: Done intiailizing UART
09-01 11:33:25.482  7058  7497 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-01 11:33:25.482  7058  7497 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-01 11:33:25.482  7058  7495 I bt-btu  : btu_task received preload complete event
09-01 11:33:25.482  7058  7520 D bt_userial_mct: Entering userial_read_thread()
09-01 11:33:25.483  7058  7495 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-01 11:33:25.483  7058  7495 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-01 11:33:25.486  7058  7495 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_HCI
09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_GAP
,09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_PAN
,09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_SDP
,09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_GATT
,09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_SMP
,09-01 11:33:25.494  7058  7495 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-01 11:33:25.495  7058  7495 I         : BTE_InitTraceLevels -- TRC_BTIF
09-01 11:33:25.605  7058  7495 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-01 11:33:25.605  7058  7495 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ad061 
09-01 11:33:25.605  7058  7495 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ad061 
,09-01 11:33:25.636  7058  7441 E bt-btif : Calling BTA_HhEnable
09-01 11:33:25.636  7058  7441 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-01 11:33:25.637  7058  7441 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-01 11:33:25.640  1026  1026 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:33:25.641  1026  1026 D BluetoothManagerService: Stored Bluetooth name: G3
09-01 11:33:25.641  7058  7441 D BluetoothAdapterProperties: Name is: G3
09-01 11:33:25.643  7058  7441 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:33:25.643  7058  7441 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:33:25.643  7058  7441 D bt_hci_bdroid: postload
09-01 11:33:25.644  7058  7441 D bte_conf: Device ID record 1 : primary
09-01 11:33:25.644  7058  7441 D bte_conf:   vendorId            = 00c4
09-01 11:33:25.644  7058  7441 D bte_conf:   vendorIdSource      = 0001
09-01 11:33:25.644  7058  7441 D bte_conf:   product             = 13a1
09-01 11:33:25.644  7058  7441 D bte_conf:   version             = 1000
09-01 11:33:25.644  7058  7441 D bte_conf:   clientExecutableURL = 
,09-01 11:33:25.644  7058  7441 D bte_conf:   serviceDescription  = 
09-01 11:33:25.644  7058  7441 D bte_conf:   documentationURL    = 
09-01 11:33:25.645  7058  7497 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:33:25.645  7058  7441 D bte_conf: bte_load_did_conf no section named DID2.
09-01 11:33:25.650  7058  7437 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-01 11:33:25.650  7058  7437 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:33:25.650  7058  7437 D BluetoothAdapterProperties: State =  11
09-01 11:33:25.650  7058  7437 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-01 11:33:25.650  7058  7437 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-01 11:33:25.651  7058  7437 D BluetoothAdapterProperties: Setting state to 12
09-01 11:33:25.651  7058  7437 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 11:33:25.657  7058  7441 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-01 11:33:25.647  7528  7528 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:25.659  1026  1088 D BluetoothManagerService: Message: 60
09-01 11:33:25.659  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-01 11:33:25.659  1026  1088 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-01 11:33:25.659  1026  1088 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:33:25.660  7058  7437 I BluetoothAdapterState: Entering On State
09-01 11:33:25.647  7528  7528 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:25.667  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:33:25.690  7058  7441 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:33:25.690  7058  7441 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-01 11:33:25.693  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:25.693  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:25.693  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:25.693  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:33:25.693  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:25.693  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:25.693  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:25.693  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:33:25.700  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:25.706  7058  7437 D LGBluetoothServiceAdapter: [BTUI] OnState
09-01 11:33:25.706  7058  7437 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-01 11:33:25.706  7058  7437 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-01 11:33:25.711  7058  7437 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-01 11:33:25.712  7058  7437 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-01 11:33:25.715  1026  1026 D BluetoothA2dp: Proxy object connected
09-01 11:33:25.723  7058  7495 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-01 11:33:25.723  7058  7495 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-01 11:33:25.723  7058  7495 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,09-01 11:33:25.726  7058  7495 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-01 11:33:25.726  7058  7495 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-01 11:33:25.726  7058  7495 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-01 11:33:25.726  7058  7441 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 11:33:25.727  7058  7497 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:33:25.745  7058  7497 D bt_hci_bdroid: Used up Tx Cmd credits
,09-01 11:33:25.748  6933  6958 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 11:33:25.763  7533  7533 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-01 11:33:25.768  7058  7520 E bt_mct  : hci lib postload completed
09-01 11:33:25.774  6933  7400 D BluetoothPan: onBluetoothStateChange on: true
09-01 11:33:25.774  6933  7400 D BluetoothPan: onBluetoothStateChange call bindService
09-01 11:33:25.786  7058  7495 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:33:25.786  7058  7495 W bt-smp  : Plain text(LSB ~ MSB) = b3 99 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:33:25.786  1026  1088 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:33:25.786  7058  7495 W bt-smp  : Encrypted text(LSB ~ MSB) = 19 13 89 64 ea 7e 3d 8d 7c 39 6a 8c d6 0a e6 23 
09-01 11:33:25.786  7058  7495 W bt-btm  : Stopping oneshot timer
,09-01 11:33:25.791  1026  1026 D BluetoothHeadset: Proxy object connected
09-01 11:33:25.792  6933  6933 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:33:25.792  6933  6933 D PanProfile: Bluetooth service connected
09-01 11:33:25.792  1848  2711 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:33:25.799  1848  1848 D BluetoothHeadset: Proxy object connected
09-01 11:33:25.799  1848  1864 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:33:25.801  1848  1848 D BluetoothHeadset: Proxy object connected
09-01 11:33:25.801  6933  6957 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 11:33:25.808  6933  6933 D BluetoothMap: Proxy object connected
09-01 11:33:25.808  6933  6933 D MapProfile: Bluetooth service connected
09-01 11:33:25.808  6933  6933 D BluetoothMap: getConnectedDevices()
09-01 11:33:25.809  7058  7074 V BluetoothMapService: getConnectedDevices()
09-01 11:33:25.810  1848  2430 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:33:25.812  1848  1848 D BluetoothHeadset: Proxy object connected
09-01 11:33:25.812  6933  7400 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 11:33:25.815  7058  7495 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:33:25.815  7058  7495 W bt-smp  : Plain text(LSB ~ MSB) = bb f2 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:33:25.815  7058  7495 W bt-smp  : Encrypted text(LSB ~ MSB) = 70 28 ff b4 ba ee 55 ec c2 47 cd 35 b9 43 77 4f 
09-01 11:33:25.815  7058  7495 W bt-btm  : Stopping oneshot timer
,09-01 11:33:25.818  1026  1088 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-01 11:33:25.818  1026  1088 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-01 11:33:25.820  6933  6933 D BluetoothInputDevice: Proxy object connected
09-01 11:33:25.820  6933  6933 D HidProfile: Bluetooth service connected
09-01 11:33:25.821  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:25.822  1936  2121 D LGBluetoothAPIService: Message: 1
09-01 11:33:25.822  1936  2121 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-01 11:33:25.826  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-01 11:33:25.830  6832  6832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-01 11:33:25.832  1026  1026 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-01 11:33:25.832  1026  1088 D BluetoothManagerService: Message: 40
09-01 11:33:25.833  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-01 11:33:25.835  7058  7495 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:33:25.835  7058  7495 W bt-smp  : Plain text(LSB ~ MSB) = d7 5f 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:33:25.835  7058  7495 W bt-smp  : Encrypted text(LSB ~ MSB) = 3c 92 ff 89 99 ac 6b 96 a2 94 51 f0 d8 99 af f3 
09-01 11:33:25.835  7058  7495 W bt-btm  : Stopping oneshot timer
09-01 11:33:25.838  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:25.838  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:25.838  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:25.838  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:33:25.838  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:25.838  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:25.838  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:25.838  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:33:25.840  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:33:25.842  1936  2121 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-01 11:33:25.842  7058  7058 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:25.842  7058  7058 D BluetoothMapService: STATE_ON
09-01 11:33:25.844  7058  7058 D LGBluetoothAPIServer: [BTUI] onCreate()
09-01 11:33:25.844  7058  7495 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:33:25.844  7058  7495 W bt-smp  : Plain text(LSB ~ MSB) = be 31 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:33:25.844  7058  7495 W bt-smp  : Encrypted text(LSB ~ MSB) = c8 35 ac aa 67 3e 5d 50 5b 9b 83 9f 1f 9b 4c 10 
09-01 11:33:25.844  7058  7495 W bt-btm  : Stopping oneshot timer
09-01 11:33:25.845  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:25.845  7058  7058 D LGBluetoothAPIServer: [BTUI] onBind()
09-01 11:33:25.846  1936  1936 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-01 11:33:25.846  1936  2121 D LGBluetoothAPIService: Message: 100
,09-01 11:33:25.846  1936  2121 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-01 11:33:25.846  7058  7058 V BluetoothMapService: Handler(): got msg=1
09-01 11:33:25.847  7058  7058 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-01 11:33:25.853  7058  7552 D BluetoothMapMasInstance: MAS initSocket()
09-01 11:33:25.854  7058  7495 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:33:25.854  7058  7495 W bt-smp  : Plain text(LSB ~ MSB) = 8d d3 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:33:25.854  7058  7495 W bt-smp  : Encrypted text(LSB ~ MSB) = 5d 41 39 6c ac 13 af 6c 6a 58 a6 a1 b2 f1 eb fc 
09-01 11:33:25.854  7058  7552 D BluetoothMapMasInstance:   masId = 00
09-01 11:33:25.854  7058  7552 D BluetoothMapMasInstance:   msgTypes = 0e
09-01 11:33:25.854  7058  7552 D BluetoothMapMasInstance:   masName = SMS/MMS
09-01 11:33:25.854  7058  7552 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-01 11:33:25.854  7058  7495 W bt-btm  : Stopping oneshot timer
,09-01 11:33:25.855  1026  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:25.856  6933  6933 D LocalBluetoothProfileManager: Adding local A2DP profile
09-01 11:33:25.858  7058  7552 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:33:25.859  7058  7552 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-01 11:33:25.859  7058  7552 V BluetoothMapMasInstance: Succeed to create listening socket 
09-01 11:33:25.859  7058  7552 D BluetoothMapMasInstance: Accepting socket connection...
09-01 11:33:25.861  7058  7441 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:33:25.861  7058  7441 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-01 11:33:25.862  1026  1088 D BluetoothManagerService: Message: 30
09-01 11:33:25.863  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:25.865  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:25.868  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:25.868  7058  7058 V BluetoothPbapService: Pbap Service onCreate
,09-01 11:33:25.868  7058  7058 V BluetoothPbapService: Starting PBAP service
09-01 11:33:25.871  7058  7058 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-01 11:33:25.871  7058  7058 V BluetoothPbapService: Pbap Service onBind
09-01 11:33:25.873  7058  7058 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:25.873  7058  7058 V BluetoothPbapService: state: 12
09-01 11:33:25.873  6933  6933 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-01 11:33:25.873  7058  7058 V BluetoothPbapService: Handler(): got msg=1
09-01 11:33:25.874  7058  7058 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-01 11:33:25.875  7058  7554 V BluetoothPbapService: Pbap Service initSocket
09-01 11:33:25.876  1026  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:25.876  1026  1088 D BluetoothManagerService: Message: 30
09-01 11:33:25.876  7058  7554 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:33:25.878  7058  7554 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-01 11:33:25.878  7058  7554 V BluetoothPbapService: Succeed to create listening socket 
09-01 11:33:25.878  7058  7554 V BluetoothPbapService: Accepting socket connection...
09-01 11:33:25.881  6933  6933 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-01 11:33:25.882  6933  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-01 11:33:25.886  6933  6933 D BluetoothA2dp: Proxy object connected
09-01 11:33:25.887  6933  6933 D A2dpProfile: Bluetooth service connected
09-01 11:33:25.888  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:33:25.888  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:25.888  7058  7058 V BluetoothPbapReceiver: ***********state = 12
09-01 11:33:25.890  6933  6933 D BluetoothPbap: Proxy object connected
09-01 11:33:25.890  6933  6933 D PbapServerProfile: Bluetooth service connected
09-01 11:33:25.891  6933  6933 D BluetoothHeadset: Proxy object connected
09-01 11:33:25.891  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:33:25.892  2209  2209 D c       : Getting all permits...
09-01 11:33:25.892  2209  2209 D a       : Opening database...
,09-01 11:33:25.896  2209  2209 D a       : Opening database auth.proximity.permit_store...
09-01 11:33:25.896  6933  6933 D HeadsetProfile: Bluetooth service connected
09-01 11:33:25.897  2209  2209 D a       : Closing database...
09-01 11:33:25.905  6933  6933 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:33:25.912  6933  6933 D BluetoothPermissionRequest: onReceive
09-01 11:33:25.915  6933  6933 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-01 11:33:25.916  6933  6933 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:33:25.920  7058  7058 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-01 11:33:25.922  7058  7058 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-01 11:33:25.930  7058  7058 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-01 11:33:25.956  7058  7058 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-01 11:33:25.956  7058  7058 V BtOppService: onCreate
,09-01 11:33:25.962  7058  7058 V BluetoothOppNotification: send message
09-01 11:33:25.968  7058  7058 V BtOppService: Starting RfcommListener
,09-01 11:33:25.975  7058  7058 D BluetoothOppPreference: Dumping Names:  
09-01 11:33:25.975  7058  7058 D BluetoothOppPreference: {}
09-01 11:33:25.975  7058  7058 D BluetoothOppPreference: Dumping Channels:  
09-01 11:33:25.975  7058  7058 D BluetoothOppPreference: {}
09-01 11:33:25.976  7058  7058 V BtOppService: onStartCommand
09-01 11:33:25.982  7058  7559 V BtOppService: Deleted complete outbound shares, number =  0
,09-01 11:33:25.983  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:25.984  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-01 11:33:25.985  7058  7562 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:33:25.986  7058  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:33:25.987  7058  7559 V BtOppService: Deleted complete inbound failed shares, number = 0
09-01 11:33:25.987  7058  7559 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-01 11:33:25.988  7058  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9c195c4 on behalf of 
09-01 11:33:25.989  7058  7058 V BluetoothOppNotification: new notify threadi!
09-01 11:33:25.991  7058  7058 V BluetoothOppNotification: send delay message
09-01 11:33:25.992  7058  7058 V BtOppService: start RfcommListener
09-01 11:33:25.992  7058  7563 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-01 11:33:25.994  7058  7559 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ca6acad on behalf of 
09-01 11:33:25.994  7058  7562 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-01 11:33:25.996  7058  7563 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16626be2 on behalf of 
09-01 11:33:25.999  7058  7058 V BtOppService: RfcommListener started
09-01 11:33:25.999  7058  7058 V BtOppService: ContentObserver received notification
09-01 11:33:26.000  7058  7563 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-01 11:33:26.001  7058  7564 V BtOppRfcommListener: Starting RFCOMM listener....
09-01 11:33:26.001  7058  7058 V BtOppService: ContentObserver received notification
09-01 11:33:26.002  1026  1568 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:26.004  7058  7564 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:33:26.005  7058  7565 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:33:26.005  7058  7565 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:33:26.006  7058  7564 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-01 11:33:26.006  7058  7564 V BtOppRfcommListener: Started RFCOMM listener....
09-01 11:33:26.006  7058  7564 I BtOppRfcommListener: Accept thread started.
09-01 11:33:26.006  7058  7564 V BtOppRfcommListener: Accepting connection...
09-01 11:33:26.007  7058  7565 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1792fb73 on behalf of 
09-01 11:33:26.008  7058  7565 V BluetoothOppNotification: update too frequent, put in queue
,09-01 11:33:26.011  7058  7565 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-01 11:33:26.011  7058  7563 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-01 11:33:26.013  7058  7563 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@244a30 on behalf of 
09-01 11:33:26.014  7058  7563 V BluetoothOppNotification: outbound: succ-0  fail-0
09-01 11:33:26.016  7058  7563 V BluetoothOppNotification: outbound notification was removed.
09-01 11:33:26.016  7058  7563 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:33:26.017  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:26.017  7058  7058 V BluetoothFtpService: Ftp Service onCreate
09-01 11:33:26.017  7058  7058 I BluetoothFtpService: Ftp Service onCreate
09-01 11:33:26.018  7058  7058 V BluetoothFtpService: Ftp Service onStartCommand
09-01 11:33:26.018  7058  7058 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:26.018  7058  7058 V BluetoothFtpService: Starting Listening on sockets
09-01 11:33:26.018  7058  7563 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9bf642e on behalf of 
09-01 11:33:26.018  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:33:26.018  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:33:26.018  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:33:26.018  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:26.018  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-01 11:33:26.019  7058  7058 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-01 11:33:26.020  7058  7058 V BluetoothFtpService: Handler(): got msg=1
,09-01 11:33:26.021  7058  7563 V BluetoothOppNotification: inbound: succ-0  fail-0
09-01 11:33:26.023  7058  7058 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-01 11:33:26.023  7058  7058 V BluetoothFtpService: Ftp Service initSocket
09-01 11:33:26.023  7058  7563 V BluetoothOppNotification: inbound notification was removed.
09-01 11:33:26.023  7058  7563 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:33:26.025  7058  7563 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2097dbcf on behalf of 
09-01 11:33:26.029  1026  1776 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:26.030  7058  7058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:33:26.031  7058  7058 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,09-01 11:33:26.032  7058  7058 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-01 11:33:26.033  7058  7566 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-01 11:33:26.051  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:26.051  7058  7058 V BluetoothSapService: Sap Service onCreate
,09-01 11:33:26.054  7058  7058 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:26.054  7058  7058 V BluetoothSapService: state: 12
09-01 11:33:26.055  7058  7058 V BluetoothSapService: Starting SAP server process
09-01 11:33:26.058  7058  7058 V BluetoothSapService: SAP Service startRfcommListenerThread
09-01 11:33:26.047  7567  7567 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:26.047  7567  7567 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:26.062  7058  7568 V BluetoothSapService: Sap Service initRfcommSocket
09-01 11:33:26.062  1026  1568 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:26.063  7058  7568 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:33:26.065  7058  7568 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-01 11:33:26.065  7058  7568 V BluetoothSapService: Succeed to create listening socket 
09-01 11:33:26.065  7058  7568 V BluetoothSapService: Accepting socket connection...
,09-01 11:33:26.072  7567  7567 V BT_SAP  : Event pipe created
,09-01 11:33:26.072  7567  7567 V BT_SAP  : create_server_socket qcom.sap.server
09-01 11:33:26.072  7567  7567 V BT_SAP  : created socket fd 6
09-01 11:33:26.114  1026  1415 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2699482a type 2 when 213645 com.google.android.gms} when 213645
,09-01 11:33:26.121   317  7570 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-01 11:33:26.122  1026  1086 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-01 11:33:26.410  1026  1529 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:26.410  1026  1529 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:33:26.430  1026  1531 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
09-01 11:33:26.430  1026  1531 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-01 11:33:26.453  1026  1729 I ActivityManager: Killing 6345:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-01 11:33:26.493  1026  1042 W libprocessgroup: failed to open /acct/uid_10011/pid_6345/cgroup.procs: No such file or directory
,09-01 11:33:26.530  1026  1084 W ProcessCpuTracker: Skipping unknown process pid 7535
09-01 11:33:26.531  1026  1084 W ProcessCpuTracker: Skipping unknown process pid 7536
09-01 11:33:26.531  1026  1084 W ProcessCpuTracker: Skipping unknown process pid 7544
09-01 11:33:26.531  1026  1084 W ProcessCpuTracker: Skipping unknown process pid 7553
09-01 11:33:26.532  1026  1084 W ProcessCpuTracker: Skipping unknown process pid 7577
,09-01 11:33:26.992  7058  7058 V BluetoothOppNotification: new notify threadi!
,09-01 11:33:26.993  7058  7058 V BluetoothOppNotification: send delay message
,09-01 11:33:27.005  7058  7580 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-01 11:33:27.009  7058  7580 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f6065eb on behalf of 
09-01 11:33:27.014  7058  7580 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-01 11:33:27.019  7058  7580 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-01 11:33:27.020  7058  7580 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9db2f48 on behalf of 
09-01 11:33:27.021  7058  7580 V BluetoothOppNotification: outbound: succ-0  fail-0
09-01 11:33:27.022  7058  7580 V BluetoothOppNotification: outbound notification was removed.
09-01 11:33:27.024  7058  7580 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:33:27.026  7058  7580 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@146b41e1 on behalf of 
09-01 11:33:27.027  7058  7580 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-01 11:33:27.030  7058  7580 V BluetoothOppNotification: inbound notification was removed.
,09-01 11:33:27.030  7058  7580 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:33:27.032  7058  7580 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34c3cb06 on behalf of 
09-01 11:33:27.458  1026  1916 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:27.459  1026  1916 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1dbcb61b mBinding = false
,09-01 11:33:27.487  1026  1026 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:33:27.487  1026  1026 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:33:27.487  1026  1026 D Ulp_jni : JNI:system_update. Event-4
,09-01 11:33:27.490  1026  1088 D BluetoothManagerService: Message: 2
09-01 11:33:27.491  1026  1088 D BluetoothManagerService: Sending off request.
09-01 11:33:27.492  7058  7543 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,09-01 11:33:27.493  7058  7437 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-01 11:33:27.493  7058  7437 D BluetoothAdapterProperties: Setting state to 13
09-01 11:33:27.493  7058  7437 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 11:33:27.494  7058  7437 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 11:33:27.494  7058  7437 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-01 11:33:27.496  7058  7441 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:33:27.499  7058  7437 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-01 11:33:27.502  7058  7437 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-01 11:33:27.507  7058  7554 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:33:27.508  7058  7564 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:33:27.508  7058  7566 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:33:27.509  7058  7568 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:33:27.510  7058  7552 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-01 11:33:27.510  7058  7552 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:33:27.510  7058  7552 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-01 11:33:27.510  7058  7552 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-01 11:33:27.510  7058  7552 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-01 11:33:27.510  7058  7552 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-01 11:33:27.510  7058  7552 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-01 11:33:27.510  7058  7552 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-01 11:33:27.510  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-01 11:33:27.510  7058  7495 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-01 11:33:27.512  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:33:27.512  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:33:27.512  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:33:27.512  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:33:27.512  7058  7495 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:33:27.512  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:33:27.512  7058  7495 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:33:27.512  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:33:27.512  7058  7495 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:33:27.512  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-01 11:33:27.512  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-01 11:33:27.512  7058  7495 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:33:27.522  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:27.522  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:27.522  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:27.522  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:27.522  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:33:27.522  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:33:27.522  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:27.522  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:27.522  6832  6832 V io.,jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:33:27.528  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:27.528  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:27.532  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:27.533  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:27.533  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:27.533  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:27.533  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:33:27.533  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:33:27.533  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:27.533  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:27.533  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:33:27.534  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:33:27.534  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:27.536  1026  1088 D BluetoothManagerService: Message: 60
09-01 11:33:27.536  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-01 11:33:27.536  1026  1088 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-01 11:33:27.540  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:27.543  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:33:27.547  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:27.548  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:33:27.553  7058  7058 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:27.553  7058  7058 D BluetoothMapService: STATE_TURNING_OFF
09-01 11:33:27.553  7058  7058 V BluetoothMapService: Handler(): got msg=4
09-01 11:33:27.553  7058  7058 D BluetoothMapService: MAP Service closeService in
09-01 11:33:27.554  7058  7058 D BluetoothMapMasInstance: MAP Service shutdown
09-01 11:33:27.554  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:33:27.554  7058  7058 V BluetoothMapService: MAP Service closeService out
09-01 11:33:27.555  7058  7058 V BtOppService: Receiver DISABLED_ACTION 
09-01 11:33:27.556  7058  7058 I BtOppRfcommListener: stopping Accept Thread
09-01 11:33:27.556  7058  7058 V BtOppRfcommListener: close mBtServerSocket
09-01 11:33:27.556  7058  7564 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 11:33:27.556  7058  7058 V BtOppRfcommListener: waiting for thread to terminate
09-01 11:33:27.557  7058  7058 V BtOppRfcommListener: done waiting for thread to terminate
09-01 11:33:27.559  6933  6933 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-01 11:33:27.571  6933  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-01 11:33:27.575  7058  7058 V BtOppService: onDestroy
09-01 11:33:27.577  7058  7058 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-01 11:33:27.582  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:33:27.582  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:27.582  7058  7058 V BluetoothPbapReceiver: ***********state = 13
09-01 11:33:27.583  7058  7058 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-01 11:33:27.587  7058  7058 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:27.587  7058  7058 V BluetoothPbapService: state: 13
09-01 11:33:27.587  7058  7058 V BluetoothPbapService: Pbap Service closeService in
09-01 11:33:27.591  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:33:27.592  7058  7058 V BluetoothPbapService: successfully stopped pbap service
09-01 11:33:27.592  7058  7058 V BluetoothPbapService: Pbap Service closeService out
09-01 11:33:27.593  7058  7058 V BluetoothPbapService: Pbap Service onDestroy
09-01 11:33:27.593  7058  7058 V BluetoothPbapService: Pbap Service closeService in
09-01 11:33:27.593  7058  7058 V BluetoothPbapService: Pbap Service closeService out
09-01 11:33:27.593  7058  7058 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-01 11:33:27.612  6933  6933 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:33:27.623  6933  6933 D BluetoothPbap: Proxy object disconnected
09-01 11:33:27.623  6933  6933 D PbapServerProfile: Bluetooth service disconnected
09-01 11:33:27.628  6933  6933 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-01 11:33:27.636  6933  6933 D BluetoothPermissionRequest: onReceive
,09-01 11:33:27.636  6933  6933 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-01 11:33:27.645  6933  6933 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-01 11:33:27.652  7058  7058 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-01 11:33:27.652  7058  7058 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-01 11:33:27.653  7058  7058 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-01 11:33:27.659  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:33:27.659  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-01 11:33:27.661  7058  7058 V BluetoothFtpService: Ftp Service onStartCommand
09-01 11:33:27.661  7058  7058 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:27.661  7058  7058 V BluetoothFtpService: Ftp Service closeService
09-01 11:33:27.662  7058  7058 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-01 11:33:27.665  7058  7058 V BluetoothFtpService: successfully stopped ftp service
09-01 11:33:27.666  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:33:27.666  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:33:27.666  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:33:27.666  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:27.666  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-01 11:33:27.667  7058  7058 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-01 11:33:27.668  7058  7058 V BluetoothFtpService: Ftp Service onDestroy
09-01 11:33:27.668  7058  7058 V BluetoothFtpService: Ftp Service closeService
09-01 11:33:27.677  7058  7058 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:27.677  7058  7058 V BluetoothSapService: state: 13
09-01 11:33:27.677  7058  7058 V BluetoothSapService: Stopping SAP server process
09-01 11:33:27.680  7058  7058 V BluetoothSapService: Sap Service closeSapService in
09-01 11:33:27.680  7058  7058 V BluetoothSapService: Close listen Socket : 
09-01 11:33:27.680  7058  7058 V BluetoothSapService: Close rfcomm Socket : 
,09-01 11:33:27.680  7058  7058 V BluetoothSapService: Close sapd  Socket : 
,09-01 11:33:27.685  7058  7058 V BluetoothSapService: Sap Service closeSapService out
09-01 11:33:27.685  7058  7058 V BluetoothSapService: Sap Service onDestroy
09-01 11:33:27.685  7058  7058 V BluetoothSapService: Sap Service closeSapService in
09-01 11:33:27.685  7058  7058 V BluetoothSapService: Close listen Socket : 
09-01 11:33:27.686  7058  7058 V BluetoothSapService: Close rfcomm Socket : 
09-01 11:33:27.686  7058  7058 V BluetoothSapService: Close sapd  Socket : 
09-01 11:33:27.686  7058  7058 V BluetoothSapService: Sap Service closeSapService out
09-01 11:33:28.501  7058  7441 D bt_hci_bdroid: cleanup
,09-01 11:33:28.512  7058  7497 I bt_lpm  : LPM is already off!!!
,09-01 11:33:28.513  7058  7520 I bt_userial_mct: exiting userial_read_thread
,09-01 11:33:28.513  7058  7520 D bt_userial_mct: Leaving userial_evt_read_thread()
09-01 11:33:28.514  7058  7495 W bt-btif : ag scb idx 1 not allocated
09-01 11:33:28.514  7058  7495 E bt-btif : BTA AG is already disabled, ignoring ...
09-01 11:33:28.514  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:33:28.514  7058  7495 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:33:28.514  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,09-01 11:33:28.514  7058  7495 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
09-01 11:33:28.514  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:33:28.514  7058  7495 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:33:28.514  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:33:28.515  7058  7495 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:33:28.515  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:33:28.515  7058  7495 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:33:28.515  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-01 11:33:28.515  7058  7495 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:33:28.515  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-01 11:33:28.515  7058  7495 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:33:28.515  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-01 11:33:28.515  7058  7495 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:33:28.515  7058  7495 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-01 11:33:28.515  7058  7495 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:33:28.515  7058  7495 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-01 11:33:28.518  7058  7441 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,09-01 11:33:28.529  7058  7497 I bt_vendor: hw_epilog_process
09-01 11:33:28.530  7058  7441 D bt_hci_bdroid: cleanup Finalizing cleanup
09-01 11:33:28.530  7058  7441 D bt_userial_mct: userial_close
09-01 11:33:28.530  7058  7441 E bt_userial_mct: pthread_join() FAILED result:3
09-01 11:33:28.530  7058  7441 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-01 11:33:28.536  7058  7441 D bt_hci_bdroid: set_power 0
09-01 11:33:28.536  7058  7441 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-01 11:33:28.536  7058  7441 I bt_vendor: bluetooth satus is on
09-01 11:33:28.536  7058  7441 I bt_vendor: bt-vendor : resetting BT status
09-01 11:33:28.536  7058  7441 I bt_vendor: Starting hciattach daemon
09-01 11:33:28.536  7058  7441 I bt_vendor: try to set false
,09-01 11:33:28.537  7058  7441 I bt_vendor: Starting hciattach daemon
09-01 11:33:28.537  7058  7441 I bt_vendor: try to set false
09-01 11:33:28.539  7058  7441 I bt_vendor: cleanup
,09-01 11:33:28.543  7058  7495 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-01 11:33:28.545  7058  7441 I GKI_LINUX: GKI_exit_task 0 done
09-01 11:33:28.545  7058  7441 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-01 11:33:28.547  7058  7437 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-01 11:33:28.554  7058  7058 D HeadsetService: Received stop request...Stopping profile...
,09-01 11:33:28.559  7058  7058 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:33:28.559  7058  7058 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:33:28.559  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:28.561  1848  1848 D BluetoothHeadset: Proxy object disconnected
09-01 11:33:28.561  1848  1848 D BluetoothHeadset: Proxy object disconnected
09-01 11:33:28.562  1848  1848 D BluetoothHeadset: Proxy object disconnected
09-01 11:33:28.562  7058  7470 D HeadsetStateMachine: Exit Disconnected: -1
09-01 11:33:28.563  1026  1026 D BluetoothHeadset: Proxy object disconnected
09-01 11:33:28.563  1026  1026 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-01 11:33:28.564  7058  7437 D BluetoothAdapterState: Stopping profile services that were post enabled
09-01 11:33:28.565  7058  7058 D A2dpService: Received stop request...Stopping profile...
09-01 11:33:28.565  7058  7484 D A2dpStateMachine: Exit Disconnected: -1
09-01 11:33:28.567  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-01 11:33:28.571  7058  7058 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-01 11:33:28.572  7058  7058 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:33:28.572  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:28.574  1026  1026 D BluetoothA2dp: Proxy object disconnected
09-01 11:33:28.574  1026  1026 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-01 11:33:28.574  7058  7058 D HidService: Received stop request...Stopping profile...
09-01 11:33:28.574  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:28.577  7058  7058 D HealthService: Received stop request...Stopping profile...
09-01 11:33:28.577  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:28.579  7058  7058 D PanService: Received stop request...Stopping profile...
,09-01 11:33:28.582  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:28.584  7058  7058 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 11:33:28.585  7058  7058 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 11:33:28.585  7058  7058 D BtGatt.GattService: stop()
09-01 11:33:28.585  7058  7058 D BtGatt.AdvertiseManager: advertise clients cleared
09-01 11:33:28.586  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:28.587  7058  7058 D BluetoothMapService: Received stop request...Stopping profile...
09-01 11:33:28.587  7058  7058 D BluetoothMapService: stop()
09-01 11:33:28.588  7058  7058 D BluetoothMapEmailAppObserver: deinitObservers()
09-01 11:33:28.588  7058  7058 D BluetoothMapEmailAppObserver: removeReceiver()
09-01 11:33:28.589  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3013162b
09-01 11:33:28.590  7058  7058 D HeadsetStateMachine: Unbinding service...
09-01 11:33:28.592  7058  7058 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:33:28.592  7058  7058 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:33:28.592  7058  7058 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:33:28.592  7058  7058 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:33:28.592  7058  7058 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 11:33:28.592  7058  7058 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 11:33:28.592  7058  7058 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-01 11:33:28.593  7058  7058 I BluetoothA2dpServiceJni: cleanupNative
,09-01 11:33:28.597  7058  7485 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-01 11:33:28.601  7058  7058 I GKI_LINUX: GKI_exit_task 2 done
09-01 11:33:28.601  7058  7058 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-01 11:33:28.601  7058  7058 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 11:33:28.601  7058  7058 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:33:28.602  7058  7058 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 11:33:28.602  7058  7058 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:33:28.602  7058  7058 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:33:28.602  7058  7058 V BluetoothMapService: Handler(): got msg=4
09-01 11:33:28.602  7058  7058 D BluetoothMapService: MAP Service closeService in
09-01 11:33:28.602  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:33:28.602  7058  7058 V BluetoothMapService: MAP Service closeService out
09-01 11:33:28.603  7058  7437 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-01 11:33:28.603  7058  7437 D BluetoothAdapterProperties: Setting state to 10
09-01 11:33:28.603  7058  7437 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-01 11:33:28.604  7058  7058 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 11:33:28.604  7058  7058 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 11:33:28.605  1026  1088 D BluetoothManagerService: Message: 60
09-01 11:33:28.606  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-01 11:33:28.606  1026  1088 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-01 11:33:28.606  1026  1088 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 11:33:28.609  7058  7437 I BluetoothAdapterState: Entering OffState
09-01 11:33:28.611  7058  7058 D BluetoothMapService: cleanup()
09-01 11:33:28.611  7058  7058 D BluetoothMapService: MAP Service closeService in
09-01 11:33:28.611  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-01 11:33:28.611  7058  7058 V BluetoothMapService: MAP Service closeService out
09-01 11:33:28.612  6933  6957 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 11:33:28.613  6933  6957 D BluetoothPan: onBluetoothStateChange on: false
09-01 11:33:28.613  1026  1088 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:33:28.614  6933  6957 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:33:28.614  1848  2711 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:33:28.617  1848  1864 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:33:28.617  6933  6957 D BluetoothMap: onBluetoothStateChange: up=false
,09-01 11:33:28.620  6933  6957 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:33:28.620  1848  1863 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 11:33:28.622  6933  6957 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 11:33:28.623  1026  1088 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-01 11:33:28.623  1026  1088 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-01 11:33:28.625  1026  1088 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-01 11:33:28.625  1026  1088 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-01 11:33:28.625  1026  1088 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1dbcb61b mBinding = false
09-01 11:33:28.626  1026  1088 D BluetoothManagerService: Sending unbind request.
09-01 11:33:28.631  7058  7441 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-01 11:33:28.633  7058  7058 I GKI_LINUX: GKI_exit_task 1 done
09-01 11:33:28.633  7058  7058 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-01 11:33:28.634  7058  7058 I BluetoothServiceJni: cleanupNative: return from cleanup
09-01 11:33:28.634  7058  7058 I art     : --- WEIRD: removing null entry 248
09-01 11:33:28.634  7058  7058 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-01 11:33:28.634  7058  7058 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-01 11:33:28.636  7058  7058 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-01 11:33:28.637  1026  1088 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-01 11:33:28.639  7058  7058 I art     : System.exit called, status: 0
09-01 11:33:28.639  7058  7058 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-01 11:33:28.659   321  1375 V AudioFlinger: 7058 died, releasing its sessions
09-01 11:33:28.659   321  1375 V AudioFlinger:  pid 1848 @ 0
09-01 11:33:28.659   321  1375 V AudioFlinger:  pid 3450 @ 1
09-01 11:33:28.659   321  1375 V AudioFlinger:  pid 3450 @ 2
,09-01 11:33:28.663  1936  1936 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-01 11:33:28.663  1936  2121 D LGBluetoothAPIService: Message: 101
09-01 11:33:28.664  1936  2121 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-01 11:33:28.664  1936  2121 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-01 11:33:28.664  1936  2121 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-01 11:33:28.666  6933  6933 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-01 11:33:28.675  1026  1767 I ActivityManager: Process com.android.bluetooth (pid 7058) has died
09-01 11:33:28.675  1026  1767 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-01 11:33:28.675  1026  1767 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,09-01 11:33:28.683  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:28.684  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:33:28.685  1936  2121 D LGBluetoothAPIService: Message: 2
09-01 11:33:28.685  1936  2121 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-01 11:33:28.686  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:28.687  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:28.693  6933  6933 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-01 11:33:28.693  6933  6933 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-01 11:33:28.708  6933  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-01 11:33:28.714  1595  1595 D BluetoothAdapter: 946697181: getState() :  mService = null. Returning STATE_OFF
09-01 11:33:28.714  1595  1595 D BluetoothAdapter: 946697181: getState() :  mService = null. Returning STATE_OFF
09-01 11:33:28.775  1026  2025 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7627 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-01 11:33:28.776  6933  6933 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:33:28.830  7627  7627 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-01 11:33:28.831  7627  7627 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:33:28.831  7627  7627 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,09-01 11:33:28.832  7627  7627 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-01 11:33:28.850  7627  7627 D BluetoothAdapterApp: Loading JNI Library
,09-01 11:33:28.880  7627  7627 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@26f8e3b3 Instance Count = 1
,09-01 11:33:28.884  7627  7627 D BluetoothAdapterApp: onCreate
09-01 11:33:28.903  7627  7627 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-01 11:33:28.903  7627  7627 D ProfileConfigQcom: Adding HeadsetService
,09-01 11:33:28.903  7627  7627 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-01 11:33:28.903  7627  7627 D ProfileConfigQcom: Adding A2dpService
,09-01 11:33:28.903  7627  7627 D ProfileConfigQcom: [BTUI] HidService is supported
09-01 11:33:28.903  7627  7627 D ProfileConfigQcom: Adding HidService
09-01 11:33:28.904  7627  7627 D ProfileConfigQcom: [BTUI] HealthService is supported
,09-01 11:33:28.904  7627  7627 D ProfileConfigQcom: Adding HealthService
,09-01 11:33:28.904  7627  7627 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-01 11:33:28.905  7627  7627 D ProfileConfigQcom: [BTUI] PanService is supported
09-01 11:33:28.905  7627  7627 D ProfileConfigQcom: Adding PanService
,09-01 11:33:28.905  7627  7627 D ProfileConfigQcom: [BTUI] GattService is supported
09-01 11:33:28.905  7627  7627 D ProfileConfigQcom: Adding GattService
09-01 11:33:28.905  7627  7627 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,09-01 11:33:28.905  7627  7627 D ProfileConfigQcom: Adding BluetoothMapService
09-01 11:33:28.906  7627  7627 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-01 11:33:28.907  7627  7627 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-01 11:33:28.907  7627  7627 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:28.908  7627  7627 V BluetoothPbapReceiver: ***********state = 10
,09-01 11:33:28.909  7627  7627 V LGMDMManagerInternal: Create singleton instance
09-01 11:33:28.964  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:33:28.964  7627  7627 D LGBluetoothAPIServer: [BTUI] onCreate()
09-01 11:33:28.964  7627  7627 D LGBluetoothAPIServer: [BTUI] onBind()
09-01 11:33:28.967  1936  1936 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,09-01 11:33:28.967  1936  2121 D LGBluetoothAPIService: Message: 100
09-01 11:33:28.967  1936  2121 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-01 11:33:28.974  6933  6933 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-01 11:33:28.987  6933  6933 D BluetoothPermissionRequest: onReceive
,09-01 11:33:28.991  6933  6933 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-01 11:33:28.991  6933  6933 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-01 11:33:28.996  6933  6933 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:33:29.004  7627  7627 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-01 11:33:29.017  7627  7627 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:33:29.024  7627  7627 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:33:29.025  7627  7627 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:33:29.026  7627  7627 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:33:29.029  7627  7627 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:29.029  7627  7627 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-01 11:33:29.036  7029  7029 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-01 11:33:30.552  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:33:30.552  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:33:33.568  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:33:33.569  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33a35def added. We now have 6 listener(s)
09-01 11:33:33.569  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:33:33.579  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:33.579  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@190800fc added. We now have 7 listener(s)
09-01 11:33:33.579  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:33.580  6832  6909 I System.out: IsBluetoothEnabled
09-01 11:33:33.581  1026  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:33.581  1026  2036 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-01 11:33:33.581  1026  1088 D BluetoothManagerService: Message: 2
09-01 11:33:33.585  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:33.586  1026  1729 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:33.587  1026  1729 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-01 11:33:33.603  1026  1026 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:33:33.604  1026  1026 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:33:33.604  1026  1026 D Ulp_jni : JNI:system_update. Event-4
,09-01 11:33:33.607  1026  1088 D BluetoothManagerService: Message: 1
09-01 11:33:33.607  1026  1088 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-01 11:33:33.634  1026  1088 D BluetoothManagerService: Message: 20
09-01 11:33:33.635  1026  1088 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@efeb282:true
,09-01 11:33:33.638  7627  7627 D BluetoothAdapterState: make
09-01 11:33:33.643  7627  7627 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-01 11:33:33.643  7627  7627 I bluedroid-qcom: init
09-01 11:33:33.644  7627  7659 I BluetoothAdapterState: Entering OffState
09-01 11:33:33.645  7627  7627 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-01 11:33:33.645  7627  7627 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 11:33:33.645  7627  7627 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 11:33:33.645  7627  7627 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 11:33:33.645  7627  7627 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-01 11:33:33.647  7627  7627 I bluedroid-qcom: get_profile_interface socket
09-01 11:33:33.647  7627  7627 I bluedroid-qcom: get_profile_interface map_client
,09-01 11:33:33.652  7627  7663 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-01 11:33:33.654  7627  7663 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-01 11:33:33.647  7662  7662 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:33.647  7662  7662 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:33.663  7662  7662 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-01 11:33:33.663  7662  7662 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-01 11:33:33.664  7662  7662 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-01 11:33:33.670  1026  1026 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-01 11:33:33.670  1026  1088 D BluetoothManagerService: Message: 40
09-01 11:33:33.671  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-01 11:33:33.671  7627  7643 I bluedroid-qcom: config_hci_snoop_log
09-01 11:33:33.673  1026  1088 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-01 11:33:33.673  1026  1088 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-01 11:33:33.674  7662  7662 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-01 11:33:33.677  1026  1026 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:33:33.678  1026  1026 D BluetoothManagerService: Stored Bluetooth name: G3
,09-01 11:33:33.683  7662  7662 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-01 11:33:33.683  7662  7662 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-01 11:33:33.693  7627  7663 D BluetoothAdapterProperties: Name is: G3
,09-01 11:33:33.699  7627  7659 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-01 11:33:33.699  7627  7659 D BluetoothAdapterProperties: Setting state to 11
09-01 11:33:33.699  7627  7659 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-01 11:33:33.701  7627  7659 I LGBluetoothServiceJni: classInitNative: succeeds
09-01 11:33:33.704  1026  1088 D BluetoothManagerService: Message: 60
09-01 11:33:33.704  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-01 11:33:33.704  1026  1088 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-01 11:33:33.709  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:33:33.712  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:33:33.722  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:33:33.727  6933  6933 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-01 11:33:33.729  7627  7659 D BluetoothBondStateMachine: make
09-01 11:33:33.735  7627  7627 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:33:33.735  7627  7659 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:33.735  7627  7627 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:33.735  7627  7627 V BluetoothPbapReceiver: ***********state = 11
,09-01 11:33:33.736  7627  7677 I BluetoothBondStateMachine: StableState(): Entering Off State
09-01 11:33:33.735  7627  7659 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-01 11:33:33.736  7627  7659 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:33.736  7627  7659 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-01 11:33:33.737  7627  7659 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,09-01 11:33:33.740  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:33:33.743  7627  7659 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:33:33.753  7627  7659 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:33:33.755  7627  7627 D HeadsetService: Received start request. Starting profile...
09-01 11:33:33.756  7627  7627 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:33:33.756  7627  7627 D LGBluetoothHfpAdapter: Version 1.6
09-01 11:33:33.759  7627  7627 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-01 11:33:33.761  7627  7627 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 11:33:33.761  7627  7627 D HeadsetStateMachine: make
09-01 11:33:33.764  7627  7659 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:33:33.769  7627  7659 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:33:33.775  7627  7659 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:33:33.781  6933  6933 D BluetoothPermissionRequest: onReceive
09-01 11:33:33.782  7627  7659 E BluetoothAdapterService: File transfer profiles supported!!
,09-01 11:33:33.791  7627  7659 E BluetoothAdapterService: File transfer profiles supported!!
09-01 11:33:33.793  6933  6933 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:33:33.802  7627  7627 D LgDataFeature: LgDataFeature() Constructor: none
09-01 11:33:33.802  7627  7627 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:33:33.808  7627  7627 D HeadsetStateMachine: max_hf_connections = 1
09-01 11:33:33.808  7627  7627 I bluedroid-qcom: get_profile_interface handsfree
09-01 11:33:33.809  7627  7659 V LGMDMManager: Create singleton instance
09-01 11:33:33.810  7627  7627 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-01 11:33:33.812   321  2144 V AudioPolicyService: registerClient() client 0xb04104c0, uid 1002
09-01 11:33:33.812   321  1375 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,09-01 11:33:33.812   321  1375 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:33:33.812   321  1375 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:33:33.812  7627  7627 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-01 11:33:33.812  7627  7659 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-01 11:33:33.813   321  2145 V AudioFlinger: registerClient() client 0xb14331f0, pid 7627
09-01 11:33:33.813   321  1370 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:33.813   321  1370 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:33:33.814  7627  7627 V ToneGenerator: Create Track: 0xb4928080
09-01 11:33:33.814  7627  7627 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-01 11:33:33.814  7627  7627 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-01 11:33:33.814  1595  1613 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:33.814  1595  1613 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:33:33.814  1848  1863 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:33.814  1848  1863 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:33:33.814   321  1376 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:33:33.814  3450  3465 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:33.814  3450  3465 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:33:33.814   321  1376 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-01 11:33:33.814   321  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:33:33.814   321  1376 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:33:33.814  7627  7644 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:33.814   321  1371 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:33:33.814  7627  7644 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-01 11:33:33.814   321  1371 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:33:33.815  1026  1971 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-01 11:33:33.815  1026  1971 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-01 11:33:33.815   321  2144 I AudioFlinger: isAudioPlaybackHookOn() false
09-01 11:33:33.816   321  1376 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-01 11:33:33.816  1026  2025 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:33:33.816  1026  2025 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:33:33.816   321  1376 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-01 11:33:33.816   321  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-01 11:33:33.816   321  1376 V AudioPolicyManagerEx: getOutput() returns output 2
09-01 11:33:33.816  7627  7676 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:33:33.816  7627  7676 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-01 11:33:33.816  7627  7627 V AudioSystem: getLatency() output 2, latency 50
09-01 11:33:33.816  7627  7627 V AudioSystem: getFrameCount() output 2, frameCount 960
09-01 11:33:33.816  7627  7627 V AudioTrack: createTrack_l() output 2 afLatency 50
09-01 11:33:33.816  3450  3466 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:33:33.816  3450  3466 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:33:33.817  1595  2532 V AudioSystem: ioConfigChan,ged() event 0, ioHandle 4
09-01 11:33:33.817  1595  2532 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-01 11:33:33.817  1848  2430 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-01 11:33:33.817  1848  2430 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-01 11:33:33.818   321  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:33:33.818   321  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:33:33.818   321  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-01 11:33:33.818   321  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-01 11:33:33.818   321  2145 V AudioFlinger: createTrack() lSessionId: 23
09-01 11:33:33.819  7627  7627 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-01 11:33:33.819   321  2145 V AudioFlinger: acquiring 23 from 7627, for 7627
09-01 11:33:33.819   321  2145 V AudioFlinger:  added new entry for 23
09-01 11:33:33.819  7627  7627 V ToneGenerator: ToneGenerator INIT OK, time: 221364
09-01 11:33:33.819  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:33.820  7627  7683 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-01 11:33:33.820  7627  7683 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-01 11:33:33.820  7627  7683 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-01 11:33:33.821  7627  7683 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-01 11:33:33.821  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:33.821   321   321 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7627
09-01 11:33:33.821   321   321 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-01 11:33:33.821   321   321 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-01 11:33:33.821   321   321 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-01 11:33:33.821   321   321 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-01 11:33:33.821   321   321 V voice   : voice_set_parameters: exit with code(0)
09-01 11:33:33.821   321   321 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-01 11:33:33.821   321   321 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-01 11:33:33.822   321   321 V msm8974_platform: platform_set_parameters: exit with code(0)
09-01 11:33:33.822   321   321 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-01 11:33:33.822   321   321 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-01 11:33:33.822   321   321 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-01 11:33:33.822  7627  7683 V ToneGenerator: ToneGenerator destructor
09-01 11:33:33.822  7627  7683 V ToneGenerator: stopTone
09-01 11:33:33.822  7627  7683 V ToneGenerator: Delete Track: 0xb4928080
09-01 11:33:33.822  7627  7627 D A2dpService: Received start request. Starting profile...
09-01 11:33:33.823  7627  7627 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 11:33:33.824  7627  7627 V Avrcp   : make
09-01 11:33:33.824  1026  1042 W Process : Unable to open /proc/7684/status
09-01 11:33:33.824  7627  7627 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-01 11:33:33.824  7627  7627 I bluedroid-qcom: get_profile_interface avrcp
09-01 11:33:33.824  7627  7683 V AudioTrack: ~AudioTrack, releasing session id from 7627 on behalf of 7627
09-01 11:33:33.824   321  1375 V AudioPolicyService: AudioCommandThread() adding release output 2
09-01 11:33:33.824   321  2145 V AudioFlinger: releasing 23 from 7627 for 7627
09-01 11:33:33.824   321  1375 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-01 11:33:33.824   321  2145 V AudioFlinger:  decremented refcount to 0
09-01 11:33:33.824   321  2145 V AudioFlinger: purging stale effects
09-01 11:33:33.824   321  1375 V AudioFlinger: PlaybackThread::Track destructor
09-01 11:33:33.824,   321  1375 V AudioFlinger: removeClient_l() pid 7627, calling pid 321
09-01 11:33:33.824   321  1251 V AudioPolicyService: AudioCommandThread() waking up
09-01 11:33:33.824   321  1251 V AudioPolicyService: AudioCommandThread() processing release output 2
09-01 11:33:33.825   321  1251 V AudioPolicyManager: releaseOutput() 2
09-01 11:33:33.825   321  1251 V AudioPolicyService: AudioCommandThread() going to sleep
09-01 11:33:33.832  7627  7627 V AudioManager: registerRemoteController: size of Media player list: 0
,09-01 11:33:33.835  7627  7627 E AudioManager: No RCC entry present to update
09-01 11:33:33.835  7627  7627 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 11:33:33.838  7627  7627 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-01 11:33:33.840  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-01 11:33:33.840  7627  7627 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-01 11:33:33.843  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-01 11:33:33.948  1026  2025 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:33:33.948  1026  2025 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:33:34.021  1026  1935 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-01 11:33:34.031  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-01 11:33:34.044  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-01 11:33:34.046  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,09-01 11:33:34.046  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-01 11:33:34.047  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-01 11:33:34.047  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:33:34.047  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
,09-01 11:33:34.048  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-01 11:33:34.048  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-01 11:33:34.048  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,09-01 11:33:34.048  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-01 11:33:34.050  7627  7627 I BluetoothA2dpServiceJni: classInitNative
09-01 11:33:34.050  7627  7627 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:33:34.051  7627  7627 D A2dpStateMachine: make
,09-01 11:33:34.052  7627  7627 I bluedroid-qcom: get_profile_interface a2dp
09-01 11:33:34.052  7627  7689 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-01 11:33:34.055  7627  7627 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-01 11:33:34.055  7627  7627 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-01 11:33:34.056  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:34.056  7627  7688 D A2dpStateMachine: Enter Disconnected: -2
09-01 11:33:34.057  7627  7627 I BluetoothHidServiceJni: classInitNative: succeeds
09-01 11:33:34.059  7627  7627 D HidService: Received start request. Starting profile...
09-01 11:33:34.059  7627  7627 I bluedroid-qcom: get_profile_interface hidhost
09-01 11:33:34.059  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:34.060  7627  7627 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:33:34.062  7627  7627 D HealthService: Received start request. Starting profile...
,09-01 11:33:34.063  7627  7627 I bluedroid-qcom: get_profile_interface health
09-01 11:33:34.063  7627  7627 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-01 11:33:34.063  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:34.064  7627  7627 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-01 11:33:34.066  7627  7627 D PanService: Received start request. Starting profile...
09-01 11:33:34.066  7627  7627 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 11:33:34.066  7627  7627 I bluedroid-qcom: get_profile_interface pan
09-01 11:33:34.075  7627  7627 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-01 11:33:34.076  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
,09-01 11:33:34.079  7627  7627 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-01 11:33:34.094  7627  7627 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 11:33:34.095  7627  7627 D BtGatt.GattService: Received start request. Starting profile...
09-01 11:33:34.095  7627  7627 D BtGatt.GattService: start()
09-01 11:33:34.095  7627  7627 I bluedroid-qcom: get_profile_interface gatt
09-01 11:33:34.096  7627  7627 D BtGatt.AdvertiseManager: advertise manager created
09-01 11:33:34.101  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:34.103  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:34.104  7627  7627 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,09-01 11:33:34.105  7627  7627 V BluetoothMapService: BluetoothMapBinder()
09-01 11:33:34.106  7627  7627 D BluetoothMapService: Received start request. Starting profile...
,09-01 11:33:34.106  7627  7627 D BluetoothMapService: start()
,09-01 11:33:34.110  7627  7627 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-01 11:33:34.110  7627  7627 D BluetoothMapEmailAppObserver: createReceiver()
09-01 11:33:34.112  7627  7627 D BluetoothMapEmailAppObserver: initObservers()
09-01 11:33:34.112  7627  7627 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-01 11:33:34.124  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:34.125  7627  7627 D HeadsetStateMachine: Proxy object connected
09-01 11:33:34.126  7627  7627 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-01 11:33:34.126  7627  7627 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-01 11:33:34.129  7627  7683 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-01 11:33:34.131  7627  7683 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 11:33:34.132  7627  7683 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-01 11:33:34.138  7627  7627 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-01 11:33:34.144  7627  7627 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:33:34.147  7627  7627 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:33:34.152  7627  7627 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:33:34.152  7627  7627 V PanService: [BTUI] SIM Extra State :ABSENT
,09-01 11:33:34.157  7627  7627 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-01 11:33:34.161  7627  7627 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-01 11:33:34.161  7627  7627 V BluetoothMapService: Handler(): got msg=1
09-01 11:33:34.163  7627  7659 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-01 11:33:34.163  7627  7659 I bluedroid-qcom: enable
09-01 11:33:34.163  7627  7699 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-01 11:33:34.163  7627  7699 I bt-btu  : btu_task pending for preload complete event
09-01 11:33:34.163  7627  7659 I bt_hci_bdroid: init
09-01 11:33:34.164  7627  7627 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:33:34.166  7627  7659 I bt_vendor: bt-vendor : init
09-01 11:33:34.166  7627  7659 I bt_vendor: bt-vendor : get_bt_soc_type
09-01 11:33:34.167  7627  7659 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-01 11:33:34.167  7627  7659 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-01 11:33:34.167  7627  7659 D bt_userial_mct: userial_init
09-01 11:33:34.167  7627  7659 D bt_hci_bdroid: set_power 1
09-01 11:33:34.167  7627  7659 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-01 11:33:34.167  7627  7659 I bt_vendor: Starting hciattach daemon
09-01 11:33:34.167  7627  7659 I bt_vendor: try to set true
09-01 11:33:34.170  7627  7627 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:33:34.170  7627  7627 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:33:34.170  7627  7627 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:33:34.170  7627  7627 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:34.170  7627  7627 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-01 11:33:34.157  7702  7702 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:34.157  7702  7702 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:34.214  7706  7706 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-01 11:33:34.287  7712  7712 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-01 11:33:34.301  7713  7713 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-01 11:33:34.327  7715  7715 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 11:33:34.340  7716  7716 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-01 11:33:34.353  7717  7717 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 11:33:34.365  7718  7718 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-01 11:33:34.405  7720  7720 I libmdmdetect: ESOC framework not supported
,09-01 11:33:34.408  7720  7720 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-01 11:33:34.418  7720  7720 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-01 11:33:34.418  7720  7720 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-01 11:33:34.418  7720  7720 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-01 11:33:34.418  7720  7720 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-01 11:33:34.418  7720  7720 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-01 11:33:34.418  7720  7720 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-01 11:33:34.418  7720  7720 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-01 11:33:34.464  7720  7722 E QC-QMI  : qmi_client [7720] 15: failed to locate client data
,09-01 11:33:34.465   473   473 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-01 11:33:34.465   473   473 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-01 11:33:34.517  7723  7723 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-01 11:33:34.530  7724  7724 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-01 11:33:34.571  7627  7659 I bt_vendor: bluetooth satus is on
09-01 11:33:34.571  7627  7659 D bt_hci_bdroid: preload
09-01 11:33:34.572  7627  7701 D bt_userial_mct: userial_open(port:0)
09-01 11:33:34.572  7627  7701 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-01 11:33:34.575  7627  7701 I bt_vendor: Done intiailizing UART
,09-01 11:33:34.576  7627  7701 I bt_vendor: Done intiailizing UART
,09-01 11:33:34.576  7627  7701 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-01 11:33:34.576  7627  7701 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-01 11:33:34.577  7627  7699 I bt-btu  : btu_task received preload complete event
09-01 11:33:34.577  7627  7726 D bt_userial_mct: Entering userial_read_thread()
09-01 11:33:34.577  7627  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,09-01 11:33:34.577  7627  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f,
,09-01 11:33:34.579  7627  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_HCI
09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_AVDT,
,09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_A2D
,09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_BTM,
,09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_GAP
,09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_SDP
,09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_BTAPP,
09-01 11:33:34.583  7627  7699 I         : BTE_InitTraceLevels -- TRC_BTIF
09-01 11:33:34.688  7627  7699 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
09-01 11:33:34.689  7627  7699 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ad061 
09-01 11:33:34.689  7627  7699 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ad061 
,09-01 11:33:34.735  7627  7663 E bt-btif : Calling BTA_HhEnable
09-01 11:33:34.735  7627  7663 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-01 11:33:34.737  7627  7663 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-01 11:33:34.738  1026  1026 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-01 11:33:34.739  1026  1026 D BluetoothManagerService: Stored Bluetooth name: G3
09-01 11:33:34.739  7627  7663 D BluetoothAdapterProperties: Name is: G3
09-01 11:33:34.740  7627  7663 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:33:34.741  7627  7663 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:33:34.741  7627  7663 D bt_hci_bdroid: postload
09-01 11:33:34.742  7627  7663 D bte_conf: Device ID record 1 : primary
09-01 11:33:34.742  7627  7663 D bte_conf:   vendorId            = 00c4
09-01 11:33:34.742  7627  7663 D bte_conf:   vendorIdSource      = 0001
09-01 11:33:34.742  7627  7663 D bte_conf:   product             = 13a1
09-01 11:33:34.742  7627  7663 D bte_conf:   version             = 1000
09-01 11:33:34.742  7627  7663 D bte_conf:   clientExecutableURL = 
09-01 11:33:34.742  7627  7663 D bte_conf:   serviceDescription  = 
09-01 11:33:34.742  7627  7663 D bte_conf:   documentationURL    = 
09-01 11:33:34.743  7627  7701 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:33:34.743  7627  7663 D bte_conf: bte_load_did_conf no section named DID2.
09-01 11:33:34.747  7627  7659 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-01 11:33:34.747  7627  7659 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:33:34.748  7627  7659 D BluetoothAdapterProperties: State =  11
09-01 11:33:34.748  7627  7659 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-01 11:33:34.748  7627  7659 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-01 11:33:34.748  7627  7659 D BluetoothAdapterProperties: Setting state to 12
09-01 11:33:34.748  7627  7659 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 11:33:34.737  7731  7731 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:34.747  7731  7731 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:34.758  1026  1088 D BluetoothManagerService: Message: 60
09-01 11:33:34.758  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-01 11:33:34.759  1026  1088 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-01 11:33:34.759  1026  1088 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:33:34.760  7627  7659 I BluetoothAdapterState: Entering On State
09-01 11:33:34.762  7627  7663 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-01 11:33:34.773  7627  7701 D bt_hci_bdroid: Used up Tx Cmd credits
09-01 11:33:34.781  7627  7726 E bt_mct  : hci lib postload completed
,09-01 11:33:34.796  7627  7663 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:33:34.796  7627  7663 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-01 11:33:34.801  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:34.801  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:34.801  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:34.801  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:33:34.801  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:34.801  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:34.801  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:34.801  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:33:34.814  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:33:34.822  7627  7659 D LGBluetoothServiceAdapter: [BTUI] OnState
09-01 11:33:34.822  7627  7659 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-01 11:33:34.822  7627  7659 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-01 11:33:34.822  1026  1026 D BluetoothA2dp: Proxy object connected
09-01 11:33:34.825  7627  7659 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-01 11:33:34.825  7627  7659 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-01 11:33:34.836  7627  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-01 11:33:34.836  7627  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-01 11:33:34.836  7627  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,09-01 11:33:34.839  7627  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-01 11:33:34.839  7627  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-01 11:33:34.840  7627  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-01 11:33:34.840  7627  7663 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 11:33:34.861  7736  7736 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-01 11:33:34.867  6933  6957 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 11:33:34.869  6933  6958 D BluetoothPan: onBluetoothStateChange on: true
09-01 11:33:34.869  6933  6958 D BluetoothPan: onBluetoothStateChange call bindService
09-01 11:33:34.872  1026  1088 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:33:34.874  7627  7699 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:33:34.874  7627  7699 W bt-smp  : Plain text(LSB ~ MSB) = 66 1b 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:33:34.874  7627  7699 W bt-smp  : Encrypted text(LSB ~ MSB) = bc ef 5d 60 55 79 4f 37 66 27 50 cd 35 df 06 db 
09-01 11:33:34.874  7627  7699 W bt-btm  : Stopping oneshot timer
09-01 11:33:34.876  1026  1026 D BluetoothHeadset: Proxy object connected
,09-01 11:33:34.879  6933  6957 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:33:34.883  1848  2711 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:33:34.885  1848  1848 D BluetoothHeadset: Proxy object connected
09-01 11:33:34.886  1848  1863 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:33:34.889  6933  6933 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:33:34.889  6933  6933 D PanProfile: Bluetooth service connected
,09-01 11:33:34.891  7627  7699 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:33:34.891  7627  7699 W bt-smp  : Plain text(LSB ~ MSB) = 1d 58 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:33:34.891  7627  7699 W bt-smp  : Encrypted text(LSB ~ MSB) = 27 df 0d be 3f da 3f 6f 3b 09 70 5b e9 74 7b 32 
09-01 11:33:34.892  7627  7699 W bt-btm  : Stopping oneshot timer
09-01 11:33:34.892  1848  1848 D BluetoothHeadset: Proxy object connected
09-01 11:33:34.893  6933  6958 D BluetoothMap: onBluetoothStateChange: up=true
09-01 11:33:34.905  6933  7400 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:33:34.905  6933  6933 D BluetoothHeadset: Proxy object connected
09-01 11:33:34.905  6933  6933 D HeadsetProfile: Bluetooth service connected
,09-01 11:33:34.910  6933  6933 D BluetoothMap: Proxy object connected
09-01 11:33:34.910  6933  6933 D MapProfile: Bluetooth service connected
09-01 11:33:34.910  6933  6933 D BluetoothMap: getConnectedDevices()
09-01 11:33:34.911  7627  7644 V BluetoothMapService: getConnectedDevices()
09-01 11:33:34.912  7627  7699 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:33:34.912  7627  7699 W bt-smp  : Plain text(LSB ~ MSB) = 5f 80 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:33:34.912  7627  7699 W bt-smp  : Encrypted text(LSB ~ MSB) = be 71 0e 0c a5 16 bb 4d 2c 32 19 cb e3 9b a5 ac 
09-01 11:33:34.912  7627  7699 W bt-btm  : Stopping oneshot timer
09-01 11:33:34.912  1848  2710 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 11:33:34.913  6933  6933 D BluetoothA2dp: Proxy object connected
09-01 11:33:34.913  6933  6933 D A2dpProfile: Bluetooth service connected
09-01 11:33:34.916  1848  1848 D BluetoothHeadset: Proxy object connected
09-01 11:33:34.916  6933  6958 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 11:33:34.919  1026  1088 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-01 11:33:34.919  6933  6933 D BluetoothInputDevice: Proxy object connected
09-01 11:33:34.919  6933  6933 D HidProfile: Bluetooth service connected
09-01 11:33:34.920  1026  1026 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,09-01 11:33:34.920  1026  1088 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-01 11:33:34.921  1026  1088 D BluetoothManagerService: Message: 40
09-01 11:33:34.921  1026  1088 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-01 11:33:34.922  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-01 11:33:34.924  7627  7699 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:33:34.924  7627  7699 W bt-smp  : Plain text(LSB ~ MSB) = 39 08 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:33:34.924  7627  7699 W bt-smp  : Encrypted text(LSB ~ MSB) = 64 5a 3b c1 96 9e f6 c6 fd 05 4b 57 8b 7c a0 6f 
09-01 11:33:34.924  7627  7699 W bt-btm  : Stopping oneshot timer
09-01 11:33:34.924  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:34.926  1936  2121 D LGBluetoothAPIService: Message: 1
09-01 11:33:34.926  1936  2121 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-01 11:33:34.927  1936  2121 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-01 11:33:34.927  1936  2121 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-01 11:33:34.929  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:34.934  7627  7699 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-01 11:33:34.934  7627  7699 W bt-smp  : Plain text(LSB ~ MSB) = 7e c9 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-01 11:33:34.934  7627  7699 W bt-smp  : Encrypted text(LSB ~ MSB) = 33 b2 d6 86 67 ce f7 b2 58 81 97 a1 18 a3 2e 7f 
09-01 11:33:34.934  7627  7699 W bt-btm  : Stopping oneshot timer
,09-01 11:33:34.937  7627  7627 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:34.937  7627  7627 D BluetoothMapService: STATE_ON
09-01 11:33:34.941  6933  6933 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-01 11:33:34.942  6933  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-01 11:33:34.953  6933  6933 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:33:34.954  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:34.954  7627  7627 V BluetoothPbapService: Pbap Service onCreate
09-01 11:33:34.954  7627  7627 V BluetoothPbapService: Starting PBAP service
09-01 11:33:34.956  7627  7627 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-01 11:33:34.956  7627  7627 V BluetoothMapService: Handler(): got msg=1
09-01 11:33:34.956  7627  7627 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-01 11:33:34.957  7627  7627 V BluetoothPbapService: Pbap Service onBind
09-01 11:33:34.958  7627  7754 D BluetoothMapMasInstance: MAS initSocket()
09-01 11:33:34.958  7627  7754 D BluetoothMapMasInstance:   masId = 00
09-01 11:33:34.958  7627  7754 D BluetoothMapMasInstance:   msgTypes = 0e
09-01 11:33:34.958  7627  7754 D BluetoothMapMasInstance:   masName = SMS/MMS
09-01 11:33:34.958  7627  7754 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-01 11:33:34.959  7627  7627 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:34.959  7627  7627 V BluetoothPbapService: state: 12
09-01 11:33:34.959  7627  7627 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-01 11:33:34.959  7627  7627 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:34.959  7627  7627 V BluetoothPbapReceiver: ***********state = 12
09-01 11:33:34.960  6933  6933 D BluetoothPbap: Proxy object connected
09-01 11:33:34.960  6933  6933 D PbapServerProfile: Bluetooth service connected
09-01 11:33:34.960  1026  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:34.960  7627  7627 V BluetoothPbapService: Handler(): got msg=1
09-01 11:33:34.961  7627  7627 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-01 11:33:34.962  2209  2209 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 11:33:34.962  7627  7754 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:33:34.962  7627  7755 V BluetoothPbapService: Pbap Service initSocket
09-01 11:33:34.963  1026  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:34.964  2209  2209 D c       : Getting all permits...
09-01 11:33:34.964  2209  2209 D a       : Opening database...
09-01 11:33:34.964  7627  7754 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-01 11:33:34.965  7627  7663 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:33:34.965  7627  7663 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-01 11:33:34.965  7627  7754 V BluetoothMapMasInstance: Succeed to create listening socket 
09-01 11:33:34.965  7627  7754 D BluetoothMapMasInstance: Accepting socket connection...
09-01 11:33:34.967  7627  7755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:33:34.970  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:34.971  7627  7755 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-01 11:33:34.971  2209  2209 D a       : Opening database auth.proximity.permit_store...
09-01 11:33:34.971  7627  7755 V BluetoothPbapService: Succeed to create listening socket 
09-01 11:33:34.971  7627  7755 V BluetoothPbapService: Accepting socket connection...
09-01 11:33:34.971  2209  2209 D a       : Closing database...
09-01 11:33:34.980  6933  6933 D BluetoothPermissionRequest: onReceive
,09-01 11:33:34.982  6933  6933 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-01 11:33:34.984  6933  6933 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-01 11:33:34.987  7627  7627 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-01 11:33:34.988  7627  7627 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-01 11:33:34.994  7627  7627 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-01 11:33:35.010  7627  7627 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-01 11:33:35.010  7627  7627 V BtOppService: onCreate
,09-01 11:33:35.013  7627  7627 V BluetoothOppNotification: send message
09-01 11:33:35.016  7627  7627 V BtOppService: Starting RfcommListener
09-01 11:33:35.019  7627  7627 D BluetoothOppPreference: Dumping Names:  
09-01 11:33:35.019  7627  7627 D BluetoothOppPreference: {}
09-01 11:33:35.020  7627  7627 D BluetoothOppPreference: Dumping Channels:  
09-01 11:33:35.020  7627  7627 D BluetoothOppPreference: {}
09-01 11:33:35.020  7627  7627 V BtOppService: onStartCommand
09-01 11:33:35.023  7627  7627 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:33:35.023  7627  7627 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-01 11:33:35.025  7627  7763 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:33:35.026  7627  7760 V BtOppService: Deleted complete outbound shares, number =  0
,09-01 11:33:35.029  7627  7763 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:33:35.031  7627  7763 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9c195c4 on behalf of 
09-01 11:33:35.031  7627  7760 V BtOppService: Deleted complete inbound failed shares, number = 0
09-01 11:33:35.032  7627  7763 V BluetoothOppNotification: update too frequent, put in queue
09-01 11:33:35.032  7627  7760 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-01 11:33:35.034  7627  7763 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-01 11:33:35.034  7627  7760 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ca6acad on behalf of 
09-01 11:33:35.119  1026  1568 I art     : Explicit concurrent mark sweep GC freed 28314(1386KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.104ms total 95.120ms
,09-01 11:33:35.121  7627  7627 V BluetoothOppNotification: new notify threadi!
09-01 11:33:35.123  7627  7627 V BluetoothOppNotification: send delay message
09-01 11:33:35.123  7627  7627 V BtOppService: start RfcommListener
09-01 11:33:35.125  7627  7627 V BtOppService: RfcommListener started
09-01 11:33:35.126  7627  7627 V BtOppService: ContentObserver received notification
09-01 11:33:35.128  7627  7627 V BtOppService: ContentObserver received notification
,09-01 11:33:35.128  7627  7766 V BtOppRfcommListener: Starting RFCOMM listener....
09-01 11:33:35.129  1026  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:35.132  7627  7766 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:33:35.132  7627  7764 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-01 11:33:35.134  7627  7767 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-01 11:33:35.134  7627  7766 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-01 11:33:35.134  7627  7767 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-01 11:33:35.134  7627  7766 V BtOppRfcommListener: Started RFCOMM listener....
09-01 11:33:35.135  7627  7766 I BtOppRfcommListener: Accept thread started.
09-01 11:33:35.135  7627  7766 V BtOppRfcommListener: Accepting connection...
09-01 11:33:35.137  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:35.137  7627  7627 V BluetoothFtpService: Ftp Service onCreate
09-01 11:33:35.137  7627  7627 I BluetoothFtpService: Ftp Service onCreate
09-01 11:33:35.138  7627  7627 V BluetoothFtpService: Ftp Service onStartCommand
09-01 11:33:35.138  7627  7627 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:35.138  7627  7627 V BluetoothFtpService: Starting Listening on sockets
09-01 11:33:35.138  7627  7627 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-01 11:33:35.138  7627  7627 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-01 11:33:35.138  7627  7627 V BluetoothSapReceiver: SapReceiver onReceive 
09-01 11:33:35.138  7627  7627 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:35.138  7627  7627 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-01 11:33:35.138  7627  7627 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-01 11:33:35.140  7627  7764 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16626be2 on behalf of 
09-01 11:33:35.141  7627  7767 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@244a30 on behalf of 
09-01 11:33:35.141  7627  7627 V BluetoothFtpService: Handler(): got msg=1
09-01 11:33:35.142  7627  7627 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-01 11:33:35.142  7627  7627 V BluetoothFtpService: Ftp Service initSocket
09-01 11:33:35.143  7627  7764 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-01 11:33:35.148  7627  7767 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-01 11:33:35.148  1026  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:35.149  7627  7627 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:33:35.150  7627  7764 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-01 11:33:35.150  7627  7627 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
,09-01 11:33:35.150  7627  7627 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-01 11:33:35.151  7627  7768 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-01 11:33:35.152  7627  7764 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f2e66a9 on behalf of 
09-01 11:33:35.155  7627  7764 V BluetoothOppNotification: outbound: succ-0  fail-0
09-01 11:33:35.156  7627  7764 V BluetoothOppNotification: outbound notification was removed.
09-01 11:33:35.156  7627  7764 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:33:35.158  7627  7764 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9bf642e on behalf of 
09-01 11:33:35.159  7627  7764 V BluetoothOppNotification: inbound: succ-0  fail-0
09-01 11:33:35.160  7627  7764 V BluetoothOppNotification: inbound notification was removed.
09-01 11:33:35.160  7627  7764 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:33:35.161  7627  7764 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2097dbcf on behalf of 
09-01 11:33:35.170  7627  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1923ba88
09-01 11:33:35.170  7627  7627 V BluetoothSapService: Sap Service onCreate
,09-01 11:33:35.173  7627  7627 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:33:35.173  7627  7627 V BluetoothSapService: state: 12
09-01 11:33:35.173  7627  7627 V BluetoothSapService: Starting SAP server process
09-01 11:33:35.174  7627  7627 V BluetoothSapService: SAP Service startRfcommListenerThread
09-01 11:33:35.175  7627  7770 V BluetoothSapService: Sap Service initRfcommSocket
09-01 11:33:35.167  7769  7769 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:35.176  1026  1776 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:35.167  7769  7769 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:35.176  7627  7770 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:33:35.177  7627  7770 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-01 11:33:35.178  7627  7770 V BluetoothSapService: Succeed to create listening socket 
09-01 11:33:35.178  7627  7770 V BluetoothSapService: Accepting socket connection...
09-01 11:33:35.181  7769  7769 V BT_SAP  : Event pipe created
09-01 11:33:35.181  7769  7769 V BT_SAP  : create_server_socket qcom.sap.server
09-01 11:33:35.181  7769  7769 V BT_SAP  : created socket fd 6
09-01 11:33:35.367  1026  1415 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39c319a7 type 2 when 222899 com.google.android.gms} when 222899
,09-01 11:33:35.380   317  7772 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-01 11:33:35.380  1026  1086 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-01 11:33:35.641  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:35.641  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:35.641  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:35.641  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:33:35.641  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:35.641  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:35.641  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:35.641  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:33:35.649  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:35.651  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:35.651  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@179d6385 added. We now have 8 listener(s)
09-01 11:33:35.651  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:35.654  1026  1766 D WifiServiceImplEx: setWifiEnabled: false pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:33:35.654  1026  1766 D WifiService: setWifiEnabled: false pid=6832, uid=10118
09-01 11:33:35.654  1026  1766 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 11:33:35.660  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:33:35.664  1026  1042 D WifiServiceImplEx: setWifiEnabled: true pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-01 11:33:35.664  1026  1042 D WifiService: setWifiEnabled: true pid=6832, uid=10118
09-01 11:33:35.664  1026  1042 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 11:33:35.683  1026  1026 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-01 11:33:35.684  1026  1026 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-01 11:33:35.684  1026  1026 D Ulp_jni : JNI:system_update. Event-4
09-01 11:33:35.685  1026  1531 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-01 11:33:35.685  1026  1531 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-01 11:33:35.688  1026  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1026] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-01 11:33:35.688  1026  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:33:35.688  1026  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1026] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-01 11:33:35.688  1026  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-01 11:33:35.688  1026  1531 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-01 11:33:35.688  1026  1531 E WifiHW  : unknown target_country: EU , set to default
09-01 11:33:35.688  1026  1531 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-01 11:33:35.688  1026  1531 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-01 11:33:35.689  1026  1531 I WifiUtil: gEnableBmps=1
09-01 11:33:36.124  7627  7627 V BluetoothOppNotification: new notify threadi!
09-01 11:33:36.125  7627  7627 V BluetoothOppNotification: send delay message
,09-01 11:33:36.130  7627  7791 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-01 11:33:36.131  7627  7791 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f6065eb on behalf of 
09-01 11:33:36.132  7627  7791 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-01 11:33:36.133  7627  7791 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-01 11:33:36.134  7627  7791 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9db2f48 on behalf of 
09-01 11:33:36.135  7627  7791 V BluetoothOppNotification: outbound: succ-0  fail-0
09-01 11:33:36.136  7627  7791 V BluetoothOppNotification: outbound notification was removed.
09-01 11:33:36.136  7627  7791 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-01 11:33:36.137  7627  7791 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@146b41e1 on behalf of 
09-01 11:33:36.138  7627  7791 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-01 11:33:36.142  7627  7791 V BluetoothOppNotification: inbound notification was removed.
09-01 11:33:36.142  7627  7791 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-01 11:33:36.143  7627  7791 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34c3cb06 on behalf of 
09-01 11:33:36.292   317   883 D SoftapController: Softap fwReload - Ok
,09-01 11:33:36.297  1026  1531 E NetdConnector: NDC Command {66 softap fwreload wlan0 STA} took too long (605ms)
09-01 11:33:36.317   317   883 D CommandListener: Setting iface cfg
09-01 11:33:36.317   317   883 D CommandListener: Trying to bring down wlan0
,09-01 11:33:36.326  1026  1088 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 11:33:36.326  1026  1088 D Tethering: InitialState.processMessage what=4
09-01 11:33:36.327   317   883 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:33:36.337  1026  1088 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 11:33:36.342  1026  1531 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-01 11:33:36.357  1026  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:33:36.357  1026  1531 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:33:36.357  1026  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-01 11:33:36.347  7793  7793 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:36.377  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:33:36.367  7793  7793 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:36.386  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-01 11:33:36.403  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:33:36.413  1026  1531 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-01 11:33:36.413  1026  1531 D WifiMonitor: connecting to supplicant
09-01 11:33:36.416  1026  1026 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-01 11:33:36.421  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:33:36.421  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:33:36.421  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:33:36.421  6933  6933 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:33:36.422  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:33:36.424  6933  6933 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:33:36.424  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-01 11:33:36.424  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:33:36.424  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:33:36.424  6933  6933 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:33:36.425  6933  6933 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:33:36.427  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:33:36.427  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:33:36.427  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:33:36.427  6933  6933 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:33:36.428  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:33:36.428  6933  6933 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:33:36.429  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-01 11:33:36.429  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:33:36.429  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:33:36.429  6933  6933 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:33:36.429  7793  7793 I wpa_supplicant: Successfully initialized wpa_supplicant
09-01 11:33:36.429  6933  6933 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:33:36.438  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:33:36.442  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:33:36.448  7075  7811 W FormManager: Network not available. Please check & try again.
,09-01 11:33:36.452  7075  7812 V FormManager: Network unavailable.
09-01 11:33:36.452  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:36.456  7075  7812 V FormManager: Network unavailable.
09-01 11:33:36.465  7793  7793 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 11:33:36.466  7793  7793 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-01 11:33:36.523  7793  7793 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 11:33:36.556  7793  7793 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-01 11:33:36.568  7793  7793 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-01 11:33:36.570  1026  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-01 11:33:36.571  1026  1531 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-01 11:33:36.571  1026  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,09-01 11:33:36.572  1026  1531 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-01 11:33:36.572  1026  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:36.572  1026  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:36.573  1026  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:36.573  1026  7814 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-01 11:33:36.573  1026  7814 D WifiMonitor: Dropping event because (p2p0) is stopped
09-01 11:33:36.573  1026  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:36.574  1026  1531 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-01 11:33:36.574  1026  1531 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-01 11:33:36.575  1026  1531 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-01 11:33:36.575  1026  1531 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-01 11:33:36.575  1026  1531 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-01 11:33:36.576  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:33:36.576  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:36.577  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:33:36.577  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:33:36.577  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-01 11:33:36.577  1026  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-01 11:33:36.577  1026  1531 E WifiStateMachine: useWiFiOffloading() : false
09-01 11:33:36.577  1026  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-01 11:33:36.583  1936  1936 D WfdService: Waiting for WifiP2p enabling
09-01 11:33:36.586  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:36.586  7793  7793 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-01 11:33:36.587  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-01 11:33:36.587  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-01 11:33:36.587  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-01 11:33:36.587  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-01 11:33:36.587  1026  7814 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,09-01 11:33:36.587  1026  7814 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-01 11:33:36.589  1026  1026 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-01 11:33:36.588  1026  1531 D WifiNative-wlan0: doBoolean: SET update_config 1
09-01 11:33:36.589  1026  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-01 11:33:36.590  1026  1531 D WifiNative-wlan0: SET update_config 1: returned true
09-01 11:33:36.590  1026  1531 D WifiConfigStore: Loading config and enabling all networks 
09-01 11:33:36.590  1026  1531 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-01 11:33:36.590  1026  1531 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-01 11:33:36.597  1026  1531 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-01 11:33:36.599  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:36.599  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:36.599  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:36.599  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:36.599  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:36.599  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:36.599  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:36.599  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:33:36.601  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:36.605  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:33:36.608  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-01 11:33:36.611  1026  1531 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-01 11:33:36.612  1026  1531 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-01 11:33:36.613  1026  1531 D WifiStateMachine: enableVerboseLogging : level 2
09-01 11:33:36.613  1026  1531 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-01 11:33:36.613  1026  1531 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-01 11:33:36.613  1026  1531 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-01 11:33:36.614  1026  1531 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-01 11:33:36.614  1026  1531 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-01 11:33:36.614  1026  1531 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-01 11:33:36.614  1026  1531 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-01 11:33:36.615  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:36.615  1026  1531 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-01 11:33:36.615  1026  1531 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-01 11:33:36.616  1026  1531 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-01 11:33:36.616  1026  1531 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-01 11:33:36.617  1026  1531 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-01 11:33:36.617  1026  1531 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-01 11:33:36.617  1026  1531 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,09-01 11:33:36.621  1936  1936 D WfdsService: Supplicant Connection state is changed : true
,09-01 11:33:36.621  7075  7816 W FormManager: Network not available. Please check & try again.
09-01 11:33:36.621  1936  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-01 11:33:36.621  1936  2300 D WfdsService: Set the WFDS Monitor: true
09-01 11:33:36.621  1936  2300 D WfdsMonitor: WfdsMonitorThread create
09-01 11:33:36.621  1026  1531 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:33:36.621  1026  1531 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-01 11:33:36.621  1936  2300 D WfdsMonitor: WFDS Monitor is created and started
09-01 11:33:36.621  1936  2300 D WfdsService: WiFi: Supplicant connection re-established
09-01 11:33:36.622  1026  1531 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-01 11:33:36.622  1026  1531 D WifiNative-HAL: Setting external_sim to 1
09-01 11:33:36.623  1026  1531 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-01 11:33:36.623  1026  1531 D WifiNative-wlan0: SET external_sim 1: returned true
09-01 11:33:36.623  1026  1531 I WifiNative-HAL: startHal
09-01 11:33:36.623  1026  1531 D wifi    : setting scan oui 0x95360f40
09-01 11:33:36.623  1936  7819 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-01 11:33:36.623  1026  1531 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:33:36.623  1026  1531 I WifiNative-HAL: startHal
09-01 11:33:36.624  1026  1531 D wifi    : setting scan oui 0x95360f40
09-01 11:33:36.624  1026  1531 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-01 11:33:36.624  1936  7819 E CtrlSupplicant: Succeed to open control connection
09-01 11:33:36.624  1936  7819 E CtrlSupplicant: Succeed to open monitor connection
09-01 11:33:36.624  1026  1531 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-01 11:33:36.624  1936  7819 D WfdsMonitor: Supplicant connection established
09-01 11:33:36.624  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-01 11:33:36.624  1936  2300 D WfdsService: Connected to the supplicant for wfds
09-01 11:33:36.625  7075  7817 V FormManager: Network unavailable.
09-01 11:33:36.625  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-01 11:33:36.626  1026  1531 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-01 11:33:36.628  7075  7817 V FormManager: Network unavailable.
09-01 11:33:36.629  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-01 11:33:36.629  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:33:36.630  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:33:36.630  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
,09-01 11:33:36.630  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-01 11:33:36.631  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-01 11:33:36.631  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:33:36.631  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:33:36.631  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-01 11:33:36.631  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,09-01 11:33:36.631  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-01 11:33:36.632  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-01 11:33:36.632  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-01 11:33:36.632  7793  7793 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-01 11:33:36.632  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-01 11:33:36.632  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-01 11:33:36.632  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-01 11:33:36.633  1026  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-01 11:33:36.634  1026  1531 E WifiNative: : [224,166,356 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-01 11:33:36.634  1026  1531 D WifiNative-wlan0: doBoolean: RECONNECT
09-01 11:33:36.634  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:33:36.635  1026  1531 D WifiNative-wlan0: RECONNECT: returned true
09-01 11:33:36.635  1026  1531 D WifiNative-wlan0: doString: [STATUS]
,09-01 11:33:36.635  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-01 11:33:36.636  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-01 11:33:36.636  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-01 11:33:36.636  1026  1531 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-01 11:33:36.636  1026  1531 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:33:36.636  1026  1531 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:33:36.637  1026  1529 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.637  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:33:36.638   317   883 D CommandListener: Setting iface cfg
09-01 11:33:36.639   317   883 D CommandListener: Trying to bring up p2p0
09-01 11:33:36.639  1026  1529 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-01 11:33:36.639  1026  1529 D LGWifiP2pService: P2pEnablingState
09-01 11:33:36.639  1026  1529 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.639  1026  1529 D LGWifiP2pService: P2p socket connection successful
09-01 11:33:36.639  1026  1529 D LGWifiP2pService: P2pEnabledState
09-01 11:33:36.640  1026  1026 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 11:33:36.640  1026  1026 D RttService: SCAN_AVAILABLE : 3
09-01 11:33:36.640  1026  1549 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.640  1026  1549 I WifiNative-HAL: startHal
09-01 11:33:36.640  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-01 11:33:36.640  1026  1529 D LGWifiP2pService: sending p2p connection changed broadcast
09-01 11:33:36.640  1026  1549 D wifi    : getting scan capabilities on interface[1] = 0x95360f40
09-01 11:33:36.640  1026  1549 D wifi    : failed to get capabilities : -3
09-01 11:33:36.640  1026  1549 E WifiScanningService: could not get scan capabilities
09-01 11:33:36.641  1026  1550 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.641  1026  1529 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-01 11:33:36.641  1026  1529 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-01 11:33:36.641  1026  1529 D WifiNative-p2p0: doBoolean: SET device_name G3
09-01 11:33:36.642  1026  1529 D WifiNative-p2p0: SET device_name G3: returned true
09-01 11:33:36.642  1026  1529 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-01 11:33:36.642  1026  1529 D LGWifiP2pService: before postfix = G3
09-01 11:33:36.642  1026  1529 D WifiServerServiceExt: postfix byte check : 2
09-01 11:33:36.642  1026  1529 D LGWifiP2pService: after postfix = G3
09-01 11:33:36.642  1026  1529 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-01 11:33:36.642  1026  1531 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-01 11:33:36.642  1026  1529 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-01 11:33:36.642  1026  1529 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-01 11:33:36.643  1026  1531 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-01 11:33:36.643  1026  1529 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-01 11:33:36.643  1026  1529 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-01 11:33:36.643  1026  1531 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-01 11:33:36.643  1026  1529 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned t,rue
09-01 11:33:36.643  1026  1529 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-01 11:33:36.643  1026  1531 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-01 11:33:36.644  1026  1529 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-01 11:33:36.644  1026  1529 D WifiNative-HAL: p2pGetDeviceAddress
09-01 11:33:36.644  1026  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=224177  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-01 11:33:36.644  1026  1529 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-01 11:33:36.645  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-01 11:33:36.646  1936  1936 D WfdsService: WifiP2pState is changed : true
09-01 11:33:36.646  1936  1936 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-01 11:33:36.646  1936  1936 D WfdsService: isConnected: false
09-01 11:33:36.647  1936  2300 D WfdsService: Receive the WFDS_ENABLE Method
09-01 11:33:36.647  1936  2300 D WfdsService: Set the WFDS Monitor: true
09-01 11:33:36.647  1936  2300 D WfdsService: Connected to the supplicant for wfds
09-01 11:33:36.647  1936  2300 D WfdsJNI : doCommand: WFDS_SET TRUE
09-01 11:33:36.647  7793  7793 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
,09-01 11:33:36.648  1936  2300 D WfdsService: selectPreferredScanChannel [36]
09-01 11:33:36.648  1936  2300 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-01 11:33:36.649  1026  1529 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-01 11:33:36.649  1026  1529 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-01 11:33:36.649  1026  1529 D WifiNative-p2p0: P2P_FLUSH: returned true
09-01 11:33:36.649  1026  1529 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-01 11:33:36.649  1936  1936 I WfdStateTracker: handleP2pThisDeviceChanged
09-01 11:33:36.650  1936  1936 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-01 11:33:36.650  1936  1936 D WfdsService: Update P2p Interface State: 3
09-01 11:33:36.650  1026  1529 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-01 11:33:36.650  1026  1529 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-01 11:33:36.650  1026  1529 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-01 11:33:36.650  1026  1529 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-01 11:33:36.651  1026  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=224184  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-01 11:33:36.653  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:36.653  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:36.653  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-01 11:33:36.654  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:36.654  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:36.654  7401  7401 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-01 11:33:36.654  7401  7401 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-01 11:33:36.654  7401  7401 V [BNRBootReceiver]: Boot Receiver Return
09-01 11:33:36.654  1026  1531 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-01 11:33:36.654  1026  1531 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-01 11:33:36.655  1026  1531 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-01 11:33:36.655  1026  1531 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-01 11:33:36.657  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:36.658  4323  7821 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-01 11:33:36.658  4323  7821 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-01 11:33:36.659  7793  7793 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-01 11:33:36.659  1026  1529 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-01 11:33:36.659  1026  1529 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-01 11:33:36.660  1026  1529 D LGWifiP2pService: InactiveState
09-01 11:33:36.660  1026  1529 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.660  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.660  1026  1529 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-01 11:33:36.660  1026  1531 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-01 11:33:36.661  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-01 11:33:36.661  1026  1531 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-01 11:33:36.662  7793  7793 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-01 11:33:36.662  1936  7819 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:33:36.662  1026  7814 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:33:36.662  1026  7814 E WifiMonitor: WifiMonitor:p2p0 cnt=36 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:36.662  1026  7814 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:36.662  1026  7814 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:36.662  1026  1531 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-01 11:33:36.662  1026  1531 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-01 11:33:36.662  7793  7793 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:33:36.662  7793  7793 E wpa_supplicant: disconnect_rssi_lvl: -100
09-01 11:33:36.662  7793  7793 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.663  1936  7819 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:36.663  1026  7814 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:36.663  1026  7814 E WifiMonitor: WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.663  1026  7814 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.663  1026  7814 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.663  7793  7793 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.663  1936  7819 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:36.663  1026  7814 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:36.663  1026  7814 E WifiMonitor: WifiMonitor:p2p0 cnt=38 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.663  1026  7814 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.663  1026  7814 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.664  1026  1529 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-01 11:33:36.664  1026  1529 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.664  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.664  1026  1529 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.664  1026  1529 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.664  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.664  1026  1529 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.665  1026  1529 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.665  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.665  1026  1529 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.665  1936  2300 W WfdsService: DefaultState - msg [9441285] is not handled
09-01 11:33:36.665  1026  1529 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.665  1026  1529 D LGW,ifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.665  1026  1529 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.665  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:36.665  1026  1026 E WifiServerServiceExt: No p2p device connected
09-01 11:33:36.666  1026  1531 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-01 11:33:36.667  1026  1531 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-01 11:33:36.667  1026  1531 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-01 11:33:36.668  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-01 11:33:36.668  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-01 11:33:36.668  7793  7793 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:36.669  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-01 11:33:36.669  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:36.669  1026  7814 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:36.669  1026  7814 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-01 11:33:36.669  4323  7820 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-01 11:33:36.669  7793  7793 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-01 11:33:36.669  7793  7793 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.669  1026  1531 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-01 11:33:36.669  1026  7814 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:36.669  1936  7819 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:36.669  1026  7814 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.670  1026  7814 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.670  1026  7814 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.670  1026  1531 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:33:36.670  7793  7793 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.670  1026  1531 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:33:36.671  1026  1531 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-01 11:33:36.671  1026  7814 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:36.671  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-01 11:33:36.671  1026  7814 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.671  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-01 11:33:36.671  1026  1529 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.671  7793  7793 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:33:36.671  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:36.672  1936  7819 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-01 11:33:36.672  1026  7814 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.672  1026  7814 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-01 11:33:36.672  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-01 11:33:36.672  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:33:36.672  1026  7814 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:33:36.672  1026  1531 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-01 11:33:36.672  1026  7814 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-01 11:33:36.672  1026  1531 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-01 11:33:36.672  1026  1531 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-01 11:33:36.673  1026  1531 D WifiNative-wlan0: doBoolean: SCAN
09-01 11:33:36.673  1026  1531 D WifiNative-wlan0: SCAN: returned false
09-01 11:33:36.674  1026  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=224207  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-01 11:33:36.676  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:33:36.676  1026  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=224209  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-01 11:33:36.678  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:36.678  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Setti,ngs.Global, returning read-only value.
09-01 11:33:36.678  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-01 11:33:36.678  1026  1531 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:33:36.680  1026  1531 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:33:36.681  1026  1531 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:33:36.681  1026  1531 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-01 11:33:36.683  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:36.684  1026  1531 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-01 11:33:36.687  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:36.687  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:36.688  1026  1026 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:33:36.688  1026  1026 D WifiServerServiceExt: setSupplicantStateSCANNING
09-01 11:33:36.688  1026  1026 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:33:36.688  1026  1026 D WifiServerServiceExt: setSupplicantStateSCANNING
09-01 11:33:36.689  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:36.694  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:36.695  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:36.696  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:33:36.699  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:33:36.702  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:33:36.702  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:36.702  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:36.702  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:36.702  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:36.702  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:33:36.702  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:33:36.702  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:33:36.704  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:33:36.705  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:33:36.710  6832  6909 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-01 11:33:36.711  6832  6909 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-01 11:33:36.713  6832  6909 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@340d12ff Bundle[{}]
09-01 11:33:36.714  6832  6909 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 11:33:36.714  6832  6909 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-01 11:33:36.715  6832  6909 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-01 11:33:36.715  6832  6909 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 11:33:36.716  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:36.716  6832  6909 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-01 11:33:36.717  6832  6909 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-01 11:33:36.721  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:36.722  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:36.723  7012  7012 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-01 11:33:36.723  6832  6909 I System.out: Running OutgoingSocketThread
,09-01 11:33:36.725  6832  7822 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 891)
09-01 11:33:36.726  6832  7822 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42796
09-01 11:33:36.726  6832  7822 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-01 11:33:37.325  7793  7793 E wpa_supplicant: USIM:  scard_init function
,09-01 11:33:37.331  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-01 11:33:37.331  7793  7793 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-01 11:33:37.334  1026  7814 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-01 11:33:37.335  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-01 11:33:37.335  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: WPS-AP-AVAILABLE 
09-01 11:33:37.335  1026  7814 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-01 11:33:37.337  1026  1531 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-01 11:33:37.337  1026  1531 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-01 11:33:37.335  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-01 11:33:37.338  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-01 11:33:37.338  1026  1531 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-01 11:33:37.339  1026  1531 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-01 11:33:37.339  1026  1531 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-01 11:33:37.359  1026  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=224892  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-01 11:33:37.366  1026  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=224899  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-01 11:33:37.366  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-01 11:33:37.369  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.369  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.370  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-01 11:33:37.370  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:37.370  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:37.374  1026  1026 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:33:37.374  1026  1026 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,09-01 11:33:37.378  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.387  6933  6933 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-01 11:33:37.393  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:37.408  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:33:37.416  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:37.424  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:37.424  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:37.425  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-01 11:33:37.451  7793  7793 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 11:33:37.458  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-01 11:33:37.458  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-01 11:33:37.458  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-01 11:33:37.458  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-01 11:33:37.459  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:33:37.459  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:33:37.462  7793  7793 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:33:37.462  7793  7793 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:33:37.468  1026  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=225001  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-01 11:33:37.472  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:33:37.472  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:33:37.473  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-01 11:33:37.473  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:33:37.473  1026  7814 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:33:37.473  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-01 11:33:37.473  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:33:37.473  1026  7814 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-01 11:33:37.473  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:33:37.473  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:33:37.475  1026  1088 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-01 11:33:37.482  1026  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=225015  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-01 11:33:37.482  1026  1531 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=225015
09-01 11:33:37.483  1026  1531 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=225016
09-01 11:33:37.483  1026  1531 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=225016
09-01 11:33:37.483  1026  1531 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=225016
09-01 11:33:37.484  1026  1531 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=225017
09-01 11:33:37.484  1026  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=225017  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-01 11:33:37.495  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.495  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.495  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-01 11:33:37.498  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:37.498  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-01 11:33:37.503  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.507  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:37.507  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:37.510  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.520  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:33:37.520  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.520  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-01 11:33:37.522  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-01 11:33:37.523  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-01 11:33:37.523  6933  6933 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-01 11:33:37.523  6933  6933 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-01 11:33:37.526  1026  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=225058  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-01 11:33:37.527  1026  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=225060  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-01 11:33:37.528  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-01 11:33:37.528  1026  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=225061  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-01 11:33:37.528  1026  1531 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=225061
09-01 11:33:37.529  1026  1531 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=225062
09-01 11:33:37.529  6933  6933 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-01 11:33:37.529  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-01 11:33:37.529  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-01 11:33:37.529  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-01 11:33:37.529  6933  6933 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-01 11:33:37.529  6933  6933 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-01 11:33:37.529  1026  1531 D WifiNative-wlan0: doString: [STATUS]
09-01 11:33:37.530  1026  7814 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-01 11:33:37.530  6933  6933 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-01 11:33:37.530  1026  7814 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-01 11:33:37.530  1026  1531 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-01 11:33:37.533  1026  1531 I WifiServiceExtension: setVHTCapabilityType  : false
09-01 11:33:37.534  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-01 11:33:37.541  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:33:37.544  1026  1531 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-01 11:33:37.544  1026  1531 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-01 11:33:37.550  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.550  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.550  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-01 11:33:37.550  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.550  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.550  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-01 11:33:37.552  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:37.553  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:37.553  1026  1415 V AlarmManager: ELAPSED_WAKEUP set : Alarm{15cb6933 type 2 when 223402 android} when 223402
09-01 11:33:37.554  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.556  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:37.556  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:37.556  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:37.558  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.558  1026  1531 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-01 11:33:37.558  1026  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:33:37.558  1026  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:33:37.558  1026  1537 D ConnectivityService: Got NetworkAgent Messenger
09-01 11:33:37.558  1026  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-01 11:33:37.558  1026  1537 D ConnectivityService: NetworkAgent connected
09-01 11:33:37.559  1026  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:33:37.559  1026  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-01 11:33:37.563  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:37.564  1026  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:33:37.564  1026  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:33:37.564  1026  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-01 11:33:37.564  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:37.564  1026  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-01 11:33:37.564  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:33:37.564  1026  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-01 11:33:37.568  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:37.569  1026  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-01 11:33:37.570   317   883 D CommandListener: Setting iface cfg
09-01 11:33:37.579  1026  1531 E WifiStateMachine: Start Dhcp Watchdog 2
09-01 11:33:37.579  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:33:37.579  1026  7850 D DhcpStateMachine: StoppedState
09-01 11:33:37.579  1026  7850 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:33:37.579  1026  7850 D DhcpStateMachine: WaitBeforeStartState
09-01 11:33:37.581  1026  1531 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=225114  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-01 11:33:37.581  1026  1531 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=225114  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:33:37.582  1026  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=225115  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:33:37.582  1026  1531 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:37.583  1026  1531 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:37.583  1026  1531 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:37.584  1026  1531 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:37.584  1026  1531 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:37.584  1026  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-01 11:33:37.586  1026  1026 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:33:37.586  1026  1026 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-01 11:33:37.587  1026  1026 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:33:37.587  1026  1026 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-01 11:33:37.588  1026  1026 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:33:37.588  1026  1026 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-01 11:33:37.588  1026  1531 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=225121  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:33:37.589  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:37.590  1026  1531 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=225122  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:33:37.591  1026  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=225124  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-01 11:33:37.592  1026  1531 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:179405] from screen [on:0 period:-451364936] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-01 11:33:37.593  1026  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-451364935] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-01 11:33:37.593  1026  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-01 11:33:37.594  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:37.595  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:37.595  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:33:37.597  1026  1531 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.598  1026  1537 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-01 11:33:37.598  1026  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.598  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.599  1026  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.599  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:37.599  1026  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.599  1026  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.600  1026  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.600  1026  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-01 11:33:37.601  1026  1531 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=134,0,0
09-01 11:33:37.601  1026  1531 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=134,0,0
09-01 11:33:37.601  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-01 11:33:37.601  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-01 11:33:37.602  1026  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-01 11:33:37.602  1026  1531 D WifiNative-wlan0: doBoolean: SET ps 0
09-01 11:33:37.602  1026  1531 D WifiNative-wlan0: SET ps 0: returned true
09-01 11:33:37.602  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-01 11:33:37.602  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-01 11:33:37.603  1026  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
,09-01 11:33:37.603  1026  1529 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2adbd5aa target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:37.603  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2adbd5aa target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:37.604  1026  7850 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:37.604  1026  7850 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-01 11:33:37.605  1026  1531 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-01 11:33:37.605  1026  1531 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-01 11:33:37.605  1026  1531 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-01 11:33:37.607   317   883 D CommandListener: Setting iface cfg
09-01 11:33:37.607   317   883 D CommandListener: Trying to bring up wlan0
09-01 11:33:37.607  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:33:37.608  1026  1531 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-01 11:33:37.608  1026  1026 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:33:37.609  1026  1026 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-01 11:33:37.610  1026  1026 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-01 11:33:37.610  1026  1026 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-01 11:33:37.610  1026  1531 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.610  1026  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.611  1026  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.611  1026  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.612  1026  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.612  1026  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-01 11:33:37.613  1026  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-01 11:33:37.613  1026  1531 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-01 11:33:37.613  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:37.615  1026  1531 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,09-01 11:33:37.615  1026  1529 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:33:37.615  1026  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:37.615  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-01 11:33:37.616  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-01 11:33:37.616  1026  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-01 11:33:37.616  1026  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-01 11:33:37.616  7793  7793 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-01 11:33:37.617  1026  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-01 11:33:37.617  1026  1531 D WifiNative-wlan0: doBoolean: SET ps 1
09-01 11:33:37.619  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:37.619  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:37.620  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:33:37.623  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:37.628  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-01 11:33:37.634  1026  1531 D WifiNative-wlan0: SET ps 1: returned true
09-01 11:33:37.635  1026  1531 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-01 11:33:37.635  1026  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-01 11:33:37.635  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:37.635  1026  1531 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-01 11:33:37.635  1026  1531 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-01 11:33:37.636  1026  1537 D ConnectivityService: ignoring duplicate network state non-change
09-01 11:33:37.640  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:37.640  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:37.641  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.642  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.642  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.642  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-01 11:33:37.647  1026  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-01 11:33:37.648  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:37.648  1026  1537 D ConnectivityService: Adding iface wlan0 to network 101
09-01 11:33:37.648  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:37.649  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:33:37.651  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.651  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.651  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-01 11:33:37.653  1026  1026 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-01 11:33:37.656  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.656  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.656  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-01 11:33:37.657  1936  1936 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-01 11:33:37.658  1026  1531 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-01 11:33:37.662  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:37.662  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-01 11:33:37.663  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.668  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 11:33:37.670  1026  1026 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-01 11:33:37.670  1026  1026 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.669  1595  1595 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-01 11:33:37.670  1026  1026 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 11:33:37.670  1026  1026 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-01 11:33:37.671  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.674  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:33:37.674  1595  1595 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-01 11:33:37.674  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.675  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:37.687  1026  1537 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-01 11:33:37.688  1026  1537 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-01 11:33:37.689  1026  1537 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-01 11:33:37.690   317   883 E Netd    : netlink response contains error (File exists)
09-01 11:33:37.691  1026  1537 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-01 11:33:37.692  1026  1537 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-01 11:33:37.692  1026  1537 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-01 11:33:37.692  1026  1537 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-01 11:33:37.693  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:33:37.694  1026  1537 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-01 11:33:37.694  1026  1537 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-01 11:33:37.694  1026  1537 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-01 11:33:37.694  1026  1537 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-01 11:33:37.694  1026  1537 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:33:37.694  1026  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:33:37.694  1026  1537 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-01 11:33:37.694  1026  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:37.695  1026  7849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:37.695  1026  7849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-01 11:33:37.695  1026  7849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:33:37.696  1026  7849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-01 11:33:37.697  1026  1537 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-01 11:33:37.697  1026  1537 D ConnectivityService: currentScore = 0, newScore = 20
09-01 11:33:37.697  1026  1537 D ConnectivityService:    accepting network in place of null
09-01 11:33:37.697  1026  1537 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:37.698  1848  1848 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:37.699  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:33:37.699  1026  1531 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:37.699  1026  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:33:37.699   317  7855 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-01 11:33:37.700  1026  1537 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvis,ioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-01 11:33:37.700  1026  1537 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-01 11:33:37.700  1026  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:33:37.700  1026  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:33:37.700  1026  1537 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-01 11:33:37.701  1026  1537 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-01 11:33:37.701  1026  1026 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-01 11:33:37.701  1026  1026 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-01 11:33:37.701  1026  1026 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-01 11:33:37.701  1026  1026 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-01 11:33:37.707  1026  1537 D ConnectivityService: validation of new default Network = false
09-01 11:33:37.707  1026  1537 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-01 11:33:37.708  1026  1537 D DSQN    : enableDataServiceNotify 
09-01 11:33:37.708  1026  1537 D DSQN    : start dsqn bin
09-01 11:33:37.713  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-01 11:33:37.714  1026  1537 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-01 11:33:37.714  1026  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:37.714  1026  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:33:37.715  1026  1537 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:33:37.716  1595  1824 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 11:33:37.707  7856  7856 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:37.707  7856  7856 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:37.725  6832  6909 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 892)
09-01 11:33:37.725  6832  6909 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 892)
,09-01 11:33:37.731  6832  6909 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 897)
09-01 11:33:37.731  7856  7856 E DSQN    : DSQN ssw
09-01 11:33:37.732  6832  6909 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-01 11:33:37.732  6832  6909 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 898)
09-01 11:33:37.736  1026  1528 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-01 11:33:37.739  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:33:37.739  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3415da added. We now have 2 listener(s)
09-01 11:33:37.741  1026  1916 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:37.741  1811  7858 I CheckinService: active receiver: enabled
,09-01 11:33:37.743  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:37.743  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:37.743  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:33:37.743  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:37.743  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:33:37.743  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:37.744  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3571ea0b added. We now have 9 listener(s)
09-01 11:33:37.744  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:37.747  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:33:37.750   317  7855 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-01 11:33:37.752  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:33:37.755  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:33:37.756  1811  7858 I CheckinService: Preparing to send checkin request
09-01 11:33:37.756  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:37.756  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:33:37.756  1811  7858 I EventLogService: Accumulating logs since 1472722298956
09-01 11:33:37.757  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.758  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.760  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:37.760  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:37.760  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:37.760  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:37.760  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:37.760  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:37.760  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:37.760  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:33:37.762  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:33:37.764  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:33:37.764  6832  6909 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:33:37.764  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:33:37.767  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:37.767  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3755b301 added. We now have 3 listener(s)
09-01 11:33:37.767  1026  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:37.769  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:37.770  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:33:37.771  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:37.771  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:33:37.771  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:37.771  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fcdb5a6 added. We now have 10 listener(s)
09-01 11:33:37.771  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:37.771  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:37.771  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:37.771  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:37.771  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:37.771  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.771  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:37.771  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:33:37.771  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3415da removed from the list
09-01 11:33:37.771  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.772  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3571ea0b removed from the list
09-01 11:33:37.772  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:37.772  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.772  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.772  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.773  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: s,topAdvertising
09-01 11:33:37.773  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:37.773  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.773  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3571ea0b not in the list
09-01 11:33:37.773  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.773  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.774  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:37.774  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:37.774  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.774  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fcdb5a6 removed from the list
09-01 11:33:37.774  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:37.774  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.774  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.774  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:33:37.774  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3755b301 removed from the list
09-01 11:33:37.775  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:33:37.775  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c531be7 added. We now have 2 listener(s)
09-01 11:33:37.775  1026  1042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-01 11:33:37.777  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:33:37.777  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:37.777  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:33:37.777  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:37.777  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8d7394 added. We now have 9 listener(s)
09-01 11:33:37.777  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:37.777  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:33:37.779  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:37.781  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:37.784   317  7855 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-01 11:33:37.785  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:37.785  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:37.785  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:37.785  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:37.785  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:37.785  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:37.785  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:37.785  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:33:37.786  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:37.787  6832  6909 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:33:37.787  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:33:37.787  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@160f8632 added. We now have 3 listener(s)
09-01 11:33:37.788  1026  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-01 11:33:37.789  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:37.790  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:37.790  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:33:37.790  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:37.790  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:33:37.790  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:37.790  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:37.790  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c2b8f83 added. We now have 10 listener(s)
09-01 11:33:37.790  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:37.790  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:33:37.791  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:33:37.791  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:33:37.791  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:37.791  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:33:37.791  7012  7012 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-01 11:33:37.792  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:37.794  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:37.796   317   882 D LGDataListener: argv[0]=dsqncommand
09-01 11:33:37.796   317   882 D LGDataListener: argv[1]=wlan0
09-01 11:33:37.796   317   882 D LGDataListener: argv[2]=1
09-01 11:33:37.796   317   882 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-01 11:33:37.797  1026  1086 D DSQN    : DSQM DsqnNotification wlan0  1
09-01 11:33:37.797  1026  1086 D DSQN    : start to monitor internet connection
09-01 11:33:37.797  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:33:37.797  1811  7858 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-01 11:33:37.802  1026  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-01 11:33:37.802  6981  6981 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-01 11:33:37.804  1026  7849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 09:33:37 GMT], X-Android-Received-Millis=[1472722417804], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472722417796]}
09-01 11:33:37.805  1026  7849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-01 11:33:37.805  1026  7849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-01 11:33:37.805  1026  1537 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-01 11:33:37.805  1026  1537 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
,09-01 11:33:37.805  1026  1537 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:33:37.805  1026  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:33:37.805  1026  1537 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-01 11:33:37.805  1026  1537 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-01 11:33:37.805  1026  1537 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-01 11:33:37.805  1026  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:37.805  1026  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:33:37.806  1026  7850 D DhcpStateMachine: DHCPV4 request on wlan0
09-01 11:33:37.806  1026  1537 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:33:37.806  1026  1537 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:37.806  1026  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-01 11:33:37.806  1026  7850 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-01 11:33:37.806  1026  7850 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-01 11:33:37.807  1026  1531 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:37.807  1026  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:33:37.807  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:33:37.807  1595  1824 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 11:33:37.807  1848  1848 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:37.808  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-01 11:33:37.808  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:33:37.797  7864  7864 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:37.797  7864  7864 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-01 11:33:37.813  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:33:37.813  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:37.814  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-01 11:33:37.817  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:33:37.819  6832  6909 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:33:37.819  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:37.819  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:37.822  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:37.822  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:37.822  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:37.822  7864  7864 I dhcpcd  : version 5.5.6 starting
09-01 11:33:37.822  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:37.822  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.823  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:37.823  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:33:37.823  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c531be7 removed from the list
09-01 11:33:37.823  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.823  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8d7394 removed from the list
09-01 11:33:37.823  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:37.823  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.823  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.823  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.824  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:37.824  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:37.824  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.824  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8d7394 not in the list
09-01 11:33:37.824  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.824  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.825  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:33:37.825  7864  7864 E dhcpcd  : get_duid: m
09-01 11:33:37.825  7864  7864 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-01 11:33:37.825  7864  7864 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-01 11:33:37.826  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:37.827  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:37.827  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:37.827  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.827  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c2b8f83 removed from the list
09-01 11:33:37.827  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:37.827  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.827  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.827  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:33:37.827  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@160f8632 removed from the list
09-01 11:33:37.827  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:33:37.828  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@222bd37e added. We now have 2 listener(s)
09-01 11:33:37.828  1026  1042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:37.830  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:37.830  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:33:37.830  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:37.830  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:33:37.830  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:37.830  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@388da0df added. We now have 9 listener(s)
09-01 11:33:37.830  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:37.830  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:33:37.832  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-01 11:33:37.833  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-01 11:33:37.833  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:37.834  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-01 11:33:37.838  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:37.838  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:37.838  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:37.838  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:37.838  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:37.838  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:37.838  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:37.838  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:33:37.838  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:37.838  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:37.839  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:37.839  7012  7012 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-01 11:33:37.839  6832  6909 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:33:37.839  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:33:37.839  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d737f5 added. We now have 3 listener(s)
09-01 11:33:37.840  1026  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:37.840  7012  7012 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-01 11:33:37.840  7012  7012 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-01 11:33:37.841  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:33:37.842  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:33:37.842  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:37.842  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:33:37.842  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:37.842  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@322da98a added. We now have 10 listener(s)
09-01 11:33:37.842  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:37.842  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:33:37.843  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:33:37.843  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:33:37.843  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:33:37.843  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:37.843  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:33:37.846  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-01 11:33:37.848  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:33:37.850  1026  1568 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:37.850  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:37.852  6981  6981 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-01 11:33:37.852  6981  6981 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-01 11:33:37.857  6933  6933 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-01 11:33:37.858  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:33:37.858  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:33:37.860  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:33:37.860  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:37.862  6933  6933 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-01 11:33:37.862  6832  6909 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:33:37.863  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:37.863  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:37.863  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:37.863  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:37.863  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.863  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:37.863  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:33:37.863  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@222bd37e removed from the list
09-01 11:33:37.863  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.863  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@388da0df removed from the list
09-01 11:33:37.863  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:37.863  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:33:37.867  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.867  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.868  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:37.868  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:37.868  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.868  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@388da0df not in the list
09-01 11:33:37.868  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.868  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.869  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:37.870  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:37.870  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:37.870  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:37.870  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.870  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@322da98a removed from the list
09-01 11:33:37.870  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:37.870  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.870  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.870  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:33:37.870  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d737f5 removed from the list
09-01 11:33:37.871  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:33:37.871  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32305e71 added. We now have 2 listener(s)
09-01 11:33:37.871  1026  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:37.871  7012  7012 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-01 11:33:37.872  7012  7012 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-01 11:33:37.872  7012  7012 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-01 11:33:37.873  7012  7012 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-01 11:33:37.873  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:33:37.873  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:37.873  68,32  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:33:37.873  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:37.873  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17c4d456 added. We now have 9 listener(s)
09-01 11:33:37.873  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:37.873  7012  7012 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-01 11:33:37.874  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:33:37.877  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:33:37.880  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:37.880  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:37.880  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:37.880  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:37.880  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:37.880  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:37.880  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:37.880  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:33:37.881  7864  7864 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-01 11:33:37.882  7864  7864 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-01 11:33:37.882  7864  7864 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-01 11:33:37.882  7864  7864 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-01 11:33:37.882  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:37.882  7864  7864 D dhcpcd  : wlan0: sending REQUEST (xid 0x7721084f), next in 3.85 seconds
09-01 11:33:37.882  6832  6909 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:33:37.882  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 11:33:37.882  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bee9c4 added. We now have 3 listener(s)
09-01 11:33:37.882  1026  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:37.884  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:33:37.884  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:37.884  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:33:37.885  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:37.885  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f1b70ad added. We now have 10 listener(s)
09-01 11:33:37.885  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:37.885  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:33:37.885  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:33:37.885  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:33:37.885  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:33:37.885  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:33:37.885  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:37.887  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:33:37.887  1026  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:37.887  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:37.890  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:33:37.890  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:33:37.892  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:33:37.893  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:37.894  6832  6909 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 11:33:37.895  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:37.895  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:37.895  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:37.895  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:37.895  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.895  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:37.895  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:33:37.895  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32305e71 removed from the list
09-01 11:33:37.895  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.895  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17c4d456 removed from the list
09-01 11:33:37.895  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:37.896  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.896  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.896  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.896  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:37.896  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:37.896  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.896  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17c4d456 not in the list
09-01 11:33:37.896  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.896  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.897  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:37.897  6832  6909 D BluetoothLeScanner: could not find callback wrapper
09-01 11:33:37.897  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:33:37.897  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:37.897  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.897  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f1b70ad removed from the list
09-,01 11:33:37.897  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:37.897  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.898  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.898  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:33:37.898  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bee9c4 removed from the list
09-01 11:33:37.898  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:33:37.898  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a2de30 added. We now have 2 listener(s)
09-01 11:33:37.898  1026  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:37.900  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:33:37.900  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:37.900  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:33:37.900  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:37.900  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2b6aa9 added. We now have 9 listener(s)
09-01 11:33:37.900  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:37.900  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:33:37.902  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:33:37.904  6832  6909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:33:37.904  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:33:37.904  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-01 11:33:37.904  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:33:37.904  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:33:37.904  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:37.904  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:33:37.904  6832  6909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:33:37.905  7864  7864 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-01 11:33:37.907  6832  6909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:33:37.907  6832  6909 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:33:37.907  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:33:37.907  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c67fcf added. We now have 3 listener(s)
09-01 11:33:37.909  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:33:37.915  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:33:37.931  7864  7864 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-01 11:33:37.931  7864  7864 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-01 11:33:37.931  7864  7864 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,09-01 11:33:37.931  7864  7864 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-01 11:33:37.931  7864  7864 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-01 11:33:37.931  7864  7864 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-01 11:33:37.931  7864  7864 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-01 11:33:37.931  7864  7864 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-01 11:33:37.940  1026  1989 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7871 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-01 11:33:37.940  1026  1916 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-01 11:33:37.943  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-01 11:33:37.943  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:33:37.943  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:33:37.943  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:33:37.943  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@228fad5c added. We now have 10 listener(s)
09-01 11:33:37.943  6832  6909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:33:37.944  6832  6909 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:33:37.944  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:37.944  6832  6909 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:33:37.945  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:37.945  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.945  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:33:37.945  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:33:37.945  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a2de30 removed from the list
09-01 11:33:37.946  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.946  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2b6aa9 removed from the list
09-01 11:33:37.946  6832  6909 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:33:37.946  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.947  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.947  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.948  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:37.948  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:37.950  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.950  6832  6909 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2b6aa9 not in the list
09-01 11:33:37.950  6832  6909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.950  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.951  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:33:37.951  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:33:37.951  6832  6909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:33:37.951  6832  6909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@228fad5c removed from the list
09-01 11:33:37.951  6832  6909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:33:37.951  6832  6909 W org.thaliproject.p,2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:33:37.951  6832  6909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:33:37.951  6832  6909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:33:37.951  6832  6909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c67fcf removed from the list
09-01 11:33:37.953  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-01 11:33:37.953  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-01 11:33:37.953  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-01 11:33:37.953  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:33:37.953  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-01 11:33:37.953  6832  6909 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:33:37.963  6832  7890 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 905, name: My test thread name)
09-01 11:33:37.964  6832  7890 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 905, thread name: My test thread name)
09-01 11:33:37.964  6832  7890 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 905, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 11:33:37.967  6832  7891 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 907, name: My test thread name)
09-01 11:33:37.967  6832  7891 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 907, thread name: My test thread name)
09-01 11:33:37.967  6832  7891 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 907, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-01 11:33:37.975  6832  6909 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-01 11:33:37.975  6832  6909 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-01 11:33:37.975  6832  6909 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-01 11:33:37.975  6832  6909 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-01 11:33:37.975  6832  6909 D com.test.thalitest.ThaliTestRunner: Total duration: 23038 ms
09-01 11:33:37.977  6832  6909 I jxcore-log: *Native tests were executed*
09-01 11:33:37.977  6832  6909 I jxcore-log: 
09-01 11:33:37.977  6832  6909 I jxcore-log: Total number of executed tests:  80
09-01 11:33:37.977  6832  6909 I jxcore-log: 
09-01 11:33:37.977  6832  6909 I jxcore-log: Number of passed tests:  80
09-01 11:33:37.977  6832  6909 I jxcore-log: 
09-01 11:33:37.977  6832  6909 I jxcore-log: Number of failed tests:  0
09-01 11:33:37.977  6832  6909 I jxcore-log: 
09-01 11:33:37.977  6832  6909 I jxcore-log: Number of ignored tests:  0
09-01 11:33:37.977  6832  6909 I jxcore-log: 
09-01 11:33:37.978  6832  6909 I jxcore-log: Total duration:  23038
09-01 11:33:37.978  6832  6909 I jxcore-log: 
,09-01 11:33:37.978  6832  6909 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-01 11:33:37.978  6832  6909 I jxcore-log: 
09-01 11:33:37.989  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:33:37.989  6832  6909 I jxcore-log: 
,09-01 11:33:37.993  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:33:37.993  6832  6909 I jxcore-log: 
09-01 11:33:37.995  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:33:37.995  6832  6909 I jxcore-log: 
09-01 11:33:37.996  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:33:37.996  6832  6909 I jxcore-log: 
09-01 11:33:37.997  6832  6832 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-01 11:33:37.997  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:33:37.997  6832  6909 I jxcore-log: 
09-01 11:33:37.999  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:33:37.999  6832  6909 I jxcore-log: 
09-01 11:33:38.003  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:33:38.003  6832  6909 I jxcore-log: 
,09-01 11:33:38.005  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:33:38.005  6832  6909 I jxcore-log: 
09-01 11:33:38.006  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:33:38.006  6832  6909 I jxcore-log: 
09-01 11:33:38.007  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:33:38.007  6832  6909 I jxcore-log: 
09-01 11:33:38.008  7871  7871 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-01 11:33:38.008  7871  7871 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-01 11:33:38.008  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:33:38.008  6832  6909 I jxcore-log: 
09-01 11:33:38.010  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:33:38.010  6832  6909 I jxcore-log: 
09-01 11:33:38.011  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:33:38.011  6832  6909 I jxcore-log: 
09-01 11:33:38.012  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:33:38.012  6832  6909 I jxcore-log: 
09-01 11:33:38.014  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:33:38.014  6832  6909 I jxcore-log: 
09-01 11:33:38.015  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:33:38.015  6832  6909 I jxcore-log: 
09-01 11:33:38.016  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:33:38.016  6832  6909 I jxcore-log: 
09-01 11:33:38.017  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:33:38.017  6832  6909 I jxcore-log: 
,09-01 11:33:38.017  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:33:38.017  6832  6909 I jxcore-log: 
,09-01 11:33:38.018  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:33:38.018  6832  6909 I jxcore-log: 
09-01 11:33:38.019  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:33:38.019  6832  6909 I jxcore-log: 
09-01 11:33:38.020  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:33:38.020  6832  6909 I jxcore-log: 
09-01 11:33:38.021  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:33:38.021  6832  6909 I jxcore-log: 
09-01 11:33:38.022  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:33:38.022  6832  6909 I jxcore-log: 
09-01 11:33:38.023  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:33:38.023  6832  6909 I jxcore-log: 
09-01 11:33:38.024  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:33:38.024  6832  6909 I jxcore-log: 
09-01 11:33:38.025  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:33:38.025  6832  6909 I jxcore-log: 
09-01 11:33:38.026  6832  6909 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:33:38.026  6832  6909 I jxcore-log: 
09-01 11:33:38.037  7871  7871 I MultiDex: VM with version 2.1.0 has multidex support
09-01 11:33:38.037  7871  7871 I MultiDex: install
,09-01 11:33:38.038  7871  7871 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-01 11:33:38.100  2209  2235 I art     : Explicit concurrent mark sweep GC freed 6861(423KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 2.286ms total 54.120ms
,09-01 11:33:38.104  7871  7871 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-01 11:33:38.113  2209  2209 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-01 11:33:38.119  2209  2209 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-01 11:33:38.120  2209  2209 D c       : Getting all permits...
09-01 11:33:38.120  2209  2209 D a       : Opening database...
09-01 11:33:38.123  2209  2209 D a       : Opening database auth.proximity.permit_store...
09-01 11:33:38.124  2209  2209 D a       : Closing database...
09-01 11:33:38.210  1026  7850 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-01 11:33:38.211  1026  7850 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-01 11:33:38.211  1026  7850 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-01 11:33:38.211  1026  7850 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-01 11:33:38.211  1026  7850 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-01 11:33:38.211  1026  7850 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-01 11:33:38.211  1026  7850 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-01 11:33:38.211  1026  7850 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-01 11:33:38.212  1026  7850 D DhcpStateMachine: RunningState
09-01 11:33:38.212  7908  7908 D AndroidRuntime: 
09-01 11:33:38.212  7908  7908 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-01 11:33:38.215  7908  7908 D AndroidRuntime: CheckJNI is OFF
09-01 11:33:38.384  7908  7908 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-01 11:33:38.406  1026  1084 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-01 11:33:38.407  1026  1084 I ActivityManager: Killing 6832:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-01 11:33:38.446  1026  1989 I WindowState: WIN DEATH: Window{2668f1f6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-01 11:33:38.446  1026  1536 D WifiService: Client connection lost with reason: 4
,09-01 11:33:38.450  1026  1989 D InputDispatcher: Window went away: Window{2668f1f6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-01 11:33:38.502  7871  7889 D LgDataFeature: LgDataFeature() Constructor: none
,09-01 11:33:38.502  7871  7889 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-01 11:33:38.627  1026  1084 I ActivityManager:   Force finishing activity ActivityRecord{35b69ab3 u0 com.test.thalitest/.MainActivity t6}
,09-01 11:33:38.657   338   400 E GBMv2   : DFP En is all cleared set to be enabled
09-01 11:33:38.658  1026  1953 W ActivityManager: Spurious death for ProcessRecord{2c605d7b 6832:com.test.thalitest/u0a118}, curProc for 6832: null
09-01 11:33:38.658  1026  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-01 11:33:38.660  1026  1101 I ActivityManager:   Force finishing activity ActivityRecord{35b69ab3 u0 com.test.thalitest/.MainActivity t6 f}
09-01 11:33:38.660  1026  1101 W ActivityManager: Duplicate finish request for ActivityRecord{35b69ab3 u0 com.test.thalitest/.MainActivity t6 f}
,09-01 11:33:38.700  1936  1952 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-01 11:33:38.701  1936  1952 D SplitWindowPolicy: topRunningActivity=ActivityInfo{182714d8 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-01 11:33:38.701  2026  2026 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-01 11:33:38.702  1936  3305 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-01 11:33:38.702  1936  3305 D SplitWindowPolicy: topRunningActivity=ActivityInfo{280de031 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-01 11:33:38.709  2026  2026 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-01 11:33:38.711  1595  1595 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-01 11:33:38.724  1026  1462 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-01 11:33:38.729  3774  3774 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-01 11:33:38.731  7627  7627 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-01 11:33:38.731  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-01 11:33:38.737  1990  1990 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-01 11:33:38.738  4463  4463 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-01 11:33:38.738  4463  4463 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-01 11:33:38.738  4463  4463 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-01 11:33:38.739  4463  4463 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-01 11:33:38.739  4463  4463 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 11:33:38.739  4463  4463 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:33:38.739  4463  4463 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:33:38.739  4463  4463 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-01 11:33:38.739  4463  4463 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:33:38.739  4463  4463 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:33:38.739  4463  4463 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-01 11:33:38.739  4463  4463 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-01 11:33:38.739  6258  6258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-01 11:33:38.749  2503  2669 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-01 11:33:38.752  2026  2026 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,09-01 11:33:38.754  2026  2120 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-01 11:33:38.797  4579  4579 I art     : Explicit concurrent mark sweep GC freed 8040(463KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 545us total 109.906ms
,09-01 11:33:38.822  1026  1531 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-01 11:33:38.822  1026  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:33:38.823  1026  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:33:38.823  1026  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:33:38.824  1026  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:33:38.824  1026  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-01 11:33:38.826  1026  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-01 11:33:38.826  1026  1083 W InputMethodInfo: Duplicated subtype definition found: , voice
09-01 11:33:38.826  1026  1537 D ConnectivityService: identical MTU - not setting
09-01 11:33:38.826  1026  1537 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-01 11:33:38.826  1026  1537 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-01 11:33:38.827  1026  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:33:38.827  1026  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:33:38.827  1026  1537 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-01 11:33:38.828  1595  1824 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-01 11:33:38.834  1026  1026 D administrator: Handling package changes for user 0
09-01 11:33:38.854  1026  1042 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7937 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-01 11:33:38.858  1811  1811 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-01 11:33:38.858  1899  1899 D ActionManagerService: notifyUserLog: 1000003
09-01 11:33:38.859  2026  2026 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-01 11:33:38.860  3774  4462 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-01 11:33:38.860  2026  2026 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-01 11:33:38.861  1865  1865 D SplitUIManager: split_name #11 / not available #0
09-01 11:33:38.863  2026  2026 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-01 11:33:38.864  2026  2026 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-01 11:33:38.865  1865  1865 D SplitUIService: removed split : 
09-01 11:33:38.865  1595  1595 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-01 11:33:38.868  1899  1899 D ActionManagerService: notifyUserLog: 1000004
09-01 11:33:38.869  3774  4462 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-01 11:33:38.869  2026  2026 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-01 11:33:38.876  3774  3792 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-01 11:33:38.877  2209  2209 I ConfigService: onCreate
09-01 11:33:38.878  2209  2209 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-01 11:33:38.881  2209  2209 I ConfigService: onBind returning update interface
09-01 11:33:38.891  1026  1776 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:33:38.897  2209  2209 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-01 11:33:38.897  2209  2209 I ConfigService: onBind returning config service
,09-01 11:33:38.899  1026  1767 V SIM_STK : Menu title from STK is T-Mobile
,09-01 11:33:38.899  1026  1767 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , create_time: 1430832262123
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , expire_time: 0
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , display: false
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , animation: false }
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , create_time: 1430832262287
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , expire_time: 0
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , display: false
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , animation: false }
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , create_time: 1472216588858
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , expire_time: 0
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , display: false
09-01 11:33:38.899  2026  2026 I GBoardWebViewUtils: , animation: false }
09-01 11:33:38.901  1811  1811 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-01 11:33:38.916  1595  1595 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-01 11:33:38.916  1595  1595 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,09-01 11:33:38.918  2026  7955 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-01 11:33:38.922  1811  1811 I ConfigFetchService: service connected
09-01 11:33:38.922  1811  1811 I ConfigClient: service connected
09-01 11:33:38.932  2026  2026 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-01 11:33:38.932  2026  2026 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-01 11:33:38.935  2209  2209 I ConfigService: onDestroy
,09-01 11:33:38.936  1865  1865 D SplitUIManager: split_name #11 / not available #0
09-01 11:33:38.936  1865  1865 I SplitUIService: split app #11
09-01 11:33:38.952  7957  7957 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-01 11:33:38.967  1026  1971 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-01 11:33:38.968  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-01 11:33:38.968  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-01 11:33:38.968  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-01 11:33:38.968  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-01 11:33:38.968  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-01 11:33:38.968  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:33:38.968  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-01 11:33:38.968  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-01 11:33:38.968  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-01 11:33:38.968  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-01 11:33:38.968  7627  7627 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-01 11:33:38.968  1811  7959 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-01 11:33:38.979  7937  7937 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,09-01 11:33:38.999  1026  2036 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7966 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-01 11:33:39.015  1026  1766 V SIM_STK : Menu title from STK is T-Mobile
09-01 11:33:39.016  7957  7957 I dex2oat : dex2oat took 64.038ms (threads: 4)
,09-01 11:33:39.030  2026  2026 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-01 11:33:39.032  1595  1648 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-01 11:33:39.032  1595  1648 D KeyguardModel: createShortcutInfo...
,09-01 11:33:39.032  7871  7889 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:33:39.032  7871  7889 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:33:39.032  7871  7889 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:33:39.032  7871  7889 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:33:39.032  7871  7889 I Adreno-EGL: Remote Branch: 
09-01 11:33:39.032  7871  7889 I Adreno-EGL: Local Patches: 
09-01 11:33:39.032  7871  7889 I Adreno-EGL: Reconstruct Branch: 
09-01 11:33:39.035  1595  1648 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-01 11:33:39.035  1595  1648 D KeyguardModel: createShortcutInfo...
09-01 11:33:39.039  1595  1648 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-01 11:33:39.039  1595  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:33:39.039  1595  1648 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-01 11:33:39.040  1595  1648 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-01 11:33:39.057  6033  7984 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-01 11:33:39.065  1595  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:33:39.065  1595  1648 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-01 11:33:39.066  1595  1648 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-01 11:33:39.066  1595  1648 D KeyguardModel: createShortcutInfo...
09-01 11:33:39.068  1595  1648 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-01 11:33:39.068  1595  1648 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:33:39.069  1595  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-01 11:33:39.069  1595  1648 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-01 11:33:39.070  1595  1648 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-01 11:33:39.070  1595  1648 D KeyguardModel: createShortcutInfo...
09-01 11:33:39.072   331   394 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-01 11:33:39.073  3214  7989 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-01 11:33:39.075  1595  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:33:39.075  1595  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-01 11:33:39.075  1595  1648 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-01 11:33:39.075  1595  1648 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-01 11:33:39.077  1595  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:33:39.077  1595  1648 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-01 11:33:39.078  1595  1648 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-01 11:33:39.078  1595  1648 D KeyguardModel: createShortcutInfo...
09-01 11:33:39.099  1026  1767 I ActivityManager: Killing 7144:com.lge.email/u0a23 (adj 15): empty #17
,09-01 11:33:39.102  1811  7991 I PeopleContactsSync: CP2 sync disabled
09-01 11:33:39.111  1026  1101 I art     : Explicit concurrent mark sweep GC freed 77121(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 7.538ms total 407.419ms
09-01 11:33:39.120  7871  7889 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:33:39.120  7871  7889 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:33:39.120  7871  7889 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:33:39.120  7871  7889 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:33:39.120  7871  7889 I Adreno-EGL: Remote Branch: 
09-01 11:33:39.120  7871  7889 I Adreno-EGL: Local Patches: 
09-01 11:33:39.120  7871  7889 I Adreno-EGL: Reconstruct Branch: 
,09-01 11:33:39.131  7966  7966 I AppUp4:AppBoxCP: onCreate
09-01 11:33:39.132  7966  7966 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-01 11:33:39.132  1026  1026 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-01 11:33:39.132  1026  1026 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-01 11:33:39.133  1026  1026 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-01 11:33:39.136  2026  2026 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-01 11:33:39.139  2026  2026 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:33:39.141  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-01 11:33:39.142  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-01 11:33:39.144  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-01 11:33:39.145  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-01 11:33:39.152  7966  7966 I AppUp4:DB:  setFingerPrint start
09-01 11:33:39.152  7966  7966 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-01 11:33:39.159  7966  7966 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-01 11:33:39.159  7966  7966 I AppUp4:DB:  SDK version = 21
09-01 11:33:39.159  7966  7966 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-01 11:33:39.163  2026  2026 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-01 11:33:39.163  2026  2026 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:33:39.165  7871  7889 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-01 11:33:39.165  7871  7889 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-01 11:33:39.165  7871  7889 I Adreno-EGL: Build Date: 12/12/14 금
09-01 11:33:39.165  7871  7889 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-01 11:33:39.165  7871  7889 I Adreno-EGL: Remote Branch: 
09-01 11:33:39.165  7871  7889 I Adreno-EGL: Local Patches: 
09-01 11:33:39.165  7871  7889 I Adreno-EGL: Reconstruct Branch: 
09-01 11:33:39.172  2026  2185 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-01 11:33:39.172  2026  2185 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,09-01 11:33:39.179  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-01 11:33:39.180  2026  2026 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-01 11:33:39.180  2026  2026 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:33:39.187  2026  2026 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,09-01 11:33:39.202  1595  1595 D KeyguardModel: handleShortcutListChanged...
09-01 11:33:39.202  1595  1595 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-01 11:33:39.204  1026  1989 W libprocessgroup: failed to open /acct/uid_10023/pid_7144/cgroup.procs: No such file or directory
09-01 11:33:39.209  1026  1089 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{368f90e4 u0 com.lge.launcher2/.Launcher t5} time:226753
09-01 11:33:39.209  2026  2026 D [Concierge]WidgetView: change position of spinner
09-01 11:33:39.210  2573  2573 D [Concierge]Service: onStartCommand(). Type : 8
09-01 11:33:39.211  2573  2573 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,09-01 11:33:39.212  1811  4725 I Icing   : doRemovePackageData com.test.thalitest
09-01 11:33:39.213  1026  1570 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-01 11:33:39.213  2573  2573 D [Concierge]Service: Update widget ID : 11
09-01 11:33:39.214  2573  2573 D [Concierge]Service: onStartCommand(). Type : 0
09-01 11:33:39.214  2026  2026 I [Concierge]WidgetView: initWebView(). Time : 1472722419214
09-01 11:33:39.214  1595  1648 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-01 11:33:39.214  1595  1648 D KeyguardModel: createShortcutInfo...
09-01 11:33:39.216  1595  1648 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-01 11:33:39.216  1595  1648 D KeyguardModel: createShortcutInfo...
09-01 11:33:39.217  1595  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:33:39.218  1595  1648 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-01 11:33:39.218  1595  1648 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-01 11:33:39.218  1595  1648 D KeyguardModel: createShortcutInfo...
09-01 11:33:39.219  1595  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:33:39.219  1595  1648 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-01 11:33:39.221  7966  7966 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-01 11:33:39.221  7908  7908 D AndroidRuntime: Shutting down VM
09-01 11:33:39.223  1595  1648 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-01 11:33:39.223  1595  1648 D KeyguardModel: createShortcutInfo...
,09-01 11:33:39.224  1595  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:33:39.224  1595  1648 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-01 11:33:39.225  1595  1648 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-01 11:33:39.225  1595  1648 D KeyguardModel: createShortcutInfo...
09-01 11:33:39.233  2026  2026 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 512415019
09-01 11:33:39.233  2026  2026 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-01 11:33:39.233  2026  2026 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-01 11:33:39.236  2026  2026 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3c5b7731
09-01 11:33:39.236  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,09-01 11:33:39.237  1811  7986 W GmsApplication: Using Auth Proxy for data requests.
09-01 11:33:39.238  2026  2026 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-01 11:33:39.238  2026  2026 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:33:39.241  1811  7986 W GmsApplication: Using Auth Proxy for data requests.
09-01 11:33:39.242  1595  1595 D KeyguardModel: handleShortcutListChanged...
09-01 11:33:39.242  1595  1595 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-01 11:33:39.244  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-01 11:33:39.244  2026  2026 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-01 11:33:39.245  2026  2026 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-01 11:33:39.245  2026  2026 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472722221134, New one : 1472722419214
09-01 11:33:39.245  2026  2026 D [Concierge]WidgetView: Unregister all receivers
09-01 11:33:39.245  2026  2026 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-01 11:33:39.246  2026  2026 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:33:39.247  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,09-01 11:33:39.249  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-01 11:33:39.249  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-01 11:33:39.250  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-01 11:33:39.251  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,09-01 11:33:39.259  2026  2026 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:33:39.259  2026  2026 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:33:39.269  7966  7966 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-01 11:33:39.296  2026  2026 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-01 11:33:39.304  2026  2026 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-01 11:33:39.305  2026  2026 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-01 11:33:39.306  2026  2026 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-01 11:33:39.312  1026  1776 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7994 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-01 11:33:39.313  1026  1776 I ActivityManager: Killing 7188:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-01 11:33:39.318   381   381 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 10.273ms
09-01 11:33:39.327  2026  2026 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1b69c0ea time:226872
,09-01 11:33:39.332   381   381 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 9.237ms
09-01 11:33:39.337  1026  1083 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:33:39.341  1026  1083 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-01 11:33:39.341   381   381 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 9.062ms
09-01 11:33:39.385  1026  2036 W libprocessgroup: failed to open /acct/uid_10046/pid_7188/cgroup.procs: No such file or directory
,09-01 11:33:39.390  2026  2026 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-01 11:33:39.402  7994  7994 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:33:39.402  7994  7994 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-01 11:33:39.402  7994  7994 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-01 11:33:39.403  7994  7994 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-01 11:33:39.403  7994  7994 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-01 11:33:39.468  1026  1101 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8012 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-01 11:33:39.491  2026  2026 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-01 11:33:39.498  7994  7994 I SystemConfig: BUILD Country: EU
,09-01 11:33:39.498  7994  7994 I SystemConfig: BUILD Operator: OPEN
09-01 11:33:39.508  1026  1729 I ActivityManager: Killing 7208:com.android.chrome/u0a57 (adj 15): empty #17
09-01 11:33:39.532  2026  2942 I GBoardtInterface: onReloaded()
09-01 11:33:39.533  2026  2026 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,09-01 11:33:39.556  1026  1767 W libprocessgroup: failed to open /acct/uid_10057/pid_7208/cgroup.procs: No such file or directory
,09-01 11:33:39.559  3774  3792 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-01 11:33:39.560  1026  1917 I ActivityManager: Killing 7229:com.lge.drmservice/u0a62 (adj 15): empty #17
09-01 11:33:39.565   317  8035 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-01 11:33:39.566   317  8035 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-01 11:33:39.576  1026  1971 W libprocessgroup: failed to open /acct/uid_10062/pid_7229/cgroup.procs: No such file or directory
,09-01 11:33:39.580  2350  2485 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-01 11:33:39.581  7994  8032 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-01 11:33:39.581  7994  8032 I SystemConfig: existFile = false
09-01 11:33:39.581  7994  8032 I SystemConfig: canReadFile = false
09-01 11:33:39.581  7994  8032 I SystemConfig: systemFeature RCS result false
09-01 11:33:39.581  7994  8032 D SystemConfig: refreshRcsSupport() :false
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:33:39.581  2350  2485 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 11:33:39.582  2350  8036 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-01 11:33:39.587  2350  8036 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
09-01 11:33:39.588  2350  8036 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-01 11:33:39.588  2350  8036 E AndroidRuntime: Process: android.process.acore, PID: 2350
09-01 11:33:39.588  2350  8036 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delet,e(DbModifierWithNotification.java:161)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-01 11:33:39.588  2350  8036 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 11:33:39.605   317  8035 D libc-netbsd: res_queryN name = android.clients.google.com succeed

```
