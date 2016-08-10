#### Test 797510159390029_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-10 08:49:49.517  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=780306535 [*alarm*], flags=0x0
,--------- beginning of main
08-10 08:49:59.126  6578  6578 D AndroidRuntime: 
08-10 08:49:59.126  6578  6578 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-10 08:49:59.132  6578  6578 D AndroidRuntime: CheckJNI is OFF
08-10 08:49:59.257  6578  6578 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-10 08:49:59.262  1036  1052 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 08:49:59.272  1939  3989 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-10 08:49:59.276  1036  1052 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-10 08:49:59.277  1036  1052 D ActivityManager: setTaskToReturnTo : TaskRecord{2e1f58b0 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 08:49:59.277  1036  1052 D ActivityManager: setTaskToReturnTo : TaskRecord{2e1f58b0 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 08:49:59.278  1036  1052 D WindowStateEx: AppWindowTokenEx init.. 
08-10 08:49:59.279   338   356 E GBMv2   : DFP En is all cleared set to be enabled
08-10 08:49:59.313  1036  1052 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6597 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-10 08:49:59.314  6578  6578 D AndroidRuntime: Shutting down VM
08-10 08:49:59.380  1939  3989 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-10 08:49:59.381  1939  3989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c9b3067 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-10 08:49:59.381  1939  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-10 08:49:59.382  1939  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3d7d2e14 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-10 08:49:59.451  6597  6597 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-10 08:49:59.551  6597  6597 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 08:49:59.562  6597  6597 I LibraryLoader: Loading: webviewchromium
,08-10 08:49:59.565  6597  6597 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6662-6666)
08-10 08:49:59.566  6597  6597 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 08:49:59.583  6597  6597 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {920f5ad}
,08-10 08:49:59.585  6597  6597 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 08:49:59.586  6597  6597 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 08:49:59.595  6597  6597 I BrowserStartupController: Initializing chromium process, renderers=0
,08-10 08:49:59.597  6597  6597 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 08:49:59.607  6597  6597 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 08:49:59.608  6597  6597 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-10 08:49:59.608  6597  6597 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-10 08:49:59.614   315  2138 V AudioPolicyService: registerClient() client 0xb558ab60, uid 10118
08-10 08:49:59.620  1036  1118 D BluetoothManagerService: Message: 20
08-10 08:49:59.620  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d002fba:true
08-10 08:49:59.629  6597  6597 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 08:49:59.629  6597  6597 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 08:49:59.629  6597  6597 I Adreno-EGL: Build Date: 12/12/14 금
08-10 08:49:59.629  6597  6597 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 08:49:59.629  6597  6597 I Adreno-EGL: Remote Branch: 
08-10 08:49:59.629  6597  6597 I Adreno-EGL: Local Patches: 
08-10 08:49:59.629  6597  6597 I Adreno-EGL: Reconstruct Branch: 
,08-10 08:49:59.704  6597  6628 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-10 08:49:59.711  6597  6597 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-10 08:49:59.727  6597  6597 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 08:49:59.732  6597  6597 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-10 08:49:59.735  6597  6597 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-10 08:49:59.737  6597  6597 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-10 08:49:59.737  6597  6597 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-10 08:49:59.753  6597  6597 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-10 08:49:59.760  6597  6597 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 08:49:59.760  6597  6597 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 08:49:59.800  6597  6644 D OpenGLRenderer: Render dirty regions requested: true
08-10 08:49:59.800  6597  6644 I OpenGLRenderer: Initialized EGL, version 1.4
08-10 08:49:59.808  6597  6644 D OpenGLRenderer: Enabling debug mode 0
,08-10 08:49:59.815  6597  6597 D Atlas   : Validating map...
08-10 08:49:59.819  1036  1051 D SplitWindow: check instance of lgWin Window{3927aca4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 08:49:59.857  6597  6638 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 08:49:59.857  6597  6638 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:49:59.954  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +575ms (total +674ms)
08-10 08:49:59.955  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{387e9329 u0 com.test.thalitest/.MainActivity t6} time:287056
08-10 08:49:59.963  6597  6597 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@28e97c60 time:287064
,08-10 08:50:00.048  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 08:50:00.048  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 08:50:00.048  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 08:50:00.048  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-10 08:50:00.050  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 08:50:00.050  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-10 08:50:00.051  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-10 08:50:00.052  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 08:50:00.068  6597  6597 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-10 08:50:00.068  6597  6597 I chromium: 
,08-10 08:50:00.110  6597  6597 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 08:50:00.170  6597  6638 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-10 08:50:00.170  6597  6638 I chromium: 
,08-10 08:50:00.338  6597  6651 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060736
,08-10 08:50:00.354  6597  6651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 08:50:00.354  6597  6651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 08:50:00.354  6597  6651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 08:50:00.354  6597  6651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 08:50:00.354  6597  6651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 08:50:00.355  6597  6651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ccf9324 added. We now have 1 listener(s)
,08-10 08:50:00.362  1036  1717 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:00.369  6597  6651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-10 08:50:00.380  6597  6651 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 08:50:00.382  6597  6651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 08:50:00.383  6597  6651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 08:50:00.393  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 08:50:00.394  6597  6651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e69a053 added. We now have 1 listener(s)
,08-10 08:50:00.394  6597  6651 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 08:50:00.399  1036  1542 D WifiService: New client listening to asynchronous messages
08-10 08:50:00.403  6597  6651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 08:50:00.404  6597  6651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 08:50:00.406  6597  6651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 08:50:00.406  6597  6651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 08:50:00.406  6597  6651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 08:50:00.409  6597  6651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 08:50:00.411  1036  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:00.412  6597  6651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-10 08:50:00.421  6597  6651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 08:50:00.422  6597  6651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:00.422  6597  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:00.422  6597  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:00.422  6597  6651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:00.422  6597  6651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:00.422  6597  6651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:00.422  6597  6651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:00.422  6597  6651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:00.422  6597  6651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 08:50:00.422  6597  6651 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 08:50:00.426  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:00.428  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:00.429  6597  6651 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 08:50:00.467  6597  6597 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 08:50:00.761   338   358 E GBMv2   : DFP En is all cleared set to be enabled
08-10 08:50:00.761   338   358 E GBMv2   : Set value is all cleared set the max
08-10 08:50:00.761   338   358 I GBMv2   : DFP Enabled. Ignore VFP set
,08-10 08:50:01.577  6597  6654 W jxcore-log: Initializing JXcore engine
08-10 08:50:01.577  6597  6654 W jxcore-log: JXcore engine is ready
,08-10 08:50:01.663  6654  6654 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10314]" dev="sockfs" ino=10314 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-10 08:50:01.663  6654  6654 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-10 08:50:01.663  6654  6654 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8689]" dev="sockfs" ino=8689 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-10 08:50:01.663  6654  6654 W Thread-767: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-10 08:50:01.663  6654  6654 W Thread-767: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32193]" dev="sockfs" ino=32193 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-10 08:50:01.705  6597  6654 W jxcore-log: Starting JXcore engine
,08-10 08:50:01.859  6597  6654 W jxcore-log: Platform android
08-10 08:50:01.859  6597  6654 W jxcore-log: 
08-10 08:50:01.859  6597  6654 W jxcore-log: Process ARCH arm
08-10 08:50:01.859  6597  6654 W jxcore-log: 
,08-10 08:50:02.122  6597  6654 I jxcore-log: JXcore Cordova bridge is ready!
08-10 08:50:02.122  6597  6654 I jxcore-log: 
,08-10 08:50:02.123  6597  6654 W jxcore-log: JXcore engine is started
,08-10 08:50:02.135  6597  6651 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-10 08:50:02.142  6597  6597 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 08:50:17.914  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 08:50:17.914  6597  6654 I jxcore-log: 
,08-10 08:50:17.917  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 08:50:17.917  6597  6654 I jxcore-log: 
08-10 08:50:17.921  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:17.921  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:17.921  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:17.921  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:17.921  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:17.921  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:17.921  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:17.921  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:17.925  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:17.927  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 08:50:17.927  6597  6654 I jxcore-log: 
,08-10 08:50:17.929  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 08:50:17.929  6597  6654 I jxcore-log: 
08-10 08:50:18.264  6597  6654 D ExecuteNativeTests: Running unit tests
,08-10 08:50:18.346  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-10 08:50:18.346  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 added. We now have 2 listener(s)
08-10 08:50:18.346  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:18.347  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 08:50:18.348  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-10 08:50:18.348  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:18.348  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:18.348  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d added. We now have 2 listener(s)
08-10 08:50:18.348  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 08:50:18.351  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 08:50:18.354  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:18.357  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:18.357  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:18.357  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:18.357  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:18.357  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:18.357  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:18.357  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:18.357  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:18.359  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:18.359  6597  6654 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 08:50:18.361  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:18.362  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 08:50:18.365  6597  6654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 08:50:18.365  6597  6654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 08:50:18.366  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:18.368  6597  6654 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-10 08:50:18.369  6597  6654 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 08:50:18.369  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 08:50:18.369  6597  6654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 08:50:18.369  6597  6654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 08:50:18.370  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.370  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.370  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.371  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.371  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.371  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:18.371  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 08:50:18.371  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 removed from the list
08-10 08:50:18.371  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.371  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d removed from the list
08-10 08:50:18.371  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.371  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.371  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.371  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.372  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.372  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.372  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.372  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.373  6597  6654 D io.jxcore.node.ConnectionHelper: onBluetoothMa,cAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-10 08:50:18.373  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.374  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.374  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.374  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.374  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.374  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.374  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.374  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.374  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.374  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.374  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.374  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.374  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.374  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.374  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.374  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 08:50:18.374  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 08:50:18.374  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 08:50:18.381  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAll,OutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 08:50:18.382  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.382  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.382  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.382  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.382  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.382  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.382  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.382  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.382  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
,08-10 08:50:18.382  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.382  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.382  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.382  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.382  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.384  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.384  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.384  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.384  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.384  6597  6654 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 08:50:18.386  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:18.388  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:18.388  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:18.388  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:18.388  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:18.388  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:18.388  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:18.388  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:18.388  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:18.388  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:18.389  6597  6654 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 08:50:18.390  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:18.390  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 08:50:18.390  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 08:50:18.391  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 08:50:18.391  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:18.391  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 08:50:18.393  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:18.394  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 08:50:18.394  1036  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:18.398  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 08:50:18.402  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 08:50:18.403  6597  6654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 08:50:18.404  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 08:50:18.404  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:18.405  6597  6654 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 08:50:18.406  6597  6654 I io.jxcore.node.ConnectionHelper: start: OK
08-10 08:50:18.407  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.408  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.408  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.408  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.408  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.408  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:18.408  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.408  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.408  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.408  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.408  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.408  6597  6654 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 08:50:18.409  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:18.411  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:18.411  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:18.411  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:18.411  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:18.411  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:18.411  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:18.411  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:18.411  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 08:50:18.412  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:18.412  6597  6654 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 08:50:18.413  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:18.415  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:18.415  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 08:50:18.415  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 08:50:18.415  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 08:50:18.415  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:18.415  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 08:50:18.418  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 08:50:18.418  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:18.419  6597  6654 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 08:50:18.419  6597  6654 I io.jxcore.node.ConnectionHelper: start: OK
08-10 08:50:18.420  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.420  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.420  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.421  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.421  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.421  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:18.421  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.421  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.421  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.421  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.421  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.421  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.421  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.422  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.422  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.423  6597  6654 D BluetoothLeScanne,r: could not find callback wrapper
08-10 08:50:18.423  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.423  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.423  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.424  6597  6654 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-10 08:50:18.425  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:18.427  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:18.427  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:18.427  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:18.427  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:18.427  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:18.427  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:18.427  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:18.427  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:18.428  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:18.428  6597  6654 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 08:50:18.429  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 08:50:18.429  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 08:50:18.429  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 08:50:18.429  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:18.429  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 08:50:18.429  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:18.431  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:18.432  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 08:50:18.432  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:18.433  6597  6654 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 08:50:18.433  6597  6654 I io.jxcore.node.ConnectionHelper: start: OK
08-10 08:50:18.433  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.433  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.433  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.434  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.434  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.434  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.434  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.434  6597  6654 W ,org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.434  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:18.434  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.434  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.434  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.434  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.434  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.434  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.434  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.435  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.435  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.435  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:18.435  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.435  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.436  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.436  6597  6654 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-10 08:50:18.436  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.436  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.436  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.436  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.437  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.437  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.437  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.437  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.437  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.437  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.437  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.437  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.437  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.437  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.437  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.437  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.438  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:18.438  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.438  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.438  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.439  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 08:50:18.439  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.439  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.439  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.439  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.439  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.439  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.439  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.439  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.439  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.439  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.439  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.439  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.439  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.439  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.440  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.440  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.441  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:18.441  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.441  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.441  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.441  6597  6654 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-10 08:50:18.441  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.441  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.441  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.442  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.442  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.442  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.442  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.442  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.442  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.442  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.442  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.442  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.442  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.442  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.442  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.443  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.443  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:18.443  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.443  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.443  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.443  6597  6654 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-10 08:50:18.443  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.444  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.444  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.444  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.444  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.444  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.444  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.444  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.444  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.444  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.444  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.444  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.444  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.444  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.445  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.445  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.445  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:18.445  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.445  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.445  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.445  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 08:50:18.446  6597  6654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 08:50:18.446  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 08:50:18.446  6597  6654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 08:50:18.446  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 08:50:18.447  6597  6654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 08:50:18.447  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.447  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.447  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.447  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.447  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.447  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.447  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.447  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.447  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.447  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.447  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.447  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.447  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.447  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.448  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.448  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.448  6597  6654 D BluetoothLeScanner: could not find callback wrapper
,08-10 08:50:18.448  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.448  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.448  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.449  6597  6654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 08:50:18.449  6597  6654 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 08:50:18.449  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 08:50:18.451  6597  6654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 08:50:18.451  6597  6654 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 08:50:18.451  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 08:50:18.452  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 08:50:18.453  6597  6654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 08:50:18.453  6597  6654 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 08:50:18.453  6597  6654 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 08:50:18.453  6597  6654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 08:50:18.453  6597  6654 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 08:50:18.453  6597  6654 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 08:50:18.453  6597  6654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 08:50:18.453  6597  6654 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 08:50:18.453  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 08:50:18.455  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-10 08:50:18.456  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 08:50:18.456  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-10 08:50:18.458  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-10 08:50:18.458  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-10 08:50:18.458  6597  6654 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-10 08:50:18.458  6597  6654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 08:50:18.458  6597  6654 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-10 08:50:18.460  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.461  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.461  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.461  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.461  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.461  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.461  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-10 08:50:18.462  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.462  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.462  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.462  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.462  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.462  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.462  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.462  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.463  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.463  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.464  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:18.464  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.464  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.464  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.467  6597  6654 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-10 08:50:18.468  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.468  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.469  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.469  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.469  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.469  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.469  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.469  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.469  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.469  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.469  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.469  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.469  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.469  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.470  6597  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 831
08-10 08:50:18.472  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.472  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.472  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:18.472  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.472  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.473  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.474  6597  6654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-10 08:50:18.474  6597  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 831)
08-10 08:50:18.474  6597  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 831)
08-10 08:50:18.475  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.475  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.475  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.476  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.476  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.476  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.476  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.476  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.476  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.476  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.476  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.476  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.476  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.476  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.477  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.477  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.478  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:18.478  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.478  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.478  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.479  6597  6654 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 08:50:18.479  6597  6654 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-10 08:50:18.479  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 08:50:18.479  6597  6654 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 08:50:18.479  6597  6654 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 08:50:18.479  6597  6654 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 08:50:18.480  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 08:50:18.480  6597  6654 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 08:50:18.480  6597  6654 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 08:50:18.480  6597  6654 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 08:50:18.480  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 08:50:18.480  6597  6654 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-10 08:50:18.480  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.480  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.480  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.480  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.481  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.481  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.481  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.481  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.481  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.481  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.481  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.481  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.481  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.481  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.482  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.482  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.482  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:18.482  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.482  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.482  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.483  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.483  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.483  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.483  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.483  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.483  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.483  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.483  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.483  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.483  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.483  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.483  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.483  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.483  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.483  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.483  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.483  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.483  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.484  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.484  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.484  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.484  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.484  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.484  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.484  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.484  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.484  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.484  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.484  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.484  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.484  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.484  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:18.484  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.484  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.484  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.486  6597  6654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 08:50:18.486  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:18.487  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-10 08:50:18.487  6597  6654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-10 08:50:18.487  6597  6654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-10 08:50:18.488  6597  6597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-10 08:50:18.488  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-10 08:50:18.488  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 08:50:18.489  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.489  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 08:50:18.489  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-10 08:50:18.489  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-10 08:50:18.489  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.490  6597  6654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-10 08:50:18.490  6597  6597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 08:50:18.490  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.490  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.490  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 08:50:18.490  6597  6654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 08:50:18.490  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 08:50:18.491  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 08:50:18.492  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:18.492  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:18.492  6597  6654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 08:50:18.492  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.492  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.493  6597  6654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 08:50:18.493  6597  6597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 08:50:18.493  6597  6597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 08:50:18.493  6597  6597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 08:50:18.494  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.494  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.494  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.494  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.494  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.494  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.494  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.494  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.495  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.495  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.495  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.495  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.495  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.495  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.495  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.496  6597  6658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-10 08:50:18.496  6597  6658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-10 08:50:18.497  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.497  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.497  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.497  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.498  6597  6654 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-10 08:50:18.498  6597  6597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-10 08:50:18.499  6597  6654 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 08:50:18.499  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 08:50:18.501  6597  6654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 08:50:18.501  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.501  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.501  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.502  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.502  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.502  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.502  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.502  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.502  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.502  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.502  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.502  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.502  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.502  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.503  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.503  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.503  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.503  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.504  1036  1972 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:18.505  1036  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:18.505  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:18.506  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.506  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.506  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.506  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.506  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.506  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.506  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.506  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.506  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.506  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.506  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.506  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.506  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.506  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.507  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.507  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.507  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.507  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.508  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:18.508  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:18.508  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:18.508  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:18.508  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.508  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.508  6597  6654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478a6e4 not in the list
08-10 08:50:18.508  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.508  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.508  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:18.508  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.508  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.508  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:18.508  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:18.510  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:18.510  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:18.510  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:18.510  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2290b74d not in the list
08-10 08:50:18.511  6597  6654 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-10 08:50:18.511  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 08:50:18.512  6597  6654 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 08:50:18.512  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 08:50:18.513  6597  6654 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-10 08:50:18.513  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 08:50:18.519  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 08:50:18.519  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-10 08:50:18.522  6597  6654 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-10 08:50:18.522  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 08:50:18.522  6597  6654 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-10 08:50:18.523  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 08:50:18.523  6597  6654 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-10 08:50:18.523  6597  6654 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-10 08:50:18.525  6597  6654 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-10 08:50:18.525  6597  6654 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-10 08:50:18.527  6597  6654 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-10 08:50:18.527  6597  6654 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 08:50:18.527  6597  6654 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-10 08:50:18.528  6597  6654 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-10 08:50:18.530  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:18.530  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fa37f5a added. We now have 2 listener(s)
08-10 08:50:18.530  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:18.531  6597  6654 D BluetoothAdapter: enable(): BT is already enabled..!
,08-10 08:50:18.531  1036  1885 D WifiServiceImplEx: setWifiEnabled: true pid=6597, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 08:50:18.532  1036  1885 D WifiService: setWifiEnabled: true pid=6597, uid=10118
08-10 08:50:18.532  1036  1885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 08:50:18.533  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:18.533  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3306d58b added. We now have 3 listener(s)
,08-10 08:50:18.533  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:18.536  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:18.536  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37b7668 added. We now have 4 listener(s)
08-10 08:50:18.537  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:18.538  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:18.538  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16154a81 added. We now have 5 listener(s)
08-10 08:50:18.538  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:18.540  1036  1885 D WifiServiceImplEx: setWifiEnabled: false pid=6597, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 08:50:18.540  1036  1885 D WifiService: setWifiEnabled: false pid=6597, uid=10118
08-10 08:50:18.540  1036  1885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 08:50:18.558  1036  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:18.559  1036  2030 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@502b517 mBinding = false
08-10 08:50:18.559  1036  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 08:50:18.559  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 08:50:18.559  1036  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-10 08:50:18.560  1036  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-10 08:50:18.560  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-10 08:50:18.560  1036  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 08:50:18.560  1036  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 08:50:18.560  1036  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 08:50:18.561  1036  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 08:50:18.561  1036  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 08:50:18.562  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 08:50:18.563  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-10 08:50:18.563  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-10 08:50:18.573  1036  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 08:50:18.573  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 08:50:18.573  1036  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 08:50:18.573  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:18.573  2742  2742 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 08:50:18.574  1036  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-10 08:50:18.574  1036  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 08:50:18.574  1036  1537 D WifiNative-wlan0: SET ps 1: returned true
08-10 08:50:18.574  1036  2867 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 08:50:18.575   311   905 D CommandListener: Clearing all IP addresses on wlan0
,08-10 08:50:18.581  1036  1118 D BluetoothManagerService: Message: 2
08-10 08:50:18.584  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 08:50:18.584  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 08:50:18.584  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-10 08:50:18.585  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:18.586  1036  1118 D BluetoothManagerService: Sending off request.
08-10 08:50:18.587  3889  3904 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-10 08:50:18.588  3889  3972 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-10 08:50:18.588  3889  3972 D BluetoothAdapterProperties: Setting state to 13
08-10 08:50:18.588  3889  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 08:50:18.603  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 08:50:18.603  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-10 08:50:18.604  3889  3972 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 08:50:18.604  3889  3972 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-10 08:50:18.606  1036  1118 D BluetoothManagerService: Message: 60
08-10 08:50:18.606  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-10 08:50:18.606  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-10 08:50:18.620  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:18.627  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:18.627  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:18.627  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:18.627  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:18.627  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:18.627  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:18.627  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:18.627  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:18.628  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:18.628  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:18.628  6597  6654 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 08:50:18.630  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-10 08:50:18.632  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:18.632  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:18.632  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 08:50:18.633  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:18.633  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:18.634  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:18.636  1036  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:18.637  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:18.637  1036  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:18.637  1036  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:18.637  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:18.638  1036  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2f86fe13
08-10 08:50:18.638  1036  1536 D LGWifiP2pService: P2pDisablingState
08-10 08:50:18.638  1036  1536 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:18.638  1036  1536 D LGWifiP2pService: p2p socket connection lost
08-10 08:50:18.638  1036  1536 D LGWifiP2pService: P2pDisabledState
08-10 08:50:18.639  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:18.639  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:18.639  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:18.639  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:18.639  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:18.639  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:18.639  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:18.639  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:18.639  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:18.641  1036  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:18.641  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:18.642  1036  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-10 08:50:18.642  1036  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 08:50:18.643  1036  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-10 08:50:18.643  1036  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:18.644  1036  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:18.644  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 08:50:18.645  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:18.645  2742  2742 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 08:50:18.645  1036  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 08:50:18.645  1036  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 08:50:18.646  1036  1537 D WifiNative-wlan0: SET ps 1: returned true
,08-10 08:50:18.647  3889  3889 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:18.647  3889  3889 D BluetoothMapService: STATE_TURNING_OFF
,08-10 08:50:18.648  3889  3889 V BtOppService: Receiver DISABLED_ACTION 
,08-10 08:50:18.648  3889  3889 V BluetoothMapService: Handler(): got msg=4
08-10 08:50:18.648  3889  3889 D BluetoothMapService: MAP Service closeService in
08-10 08:50:18.648  3889  3889 D BluetoothMapMasInstance: MAP Service shutdown
08-10 08:50:18.648  3889  4220 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-10 08:50:18.648  3889  4220 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 08:50:18.648  3889  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-10 08:50:18.648  3889  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-10 08:50:18.648  3889  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-10 08:50:18.648  3889  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-10 08:50:18.648  3889  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-10 08:50:18.648  3889  4220 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-10 08:50:18.649  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:18.649  3889  3889 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 08:50:18.649  3889  3889 V BluetoothMapService: MAP Service closeService out
08-10 08:50:18.649  3889  3889 I BtOppRfcommListener: stopping Accept Thread
08-10 08:50:18.649  3889  3889 V BtOppRfcommListener: close mBtServerSocket
08-10 08:50:18.649  3889  3889 V BtOppRfcommListener: waiting for thread to terminate
08-10 08:50:18.650  3889  4255 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 08:50:18.650  3889  4255 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 08:50:18.650  3889  3889 V BtOppRfcommListener: done waiting for thread to terminate
08-10 08:50:18.652  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-10 08:50:18.652  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:18.653  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:18.653  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:18.653  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:18.653  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:18.653  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:18.653  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:18.653  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:18.653  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:18.653  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:18.654  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:18.654  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:18.655   311   905 D CommandListener: Clearing all IP addresses on wlan0
08-10 08:50:18.659  1036  1543 D ConnectivityService: Default n,etwork via Wi-Fi disconnect. stop DSQN
08-10 08:50:18.659  1036  1543 D DSQN    : disableDataServiceNotify
08-10 08:50:18.659  1036  1543 D DSQN    : stop dsqn bin
08-10 08:50:18.661  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:18.663  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-10 08:50:18.677  1036  1103 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6678 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 08:50:18.679  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-10 08:50:18.679  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:18.679  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:18.679  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 08:50:18.679  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-10 08:50:18.679  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-10 08:50:18.680  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 08:50:18.680  1939  1939 D WfdsService: WifiP2pState is changed : false
08-10 08:50:18.680  1939  2327 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-10 08:50:18.680  1939  2327 D WfdsService: Set the WFDS Monitor: false
08-10 08:50:18.680  1036  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:18.681  1036  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:18.681  1036  1537 D WifiNative-p2p0: doBoolean: TERMINATE
08-10 08:50:18.682  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-10 08:50:18.682  1036  1537 D WifiNative-p2p0: TERMINATE: returned true
08-10 08:50:18.682  1036  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 08:50:18.682  1036  1537 E WifiStateMachine: useWiFiOffloading() : false
08-10 08:50:18.682  1036  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 08:50:18.684  1939  2327 D WfdsMonitor: WFDS Monitor is stopped
08-10 08:50:18.684  1939  2327 D WfdsService: STATE : WfdsDisabledState - enter
08-10 08:50:18.684  1939  2328 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-10 08:50:18.684  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:18.684  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:18.684  1939  2771 D CtrlSupplicant: Received on exit socket, terminate
08-10 08:50:18.684  1939  2771 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-10 08:50:18.684  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 08:50:18.684  1939  2771 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-10 08:50:18.684  1939  2771 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-10 08:50:18.684  1036  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-10 08:50:18.685  3889  3889 V BtOppService: onDestroy
08-10 08:50:18.685  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:18.685  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:18.685  1939  2327 W WfdsService: DefaultState - msg [9445378] is not handled
08-10 08:50:18.686  1036  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:18.686  1036  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-10 08:50:18.686  1036  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:18.686  1036  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, r,eason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-10 08:50:18.687  1036  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-10 08:50:18.687  1602  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-10 08:50:18.687  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 08:50:18.687  1036  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:18.687  1036  2864 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-10 08:50:18.689  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,08-10 08:50:18.689  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:18.689  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-10 08:50:18.690  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-10 08:50:18.692  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:18.692  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:18.692  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:18.692  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:18.692  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:18.692  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:18.692  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:18.692  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:18.692  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:18.692  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:18.692  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:18.693  1036  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:18.693  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 08:50:18.694  1036  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 08:50:18.694  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 08:50:18.694  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 08:50:18.694  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 08:50:18.694  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 08:50:18.695  1036  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:18.696  1036  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:18.696  1036  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:18.696  1036  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 08:50:18.696  1036  1543 D NetworkManagementService: Removing idletimer
08-10 08:50:18.696  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 08:50:18.696  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:18.697  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 08:50:18.697  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 08:50:18.697  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavai,lable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 08:50:18.697  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 08:50:18.697  1036  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:18.697  1036  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:18.697  1036  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 08:50:18.698  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:18.698  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:18.698  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:18.698  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:18.698  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:18.698  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:18.698  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:18.698  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:18.698  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:18.700  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:18.700  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 08:50:18.703  1036  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-10 08:50:18.716  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 08:50:18.716  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:18.717  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:18.747  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-10 08:50:18.747  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 08:50:18.748  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:18.749  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:18.762  2742  2742 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-10 08:50:18.762  2742  2742 I wpa_supplicant: monitor socket send errors count : 1
08-10 08:50:18.762  2742  2742 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-2\x00 that cannot receive messages
,08-10 08:50:18.764  1036  2769 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-10 08:50:18.764  1036  2769 D WifiMonitor: Dropping event because (p2p0) is stopped
08-10 08:50:18.768  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 08:50:18.769  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:18.770  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:18.774  1036  1956 I art     : Explicit concurrent mark sweep GC freed 44642(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.203ms total 187.142ms
,08-10 08:50:18.802  2742  2742 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-10 08:50:18.803  1036  2867 D DhcpStateMachine: StoppedState
08-10 08:50:18.803  1036  2867 D DhcpStateMachine: StoppedState{ when=-157ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:18.803  1036  2769 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-10 08:50:18.803  1036  2769 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 08:50:18.803  1036  2769 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 08:50:18.803  1036  2769 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-10 08:50:18.804  1036  1118 D Tethering: InitialState.processMessage what=4
08-10 08:50:18.804  2742  2742 W wpa_supplicant: USIM:  scard_deinit function
08-10 08:50:18.804  1036  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=305892
08-10 08:50:18.804  1036  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=305892
08-10 08:50:18.804  1036  2769 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 08:50:18.804  1036  2769 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 08:50:18.805  1036  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=305893  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 08:50:18.805  1036  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=305893  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-10 08:50:18.823  1036  1885 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6698 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 08:50:18.826  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 08:50:18.826  1036  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-10 08:50:18.826  1036  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-10 08:50:18.827  3889  3889 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-10 08:50:18.828  3889  3976 D BluetoothAdapterProperties: Scan Mode:20
08-10 08:50:18.829  3889  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-10 08:50:18.829  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-10 08:50:18.829  3889  4055 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-10 08:50:18.829  3889  4276 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 08:50:18.829  3889  3972 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 08:50:18.830  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 08:50:18.830  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 08:50:18.830  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 08:50:18.830  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 08:50:18.830  3889  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 08:50:18.830  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 08:50:18.830  3889  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 08:50:18.831  3889  4222 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 08:50:18.830  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 08:50:18.831  3889  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 08:50:18.831  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-10 08:50:18.831  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-10 08:50:18.831  3889  4055 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 08:50:18.831  3889  4267 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 08:50:18.831  1036  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:18.832  1036  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:18.838  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:18.838  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:18.838  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:18.838  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:18.838  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:18.838  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:18.838  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:18.838  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:18.838  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 08:50:18.840  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:18.840  6597  6597 V io.jxcore.nod,e.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:18.840  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:18.840  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:18.840  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:18.840  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:18.840  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:18.840  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:18.840  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 08:50:18.844  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 08:50:18.845  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:18.845  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:18.852  6678  6678 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 08:50:18.853  6678  6678 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-10 08:50:18.853  6678  6678 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 08:50:18.853  6678  6678 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-10 08:50:18.854  6678  6678 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 08:50:18.854  6678  6678 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-10 08:50:18.875  6698  6698 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-10 08:50:18.877  6698  6698 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 08:50:18.878  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:18.879  1036  1936 I ActivityManager: Killing 5897:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-10 08:50:18.889  2742  2742 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-10 08:50:18.891  1036  2769 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-10 08:50:18.891  1036  2769 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-10 08:50:18.891  1036  2769 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-10 08:50:18.892  1036  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-10 08:50:18.902  1036  1052 W libprocessgroup: failed to open /acct/uid_10014/pid_5897/cgroup.procs: No such file or directory
,08-10 08:50:18.905  1036  1537 D WifiOffDelayIfNotUsed: stopMonitoring
08-10 08:50:18.905  1036  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 08:50:18.905  1036  1537 E WifiStateMachine: useWiFiOffloading() : false
08-10 08:50:18.905  1036  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 08:50:18.906  1939  1939 D WfdsService: Supplicant Connection state is changed : false
08-10 08:50:18.907  1939  2327 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-10 08:50:18.907  1939  2327 D WfdsService: Set the WFDS Monitor: false
08-10 08:50:18.907  1939  2327 D WfdsMonitor: WFDS Monitor is stopped
08-10 08:50:18.908  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 08:50:18.910  2480  2480 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:18.911  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:18.913  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-10 08:50:18.913  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-10 08:50:18.913  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-10 08:50:18.914  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:18.915  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:18.952  6678  6678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-10 08:50:18.956  3889  3889 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 08:50:18.956  3889  3889 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:18.956  3889  3889 V BluetoothPbapReceiver: ***********state = 13
08-10 08:50:18.957  3889  3889 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-10 08:50:18.957  3889  3889 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:18.958  3889  3889 V BluetoothPbapService: state: 13
08-10 08:50:18.958  3889  3889 V BluetoothPbapService: Pbap Service closeService in
08-10 08:50:18.962  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 08:50:18.963  3889  3889 V BluetoothPbapService: successfully stopped pbap service
08-10 08:50:18.964  3889  3889 V BluetoothPbapService: Pbap Service closeService out
08-10 08:50:18.964  3889  3889 V BluetoothPbapService: Pbap Service onDestroy
08-10 08:50:18.964  3889  3889 V BluetoothPbapService: Pbap Service closeService in
08-10 08:50:18.964  3889  3889 V BluetoothPbapService: Pbap Service closeService out
08-10 08:50:18.964  3889  3889 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-10 08:50:18.965  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:18.994  6597  6597 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 08:50:18.994  6678  6678 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:18.994  6678  6678 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 08:50:19.002  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:19.007  1036  1118 D BluetoothManagerService: Message: 20
08-10 08:50:19.007  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@221010e9:true
,08-10 08:50:19.033  1036  1884 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6719 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-10 08:50:19.037  1036  1118 D BluetoothManagerService: Message: 30
08-10 08:50:19.040  1036  1118 D BluetoothManagerService: Message: 30
08-10 08:50:19.045  6678  6678 D LocalBluetoothProfileManager: Adding local MAP profile
08-10 08:50:19.049  6678  6678 D BluetoothMap: Create BluetoothMap proxy object
,08-10 08:50:19.051  1036  1118 D BluetoothManagerService: Message: 30
08-10 08:50:19.055  1036  1118 D BluetoothManagerService: Message: 30
08-10 08:50:19.059  6678  6678 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-10 08:50:19.061  6678  6678 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-10 08:50:19.093  6678  6678 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-10 08:50:19.097  6678  6678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-10 08:50:19.120  6678  6678 D DockEventReceiver: finishStartingService: stopping service
,08-10 08:50:19.145  6678  6678 D BluetoothInputDevice: Proxy object connected
,08-10 08:50:19.150  6678  6678 D HidProfile: Bluetooth service connected
08-10 08:50:19.152  6678  6678 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 08:50:19.154  6678  6678 D PanProfile: Bluetooth service connected
08-10 08:50:19.155  6678  6678 D BluetoothMap: Proxy object connected
,08-10 08:50:19.157  6678  6678 D MapProfile: Bluetooth service connected
08-10 08:50:19.157  6678  6678 D BluetoothMap: getConnectedDevices()
08-10 08:50:19.159  6678  6678 D BluetoothMap: Bluetooth is Not enabled
08-10 08:50:19.159  6678  6678 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-10 08:50:19.189  1036  1993 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6746 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-10 08:50:19.196  1036  1993 I ActivityManager: Killing 6208:com.android.defcontainer/u0a4 (adj 15): empty #17
08-10 08:50:19.240  6719  6719 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-10 08:50:19.241  6719  6719 W LG Account v2.2: No ProfileInfo entries
08-10 08:50:19.241  6719  6719 I LG Account v2.2: isEnabled: false
08-10 08:50:19.241  6719  6719 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-10 08:50:19.241  6719  6719 I Feature : [Lifetracker]Country: EU
08-10 08:50:19.241  6719  6719 I Feature : [Lifetracker]Operator: OPEN
08-10 08:50:19.241  6719  6719 I Feature : [Lifetracker]Ranking support: false
08-10 08:50:19.241  6719  6719 I Feature : [Lifetracker]Comfort support: false
08-10 08:50:19.241  6719  6719 I Feature : [Lifetracker]Accessory: true
08-10 08:50:19.241  6719  6719 I Feature : [Lifetracker]Health device: true
08-10 08:50:19.242  6719  6719 I Feature : [Lifetracker]Extra Pedometer: false
08-10 08:50:19.242  6719  6719 I Feature : [Lifetracker]Blood glucose device: false
08-10 08:50:19.242  6719  6719 I Feature : [Lifetracker]Device Number: 3
,08-10 08:50:19.250  1036  1052 W libprocessgroup: failed to open /acct/uid_10004/pid_6208/cgroup.procs: No such file or directory
08-10 08:50:19.270  6678  6678 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-10 08:50:19.279  6678  6678 D BluetoothPermissionRequest: onReceive
08-10 08:50:19.281  6746  6746 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 08:50:19.281  6678  6678 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-10 08:50:19.292  6678  6678 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 08:50:19.294  1036  2048 I ActivityManager: Killing 6326:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-10 08:50:19.320  3889  3889 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-10 08:50:19.321  3889  3889 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-10 08:50:19.321  1036  1956 W libprocessgroup: failed to open /acct/uid_10008/pid_6326/cgroup.procs: No such file or directory
,08-10 08:50:19.323  3889  3889 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-10 08:50:19.330  3889  3889 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-10 08:50:19.331  3889  3889 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 08:50:19.332  3889  3889 V BluetoothFtpService: Ftp Service onStartCommand
08-10 08:50:19.332  3889  3889 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:19.333  6746  6746 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-10 08:50:19.335  3889  3889 V BluetoothFtpService: Ftp Service closeService
08-10 08:50:19.336  3889  3889 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-10 08:50:19.337  3889  3889 V BluetoothFtpService: successfully stopped ftp service
08-10 08:50:19.337  3889  3889 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 08:50:19.337  3889  3889 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 08:50:19.337  3889  3889 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 08:50:19.337  3889  3889 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:19.338  3889  3889 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-10 08:50:19.338  3889  3889 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 08:50:19.339  3889  3889 V BluetoothFtpService: Ftp Service onDestroy
08-10 08:50:19.339  3889  3889 V BluetoothFtpService: Ftp Service closeService
08-10 08:50:19.374  6746  6746 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-10 08:50:19.375  6746  6746 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-10 08:50:19.375  6746  6746 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-10 08:50:19.376  6746  6746 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-10 08:50:19.376  6746  6746 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-10 08:50:19.378  6746  6746 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-10 08:50:19.384  6746  6746 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-10 08:50:19.402  1036  1574 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6765 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 08:50:19.409  3889  3889 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:19.409  3889  3889 V BluetoothSapService: state: 13
08-10 08:50:19.409  3889  3889 V BluetoothSapService: Stopping SAP server process
08-10 08:50:19.411  3889  3889 V BluetoothSapService: Sap Service closeSapService in
08-10 08:50:19.411  3889  3889 V BluetoothSapService: Close listen Socket : 
08-10 08:50:19.411  3889  3889 V BluetoothSapService: Close rfcomm Socket : 
08-10 08:50:19.411  3889  3889 V BluetoothSapService: Close sapd  Socket : 
08-10 08:50:19.412  3889  3889 V BluetoothSapService: Sap Service closeSapService out
08-10 08:50:19.413  3889  3889 V BluetoothSapService: Sap Service onDestroy
08-10 08:50:19.413  3889  3889 V BluetoothSapService: Sap Service closeSapService in
08-10 08:50:19.413  3889  3889 V BluetoothSapService: Close listen Socket : 
08-10 08:50:19.413  3889  3889 V BluetoothSapService: Close rfcomm Socket : 
08-10 08:50:19.413  3889  3889 V BluetoothSapService: Close sapd  Socket : 
08-10 08:50:19.413  3889  3889 V BluetoothSapService: Sap Service closeSapService out
08-10 08:50:19.416  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:19.419  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:19.428   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 472us total 25.686ms
,08-10 08:50:19.438  6746  6746 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 08:50:19.441  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:19.447  6698  6698 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 08:50:19.447  6698  6698 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 08:50:19.447  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:19.449  6746  6746 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-10 08:50:19.450   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 20.424ms
08-10 08:50:19.454  6746  6746 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-10 08:50:19.459  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:19.470  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:19.471   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 422us total 19.593ms
08-10 08:50:19.481  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:19.481  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 08:50:19.484  6746  6746 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 08:50:19.488  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:19.491  6698  6698 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 08:50:19.491  6698  6698 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 08:50:19.491  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:19.494  6765  6765 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 08:50:19.498  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 08:50:19.504  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:19.509  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:19.509  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 08:50:19.512  1036  1885 I ActivityManager: Killing 5996:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-10 08:50:19.542  1036  1717 W libprocessgroup: failed to open /acct/uid_10011/pid_5996/cgroup.procs: No such file or directory
08-10 08:50:19.543  6746  6746 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-10 08:50:19.626  1036  1884 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6790 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-10 08:50:19.742  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 08:50:19.748  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 08:50:19.760  6790  6810 W FormManager: Network not available. Please check & try again.
08-10 08:50:19.762  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:19.777  6790  6811 V FormManager: Network unavailable.
,08-10 08:50:19.787  6790  6811 V FormManager: Network unavailable.
08-10 08:50:19.791  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 08:50:19.791  6678  6678 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 08:50:19.792  6678  6678 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 08:50:19.792  6678  6678 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 08:50:19.794  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 08:50:19.808  6678  6678 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-10 08:50:19.809  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 08:50:19.809  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 08:50:19.809  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 08:50:19.810  6678  6678 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 08:50:19.812  6678  6678 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 08:50:19.814  1036  1920 I ActivityManager: Killing 6018:com.android.contacts/u0a19 (adj 15): empty #17
08-10 08:50:19.833  3889  3976 D bt_hci_bdroid: cleanup
08-10 08:50:19.833  3889  4055 W bt-btif : ag scb idx 1 not allocated
08-10 08:50:19.833  3889  4055 E bt-btif : BTA AG is already disabled, ignoring ...
08-10 08:50:19.833  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 08:50:19.833  3889  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-10 08:50:19.833  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 08:50:19.833  3889  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-10 08:50:19.833  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 08:50:19.833  3889  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 08:50:19.833  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 08:50:19.833  3889  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 08:50:19.833  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 08:50:19.833  3889  4211 I bt_userial_mct: exiting userial_read_thread
08-10 08:50:19.833  3889  4211 D bt_userial_mct: Leaving userial_evt_read_thread()
08-10 08:50:19.833  3889  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 08:50:19.834  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 08:50:19.834  3889  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 08:50:19.834  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 08:50:19.834  3889  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 08:50:19.834  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 08:50:19.834  3889  3976 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-10 08:50:19.834  3889  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 08:50:19.834  3889  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 08:50:19.834  3889  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 08:50:19.834  3889  4059 I bt_lpm  : LPM is already off!!!
08-10 08:50:19.834  3889  4055 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 08:50:19.834  3889  4059 I bt_vendor: hw_epilog_process
08-10 08:50:19.836  3889  3976 D bt_hci_bdroid: cleanup Finalizing cleanup
08-10 08:50:19.836  3889  3976 D bt_userial_mct: userial_close
,08-10 08:50:19.836  3889  3976 E bt_userial_mct: pthread_join() FAILED result:3
08-10 08:50:19.836  3889  3976 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-10 08:50:19.871  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 08:50:19.871  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 08:50:19.872  1036  1956 W libprocessgroup: failed to open /acct/uid_10019/pid_6018/cgroup.procs: No such file or directory
08-10 08:50:19.876  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 08:50:19.878  1036  1376 D PowerManagerServiceEx: acquireWakeLockInternal: lock=780306535, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
08-10 08:50:19.882  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:19.882  1036  1376 V AlarmManager: ELAPSED_WAKEUP set : Alarm{e1ecc82 type 2 when 306958 com.google.android.gms} when 306958
08-10 08:50:19.898  6698  6698 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-10 08:50:19.898  6698  6698 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 08:50:19.898  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 08:50:19.899  4353  6815 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 08:50:19.902  4353  6817 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-10 08:50:19.902  4353  6817 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 08:50:19.907  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 08:50:19.910  3889  3976 D bt_hci_bdroid: set_power 0
08-10 08:50:19.910  3889  3976 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-10 08:50:19.910  3889  3976 I bt_vendor: bluetooth satus is on
,08-10 08:50:19.910  3889  3976 I bt_vendor: bt-vendor : resetting BT status
08-10 08:50:19.910  3889  3976 I bt_vendor: Starting hciattach daemon
08-10 08:50:19.910  3889  3976 I bt_vendor: try to set false
08-10 08:50:19.910  3889  3976 I bt_vendor: Starting hciattach daemon
08-10 08:50:19.910  3889  3976 I bt_vendor: try to set false
08-10 08:50:19.911  3889  3976 I bt_vendor: cleanup
08-10 08:50:19.911  3889  4055 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-10 08:50:19.912  3889  3976 I GKI_LINUX: GKI_exit_task 0 done
08-10 08:50:19.912  3889  3976 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-10 08:50:19.913  3889  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-10 08:50:19.916  3889  3889 D HeadsetService: Received stop request...Stopping profile...
08-10 08:50:19.919  3889  3889 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 08:50:19.919  3889  3889 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 08:50:19.919  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eb180e2
08-10 08:50:19.920  3889  4003 D HeadsetStateMachine: Exit Disconnected: -1
08-10 08:50:19.922  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-10 08:50:19.922  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-10 08:50:19.923  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-10 08:50:19.923  3889  3889 D A2dpService: Received stop request...Stopping profile...
08-10 08:50:19.923  3889  4041 D A2dpStateMachine: Exit Disconnected: -1
08-10 08:50:19.924  1850  1850 D BluetoothHeadset: Proxy object disconnected
,08-10 08:50:19.927  3889  3889 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-10 08:50:19.928  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-10 08:50:19.928  6790  6818 W FormManager: Network not available. Please check & try again.
08-10 08:50:19.929  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:19.934  3889  3889 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-10 08:50:19.934  3889  3889 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 08:50:19.934  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eb180e2
08-10 08:50:19.935  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-10 08:50:19.935  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-10 08:50:19.936  2594  2594 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 08:50:19.938  3889  3889 D HidService: Received stop request...Stopping profile...
08-10 08:50:19.938  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eb180e2
08-10 08:50:19.946  3889  3972 D BluetoothAdapterState: Stopping profile services that were post enabled
08-10 08:50:19.947  6678  6678 D BluetoothInputDevice: Proxy object disconnected
,08-10 08:50:19.947  6678  6678 D HidProfile: Bluetooth service disconnected
08-10 08:50:19.947  3889  3889 D HeadsetStateMachine: Unbinding service...
08-10 08:50:19.948  3889  3889 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 08:50:19.948  3889  3889 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,08-10 08:50:19.948  3889  3889 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,08-10 08:50:19.948  3889  3889 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 08:50:19.948  3889  3889 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 08:50:19.948  3889  3889 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 08:50:19.948  3889  3889 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 08:50:19.949  3889  3889 D HealthService: Received stop request...Stopping profile...
08-10 08:50:19.949  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eb180e2
08-10 08:50:19.952  3889  3889 D PanService: Received stop request...Stopping profile...
08-10 08:50:19.953  6790  6819 V FormManager: Network unavailable.
08-10 08:50:19.956  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eb180e2
08-10 08:50:19.957  6678  6678 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 08:50:19.957  6678  6678 D PanProfile: Bluetooth service disconnected
08-10 08:50:19.957  3889  3889 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 08:50:19.957  3889  3889 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 08:50:19.957  3889  3889 D BtGatt.GattService: stop()
08-10 08:50:19.958  3889  3889 D BtGatt.AdvertiseManager: advertise clients cleared
08-10 08:50:19.961  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eb180e2
,08-10 08:50:19.963  6790  6819 V FormManager: Network unavailable.
08-10 08:50:19.963  3889  3889 I BluetoothA2dpServiceJni: cleanupNative
08-10 08:50:19.963  3889  4042 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-10 08:50:19.964  3889  3889 I GKI_LINUX: GKI_exit_task 2 done
08-10 08:50:19.964  3889  3889 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-10 08:50:19.965  3889  3889 D BluetoothMapService: Received stop request...Stopping profile...
08-10 08:50:19.965  3889  3889 D BluetoothMapService: stop()
08-10 08:50:19.966  3889  3889 D BluetoothMapEmailAppObserver: deinitObservers()
08-10 08:50:19.966  3889  3889 D BluetoothMapEmailAppObserver: removeReceiver()
08-10 08:50:19.967  3889  3889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eb180e2
08-10 08:50:19.968  3889  3889 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 08:50:19.968  6678  6678 D BluetoothMap: Proxy object disconnected
08-10 08:50:19.968  3889  3889 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-10 08:50:19.968  6678  6678 D MapProfile: Bluetooth service disconnected
08-10 08:50:19.968  3889  3889 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 08:50:19.968  3889  3889 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 08:50:19.969  3889  3889 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 08:50:19.969  3889  3889 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 08:50:19.969  3889  3889 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 08:50:19.971  3889  3889 V BluetoothMapService: Handler(): got msg=4
08-10 08:50:19.971  3889  3889 D BluetoothMapService: MAP Service closeService in
08-10 08:50:19.971  3889  3889 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 08:50:19.971  3889  3889 V BluetoothMapService: MAP Service closeService out
08-10 08:50:19.971  3889  3889 D BluetoothMapService: cleanup()
08-10 08:50:19.971  3889  3889 D BluetoothMapService: MAP Service closeService in
08-10 08:50:19.971  3889  3889 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 08:50:19.971  3889  3889 V BluetoothMapService: MAP Service closeService out
08-10 08:50:19.971  3889  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-10 08:50:19.971  3889  3972 D BluetoothAdapterProperties: Setting state to 10
08-10 08:50:19.971  3889  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-10 08:50:19.972  1036  1118 D BluetoothManagerService: Message: 60
08-10 08:50:19.972  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-10 08:50:19.972  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-10 08:50:19.972  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 08:50:19.972  3889  3972 I BluetoothAdapterState: Entering OffState
08-10 08:50:19.974  6678  6694 D BluetoothMap: onBluetoothStateChange: up=false
08-10 08:50:19.975  6678  6693 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-10 08:50:19.980  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 08:50:19.981  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 08:50:19.982  6746  6746 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 08:50:19.983  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 08:50:19.984  6746  6746 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-10 08:50:19.989  1850  2402 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 08:50:19.992  6678  6694 D BluetoothPbap: onBluetoothStateChange: up=false
,08-10 08:50:19.995  6678  6693 D BluetoothPan: onBluetoothStateChange on: false
08-10 08:50:19.996  1850  2775 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 08:50:19.999  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-10 08:50:19.999  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-10 08:50:20.002  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-10 08:50:20.002  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-10 08:50:20.002  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@502b517 mBinding = false
08-10 08:50:20.003  1036  1118 D BluetoothManagerService: Sending unbind request.
08-10 08:50:20.004  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-10 08:50:20.006  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-10 08:50:20.006  1939  2123 D LGBluetoothAPIService: Message: 2
08-10 08:50:20.007  1939  2123 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@9cee6bd mBinding = false
08-10 08:50:20.007  1939  2123 D LGBluetoothAPIService: Sending unbind request.
08-10 08:50:20.007  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 08:50:20.010  6678  6678 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 08:50:20.010  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:20.010  6678  6678 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-10 08:50:20.011  6678  6678 D LGBluetoothEventManager: [BTUI] clear device connection state
08-10 08:50:20.012  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:20.014  1602  1602 D BluetoothAdapter: 786584250: getState() :  mService = null. Returning STATE_OFF
08-10 08:50:20.015  1602  1602 D BluetoothAdapter: 786584250: getState() :  mService = null. Returning STATE_OFF
08-10 08:50:20.018  3889  3976 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-10 08:50:20.018  3889  3889 I GKI_LINUX: GKI_exit_task 1 done
08-10 08:50:20.018  3889  3889 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-10 08:50:20.019  3889  3889 I BluetoothServiceJni: cleanupNative: return from cleanup
08-10 08:50:20.019  3889  3889 I art     : --- WEIRD: removing null entry 246
08-10 08:50:20.019  3889  3889 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-10 08:50:20.019  3889  3889 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-10 08:50:20.020  3889  3889 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-10 08:50:20.021  6678  6678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-10 08:50:20.024  3889  3889 I art     : System.exit called, status: 0
08-10 08:50:20.024  3889  3889 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-10 08:50:20.028  6678  6678 D DockEventReceiver: finishStartingService: stopping service
08-10 08:50:20.044  6678  6678 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-10 08:50:20.044   315   315 V AudioFlinger: 3889 died, releasing its sessions
08-10 08:50:20.044   315   315 V AudioFlinger:  pid 1850 @ 0
08-10 08:50:20.044   315   315 V AudioFlinger:  pid 3462 @ 1
08-10 08:50:20.044   315   315 V AudioFlinger:  pid 3462 @ 2
,08-10 08:50:20.050  6746  6746 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:20.050  6746  6746 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 08:50:20.057  6746  6746 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-10 08:50:20.058  6746  6746 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-10 08:50:20.058  6746  6746 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
,08-10 08:50:20.058  6746  6746 V SoundPool: doLoad: loading sample sampleID=1
,08-10 08:50:20.059  6746  6746 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 08:50:20.060  6746  6824 V SoundPool: Start decode
08-10 08:50:20.060  6746  6824 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-10 08:50:20.060   315  1385 V MediaPlayerService: decode(23, 10857164, 17813)
08-10 08:50:20.060   315  1385 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-10 08:50:20.060   315  1385 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-10 08:50:20.060   315  1385 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-10 08:50:20.060   315  1385 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-10 08:50:20.060   315  1385 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-10 08:50:20.060   315  1385 V MediaPlayerService: player type = 3
08-10 08:50:20.060   315  1385 V AwesomePlayer: AwesomePlayer create()
08-10 08:50:20.061   315  1385 V AwesomePlayer: reset_l() 
08-10 08:50:20.061   315  1385 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:20.061   315  1385 V AwesomePlayer: setAudioSink() 
08-10 08:50:20.061   315  1385 V AwesomePlayer: reset_l() 
08-10 08:50:20.061   315  1385 V AudioCache: notify(0xb1432200, 8, 0, 0)
08-10 08:50:20.061   315  1385 V AudioCache: ignored
08-10 08:50:20.061   315  1385 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:20.061   315  1385 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-10 08:50:20.061   315  1385 V AwesomePlayer: setDataSource_l dataSource
08-10 08:50:20.061   315  1385 V LGParserOSAL: SniffLGParser start
08-10 08:50:20.061   315  1385 V LGParserOSAL: MainType:5, SubType=0
08-10 08:50:20.061   315  1385 V LGParserOSAL: #### check Mime : application/ogg
08-10 08:50:20.061   315  1385 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-10 08:50:20.061   315  1385 E MediaExtractor: Use LGExtractor :application/ogg 
08-10 08:50:20.089  1036  1574 I ActivityManager: Process com.android.bluetooth (pid 3889) has died
08-10 08:50:20.089  1036  1574 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-10 08:50:20.095  6515  6515 D UEI.SmartControl: QS Service created
08-10 08:50:20.096  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 08:50:20.096  6746  6746 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-10 08:50:20.097  6746  6746 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 08:50:20.097  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-10 08:50:20.108  6678  6678 D BluetoothPermissionRequest: onReceive
,08-10 08:50:20.111  6678  6678 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 08:50:20.112  6678  6678 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-10 08:50:20.113  6746  6746 V LGMDMManager: Create singleton instance
08-10 08:50:20.115  6678  6678 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 08:50:20.116  6515  6515 I UEI.SmartControl: Service initServices...
08-10 08:50:20.116   315  1385 V LGParserOSAL: supported mime: application/ogg
08-10 08:50:20.116   315  1385 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-10 08:50:20.116   315  1385 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-10 08:50:20.116   315  1385 V AwesomePlayer: mBitrate = -1 bits/sec
08-10 08:50:20.116  6515  6515 D UEI.SmartControl: QS start get config
08-10 08:50:20.116   315  1385 V AwesomePlayer: AudioTrack Setting
08-10 08:50:20.116   315  1385 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-10 08:50:20.116   315  1385 V AwesomePlayer: setAudioSource() 
,08-10 08:50:20.116   315  1385 V MediaPlayerService: prepare
08-10 08:50:20.116   315  1385 V AwesomePlayer: prepareAsync_l() 
08-10 08:50:20.117   315  1385 V MediaPlayerService: wait for prepare
08-10 08:50:20.117   315  6825 V AwesomePlayer: onPrepareAsyncEvent() 
08-10 08:50:20.117   315  6825 V AwesomePlayer: initAudioDecoder() 
08-10 08:50:20.117   315  6825 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 08:50:20.117   315  6825 V AudioSystem: isOffloadSupported()
08-10 08:50:20.117   315  6825 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 08:50:20.117   315  6825 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 08:50:20.117   315  6825 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 08:50:20.117   315  6825 V AwesomePlayer: getUseOffload() = 0 
08-10 08:50:20.117   315  6825 V OMXCodec: OMXCodec::Create
08-10 08:50:20.117   315  6825 V OMXCodec: findMatchingCodecs()
08-10 08:50:20.117   315  6825 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-10 08:50:20.117   315  6825 V OMXCodec: matchingCodecs.size()=1
08-10 08:50:20.117   315  6825 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-10 08:50:20.120   315  6825 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-10 08:50:20.120   315  6825 V LGCodecAdapter: LG Codec Adapter start
08-10 08:50:20.120   315  6825 V OMXCodec: OMXCodec Createtor
08-10 08:50:20.120   315  6825 V OMXCodec: setComponentRole
08-10 08:50:20.120   315  6825 V OMXCodec: configureCodec protected=0
08-10 08:50:20.120   315  6825 V LGCodecAdapter: called getLGCodecSpecificData
08-10 08:50:20.120   315  6825 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-10 08:50:20.120   315  6825 V LGCodecOSAL: Called LGconfigureCodecMETA
08-10 08:50:20.120   315  6825 V LGCodecOSAL: Called LGconfigureCodecMSG
08-10 08:50:20.120   315  6825 V LGCodecOSAL: Not support LGCodec
08-10 08:50:20.120   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 08:50:20.120   315  6825 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-10 08:50:20.121   315  6825 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-10 08:50:20.121   315  6825 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-10 08:50:20.121   315  6825 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 08:50:20.121   315  6825 V AudioSystem: isOffloadSupported()
08-10 08:50:20.121   315  6825 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 08:50:20.121   315  6825 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-10 08:50:20.121   315  6825 V OMXCodec: init()
08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-10 08:50:20.121   315  6825 V OMXCodec: allocateBuffers
08-10 08:50:20.121   315  6825 V OMXCodec: allocateBuffersOnPort portIndex=0
08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-10 08:50:20.121   315  6825 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
,08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-10 08:50:20.121   315  6825 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ff420 on output port
08-10 08:50:20.121   315  6825 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 08:50:20.122   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 08:50:20.122   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 08:50:20.122   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-10 08:50:20.122   315  6825 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 08:50:20.122   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-10 08:50:20.122   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-10 08:50:20.122   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-10 08:50:20.122   315  6825 V OMXCodec: init() mAsyncCompletion wait free! 
,08-10 08:50:20.122   315  6825 V AwesomePlayer: finishAsyncPrepare_l() 
08-10 08:50:20.122   315  6825 V AudioCache: notify(0xb1432200, 5, 0, 0)
08-10 08:50:20.122   315  6825 V AudioCache: ignored
08-10 08:50:20.122   315  6825 V AudioCache: notify(0xb1432200, 1, 0, 0)
08-10 08:50:20.122   315  6825 V AudioCache: prepared
08-10 08:50:20.122   315  1385 V AudioCache: wait - success
08-10 08:50:20.122   315  1385 V MediaPlayerService: start
08-10 08:50:20.122   315  1385 V AwesomePlayer: play_l() 
08-10 08:50:20.122   315  1385 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-10 08:50:20.122   315  1385 V AwesomePlayer: createAudioPlayer_l
08-10 08:50:20.122   315  1385 V AwesomePlayer: seekAudioIfNecessary_l() 
,08-10 08:50:20.122   315  1385 V AwesomePlayer: startAudioPlayer_l() 
,08-10 08:50:20.122   315  1385 D AudioPlayer: start of Playback, useOffload 0
08-10 08:50:20.122   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 08:50:20.122   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 08:50:20.125   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-10 08:50:20.125   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-10 08:50:20.125   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-10 08:50:20.125   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-10 08:50:20.125   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045061664
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-10 08:50:20.129   315  6827 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 08:50:20.129   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 08:50:20.130   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-10 08:50:20.130   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-10 08:50:20.130   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-10 08:50:20.130   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ff920 on output port
08-10 08:50:20.130   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-10 08:50:20.130   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-10 08:50:20.131   315  1385 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-10 08:50:20.131   315  1385 V AudioCache: notify(0xb1432200, 6, 0, 0)
08-10 08:50:20.131   315  1385 V AudioCache: ignored
08-10 08:50:20.132   315  1385 V MediaPlayerService: wait for playback complete
08-10 08:50:20.132   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.132   315  6828 V AudioCache: memcpy(0xaf006000, 0xb1507000, 4096)
08-10 08:50:20.139   315  6828 V AudioCache: write(0xb1507000, 4096)
,08-10 08:50:20.139   315  6828 V AudioCache: memcpy(0xaf007000, 0xb1507000, 4096)
08-10 08:50:20.139   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.139   315  6828 V AudioCache: memcpy(0xaf008000, 0xb1507000, 4096)
08-10 08:50:20.139   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.139   315  6828 V AudioCache: memcpy(0xaf009000, 0xb1507000, 4096)
08-10 08:50:20.143   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.143   315  6828 V AudioCache: memcpy(0xaf00a000, 0xb1507000, 4096)
08-10 08:50:20.143   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.143   315  6828 V AudioCache: memcpy(0xaf00b000, 0xb1507000, 4096)
08-10 08:50:20.143   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.143   315  6828 V AudioCache: memcpy(0xaf00c000, 0xb1507000, 4096)
08-10 08:50:20.143   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.143   315  6828 V AudioCache: memcpy(0xaf00d000, 0xb1507000, 4096)
08-10 08:50:20.145   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.146   315  6828 V AudioCache: memcpy(0xaf00e000, 0xb1507000, 4096)
08-10 08:50:20.146   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.146   315  6828 V AudioCache: memcpy(0xaf00f000, 0xb1507000, 4096)
08-10 08:50:20.146   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.146   315  6828 V AudioCache: memcpy(0xaf010000, 0xb1507000, 4096)
08-10 08:50:20.146   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.146   315  6828 V AudioCache: memcpy(0xaf011000, 0xb1507000, 4096)
08-10 08:50:20.147   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.147   315  6828 V AudioCache: memcpy(0xaf012000, 0xb1507000, 4096)
08-10 08:50:20.148   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.148   315  6828 V AudioCache: memcpy(0xaf013000, 0xb1507000, 4096)
08-10 08:50:20.149   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.149   315  6828 V AudioCache: memcpy(0xaf014000, 0xb1507000, 4096)
,08-10 08:50:20.150   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.150   315  6828 V AudioCache: memcpy(0xaf015000, 0xb1507000, 4096)
08-10 08:50:20.150   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.150   315  6828 V AudioCache: memcpy(0xaf016000, 0xb1507000, 4096)
08-10 08:50:20.151   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.151   315  6828 V AudioCache: memcpy(0xaf017000, 0xb1507000, 4096)
08-10 08:50:20.152   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.152   315  6828 V AudioCache: memcpy(0xaf018000, 0xb1507000, 4096)
08-10 08:50:20.153   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.153   315  6828 V AudioCache: memcpy(0xaf019000, 0xb1507000, 4096)
08-10 08:50:20.155   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.155   315  6828 V AudioCache: memcpy(0xaf01a000, 0xb1507000, 4096)
08-10 08:50:20.156   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.156   315  6828 V AudioCache: memcpy(0xaf01b000, 0xb1507000, 4096)
08-10 08:50:20.157   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.157   315  6828 V AudioCache: memcpy(0xaf01c000, 0xb1507000, 4096)
,08-10 08:50:20.157  1036  1717 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6829 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-10 08:50:20.158   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.158   315  6828 V AudioCache: memcpy(0xaf01d000, 0xb1507000, 4096)
08-10 08:50:20.158   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.158   315  6828 V AudioCache: memcpy(0xaf01e000, 0xb1507000, 4096)
08-10 08:50:20.159   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.159   315  6828 V AudioCache: memcpy(0xaf01f000, 0xb1507000, 4096)
08-10 08:50:20.160   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.160   315  6828 V AudioCache: memcpy(0xaf020000, 0xb1507000, 4096)
08-10 08:50:20.160   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.160   315  6828 V AudioCache: memcpy(0xaf021000, 0xb1507000, 4096)
08-10 08:50:20.161   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.161   315  6828 V AudioCache: memcpy(0xaf022000, 0xb1507000, 4096)
08-10 08:50:20.162   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.162   315  6828 V AudioCache: memcpy(0xaf023000, 0xb1507000, 4096)
08-10 08:50:20.162   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.162   315  6828 V AudioCache: memcpy(0xaf024000, 0xb1507000, 4096)
08-10 08:50:20.163   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.163   315  6828 V AudioCache: memcpy(0xaf025000, 0xb1507000, 4096)
08-10 08:50:20.164   315  6828 V AudioCache: write(0xb1507000, 4096)
,08-10 08:50:20.164   315  6828 V AudioCache: memcpy(0xaf026000, 0xb1507000, 4096)
08-10 08:50:20.165   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.165   315  6828 V AudioCache: memcpy(0xaf027000, 0xb1507000, 4096)
08-10 08:50:20.166   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.166   315  6828 V AudioCache: memcpy(0xaf028000, 0xb1507000, 4096)
08-10 08:50:20.167   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.167   315  6828 V AudioCache: memcpy(0xaf029000, 0xb1507000, 4096)
08-10 08:50:20.168   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.168   315  6828 V AudioCache: memcpy(0xaf02a000, 0xb1507000, 4096)
08-10 08:50:20.168   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.168   315  6828 V AudioCache: memcpy(0xaf02b000, 0xb1507000, 4096)
08-10 08:50:20.169   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.169   315  6828 V AudioCache: memcpy(0xaf02c000, 0xb1507000, 4096)
,08-10 08:50:20.170   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.170   315  6828 V AudioCache: memcpy(0xaf02d000, 0xb1507000, 4096)
08-10 08:50:20.171   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.171   315  6828 V AudioCache: memcpy(0xaf02e000, 0xb1507000, 4096)
08-10 08:50:20.172   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.172   315  6828 V AudioCache: memcpy(0xaf02f000, 0xb1507000, 4096)
08-10 08:50:20.172   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.172   315  6828 V AudioCache: memcpy(0xaf030000, 0xb1507000, 4096)
08-10 08:50:20.173   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.173   315  6828 V AudioCache: memcpy(0xaf031000, 0xb1507000, 4096)
08-10 08:50:20.174   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.174   315  6828 V AudioCache: memcpy(0xaf032000, 0xb1507000, 4096)
08-10 08:50:20.175   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.175   315  6828 V AudioCache: memcpy(0xaf033000, 0xb1507000, 4096)
08-10 08:50:20.175   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.175   315  6828 V AudioCache: memcpy(0xaf034000, 0xb1507000, 4096)
08-10 08:50:20.176   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.176   315  6828 V AudioCache: memcpy(0xaf035000, 0xb1507000, 4096)
08-10 08:50:20.178   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.178   315  6828 V AudioCache: memcpy(0xaf036000, 0xb1507000, 4096)
08-10 08:50:20.178   315  6828 V AudioCache: write(0xb1507000, 4096)
08-10 08:50:20.178   315  6828 V AudioCache: memcpy(0xaf037000, 0xb1507000, 4096)
08-10 08:50:20.179   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-10 08:50:20.179   315  6828 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-10 08:50:20.179   315  6828 V AwesomePlayer: postAudioEOS() 
08-10 08:50:20.179   315  6828 V AudioCache: write(0xb1507000, 280)
08-10 08:50:20.179   315  6828 V AudioCache: memcpy(0xaf038000, 0xb1507000, 280)
08-10 08:50:20.180   315  6825 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-10 08:50:20.180   315  6825 V AwesomePlayer: onStreamDone
08-10 08:50:20.180   315  6825 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-10 08:50:20.181   315  6825 V AudioCache: notify(0xb1432200, 2, 0, 0)
08-10 08:50:20.181   315  6825 V AudioCache: playback complete
08-10 08:50:20.181   315  6825 V AwesomePlayer: pause_l() 
08-10 08:50:20.181   315  6825 V AudioCache: notify(0xb1432200, 7, 0, 0)
08-10 08:50:20.181   315  6825 V AudioCache: ignored
08-10 08:50:20.181   315  6825 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:20.181   315  1385 V AudioCache: wait - success
08-10 08:50:20.181   315  1385 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-10 08:50:20.181   315  6825 D AudioPlayer: Pause Playback at 1068125
08-10 08:50:20.181   315  1385 V AwesomePlayer: reset_l() 
08-10 08:50:20.181   315  1385 V AudioCache: notify(0xb1432200, 8, 0, 0)
08-10 08:50:20.181   315  1385 V AudioCache: ignored
08-10 08:50:20.181   315  1385 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:20.181   315  1385 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-10 08:50:20.181   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-10 08:50:20.181   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-10 08:50:20.181   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-10 08:50:20.181   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeing ,buffer 0xb54f7ab0 on port 0
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57ff920 on port 1
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 08:50:20.182   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-10 08:50:20.182   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 08:50:20.182   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 08:50:20.183   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-10 08:50:20.183   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-10 08:50:20.183   315  6827 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-10 08:50:20.183   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 08:50:20.183   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-10 08:50:20.183   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-10 08:50:20.184   315  1385 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-10 08:50:20.184   315  1385 D AudioPlayer: AudioPlayer releasing audio source
08-10 08:50:20.184   315  1385 D AudioPlayer: AudioPlayer done releasing audio source
08-10 08:50:20.184   315  1385 V AwesomePlayer: reset_l() 
08-10 08:50:20.184   315  1385 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:20.184   315  1385 V AwesomePlayer: ~AwesomePlayer call
08-10 08:50:20.184   315  1385 V AwesomePlayer: reset_l() 
08-10 08:50:20.184   315  1385 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:20.185  6746  6824 V SoundPool: close(32)
08-10 08:50:20.185  6746  6824 V SoundPool: pointer = 0xa0026000, size = 205080, sampleRate = 48000, numChannels = 2
,08-10 08:50:20.192  6829  6829 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-10 08:50:20.192  6829  6829 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 08:50:20.192  6829  6829 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-10 08:50:20.193  6829  6829 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-10 08:50:20.204  6829  6829 D BluetoothAdapterApp: Loading JNI Library
,08-10 08:50:20.204  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-10 08:50:20.206  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-10 08:50:20.207  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5002
08-10 08:50:20.210  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=780306535 [*alarm*], flags=0x0
08-10 08:50:20.211   311  6847 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-10 08:50:20.212  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 08:50:20.225  6829  6829 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@200a58fb Instance Count = 1
,08-10 08:50:20.229  6829  6829 D BluetoothAdapterApp: onCreate
,08-10 08:50:20.243  6829  6829 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-10 08:50:20.243  6829  6829 D ProfileConfigQcom: Adding HeadsetService
08-10 08:50:20.244  6829  6829 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-10 08:50:20.244  6829  6829 D ProfileConfigQcom: Adding A2dpService
08-10 08:50:20.244  6829  6829 D ProfileConfigQcom: [BTUI] HidService is supported
08-10 08:50:20.244  6829  6829 D ProfileConfigQcom: Adding HidService
08-10 08:50:20.244  6829  6829 D ProfileConfigQcom: [BTUI] HealthService is supported
08-10 08:50:20.244  6829  6829 D ProfileConfigQcom: Adding HealthService
08-10 08:50:20.244  6829  6829 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-10 08:50:20.245  6829  6829 D ProfileConfigQcom: [BTUI] PanService is supported
08-10 08:50:20.245  6829  6829 D ProfileConfigQcom: Adding PanService
08-10 08:50:20.245  6829  6829 D ProfileConfigQcom: [BTUI] GattService is supported
08-10 08:50:20.245  6829  6829 D ProfileConfigQcom: Adding GattService
08-10 08:50:20.245  6829  6829 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-10 08:50:20.245  6829  6829 D ProfileConfigQcom: Adding BluetoothMapService
,08-10 08:50:20.246  6829  6829 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-10 08:50:20.247  6829  6829 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-10 08:50:20.249  6678  6678 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-10 08:50:20.250  6829  6829 V LGMDMManagerInternal: Create singleton instance
,08-10 08:50:20.292  6829  6829 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:20.294  6829  6829 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-10 08:50:20.294  6829  6829 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 08:50:20.294  6829  6829 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 08:50:20.295  6829  6829 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:20.295  6829  6829 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-10 08:50:20.306  6765  6765 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-10 08:50:20.424  6515  6515 I UEI.SmartControl: Supports setup maps: true
08-10 08:50:20.427  6515  6515 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 08:50:20.427  6515  6515 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-10 08:50:20.427  6515  6515 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 08:50:20.427  6515  6515 I UEI.SmartControl: ### init IR Blaster...
08-10 08:50:20.430  6515  6515 D serial_port: Configuring serial port
,08-10 08:50:20.431  6515  6515 E UEI.SmartControl: UEIBLaster setting for 616
08-10 08:50:20.431  6515  6515 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 08:50:20.431  6515  6515 I UEI.SmartControl: configuring settings for MAXQ616
08-10 08:50:20.431  6515  6515 I UEI.SmartControl: Get version...
08-10 08:50:20.450  6515  6850 D UEI.SmartControl: serial port data available: 21
,08-10 08:50:20.476  6515  6515 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-10 08:50:20.477  6515  6515 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 08:50:20.477  6515  6515 I UEI.SmartControl: QS saving settings...
,08-10 08:50:20.479  6515  6515 D UEI.SmartControl: IR Blaster version: 25672567
,08-10 08:50:20.498  6515  6850 D UEI.SmartControl: serial port data available: 4
,08-10 08:50:20.529  6515  6856 I UEI.SmartControl: Device manager: loading config....
,08-10 08:50:20.529  6515  6856 D UEI.SmartControl: ----------- loading internal config...
,08-10 08:50:20.532  6515  6515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-10 08:50:20.534  6515  6515 E UEI.SmartControl: Services init done
08-10 08:50:20.534  6515  6515 D UEI.SmartControl: QS Service init finished
08-10 08:50:20.535  6515  6515 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 08:50:20.535  6515  6515 D UEI.SmartControl: QS Service version code: 201091
08-10 08:50:20.535  6515  6515 D UEI.SmartControl: Service requested: Control
08-10 08:50:20.541  6515  6515 D UEI.SmartControl: Request IControl service: devices are loaded...
08-10 08:50:20.543  6515  6856 E UEI.SmartControl: Loading SETTINGS...
08-10 08:50:20.546  6746  6746 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-10 08:50:20.549  6515  6531 I UEI.SmartControl: ------ IControl API: 11
08-10 08:50:20.549  6515  6531 D UEI.SmartControl: File observer start...
,08-10 08:50:20.558  6515  6515 D UEI.SmartControl: Internal service binding...
08-10 08:50:20.559  6515  6531 E UEI.SmartControl: IR Port is disabled: false
08-10 08:50:20.560  6515  6531 D UEI.SmartControl: Starting file observer...
08-10 08:50:20.563  6515  6531 I UEI.SmartControl: Registering callback...
08-10 08:50:20.565  6515  6530 I UEI.SmartControl: ------ IControl API: 19
08-10 08:50:20.568  6515  6530 I UEI.SmartControl: Registering Services Ready callback...
,08-10 08:50:20.574  6515  6856 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-10 08:50:20.585  6515  6855 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-10 08:50:20.586  6746  6762 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-10 08:50:20.587  6746  6822 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-10 08:50:20.587  6515  6855 D UEI.SmartControl: -----service ready thread exits
08-10 08:50:20.588  6746  6822 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-10 08:50:20.588  6746  6746 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-10 08:50:20.589  6746  6746 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-10 08:50:20.589  6515  6531 I UEI.SmartControl: ------ IControl API: 8
08-10 08:50:20.590  6746  6746 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-10 08:50:20.591  6746  6746 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-10 08:50:20.591  6746  6746 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-10 08:50:20.591  6746  6746 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-10 08:50:20.592  6746  6746 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-10 08:50:20.592  6746  6746 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-10 08:50:20.595  6746  6746 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-10 08:50:20.597  6746  6746 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 08:50:20.598  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-10 08:50:20.599  6746  6746 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 08:50:20.599  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-10 08:50:20.600  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 08:50:20.602  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-10 08:50:20.602  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-10 08:50:20.603  6746  6746 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470811820603]
08-10 08:50:20.605  6746  6746 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-10 08:50:20.606  1036  1885 I ActivityManager: Killing 6046:com.android.gallery3d/u0a27 (adj 15): empty #17
08-10 08:50:20.628  6746  6861 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-10 08:50:20.639  1036  1885 I ActivityManager: Killing 6379:com.lge.email/u0a23 (adj 15): empty #18
,08-10 08:50:20.671  1036  1920 W libprocessgroup: failed to open /acct/uid_10027/pid_6046/cgroup.procs: No such file or directory
,08-10 08:50:20.676  1036  2048 W libprocessgroup: failed to open /acct/uid_10023/pid_6379/cgroup.procs: No such file or directory
08-10 08:50:20.683  6746  6746 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-10 08:50:20.684  6746  6746 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 08:50:20.685  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-10 08:50:20.685  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-10 08:50:20.686  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-10 08:50:20.686  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-10 08:50:20.687  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-10 08:50:20.697  6746  6746 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-10 08:50:21.634  1036  1717 D WifiServiceImplEx: setWifiEnabled: true pid=6597, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 08:50:21.636  1036  1717 D WifiService: setWifiEnabled: true pid=6597, uid=10118
08-10 08:50:21.636  1036  1717 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 08:50:21.659  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 08:50:21.660  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 08:50:21.660  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-10 08:50:21.664  1036  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-10 08:50:21.664  1036  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-10 08:50:21.666  1036  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-10 08:50:21.666  1036  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 08:50:21.667  1036  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-10 08:50:21.667  1036  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 08:50:21.667  1036  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-10 08:50:21.667  1036  1537 E WifiHW  : unknown target_country: EU , set to default
08-10 08:50:21.667  1036  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-10 08:50:21.667  1036  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-10 08:50:21.667  1036  1537 I WifiUtil: gEnableBmps=1
08-10 08:50:21.695  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:21.702  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-10 08:50:21.712  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:21.719  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:21.720  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:21.727  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-10 08:50:21.739  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:21.741  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:21.743  1036  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:21.745  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 08:50:21.748  6279  6672 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 08:50:21.760  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-10 08:50:21.769  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-10 08:50:21.791  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:21.830  1036  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:21.868  1036  1717 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6880 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-10 08:50:21.873  1036  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-10 08:50:21.873  1036  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 08:50:21.949  6880  6880 I AppUp4:AppBoxCP: onCreate
08-10 08:50:21.950  6880  6880 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-10 08:50:21.964  6880  6880 I AppUp4:DB:  setFingerPrint start
,08-10 08:50:21.965  6880  6880 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-10 08:50:21.974  6880  6880 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-10 08:50:21.974  6880  6880 I AppUp4:DB:  SDK version = 21
08-10 08:50:21.974  6880  6880 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-10 08:50:21.976  6880  6880 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-10 08:50:21.978  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 08:50:21.978  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:21.981  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 08:50:21.981  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 08:50:21.989  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
,08-10 08:50:22.039  6880  6880 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:22.040  6880  6880 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:50:22.053  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@920f5ad
08-10 08:50:22.053  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 08:50:22.053  6880  6880 D AppUp4:CustFacade: isPhone : true
08-10 08:50:22.054  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-10 08:50:22.054  6880  6880 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-10 08:50:22.054  6880  6880 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-10 08:50:22.055  6880  6900 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-10 08:50:22.056  6880  6900 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-10 08:50:22.056  6880  6900 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-10 08:50:22.059  1036  1717 I ActivityManager: Killing 2124:com.lge.music/u0a34 (adj 15): empty #17
,08-10 08:50:22.095   315   315 V AudioFlinger: 2124 died, releasing its sessions
08-10 08:50:22.095   315   315 V AudioFlinger:  pid 1850 @ 0
08-10 08:50:22.095   315   315 V AudioFlinger:  pid 3462 @ 1
08-10 08:50:22.095   315   315 V AudioFlinger:  pid 3462 @ 2
,08-10 08:50:22.117  1036  2030 W libprocessgroup: failed to open /acct/uid_10034/pid_2124/cgroup.procs: No such file or directory
,08-10 08:50:22.119  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:22.119  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 08:50:22.122  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:22.127  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:22.137  4353  6906 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 08:50:22.140  4353  6907 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:22.140  4353  6907 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 08:50:22.196  1036  1780 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6908 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-10 08:50:22.277  6908  6908 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 08:50:22.277  6908  6908 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 08:50:22.279  6908  6908 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 08:50:22.280  6908  6908 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 08:50:22.377  6908  6908 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-10 08:50:22.409  6908  6908 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-10 08:50:22.455   311   905 D SoftapController: Softap fwReload - Ok
,08-10 08:50:22.456  1036  1537 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (784ms)
08-10 08:50:22.457   311   905 D CommandListener: Setting iface cfg
08-10 08:50:22.457   311   905 D CommandListener: Trying to bring down wlan0
08-10 08:50:22.458   311   905 D CommandListener: Clearing all IP addresses on wlan0
08-10 08:50:22.460  1036  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-10 08:50:22.460  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 08:50:22.460  1036  1118 D Tethering: InitialState.processMessage what=4
08-10 08:50:22.453  6933  6933 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:22.453  6933  6933 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:22.485  6908  6908 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-10 08:50:22.489  6933  6933 I wpa_supplicant: Successfully initialized wpa_supplicant
08-10 08:50:22.496  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 08:50:22.522  6933  6933 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-10 08:50:22.522  6933  6933 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-10 08:50:22.527  6908  6908 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 08:50:22.527  6908  6908 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:50:22.561  1036  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 08:50:22.561  1036  1537 E WifiStateMachine: useWiFiOffloading() : false
08-10 08:50:22.561  1036  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 08:50:22.562  1036  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-10 08:50:22.562  1036  1537 D WifiMonitor: connecting to supplicant
,08-10 08:50:22.563  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-10 08:50:22.564  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:22.568  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-10 08:50:22.571  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:22.572  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:22.594  6933  6933 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-10 08:50:22.640  6908  6908 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 08:50:22.662  6933  6933 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-10 08:50:22.667  6933  6933 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-10 08:50:22.669  1036  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-10 08:50:22.670  1036  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-10 08:50:22.670  1036  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-10 08:50:22.671  1036  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-10 08:50:22.671  1036  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:22.671  1036  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:22.671  1036  6937 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-10 08:50:22.672  1036  6937 D WifiMonitor: Dropping event because (p2p0) is stopped
08-10 08:50:22.672  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-10 08:50:22.672  6933  6933 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-10 08:50:22.672  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-10 08:50:22.672  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-10 08:50:22.673  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-10 08:50:22.673  1036  6937 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-10 08:50:22.673  1036  6937 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-10 08:50:22.674  1036  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:22.675  1036  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:22.678  1036  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-10 08:50:22.678  1036  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-10 08:50:22.679  1036  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-10 08:50:22.680  1036  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-10 08:50:22.680  1036  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-10 08:50:22.683  1036  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 08:50:22.683  1036  1537 E WifiStateMachine: useWiFiOffloading() : false
08-10 08:50:22.683  1036  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 08:50:22.683  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:22.684  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:22.684  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:22.684  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:22.684  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 08:50:22.685  1939  1939 D WfdService: Waiting for WifiP2p enabling
08-10 08:50:22.686  1036  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
08-10 08:50:22.687  1036  1537 D WifiNative-wlan0: SET update_config 1: returned true
08-10 08:50:22.687  1036  1537 D WifiConfigStore: Loading config and enabling all networks 
08-10 08:50:22.687  1036  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-10 08:50:22.688  1036  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-10 08:50:22.688  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-10 08:50:22.689  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:22.691  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:22.691  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:22.691  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:22.691  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:22.691  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:22.691  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:22.691  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:22.691  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:22.691  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 08:50:22.691  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:22.691  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:22.693  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-10 08:50:22.693  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:22.693  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:22.693  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:22.693  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:22.693  6597  6597 V io.jxcore.node.Co,nnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:22.693  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:22.693  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:22.693  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:22.693  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 08:50:22.693  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:22.693  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 08:50:22.701  3462  3462 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 08:50:22.701  3462  3462 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:22.701  3462  3462 I LgeMiscReceiver: networkInfo.isConnected() = false
08-10 08:50:22.705  1036  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-10 08:50:22.709  6908  6908 I HubEmail: JNI_OnLoad()
08-10 08:50:22.709  6908  6908 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 08:50:22.709  6908  6908 I HubEmail: registerNatives()
08-10 08:50:22.709  6908  6908 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 08:50:22.709  6908  6908 I HubEmail: registerNativeMethods()
08-10 08:50:22.709  6908  6908 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 08:50:22.709  6908  6908 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-10 08:50:22.717  1036  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-10 08:50:22.717  1036  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-10 08:50:22.749  1036  2030 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6943 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-10 08:50:22.753  1036  1537 D WifiStateMachine: enableVerboseLogging : level 2
08-10 08:50:22.753  1036  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-10 08:50:22.754  1036  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-10 08:50:22.754  1036  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-10 08:50:22.755  1036  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-10 08:50:22.755  1036  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,08-10 08:50:22.756  1036  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-10 08:50:22.756  1036  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-10 08:50:22.757  6908  6942 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:22.757  1036  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-10 08:50:22.758  1036  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-10 08:50:22.759  1036  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-10 08:50:22.759  1036  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-10 08:50:22.760  1036  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-10 08:50:22.760  1036  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-10 08:50:22.760  1036  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-10 08:50:22.760  6790  6940 W FormManager: Network not available. Please check & try again.
08-10 08:50:22.760  1036  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 08:50:22.761  1036  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-10 08:50:22.761  1036  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-10 08:50:22.761  1036  1537 D WifiNative-HAL: Setting external_sim to 1
08-10 08:50:22.761  1036  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-10 08:50:22.762  1036  1537 D WifiNative-wlan0: SET external_sim 1: returned true
08-10 08:50:22.762  1036  1537 I WifiNative-HAL: startHal
08-10 08:50:22.762  1036  1537 D wifi    : setting scan oui 0xaf6560a0
08-10 08:50:22.762  1939  1939 D WfdsService: Supplicant Connection state is changed : true
08-10 08:50:22.762  1939  2327 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-10 08:50:22.762  1939  2327 D WfdsService: Set the WFDS Monitor: true
08-10 08:50:22.762  1939  2327 D WfdsMonitor: WfdsMonitorThread create
,08-10 08:50:22.762  1939  2327 D WfdsMonitor: WFDS Monitor is created and started
08-10 08:50:22.762  1939  2327 D WfdsService: WiFi: Supplicant connection re-established
08-10 08:50:22.763  1036  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 08:50:22.763  1036  1537 I WifiNative-HAL: startHal
08-10 08:50:22.763  1036  1537 D wifi    : setting scan oui 0xaf6560a0
08-10 08:50:22.763  1036  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-10 08:50:22.764  1036  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-10 08:50:22.764  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-10 08:50:22.764  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-10 08:50:22.764  1036  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-10 08:50:22.765  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 08:50:22.765  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 08:50:22.765  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 08:50:22.765  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-10 08:50:22.765  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-10 08:50:22.766  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-10 08:50:22.766  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 08:50:22.766  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 08:50:22.766  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 08:50:22.766  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 08:50:22.766  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 08:50:22.767  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 08:50:22.767  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-10 08:50:22.767  6933  6933 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,08-10 08:50:22.769  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-10 08:50:22.769  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 08:50:22.769  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 08:50:22.770  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 08:50:22.770  1939  6952 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-10 08:50:22.770  1939  6952 E CtrlSupplicant: Succeed to open control connection
08-10 08:50:22.771  1939  6952 E CtrlSupplicant: Succeed to open monitor connection
,08-10 08:50:22.771  1036  1537 E WifiNative: : [309,858,022 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-10 08:50:22.771  1036  1537 D WifiNative-wlan0: doBoolean: RECONNECT
08-10 08:50:22.771  1036  1537 D WifiNative-wlan0: RECONNECT: returned true
08-10 08:50:22.771  1036  1537 D WifiNative-wlan0: doString: [STATUS]
08-10 08:50:22.772  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-10 08:50:22.772  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-10 08:50:22.772  1036  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 08:50:22.772  1036  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 08:50:22.772  1939  6952 D WfdsMonitor: Supplicant connection established
08-10 08:50:22.772  1036  1537 D WifiNative-wlan0: SET ps 1: returned true
08-10 08:50:22.773  1036  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.773  6790  6941 V FormManager: Network unavailable.
08-10 08:50:22.774   311   905 D CommandListener: Setting iface cfg
08-10 08:50:22.774  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-10 08:50:22.774   311   905 D CommandListener: Trying to bring up p2p0
08-10 08:50:22.774  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-10 08:50:22.775  1939  2327 D WfdsService: Connected to the supplicant for wfds
08-10 08:50:22.775  1036  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.775  1036  1555 I WifiNative-HAL: startHal
08-10 08:50:22.775  1036  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6560a0
08-10 08:50:22.775  1036  1555 D wifi    : failed to get capabilities : -3
08-10 08:50:22.775  1036  1555 E WifiScanningService: could not get scan capabilities
08-10 08:50:22.775  1036  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.775  1036  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-10 08:50:22.775  1036  1536 D LGWifiP2pService: P2pEnablingState
08-10 08:50:22.775  1036  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.775  1036  1536 D LGWifiP2pService: P2p socket connection successful
08-10 08:50:22.775  1036  1536 D LGWifiP2pService: P2pEnabledState
08-10 08:50:22.777  1036  1536 D LGWifiP2pService: sending p2p connection changed broadcast
08-10 08:50:22.777  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-10 08:50:22.777  1939  1939 D WfdsService: WifiP2pState is changed : true
08-10 08:50:22.777  1939  2327 D WfdsService: Receive the WFDS_ENABLE Method
08-10 08:50:22.777  1939  2327 D WfdsService: Set the WFDS Monitor: true
08-10 08:50:22.777  1939  2327 D WfdsService: Connected to the supplicant for wfds
08-10 08:50:22.777  1939  2327 D WfdsJNI : doCommand: WFDS_SET TRUE
08-10 08:50:22.777  6933  6933 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-10 08:50:22.779  1939  2327 D WfdsService: selectPreferredScanChannel [36]
08-10 08:50:22.779  1939  2327 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-10 08:50:22.779  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
,08-10 08:50:22.780  1939  1939 D WfdsService: isConnected: false
08-10 08:50:22.781  1036  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-10 08:50:22.782  1036  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-10 08:50:22.782  1036  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
08-10 08:50:22.783  1036  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-10 08:50:22.783  1036  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-10 08:50:22.783  1036  1536 D LGWifiP2pService: before postfix = G3
08-10 08:50:22.783  1036  1536 D WifiServerServiceExt: postfix byte check : 2
08-10 08:50:22.783  1036  1536 D LGWifiP2pService: after postfix = G3
08-10 08:50:22.783  1036  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-10 08:50:22.784  1036  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-10 08:50:22.784  1036  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-10 08:50:22.784  1036  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-10 08:50:22.784  1036  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-10 08:50:22.785  1036  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-10 08:50:22.785  1036  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-10 08:50:22.785  1036  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,08-10 08:50:22.785  1036  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-10 08:50:22.785  1036  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-10 08:50:22.787  1036  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-10 08:50:22.787  1036  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-10 08:50:22.787  1036  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-10 08:50:22.787  1939  1939 I WfdStateTracker: handleP2pThisDeviceChanged
08-10 08:50:22.787  1036  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-10 08:50:22.787  1939  1939 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-10 08:50:22.787  1939  1939 D WfdsService: Update P2p Interface State: 3
08-10 08:50:22.787  1036  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-10 08:50:22.787  1036  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-10 08:50:22.787  1036  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-10 08:50:22.788  1036  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-10 08:50:22.788  1036  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-10 08:50:22.788  1036  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-10 08:50:22.788  1036  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-10 08:50:22.788  1036  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-10 08:50:22.789  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=309877  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 08:50:22.790  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=309878  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 08:50:22.791  1036  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-10 08:50:22.791  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:22.791  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:22.791  1036  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-10 08:50:22.792  1036  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-10 08:50:22.792  1036  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-10 08:50:22.794  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:22.796  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:22.796  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:22.796  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 08:50:22.797  6933  6933 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-10 08:50:22.797  1036  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-10 08:50:22.797  1036  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-10 08:50:22.797  1036  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-10 08:50:22.798  1036  1536 D LGWifiP2pService: InactiveState
08-10 08:50:22.798  1036  1536 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.798  1036  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-10 08:50:22.798  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.798  1036  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-10 08:50:22.798  1036  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-10 08:50:22.798  1036  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-10 08:50:22.799  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 08:50:22.799  6933  6933 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:22.800  1939  6952 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 08:50:22.800  1036  6937 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 08:50:22.800  6933  6933 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 08:50:22.800  1036  6937 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:22.800  1036  6937 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:22.800  6933  6933 E wpa_supplicant: disconnect_rssi_lvl: -100
08-10 08:50:22.800  1036  6937 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:22.800  6933  6933 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.800  1939  6952 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:22.801  1036  6937 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:22.801  1036  6937 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.801  1036  6937 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.801  1036  6937 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.801  1036  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 08:50:22.801  1036  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 08:50:22.802  6933  6933 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.802  1939  6952 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:22.802  1036  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 08:50:22.802  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-10 08:50:22.802  1036  6937 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:22.802  1036  6937 ,E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.802  1036  6937 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.802  1036  6937 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.804  1036  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-10 08:50:22.804  1036  1536 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.804  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.804  1036  1536 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.804  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 08:50:22.805  1036  1536 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.805  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.805  6933  6933 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:22.805  6933  6933 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 08:50:22.806  6933  6933 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.806  6933  6933 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.807  1939  6952 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:22.807  1939  6952 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-10 08:50:22.807  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 08:50:22.808  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:22.808  1036  6937 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:22.808  1036  6937 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:22.808  1036  6937 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:22.808  1036  6937 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.808  1036  6937 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.808  1036  6937 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.808  1036  6937 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:22.808  1036  6937 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.808  1036  6937 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.808  1036  6937 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:22.809  6790  6941 V FormManager: Network unavailable.
,08-10 08:50:22.809  1036  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-10 08:50:22.809  1036  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-10 08:50:22.810  1036  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-10 08:50:22.810  1036  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-10 08:50:22.811  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-10 08:50:22.811  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-10 08:50:22.811  6933  6933 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 08:50:22.812  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-10 08:50:22.812  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 08:50:22.812  1036  6937 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 08:50:22.812  1036  6937 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-10 08:50:22.812  1036  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-10 08:50:22.812  1036  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-10 08:50:22.813  1036  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-10 08:50:22.813  1036  1537 D WifiNative-wlan0: doBoolean: SCAN
08-10 08:50:22.813  1036  1537 D WifiNative-wlan0: SCAN: returned false
08-10 08:50:22.814  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=309901  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 08:50:22.814  1036  1536 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.815  1939  2327 W WfdsService: DefaultState - msg [9441285] is not handled
08-10 08:50:22.815  1036  1536 D LGWifiP2pService: InactiveState{ when=-17ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.815  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.815  1036  1536 D LGWifiP2pService: DefaultState{ when=-18ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.816  1036  1536 D LGWifiP2pService: InactiveState{ when=-18ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.816  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.816  1036  1536 D LGWifiP2pService: DefaultState{ when=-18ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.818  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=309905  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 08:50:22.818  1036  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 08:50:22.819  1036  1036 E WifiServerServiceExt: No p2p device connected
08-10 08:50:22.819  1036  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 08:50:22.819  1036  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 08:50:22.820  1036  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 08:50:22.820  1036  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 08:50:22.821  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:22.821  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:22.822  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:22.822  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:22.822  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:22.822  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 08:50:22.822  1036  1536 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.822  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:22.823  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:22.823  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-10 08:50:22.827  1036  1993 I ActivityManager: Killing 6109:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-10 08:50:22.891  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:22.891  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-10 08:50:22.892  1036  1780 W libprocessgroup: failed to open /acct/uid_10080/pid_6109/cgroup.procs: No such file or directory
,08-10 08:50:22.988  6943  6943 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 08:50:22.988  6943  6943 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:50:22.992  6943  6943 D PhoneMonitor: Register our PhoneStateListener
08-10 08:50:23.018  6943  6943 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-10 08:50:23.021  6943  6943 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-10 08:50:23.044  6943  6943 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-10 08:50:23.045  6943  6943 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-10 08:50:23.047  6943  6943 D TelephonyAutoProfiling: [parse] Load xml
08-10 08:50:23.055  6943  6943 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-10 08:50:23.055  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-10 08:50:23.055  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-10 08:50:23.055  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-10 08:50:23.055  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-10 08:50:23.055  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-10 08:50:23.055  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-10 08:50:23.055  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-10 08:50:23.055  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-10 08:50:23.056  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-10 08:50:23.056  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-10 08:50:23.056  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-10 08:50:23.056  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-10 08:50:23.056  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-10 08:50:23.056  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-10 08:50:23.056  6943  6943 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-10 08:50:23.056  6943  6943 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-10 08:50:23.062  1036  1780 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6968 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 08:50:23.062  1036  1780 I ActivityManager: Killing 6416:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-10 08:50:23.071  6943  6943 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-10 08:50:23.117  1036  1972 W libprocessgroup: failed to open /acct/uid_10061/pid_6416/cgroup.procs: No such file or directory
,08-10 08:50:23.361  1036  1780 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6987 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-10 08:50:23.367  1036  1780 I ActivityManager: Killing 6129:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-10 08:50:23.382  6933  6933 E wpa_supplicant: USIM:  scard_init function
,08-10 08:50:23.382  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-10 08:50:23.382  1036  6937 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-10 08:50:23.382  6933  6933 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-10 08:50:23.382  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-10 08:50:23.382  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-10 08:50:23.382  1036  6937 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-10 08:50:23.383  1036  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-10 08:50:23.383  1036  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-10 08:50:23.384  1036  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-10 08:50:23.384  1036  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-10 08:50:23.384  1036  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-10 08:50:23.385  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-10 08:50:23.385  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-10 08:50:23.420  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=310508  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-10 08:50:23.421  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=310509  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-10 08:50:23.425  1036  1052 W libprocessgroup: failed to open /acct/uid_10097/pid_6129/cgroup.procs: No such file or directory
08-10 08:50:23.431  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:23.431  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:23.432  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 08:50:23.433  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.433  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.433  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 08:50:23.433  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:23.433  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-10 08:50:23.489  6933  6933 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 08:50:23.491  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-10 08:50:23.491  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-10 08:50:23.491  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-10 08:50:23.491  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-10 08:50:23.492  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 08:50:23.492  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 08:50:23.493  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=310580  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 08:50:23.493  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=310581  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 08:50:23.494  1036  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=310581
08-10 08:50:23.494  1036  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=310582
08-10 08:50:23.495  1036  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=310582
08-10 08:50:23.495  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=310583
08-10 08:50:23.495  1036  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=310583
08-10 08:50:23.499  6933  6933 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 08:50:23.499  6933  6933 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 08:50:23.501  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 08:50:23.501  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 08:50:23.501  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-10 08:50:23.501  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 08:50:23.501  1036  6937 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 08:50:23.501  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-10 08:50:23.501  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 08:50:23.501  1036  6937 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 08:50:23.501  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 08:50:23.501  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-10 08:50:23.534  1036  1051 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7007 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-10 08:50:23.536  1036  1051 I ActivityManager: Killing 6469:com.lge.eula/1000 (adj 15): empty #17
08-10 08:50:23.595  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-10 08:50:23.599  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:23.599  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-10 08:50:23.600  1036  1936 W libprocessgroup: failed to open /acct/uid_1000/pid_6469/cgroup.procs: No such file or directory
08-10 08:50:23.601  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=310686  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-10 08:50:23.618  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:23.618  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:23.620  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.620  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.620  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 08:50:23.621  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=310709  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 08:50:23.622  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:23.622  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=310710  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 08:50:23.625  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=310711  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 08:50:23.626  1036  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=310714
08-10 08:50:23.627  1036  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=310715
08-10 08:50:23.629  1036  1537 D WifiNative-wlan0: doString: [STATUS]
,08-10 08:50:23.630  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.630  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.630  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-10 08:50:23.631  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 08:50:23.631  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 08:50:23.632  1036  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 08:50:23.634  1036  1537 I WifiServiceExtension: setVHTCapabilityType  : false
08-10 08:50:23.639  1036  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-10 08:50:23.639  1036  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-10 08:50:23.639  1036  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:23.639  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:23.639  1036  1536 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:23.643  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 08:50:23.643  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.643  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 08:50:23.644  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:23.644  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:23.646  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 08:50:23.649  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:23.649  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:23.651  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:23.652  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.652  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.653  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 08:50:23.654  1036  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-10 08:50:23.655  1036  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 08:50:23.655  1036  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 08:50:23.655  1036  1543 D ConnectivityService: Got NetworkAgent Messenger
08-10 08:50:23.655  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-10 08:50:23.655  1036  1543 D ConnectivityService: NetworkAgent connected
08-10 08:50:23.655  1036  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 08:50:23.655  1036  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 08:50:23.659  1036  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 08:50:23.659  1036  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 08:50:23.659  1036  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 08:50:23.659  1036  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 08:50:23.659  1036  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 08:50:23.663  1036  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 08:50:23.664   311   905 D CommandListener: Setting iface cfg
,08-10 08:50:23.667  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:23.667  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:23.669  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:23.671  1036  1537 E WifiStateMachine: Start Dhcp Watchdog 2
08-10 08:50:23.671  1036  7025 D DhcpStateMachine: StoppedState
08-10 08:50:23.671  1036  7025 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:23.671  1036  7025 D DhcpStateMachine: WaitBeforeStartState
08-10 08:50:23.672  1036  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=310759  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 08:50:23.672  1036  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=310760  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 08:50:23.673  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=310760  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 08:50:23.673  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:23.674  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:23.674  1036  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:23.675  1036  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:23.675  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:23.675  1036  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:23.677  7007  7007 I art     : Almond Protected OAT
08-10 08:50:23.677  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:23.677  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-10 08:50:23.678  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:23.678  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-10 08:50:23.679  1036  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=310767  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 08:50:23.680  1036  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=310768  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-10 08:50:23.681  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=310768  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 08:50:23.682  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:265395] from screen [on:0 period:1933008450] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 08:50:23.683  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1933008451] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 08:50:23.683  1036  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 08:50:23.687  1036  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-10 08:50:23.687  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:23.688  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:23.688  1036  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:23.689  1036  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:23.689  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:23.690  1036  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:23.690  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-10 08:50:23.691  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
08-10 08:50:23.691  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
08-10 08:50:23.691  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-10 08:50:23.691  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:23.692  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-10 08:50:23.692  1036  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-10 08:50:23.692  1036  1537 D WifiNative-wlan0: doBoolean: SET ps 0
08-10 08:50:23.693  1036  1537 D WifiNative-wlan0: SET ps 0: returned true
08-10 08:50:23.693  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-10 08:50:23.693  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-10 08:50:23.694  1036  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-10 08:50:23.694  1036  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ccf8ba7 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:23.694  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ccf8ba7 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:23.694  1036  7025 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:23.694  1036  7025 D DhcpStateMachine: DHCP Start wake lock is acquired.
,08-10 08:50:23.694  1036  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-10 08:50:23.694  1036  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 08:50:23.695  1036  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 08:50:23.696   311   905 D CommandListener: Setting iface cfg
08-10 08:50:23.696   311   905 D CommandListener: Trying to bring up wlan0
08-10 08:50:23.697  1036  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-10 08:50:23.699  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 08:50:23.699  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 08:50:23.699  1036  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 08:50:23.700  1036  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 08:50:23.700  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 08:50:23.701  1036  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 08:50:23.701  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-10 08:50:23.701  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-10 08:50:23.702  1036  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:23.702  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:23.702  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 08:50:23.703  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 08:50:23.703  1036  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 08:50:23.703  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-10 08:50:23.703  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-10 08:50:23.703  1036  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-10 08:50:23.704  1036  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 08:50:23.726  1036  1537 D WifiNative-wlan0: SET ps 1: returned true
08-10 08:50:23.727  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-10 08:50:23.730  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 08:50:23.731  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:23.732  1036  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:23.732  1036  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:23.732  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:23.733  1036  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:23.734  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-10 08:50:23.734  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 08:50:23.735  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 08:50:23.735  1036  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-10 08:50:23.735  1036  1543 D ConnectivityService: ignoring duplicate network state non-change
08-10 08:50:23.736  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-10 08:50:23.737  1036  1543 D ConnectivityService: Adding iface wlan0 to network 101
08-10 08:50:23.738  1036  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-10 08:50:23.744  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:23.744  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-10 08:50:23.750  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:23.750  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:23.752  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.752  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.752  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 08:50:23.753  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:23.762  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.762  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.762  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-10 08:50:23.765  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-10 08:50:23.769  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-10 08:50:23.770  1036  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-10 08:50:23.770  1036  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-10 08:50:23.771  1036  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-10 08:50:23.772   311   905 E Netd    : netlink response contains error (File exists)
08-10 08:50:23.773  1036  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-10 08:50:23.775  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:23.775  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 08:50:23.776  1036  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-10 08:50:23.776  1036  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-10 08:50:23.776  1036  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-10 08:50:23.777  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:23.778  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.778  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.778  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 08:50:23.779  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-10 08:50:23.781  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:23.781  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 08:50:23.781  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:23.783  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.784  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:23.784  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 08:50:23.784  1036  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-10 08:50:23.784  1036  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-10 08:50:23.784  1036  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-10 08:50:23.784  1036  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-10 08:50:23.784  1036  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 08:50:23.784  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:23.786  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 08:50:23.786  1036  7024 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:23.786  1036  7024 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-10 08:50:23.786  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:23.786  1036  7024 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:23.786  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-10 08:50:23.786  1036  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-10 08:50:23.786  1036  1543 D ConnectivityService:    accepting network in place of null
08-10 08:50:23.786  1036  7024 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-10 08:50:23.786  1036  154,3 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:23.786  1036  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:23.787  1036  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-10 08:50:23.790  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:23.790  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 08:50:23.791  1036  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-10 08:50:23.791  1036  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-10 08:50:23.791  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 08:50:23.792   311  7035 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-10 08:50:23.792  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-10 08:50:23.793  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 08:50:23.793  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 08:50:23.793  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 08:50:23.794  1036  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:23.794  1036  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-10 08:50:23.795  1036  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-10 08:50:23.796  1036  1543 D ConnectivityService: validation of new default Network = false
08-10 08:50:23.796  1036  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-10 08:50:23.796  1036  1543 D DSQN    : enableDataServiceNotify 
08-10 08:50:23.796  1036  1543 D DSQN    : start dsqn bin
,08-10 08:50:23.800  1036  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-10 08:50:23.800  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:23.800  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:23.801  1036  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:23.801  1602  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 08:50:23.802  7007  7007 D WeatherApplication: removeAccount
08-10 08:50:23.803  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:23.803  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 08:50:23.803  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:23.803  7007  7007 D WeatherApplication: Account.length = 0
08-10 08:50:23.803  7007  7007 E WeatherApplication: OPERATOR:OPEN
08-10 08:50:23.793  7036  7036 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:23.793  7036  7036 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 08:50:23.817  7007  7007 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:23
08-10 08:50:23.818  1815  7037 I CheckinService: active receiver: enabled
08-10 08:50:23.818  1036  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-10 08:50:23.820  7036  7036 E DSQN    : DSQN ssw
,08-10 08:50:23.827  7007  7007 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 08:50:23.827  1815  7037 I CheckinService: Preparing to send checkin request
08-10 08:50:23.827  7007  7007 D Weather.Utils: 2 : All the weather widget is gone.
08-10 08:50:23.827  1815  7037 I EventLogService: Accumulating logs since 1470811571255
08-10 08:50:23.835  7007  7007 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 08:50:23.836  7007  7007 D WeatherAncestor: connectivity changed - connection : true
,08-10 08:50:23.837  7007  7007 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-10 08:50:23.839  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 08:50:23.840  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:23.841  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:23.843  7007  7007 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 08:50:23.843  7007  7007 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 08:50:23.843  7007  7007 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-10 08:50:23.844   311  7035 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-10 08:50:23.861  7007  7007 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 08:50:23.861  7007  7007 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:23
,08-10 08:50:23.876   311  7035 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-10 08:50:23.884   311   904 D LGDataListener: argv[0]=dsqncommand
08-10 08:50:23.884   311   904 D LGDataListener: argv[1]=wlan0
08-10 08:50:23.884   311   904 D LGDataListener: argv[2]=1
08-10 08:50:23.884   311   904 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-10 08:50:23.884  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-10 08:50:23.884  1036  1116 D DSQN    : start to monitor internet connection
08-10 08:50:23.891  1036  7024 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 06:50:23 GMT], X-Android-Received-Millis=[1470811823891], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470811823884]}
08-10 08:50:23.891  1036  7024 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-10 08:50:23.891  1036  7024 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-10 08:50:23.891  1036  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-10 08:50:23.891  1036  2030 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7045 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 08:50:23.891  1036  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-10 08:50:23.891  1036  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 08:50:23.891  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-10 08:50:23.891  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 08:50:23.891  1036  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-10 08:50:23.891  1036  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-10 08:50:23.891  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:23.892  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:23.892  1036  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:23.892  1036  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:23.892  1602  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 08:50:23.892  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 08:50:23.892  1036  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:23.892  1036  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 08:50:23.892  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:23.893  1036  2030 I ActivityManager: Killing 6487:com.lge.bnr/1000 (adj 15): empty #17
08-10 08:50:23.893  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-10 08:50:23.899  1036  7025 D DhcpStateMachine: DHCPV4 request on wlan0
08-10 08:50:23.899  1036  7025 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-10 08:50:23.899  1036  7025 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-10 08:50:23.893  7060  7060 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:23.893  7060  7060 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:23.906  7060  7060 I dhcpcd  : version 5.5.6 starting
,08-10 08:50:23.907  7060  7060 E dhcpcd  : get_duid: m
,08-10 08:50:23.907  7060  7060 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-10 08:50:23.907  7060  7060 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-10 08:50:23.974  7060  7060 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 08:50:23.975  7060  7060 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 08:50:23.975  7060  7060 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-10 08:50:23.975  7060  7060 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-10 08:50:23.976  7060  7060 D dhcpcd  : wlan0: sending REQUEST (xid 0xc0a2ba83), next in 3.85 seconds
08-10 08:50:23.988  7060  7060 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-10 08:50:23.990  1815  7037 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-10 08:50:23.990  1036  1936 W libprocessgroup: failed to open /acct/uid_1000/pid_6487/cgroup.procs: No such file or directory
,08-10 08:50:24.013  7060  7060 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-10 08:50:24.013  7060  7060 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-10 08:50:24.014  7060  7060 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-10 08:50:24.014  7060  7060 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-10 08:50:24.014  7060  7060 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-10 08:50:24.015  7060  7060 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 08:50:24.015  7060  7060 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 08:50:24.015  7060  7060 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-10 08:50:24.036  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 08:50:24.038  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:24.038  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 08:50:24.132   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 08:50:24.132   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 08:50:24.132   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
,08-10 08:50:24.133  7045  7080 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 08:50:24.136   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 08:50:24.136   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 08:50:24.136   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 08:50:24.136  7045  7080 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 08:50:24.146   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 08:50:24.146   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 08:50:24.146   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
,08-10 08:50:24.147  7045  7084 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 08:50:24.152   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 08:50:24.152   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 08:50:24.152   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 08:50:24.152  7045  7084 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 08:50:24.167  1036  2029 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7088 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-10 08:50:24.233  7088  7088 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-10 08:50:24.233  7088  7088 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-10 08:50:24.268  7088  7088 I MultiDex: VM with version 2.1.0 has multidex support
08-10 08:50:24.268  7088  7088 I MultiDex: install
08-10 08:50:24.268  7088  7088 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-10 08:50:24.279  7088  7088 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-10 08:50:24.301  1036  7025 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-10 08:50:24.302  1036  7025 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-10 08:50:24.302  1036  7025 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 08:50:24.302  1036  7025 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-10 08:50:24.302  1036  7025 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-10 08:50:24.302  1036  7025 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 08:50:24.302  1036  7025 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-10 08:50:24.303  1036  7025 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-10 08:50:24.303  1036  7025 D DhcpStateMachine: RunningState
,08-10 08:50:24.361  7045  7045 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 08:50:24.367  7045  7045 I LibraryLoader: Loading: webviewchromium
08-10 08:50:24.370  7045  7045 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1468-1471)
08-10 08:50:24.370  7045  7045 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 08:50:24.374  7045  7045 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cd9fe8c}
08-10 08:50:24.375  7045  7045 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 08:50:24.375  7045  7045 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 08:50:24.383  7045  7045 I BrowserStartupController: Initializing chromium process, renderers=0
08-10 08:50:24.384  7045  7045 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 08:50:24.399  7045  7045 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-10 08:50:24.403  7045  7045 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-10 08:50:24.404  7045  7045 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-10 08:50:24.410   315  1386 V AudioPolicyService: registerClient() client 0xb558ac20, uid 10093
08-10 08:50:24.411  7045  7133 W AudioManagerAndroid: Requires BLUETOOTH permission
08-10 08:50:24.424  7045  7045 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 08:50:24.424  7045  7045 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 08:50:24.424  7045  7045 I Adreno-EGL: Build Date: 12/12/14 금
08-10 08:50:24.424  7045  7045 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 08:50:24.424  7045  7045 I Adreno-EGL: Remote Branch: 
08-10 08:50:24.424  7045  7045 I Adreno-EGL: Local Patches: 
08-10 08:50:24.424  7045  7045 I Adreno-EGL: Reconstruct Branch: 
,08-10 08:50:24.505  7045  7045 I NSApplication: Starting up...
,08-10 08:50:24.561  1036  1574 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7149 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-10 08:50:24.562  1036  1574 I ActivityManager: Killing 6065:com.android.vending/u0a44 (adj 15): empty #17
08-10 08:50:24.565  7088  7107 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:24.565  7088  7107 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:50:24.583   342   342 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 22.236ms
,08-10 08:50:24.600   342   342 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 350us total 16.614ms
,08-10 08:50:24.618   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 335us total 15.811ms
,08-10 08:50:24.631  1036  2029 W libprocessgroup: failed to open /acct/uid_10044/pid_6065/cgroup.procs: No such file or directory
,08-10 08:50:24.666  1036  1574 D WifiServiceImplEx: setWifiEnabled: false pid=6597, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 08:50:24.666  1036  1574 D WifiService: setWifiEnabled: false pid=6597, uid=10118
08-10 08:50:24.666  1036  1574 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 08:50:24.676  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 08:50:24.677  1036  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 08:50:24.677  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 08:50:24.677  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-10 08:50:24.678  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 08:50:24.679  1036  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-10 08:50:24.680  1036  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-10 08:50:24.681  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-10 08:50:24.681  1036  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 08:50:24.681  1036  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 08:50:24.682  1036  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-10 08:50:24.689  1036  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 08:50:24.689  1036  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 08:50:24.695  1036  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 08:50:24.696  1036  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.696  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.696  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 08:50:24.696  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 08:50:24.696  1036  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 08:50:24.696  1036  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 08:50:24.697  1036  1537 D WifiNative-wlan0: SET ps 1: returned true
08-10 08:50:24.698  1036  7025 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.703   311   905 D CommandListener: Clearing all IP addresses on wlan0
,08-10 08:50:24.724  7167  7167 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-10 08:50:24.736  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 08:50:24.736  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-10 08:50:24.739  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-10 08:50:24.740  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:24.740  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:24.742  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:24.742  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:24.742  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-10 08:50:24.743  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:24.745  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-10 08:50:24.746  1036  1536 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.746  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.746  1036  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2f86fe13
08-10 08:50:24.746  1036  1536 D LGWifiP2pService: P2pDisablingState
08-10 08:50:24.746  1036  1536 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.746  1036  1536 D LGWifiP2pService: p2p socket connection lost
08-10 08:50:24.746  1036  1536 D LGWifiP2pService: P2pDisabledState
08-10 08:50:24.747  1036  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:24.747  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:24.748  1036  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:24.748  1036  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 08:50:24.748  1036  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-10 08:50:24.751  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-10 08:50:24.754  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:24.754  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:24.754  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 08:50:24.754  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-10 08:50:24.754  1036  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.755  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-10 08:50:24.755  1036  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.758  1036  1536 D LGWifiP2pService: P2pDisabledState{ when=-10ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.758  1036  1536 D LGWifiP2pService: DefaultState{ when=-10ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.758  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 08:50:24.759  6933  6933 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 08:50:24.759  1036  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 08:50:24.759  1036  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 08:50:24.759  1036  1537 D WifiNative-wlan0: SET ps 1: returned true
08-10 08:50:24.767  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 08:50:24.767  1939  1939 D WfdsService: WifiP2pState is changed : false
08-10 08:50:24.769  1939  2327 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-10 08:50:24.769  1939  2327 D WfdsService: Set the WFDS Monitor: false
08-10 08:50:24.770  1939  2327 D WfdsMonitor: WFDS Monitor is stopped
08-10 08:50:24.770  1939  2327 D WfdsService: STATE : WfdsDisabledState - enter
,08-10 08:50:24.770  1939  6952 D CtrlSupplicant: Received on exit socket, terminate
08-10 08:50:24.770  1939  6952 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-10 08:50:24.770  1939  6952 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-10 08:50:24.770  1939  6952 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-10 08:50:24.771  1939  2328 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-10 08:50:24.771  1939  2327 W WfdsService: DefaultState - msg [9445378] is not handled
08-10 08:50:24.775  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:24.775  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:24.776  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:24.803   311   905 D CommandListener: Clearing all IP addresses on wlan0
08-10 08:50:24.803  1036  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
,08-10 08:50:24.803  1036  1543 D DSQN    : disableDataServiceNotify
08-10 08:50:24.803  1036  1543 D DSQN    : stop dsqn bin
08-10 08:50:24.804  1036  1537 D WifiNative-p2p0: doBoolean: TERMINATE
08-10 08:50:24.804  1036  1537 D WifiNative-p2p0: TERMINATE: returned true
08-10 08:50:24.804  1036  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 08:50:24.804  1036  1537 E WifiStateMachine: useWiFiOffloading() : false
08-10 08:50:24.804  1036  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-10 08:50:24.807  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-10 08:50:24.807  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:24.807  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:24.807  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 08:50:24.808  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-10 08:50:24.809  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-10 08:50:24.809  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:24.809  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-10 08:50:24.809  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:24.809  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-10 08:50:24.809  1036  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-10 08:50:24.809  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:24.809  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:24.810  1036  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:24.811  1036  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-10 08:50:24.811  1036  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-10 08:50:24.811  1036  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-10 08:50:24.811  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 08:50:24.811  1036  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:24.812  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 08:50:24.812  1036  7024 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.812  1036  7024 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:24.812  1036  7024 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-10 08:50:24.812  1602  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-10 08:50:24.812  1036  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 08:50:24.813  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking s,upport for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:24.813  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:24.813  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:24.813  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:24.813  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:24.813  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:24.813  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:24.813  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:24.813  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:24.813  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:24.813  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:24.813  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 08:50:24.813  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 08:50:24.814  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 08:50:24.814  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 08:50:24.814  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:24.815  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:24.815  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:24.815  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:24.815  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:24.815  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:24.815  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:24.815  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:24.815  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:24.815  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:24.815  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:24.815  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:24.816  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:24.817  1036  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:24.817  1036  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 ,08:50:24.817  1036  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:24.817  1036  1543 D NetworkManagementService: Removing idletimer
08-10 08:50:24.817  1036  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:24.817  1036  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-10 08:50:24.818  1036  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:24.818  1036  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 08:50:24.818  1036  1543 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-10 08:50:24.818  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:24.818  1036  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 08:50:24.819  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 08:50:24.820  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 08:50:24.820  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 08:50:24.820  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 08:50:24.820  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 08:50:24.843  7167  7167 I dex2oat : dex2oat took 118.581ms (threads: 4)
08-10 08:50:24.850  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-10 08:50:24.851  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 08:50:24.851  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:24.856  7088  7107 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 08:50:24.856  7088  7107 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 08:50:24.856  7088  7107 I Adreno-EGL: Build Date: 12/12/14 금
08-10 08:50:24.856  7088  7107 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 08:50:24.856  7088  7107 I Adreno-EGL: Remote Branch: 
08-10 08:50:24.856  7088  7107 I Adreno-EGL: Local Patches: 
08-10 08:50:24.856  7088  7107 I Adreno-EGL: Reconstruct Branch: 
08-10 08:50:24.869  1036  1972 I art     : Explicit concurrent mark sweep GC freed 96537(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.993ms total 220.964ms
,08-10 08:50:24.876  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 08:50:24.876  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:24.877  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:24.885  7149  7149 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 08:50:24.890  6933  6933 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-10 08:50:24.890  6933  6933 I wpa_supplicant: monitor socket send errors count : 1
08-10 08:50:24.890  6933  6933 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-4\x00 that cannot receive messages
08-10 08:50:24.891  1036  6937 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-10 08:50:24.891  1036  6937 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-10 08:50:24.910  1036  7025 D DhcpStateMachine: StoppedState
08-10 08:50:24.910  1036  7025 D DhcpStateMachine: StoppedState{ when=-150ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 08:50:24.911  1036  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-10 08:50:24.911  1036  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-10 08:50:24.911  6933  6933 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 08:50:24.912  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-10 08:50:24.912  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 08:50:24.912  1036  6937 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 08:50:24.912  1036  6937 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-10 08:50:24.912  1036  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=312000
08-10 08:50:24.912  1036  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=312000
08-10 08:50:24.913  6933  6933 W wpa_supplicant: USIM:  scard_deinit function
08-10 08:50:24.913  1036  1118 D Tethering: InitialState.processMessage what=4
08-10 08:50:24.914  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 08:50:24.914  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 08:50:24.914  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 08:50:24.914  1036  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=312002  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 08:50:24.915  1036  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=312002  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 08:50:24.915  1036  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:24.915  1036  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:24.945  7088  7107 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 08:50:24.945  7088  7107 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 08:50:24.945  7088  7107 I Adreno-EGL: Build Date: 12/12/14 금
08-10 08:50:24.945  7088  7107 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 08:50:24.945  7088  7107 I Adreno-EGL: Remote Branch: 
08-10 08:50:24.945  7088  7107 I Adreno-EGL: Local Patches: 
08-10 08:50:24.945  7088  7107 I Adreno-EGL: Reconstruct Branch: 
,08-10 08:50:24.987  7088  7107 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 08:50:24.987  7088  7107 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 08:50:24.987  7088  7107 I Adreno-EGL: Build Date: 12/12/14 금
08-10 08:50:24.987  7088  7107 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 08:50:24.987  7088  7107 I Adreno-EGL: Remote Branch: 
08-10 08:50:24.987  7088  7107 I Adreno-EGL: Local Patches: 
08-10 08:50:24.987  7088  7107 I Adreno-EGL: Reconstruct Branch: 
,08-10 08:50:25.081  6933  6933 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-10 08:50:25.081  1036  6937 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-10 08:50:25.082  1036  6937 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-10 08:50:25.082  1036  6937 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-10 08:50:25.084  1036  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-10 08:50:25.150  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-10 08:50:25.152  6279  6672 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 08:50:25.174  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:25.191  1939  1939 D WfdsService: Supplicant Connection state is changed : false
08-10 08:50:25.191  1939  2327 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-10 08:50:25.191  1939  2327 D WfdsService: Set the WFDS Monitor: false
08-10 08:50:25.191  1939  2327 D WfdsMonitor: WFDS Monitor is stopped
08-10 08:50:25.194  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 08:50:25.194  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:25.194  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 08:50:25.194  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-10 08:50:25.195  1036  1537 D WifiOffDelayIfNotUsed: stopMonitoring
,08-10 08:50:25.195  1036  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 08:50:25.195  1036  1537 E WifiStateMachine: useWiFiOffloading() : false
08-10 08:50:25.195  1036  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 08:50:25.200  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:25.201  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 08:50:25.202  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-10 08:50:25.202  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:25.202  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:25.202  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:25.202  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:25.202  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:25.202  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:25.202  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:25.202  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:25.202  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 08:50:25.203  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:25.203  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:25.203  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:25.203  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:25.203  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:25.203  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:25.203  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:25.203  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:25.203  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 08:50:25.203  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-10 08:50:25.203  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-10 08:50:25.205  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
08-10 08:50:25.208  2480  2480 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:25.219  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@920f5ad
08-10 08:50:25.219  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 08:50:25.219  6880  6880 D AppUp4:CustFacade: isPhone : true
,08-10 08:50:25.229  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-10 08:50:25.229  6880  6880 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 08:50:25.232  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:25.232  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 08:50:25.233  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:25.235  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:25.238  4353  7197 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 08:50:25.242  6908  6908 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-10 08:50:25.246  4353  7198 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:25.246  4353  7198 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 08:50:25.257  3462  3462 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 08:50:25.257  3462  3462 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:25.257  3462  3462 I LgeMiscReceiver: networkInfo.isConnected() = false
08-10 08:50:25.260  6943  6943 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-10 08:50:25.260  6943  6943 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 08:50:25.269  6908  7199 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:25.270  6790  7201 W FormManager: Network not available. Please check & try again.
08-10 08:50:25.274  7007  7007 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:25
08-10 08:50:25.275  7007  7007 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 08:50:25.275  7007  7007 D Weather.Utils: 2 : All the weather widget is gone.
08-10 08:50:25.275  7007  7007 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-10 08:50:25.275  7007  7007 D WeatherAncestor: connectivity changed - connection : true
08-10 08:50:25.275  6790  7202 V FormManager: Network unavailable.
08-10 08:50:25.275  7007  7007 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@37a4ec73
08-10 08:50:25.278  7007  7007 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 08:50:25.278  7007  7007 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 08:50:25.278  7007  7007 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 08:50:25.278  7007  7007 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 08:50:25.278  7007  7007 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:25
08-10 08:50:25.279  6790  7202 V FormManager: Network unavailable.
08-10 08:50:25.298  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 08:50:25.298  6678  6678 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 08:50:25.298  6678  6678 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 08:50:25.298  6678  6678 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-10 08:50:25.299  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 08:50:25.299  6678  6678 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 08:50:25.299  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-10 08:50:25.299  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 08:50:25.299  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 08:50:25.299  6678  6678 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 08:50:25.299  6678  6678 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 08:50:25.306  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:25.308  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 08:50:25.313  6790  7205 W FormManager: Network not available. Please check & try again.
08-10 08:50:25.314  6790  7206 V FormManager: Network unavailable.
,08-10 08:50:25.316  6790  7206 V FormManager: Network unavailable.
08-10 08:50:25.324  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 08:50:25.336   311  7208 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-10 08:50:25.337  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 08:50:25.338  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:25.339  1815  7037 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-10 08:50:25.342  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 08:50:25.348  6790  7210 W FormManager: Network not available. Please check & try again.
08-10 08:50:25.350  1815  7037 I CheckinService: active receiver: disabled
08-10 08:50:25.350  6790  7211 V FormManager: Network unavailable.
,08-10 08:50:25.351  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:25.362  6790  7211 V FormManager: Network unavailable.
,08-10 08:50:25.370  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-10 08:50:25.370  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 08:50:25.372  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:25.373  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:25.376  4353  7212 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-10 08:50:25.378  4353  7213 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-10 08:50:25.378  4353  7213 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 08:50:25.406  1036  1717 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7214 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-10 08:50:25.529  6515  6857 D UEI.SmartControl: Internal timer expired: 2
08-10 08:50:25.529  6515  6857 D UEI.SmartControl: unbind internal service
,08-10 08:50:25.543  7214  7214 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-10 08:50:25.543  7214  7214 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-10 08:50:25.557  7214  7214 V [BNRBootReceiver]: Boot Receiver Return
,08-10 08:50:25.559  7214  7214 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-10 08:50:25.562  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:25.574  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:25.579  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:25.594  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:25.595  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 08:50:25.596  6746  6746 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-10 08:50:25.601  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:25.611  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:25.619  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:25.630  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 08:50:25.635  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:25.639  6746  6746 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 08:50:25.650  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-10 08:50:25.664  6678  6678 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-10 08:50:25.674  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:25.695  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:25.703  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:25.716  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:25.716  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:25.717  6746  6746 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 08:50:25.728  6515  6851 D serial_port: close(fd = 24)
08-10 08:50:25.729  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:25.735  6515  6851 I UEI.SmartControl: Serial port is closed.
08-10 08:50:25.736  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:25.744  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:25.754  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:25.754  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 08:50:25.755  6746  6746 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 08:50:25.762  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:25.773  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:25.781  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:25.792  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:25.792  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 08:50:25.793  6746  6746 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 08:50:25.801  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:25.815  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:25.823  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:25.833  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:25.834  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 08:50:25.834  6746  6746 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 08:50:25.840  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:25.849  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:25.857  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:25.866  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:25.867  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:25.868  6746  6746 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 08:50:25.880  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:25.900  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:25.911  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:25.922  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 08:50:25.923  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:25.932  6746  6746 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 08:50:25.939  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:25.957  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:25.970  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:25.985  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:25.986  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 08:50:25.988  6746  6746 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 08:50:26.000  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:26.010  6698  6698 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-10 08:50:26.029  1036  1542 D WifiService: New client listening to asynchronous messages
,08-10 08:50:26.030  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:26.040  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:26.054  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:26.072  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 08:50:26.073  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:26.075  6746  6746 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 08:50:26.077  6746  6746 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-10 08:50:26.079  6746  6746 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-10 08:50:26.092  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:26.102  6698  6698 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-10 08:50:26.105  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:26.115  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:26.127  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 08:50:26.145  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 08:50:26.145  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:26.146  6746  6746 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 08:50:26.148  6746  6746 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-10 08:50:26.148  6746  6746 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-10 08:50:26.152  1036  1051 I ActivityManager: Killing 6719:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-10 08:50:26.266  1036  1885 W libprocessgroup: failed to open /acct/uid_10037/pid_6719/cgroup.procs: No such file or directory
,08-10 08:50:26.282  2210  2210 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-10 08:50:26.301  2210  2210 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-10 08:50:26.302  2210  2210 D c       : Getting all permits...
08-10 08:50:26.302  2210  2210 D a       : Opening database...
08-10 08:50:26.309  2210  2210 D a       : Opening database auth.proximity.permit_store...
08-10 08:50:26.310  2210  2210 D a       : Closing database...
08-10 08:50:26.321  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:26.327  6698  6698 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 08:50:26.327  6698  6698 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 08:50:26.327  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:26.330  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:26.339  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:26.346  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 08:50:26.347  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:26.349  6746  6746 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 08:50:26.353  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:26.359  6698  6698 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 08:50:26.359  6698  6698 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 08:50:26.359  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 08:50:26.364  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:26.370  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:26.377  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:26.377  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:26.380  6746  6746 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 08:50:26.384  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:26.389  6698  6698 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 08:50:26.389  6698  6698 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 08:50:26.389  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:26.393  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:26.400  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:26.406  6746  6746 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:26.406  6746  6746 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 08:50:26.409  6746  6746 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 08:50:26.419  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:26.422  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 08:50:26.430  6790  7242 W FormManager: Network not available. Please check & try again.
08-10 08:50:26.430  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:26.431  6790  7243 V FormManager: Network unavailable.
08-10 08:50:26.446  6790  7243 V FormManager: Network unavailable.
,08-10 08:50:26.455  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 08:50:26.455  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 08:50:26.457  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:26.459  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:26.467  6698  6698 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-10 08:50:26.467  6698  6698 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 08:50:26.467  6698  6698 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 08:50:26.472  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 08:50:26.479  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 08:50:26.482  4353  7246 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 08:50:26.482  4353  7246 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 08:50:26.483  4353  7244 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 08:50:26.488  6790  7247 W FormManager: Network not available. Please check & try again.
08-10 08:50:26.499  2210  2210 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-10 08:50:26.518  6790  7248 V FormManager: Network unavailable.
,08-10 08:50:26.524  6790  7248 V FormManager: Network unavailable.
,08-10 08:50:26.691  1036  1537 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1933011458] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 08:50:26.693  1036  1537 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1933011461] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 08:50:26.796  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:26.803  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-10 08:50:26.804  1036  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:26.809  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:26.811  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:26.812  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 08:50:26.817  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-10 08:50:26.821  6279  6672 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 08:50:26.832  1036  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 08:50:26.839  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:26.852  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 08:50:26.852  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:26.852  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 08:50:26.852  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 08:50:26.858  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
08-10 08:50:26.862  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@920f5ad
08-10 08:50:26.862  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 08:50:26.862  6880  6880 D AppUp4:CustFacade: isPhone : true
08-10 08:50:26.862  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-10 08:50:26.862  6880  6880 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 08:50:26.867  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:26.867  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-10 08:50:26.869  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:26.872  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:26.878  4353  7265 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 08:50:26.880  6908  6908 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-10 08:50:26.888  4353  7266 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:26.888  4353  7266 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-10 08:50:26.905  6908  7267 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 08:50:26.914  3462  3462 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 08:50:26.914  3462  3462 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:26.914  3462  3462 I LgeMiscReceiver: networkInfo.isConnected() = true
08-10 08:50:26.914  3462  3462 D PhoneState: setPdpRejectCasuse : false
08-10 08:50:26.917  6943  6943 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 08:50:26.917  6943  6943 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 08:50:26.930  6790  7269 W FormManager: Network not available. Please check & try again.
,08-10 08:50:26.936  7007  7007 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:26
08-10 08:50:26.937  6790  7270 V FormManager: Network unavailable.
08-10 08:50:26.939  7007  7007 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 08:50:26.939  7007  7007 D Weather.Utils: 2 : All the weather widget is gone.
08-10 08:50:26.940  6790  7270 V FormManager: Network unavailable.
08-10 08:50:26.940  7007  7007 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 08:50:26.940  7007  7007 D WeatherAncestor: connectivity changed - connection : true
08-10 08:50:26.940  7007  7007 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@37a4ec73
08-10 08:50:26.942  7007  7007 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 08:50:26.942  7007  7007 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 08:50:26.942  7007  7007 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 08:50:26.942  7007  7007 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 08:50:26.943  7007  7007 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:26
08-10 08:50:27.680  1036  2048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:27.680  1036  2048 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-10 08:50:27.701  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 08:50:27.701  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 08:50:27.701  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-10 08:50:27.702  1036  1118 D BluetoothManagerService: Message: 1
08-10 08:50:27.702  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-10 08:50:27.727  1036  1118 D BluetoothManagerService: Message: 20
08-10 08:50:27.727  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@135a914:true
,08-10 08:50:27.732  6829  6829 D BluetoothAdapterState: make
08-10 08:50:27.737  6829  6829 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-10 08:50:27.737  6829  6829 I bluedroid-qcom: init
08-10 08:50:27.738  6829  7284 I BluetoothAdapterState: Entering OffState
08-10 08:50:27.739  6829  6829 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-10 08:50:27.739  6829  6829 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-10 08:50:27.739  6829  6829 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 08:50:27.739  6829  6829 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 08:50:27.739  6829  6829 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-10 08:50:27.741  6829  6829 I bluedroid-qcom: get_profile_interface socket
08-10 08:50:27.741  6829  6829 I bluedroid-qcom: get_profile_interface map_client
,08-10 08:50:27.746  6829  7288 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-10 08:50:27.733  7287  7287 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:27.751  6829  7288 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-10 08:50:27.743  7287  7287 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:27.760  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 08:50:27.761  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-10 08:50:27.766  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-10 08:50:27.767  1036  1118 D BluetoothManagerService: Message: 40
08-10 08:50:27.767  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-10 08:50:27.768  6829  6845 I bluedroid-qcom: config_hci_snoop_log
08-10 08:50:27.770  7287  7287 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-10 08:50:27.770  7287  7287 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-10 08:50:27.770  7287  7287 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-10 08:50:27.771  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-10 08:50:27.771  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-10 08:50:27.772  7287  7287 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-10 08:50:27.776  7287  7287 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-10 08:50:27.776  7287  7287 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-10 08:50:27.785  6829  7284 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-10 08:50:27.785  6829  7288 D BluetoothAdapterProperties: Name is: G3
08-10 08:50:27.786  6829  7284 D BluetoothAdapterProperties: Setting state to 11
08-10 08:50:27.786  6829  7284 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-10 08:50:27.787  1036  1118 D BluetoothManagerService: Message: 60
08-10 08:50:27.787  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-10 08:50:27.787  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-10 08:50:27.788  6829  7284 I LGBluetoothServiceJni: classInitNative: succeeds
08-10 08:50:27.795  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-10 08:50:27.799  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 08:50:27.801  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:27.803  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:27.806  6678  6678 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-10 08:50:27.814  6829  6829 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 08:50:27.814  6829  6829 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:27.815  6829  6829 V BluetoothPbapReceiver: ***********state = 11
,08-10 08:50:27.818  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:27.826  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:27.827  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-10 08:50:27.833  1036  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:27.848  6829  7284 D BluetoothBondStateMachine: make
08-10 08:50:27.852  6829  7284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:27.852  6829  7284 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-10 08:50:27.852  6829  7284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:27.852  6829  7284 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-10 08:50:27.853  6829  7284 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-10 08:50:27.853  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:27.854  6829  7302 I BluetoothBondStateMachine: StableState(): Entering Off State
08-10 08:50:27.855  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-10 08:50:27.857  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:27.863  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:27.863  6829  7284 E BluetoothAdapterService: File transfer profiles supported!!
08-10 08:50:27.864  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 08:50:27.865  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:27.866  6279  6672 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 08:50:27.867  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 08:50:27.871  1036  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:27.877  6829  6829 D HeadsetService: Received start request. Starting profile...
08-10 08:50:27.877  6829  6829 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 08:50:27.878  6829  6829 D LGBluetoothHfpAdapter: Version 1.6
08-10 08:50:27.878  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-10 08:50:27.881  6829  6829 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 08:50:27.882  6829  7284 E BluetoothAdapterService: File transfer profiles supported!!
08-10 08:50:27.882  6829  6829 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 08:50:27.883  6829  6829 D HeadsetStateMachine: make
,08-10 08:50:27.924  6829  6829 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:27.924  6829  6829 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:50:27.926  1036  1956 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7308 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-10 08:50:27.932  6829  6829 D HeadsetStateMachine: max_hf_connections = 1
08-10 08:50:27.932  6829  6829 I bluedroid-qcom: get_profile_interface handsfree
08-10 08:50:27.932  1036  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:27.932  6829  7284 E BluetoothAdapterService: File transfer profiles supported!!
08-10 08:50:27.933  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-10 08:50:27.934  6829  6829 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-10 08:50:27.934   315  1385 V AudioPolicyService: registerClient() client 0xb558ad60, uid 1002
08-10 08:50:27.935   315   315 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-10 08:50:27.935   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 08:50:27.935   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 08:50:27.935  6829  6829 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-10 08:50:27.935  1036  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:27.935   315  1386 V AudioFlinger: registerClient() client 0xb57bb1d8, pid 6829
08-10 08:50:27.936   315  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:27.936   315  1380 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 08:50:27.936  6829  6829 V ToneGenerator: Create Track: 0xb4928080
08-10 08:50:27.936  6829  6829 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-10 08:50:27.936  6829  6829 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-10 08:50:27.936  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:27.936  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 08:50:27.936   315  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 08:50:27.936   315  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-10 08:50:27.936   315  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 08:50:27.936   315  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 08:50:27.936  1602  2077 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:27.936  1602  2077 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 08:50:27.936   315  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:27.936   315  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 08:50:27.937  6829  6829 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-10 08:50:27.937  6829  6844 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:27.937  6829  6844 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-10 08:50:27.937  1036  2048 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:27.937  1036  2048 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 08:50:27.937  1602  2077 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:27.937  1602  2077 V AudioSystem: ioConfigChanged() opening alrea,dy existing output! 4
08-10 08:50:27.937  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:27.937  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 08:50:27.937  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:27.937  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 08:50:27.937  3462  3481 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:27.937  3462  3481 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 08:50:27.937  3462  3481 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:27.937  3462  3481 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 08:50:27.938  6829  6844 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:27.938  6829  6844 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-10 08:50:27.938   315  2139 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 08:50:27.938   315  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 08:50:27.938   315  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-10 08:50:27.938   315  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 08:50:27.938   315  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 08:50:27.938  6829  6829 V AudioSystem: getLatency() output 2, latency 50
08-10 08:50:27.938  6829  6829 V AudioSystem: getFrameCount() output 2, frameCount 960
08-10 08:50:27.938  6829  6829 V AudioTrack: createTrack_l() output 2 afLatency 50
08-10 08:50:27.938   315  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 08:50:27.938   315  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 08:50:27.938   315  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 08:50:27.939   315  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 08:50:27.939   315  2138 V AudioFlinger: createTrack() lSessionId: 22
,08-10 08:50:27.944  6829  6829 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-10 08:50:27.945  6829  7284 E BluetoothAdapterService: File transfer profiles supported!!
08-10 08:50:27.945   315  2138 V AudioFlinger: acquiring 22 from 6829, for 6829
08-10 08:50:27.945   315  2138 V AudioFlinger:  added new entry for 22
08-10 08:50:27.945  6829  6829 V ToneGenerator: ToneGenerator INIT OK, time: 315046
08-10 08:50:27.945  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:27.946  6829  7307 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-10 08:50:27.946  6829  7307 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 08:50:27.946  6829  7307 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 08:50:27.946  6829  7307 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-10 08:50:27.947  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:27.947   315  2138 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6829
08-10 08:50:27.947   315  2138 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-10 08:50:27.947   315  2138 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-10 08:50:27.947   315  2138 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-10 08:50:27.947   315  2138 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-10 08:50:27.947   315  2138 V voice   : voice_set_parameters: exit with code(0)
08-10 08:50:27.947   315  2138 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-10 08:50:27.947   315  2138 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-10 08:50:27.948   315  2138 V msm8974_platform: platform_set_parameters: exit with code(0)
08-10 08:50:27.948   315  2138 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-10 08:50:27.948   315  2138 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-10 08:50:27.948   315  2138 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-10 08:50:27.948  6829  7307 V ToneGenerator: ToneGenerator destructor
08-10 08:50:27.948  6829  7307 V ToneGenerator: stopTone
08-10 08:50:27.948  6829  7307 V ToneGenerator: Delete Track: 0xb4928080
08-10 08:50:27.948  6829  7307 V AudioTrack: ~AudioTrack, releasing session id from 6829 on behalf of 6829
08-10 08:50:27.948   315   315 V AudioFlinger: releasing 22 from 6829 for 6829
08-10 08:50:27.948   315   315 V AudioFlinger:  decremented refcount to 0
08-10 08:50:27.948   315   315 V AudioFlinger: purging stale effects
08-10 08:50:27.948   315   315 V AudioPolicyService: AudioCommandThread() adding release output 2
08-10 08:50:27.948   315   315 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-10 08:50:27.948   315   315 V AudioFlinger: PlaybackThread::Track destructor
08-10 08:50:27.948   315  1274 V AudioPolicyService: AudioCommandThread() waking up
08-10 08:50:27.948   315   315 V AudioFlinger: removeClient_l() pid 6829, calling pid 315
08-10 08:50:27.948   315  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-10 08:50:27.949   315  1274 V AudioPolicyManager: releaseOutput() 2
08-10 08:50:27.949   315  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-10 08:50:27.949  6829  6829 D A2dpService: Received start request. Starting profile...
08-10 08:50:27.950  6829  6829 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 08:50:27.950  6829  6829 V Avrcp   : make
08-10 08:50:27.951  6829  6829 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-10 08:50:27.951  6829  6829 I bluedroid-qcom: get_profile_interface avrcp
08-10 08:50:27.954  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CON,NECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:27.954  6829  7284 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 08:50:27.960  6829  6829 V AudioManager: registerRemoteController: size of Media player list: 0
08-10 08:50:27.961  6829  6829 E AudioManager: No RCC entry present to update
08-10 08:50:27.961  6829  6829 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-10 08:50:27.962  6829  7284 E BluetoothAdapterService: File transfer profiles supported!!
08-10 08:50:27.964  6829  6829 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-10 08:50:27.965  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-10 08:50:27.965  6829  6829 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-10 08:50:27.971  6829  7284 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 08:50:27.977  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-10 08:50:27.992  6829  7284 V LGMDMManager: Create singleton instance
,08-10 08:50:27.994  6829  7284 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-10 08:50:28.019  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-10 08:50:28.019  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:28.019  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 08:50:28.019  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-10 08:50:28.020  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
08-10 08:50:28.024  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@920f5ad
08-10 08:50:28.024  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 08:50:28.024  6880  6880 D AppUp4:CustFacade: isPhone : true
08-10 08:50:28.024  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-10 08:50:28.024  6880  6880 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 08:50:28.028  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:28.028  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 08:50:28.029  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 08:50:28.031  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:28.037  6908  6908 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-10 08:50:28.040  4353  7330 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 08:50:28.045  4353  7331 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:28.045  4353  7331 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-10 08:50:28.057  3462  3462 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 08:50:28.057  3462  3462 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:28.057  3462  3462 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-10 08:50:28.059  7308  7308 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-10 08:50:28.059  7308  7308 W LG Account v2.2: No ProfileInfo entries
08-10 08:50:28.059  7308  7308 I LG Account v2.2: isEnabled: false
08-10 08:50:28.059  7308  7308 I Feature : [Lifetracker]ver: 4.21.112(40211120)
,08-10 08:50:28.059  7308  7308 I Feature : [Lifetracker]Country: EU
08-10 08:50:28.059  7308  7308 I Feature : [Lifetracker]Operator: OPEN
08-10 08:50:28.059  7308  7308 I Feature : [Lifetracker]Ranking support: false
08-10 08:50:28.059  7308  7308 I Feature : [Lifetracker]Comfort support: false
08-10 08:50:28.060  7308  7308 I Feature : [Lifetracker]Accessory: true
08-10 08:50:28.060  7308  7308 I Feature : [Lifetracker]Health device: true
08-10 08:50:28.060  7308  7308 I Feature : [Lifetracker]Extra Pedometer: false
08-10 08:50:28.060  7308  7308 I Feature : [Lifetracker]Blood glucose device: false
08-10 08:50:28.060  7308  7308 I Feature : [Lifetracker]Device Number: 3
08-10 08:50:28.060  6943  6943 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 08:50:28.060  6943  6943 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 08:50:28.062  1036  1885 V SIM_STK : Menu title from STK is T-Mobile
08-10 08:50:28.062  1036  1885 V SIM_STK : Menu title from STK is T-Mobile
08-10 08:50:28.067  6790  7334 W FormManager: Network not available. Please check & try again.
08-10 08:50:28.069  6908  7333 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 08:50:28.074  6678  6678 D BluetoothPermissionRequest: onReceive
08-10 08:50:28.076  7007  7007 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:28
08-10 08:50:28.076  6790  7335 V FormManager: Network unavailable.
08-10 08:50:28.077  7007  7007 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 08:50:28.077  7007  7007 D Weather.Utils: 2 : All the weather widget is gone.
08-10 08:50:28.078  7007  7007 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 08:50:28.078  7007  7007 D WeatherAncestor: connectivity changed - connection : true
08-10 08:50:28.078  7007  7007 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@37a4ec73
08-10 08:50:28.079  7007  7007 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 08:50:28.079  7007  7007 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 08:50:28.079  7007  7007 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 08:50:28.079  7007  7007 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 08:50:28.079  6678  6678 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 08:50:28.079  7007  7007 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:28
08-10 08:50:28.083  6790  7335 V FormManager: Network unavailable.
,08-10 08:50:28.098  6279  6279 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-10 08:50:28.099  6279  6672 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 08:50:28.110  1036  1992 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-10 08:50:28.111  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:28.116  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-10 08:50:28.118  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 08:50:28.118  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:28.118  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 08:50:28.118  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 08:50:28.118  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-10 08:50:28.119  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-10 08:50:28.119  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 08:50:28.119  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 08:50:28.119  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 08:50:28.119  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 08:50:28.119  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 08:50:28.119  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-10 08:50:28.119  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 08:50:28.119  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-10 08:50:28.119  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
08-10 08:50:28.120  6829  6829 I BluetoothA2dpServiceJni: classInitNative
08-10 08:50:28.120  6829  6829 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 08:50:28.120  6829  6829 D A2dpStateMachine: make
08-10 08:50:28.121  6829  6829 I bluedroid-qcom: get_profile_interface a2dp
08-10 08:50:28.121  6829  7340 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-10 08:50:28.122  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@920f5ad
08-10 08:50:28.122  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 08:50:28.122  6880  6880 D AppUp4:CustFacade: isPhone : true
08-10 08:50:28.122  6829  6829 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-10 08:50:28.122  6829  6829 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-10 08:50:28.122  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-10 08:50:28.122  6880  6880 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 08:50:28.123  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:28.123  6829  6829 D HeadsetStateMachine: Proxy object connected
,08-10 08:50:28.124  6829  6829 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-10 08:50:28.124  6829  6829 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-10 08:50:28.124  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:28.124  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 08:50:28.125  6829  6829 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 08:50:28.125  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:28.126  6829  6829 D HidService: Received start request. Starting profile...
08-10 08:50:28.126  6829  6829 I bluedroid-qcom: get_profile_interface hidhost
08-10 08:50:28.126  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:28.127  6829  7339 D A2dpStateMachine: Enter Disconnected: -2
08-10 08:50:28.127  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:28.131  6829  6829 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 08:50:28.131  6829  7307 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-10 08:50:28.131  6829  6829 I BluetoothHealthServiceJni: classInitNative: succeeds
08-10 08:50:28.132  6829  7307 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 08:50:28.132  6829  7307 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-10 08:50:28.132  6829  6829 D HealthService: Received start request. Starting profile...
08-10 08:50:28.134  6829  6829 I bluedroid-qcom: get_profile_interface health
08-10 08:50:28.134  6829  6829 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-10 08:50:28.134  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:28.134  4353  7342 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 08:50:28.134  6829  6829 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-10 08:50:28.136  6829  6829 D PanService: Received start request. Starting profile...
08-10 08:50:28.136  6829  6829 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 08:50:28.136  6829  6829 I bluedroid-qcom: get_profile_interface pan
,08-10 08:50:28.139  6908  6908 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-10 08:50:28.142  6829  6829 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-10 08:50:28.142  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:28.142  4353  7345 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:28.142  4353  7345 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 08:50:28.142  6829  6829 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-10 08:50:28.146  6829  6829 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 08:50:28.146  6829  6829 D BtGatt.GattService: Received start request. Starting profile...
08-10 08:50:28.146  6829  6829 D BtGatt.GattService: start()
08-10 08:50:28.146  6829  6829 I bluedroid-qcom: get_profile_interface gatt
08-10 08:50:28.146  6829  6829 D BtGatt.AdvertiseManager: advertise manager created
08-10 08:50:28.152  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:28.153  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:28.153  6829  6829 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-10 08:50:28.156  3462  3462 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 08:50:28.156  3462  3462 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:28.156  3462  3462 I LgeMiscReceiver: networkInfo.isConnected() = false
08-10 08:50:28.156  6829  6829 V BluetoothMapService: BluetoothMapBinder()
08-10 08:50:28.156  6829  6829 D BluetoothMapService: Received start request. Starting profile...
08-10 08:50:28.156  6829  6829 D BluetoothMapService: start()
08-10 08:50:28.159  6943  6943 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 08:50:28.159  6943  6943 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 08:50:28.161  6908  7349 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:28.161  6790  7352 W FormManager: Network not available. Please check & try again.
08-10 08:50:28.162  6829  6829 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-10 08:50:28.162  6829  6829 D BluetoothMapEmailAppObserver: createReceiver()
08-10 08:50:28.164  6829  6829 D BluetoothMapEmailAppObserver: initObservers()
08-10 08:50:28.164  6829  6829 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-10 08:50:28.166  6790  7353 V FormManager: Network unavailable.
,08-10 08:50:28.169  6790  7353 V FormManager: Network unavailable.
08-10 08:50:28.171  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:28.173  7007  7007 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:28
08-10 08:50:28.173  6829  6829 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 08:50:28.175  6829  6829 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 08:50:28.176  7007  7007 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 08:50:28.176  7007  7007 D Weather.Utils: 2 : All the weather widget is gone.
08-10 08:50:28.177  7007  7007 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-10 08:50:28.178  7007  7007 D WeatherAncestor: connectivity changed - connection : true
,08-10 08:50:28.178  7007  7007 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@37a4ec73
08-10 08:50:28.178  6829  6829 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 08:50:28.178  7007  7007 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 08:50:28.178  7007  7007 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 08:50:28.178  7007  7007 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 08:50:28.178  6829  6829 V PanService: [BTUI] SIM Extra State :ABSENT
08-10 08:50:28.178  7007  7007 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 08:50:28.178  7007  7007 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:28
08-10 08:50:28.181  6829  6829 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 08:50:28.183  6829  6829 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-10 08:50:28.183  6829  6829 V BluetoothMapService: Handler(): got msg=1
08-10 08:50:28.184  6829  7284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-10 08:50:28.184  6829  7284 I bluedroid-qcom: enable
08-10 08:50:28.185  6829  7354 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-10 08:50:28.185  6829  7354 I bt-btu  : btu_task pending for preload complete event
08-10 08:50:28.185  6829  7284 I bt_hci_bdroid: init
08-10 08:50:28.185  6829  6829 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:28.186  6829  7284 I bt_vendor: bt-vendor : init
08-10 08:50:28.186  6829  7284 I bt_vendor: bt-vendor : get_bt_soc_type
08-10 08:50:28.186  6829  7284 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-10 08:50:28.186  6829  7284 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-10 08:50:28.186  6829  7284 D bt_userial_mct: userial_init
08-10 08:50:28.186  6829  7284 D bt_hci_bdroid: set_power 1
08-10 08:50:28.186  6829  7284 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-10 08:50:28.186  6829  7284 I bt_vendor: Starting hciattach daemon
08-10 08:50:28.186  6829  7284 I bt_vendor: try to set true
08-10 08:50:28.186  6829  6829 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 08:50:28.186  6829  6829 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 08:50:28.186  6829  6829 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 08:50:28.186  6829  6829 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:28.186  6829  6829 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-10 08:50:28.173  7357  7357 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:28.173  7357  7357 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 08:50:28.202  7358  7358 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-10 08:50:28.265  7364  7364 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-10 08:50:28.290  7365  7365 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-10 08:50:28.325  7367  7367 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 08:50:28.340  7368  7368 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-10 08:50:28.354  7369  7369 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 08:50:28.367  7370  7370 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-10 08:50:28.405  7372  7372 I libmdmdetect: ESOC framework not supported
08-10 08:50:28.407  7372  7372 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-10 08:50:28.418  7372  7372 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-10 08:50:28.418  7372  7372 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-10 08:50:28.418  7372  7372 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-10 08:50:28.419  7372  7372 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-10 08:50:28.419  7372  7372 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-10 08:50:28.419  7372  7372 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-10 08:50:28.419  7372  7372 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-10 08:50:28.464  7372  7373 E QC-QMI  : qmi_client [7372] 14: failed to locate client data
,08-10 08:50:28.465   464   464 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-10 08:50:28.465   464   464 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-10 08:50:28.531  7380  7380 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-10 08:50:28.546  7381  7381 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-10 08:50:28.588  6829  7284 I bt_vendor: bluetooth satus is on
08-10 08:50:28.588  6829  7284 D bt_hci_bdroid: preload
,08-10 08:50:28.589  6829  7356 D bt_userial_mct: userial_open(port:0)
08-10 08:50:28.589  6829  7356 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-10 08:50:28.593  6829  7356 I bt_vendor: Done intiailizing UART
08-10 08:50:28.596  6829  7356 I bt_vendor: Done intiailizing UART
08-10 08:50:28.596  6829  7356 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-10 08:50:28.596  6829  7356 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-10 08:50:28.596  6829  7383 D bt_userial_mct: Entering userial_read_thread()
08-10 08:50:28.596  6829  7354 I bt-btu  : btu_task received preload complete event
08-10 08:50:28.597  6829  7354 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-10 08:50:28.597  6829  7354 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-10 08:50:28.599  6829  7354 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_HCI
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 08:50:28.604  6829  7354 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 08:50:28.666  6829  7354 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-10 08:50:28.667  6829  7354 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0234061 
08-10 08:50:28.667  6829  7354 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0234061 
,08-10 08:50:28.680  6829  7288 E bt-btif : Calling BTA_HhEnable
,08-10 08:50:28.680  6829  7354 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-10 08:50:28.680  6829  7288 E bt-btif : L2CAP - L2CA_Register() called for PSM: 0x0019
08-10 08:50:28.680  6829  7354 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-10 08:50:28.680  6829  7354 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-10 08:50:28.680  6829  7354 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-10 08:50:28.680  6829  7354 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-10 08:50:28.680  6829  7288 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-10 08:50:28.684  6829  7288 D BluetoothAdapterProperties: Name is: G3
,08-10 08:50:28.684  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 08:50:28.685  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-10 08:50:28.686  6829  7288 D BluetoothAdapterProperties: Scan Mode:20
08-10 08:50:28.687  6829  7288 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 08:50:28.687  6829  7288 D bt_hci_bdroid: postload
08-10 08:50:28.688  6829  7356 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 08:50:28.689  6829  7354 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-10 08:50:28.689  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:28.689  6829  7288 D bte_conf: Device ID record 1 : primary
08-10 08:50:28.689  6829  7288 D bte_conf:   vendorId            = 00c4
08-10 08:50:28.689  6829  7288 D bte_conf:   vendorIdSource      = 0001
08-10 08:50:28.689  6829  7288 D bte_conf:   product             = 13a1
08-10 08:50:28.689  6829  7288 D bte_conf:   version             = 1000
08-10 08:50:28.689  6829  7288 D bte_conf:   clientExecutableURL = 
08-10 08:50:28.689  6829  7288 D bte_conf:   serviceDescription  = 
08-10 08:50:28.689  6829  7288 D bte_conf:   documentationURL    = 
08-10 08:50:28.689  6829  7288 D bte_conf: bte_load_did_conf no section named DID2.
08-10 08:50:28.691  6829  7356 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 08:50:28.691  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:28.694  6829  7284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-10 08:50:28.695  6829  7284 D BluetoothAdapterProperties: ScanMode =  20
08-10 08:50:28.695  6829  7356 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 08:50:28.683  7385  7385 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:28.683  7385  7385 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 08:50:28.699  6829  7284 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-10 08:50:28.700  6829  7284 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-10 08:50:28.700  6829  7284 D BluetoothAdapterProperties: Setting state to 12
08-10 08:50:28.700  6829  7284 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 08:50:28.701  1036  1118 D BluetoothManagerService: Message: 60
08-10 08:50:28.701  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-10 08:50:28.701  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-10 08:50:28.702  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 08:50:28.703  6829  7288 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-10 08:50:28.704  6829  7354 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 08:50:28.704  6829  7354 W bt-smp  : Plain text(LSB ~ MSB) = ed fe 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 08:50:28.704  6829  7354 W bt-smp  : Encrypted text(LSB ~ MSB) = 30 06 c4 72 60 c3 de 68 c1 4c 7a 3f 3f ab b0 ca 
08-10 08:50:28.704  6829  7356 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 08:50:28.704  6829  7354 W bt-btm  : Stopping oneshot timer
08-10 08:50:28.705  6829  7288 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 08:50:28.708  6829  7383 E bt_mct  : hci lib postload completed
08-10 08:50:28.709  6829  7284 I BluetoothAdapterState: Entering On State
08-10 08:50:28.712  6829  7284 D LGBluetoothServiceAdapter: [BTUI] OnState
08-10 08:50:28.712  6829  7284 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-10 08:50:28.712  6829  7284 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-10 08:50:28.713  6829  7284 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-10 08:50:28.714  1036  1036 D BluetoothA2dp: Proxy object connected
08-10 08:50:28.716  6678  6694 D BluetoothMap: onBluetoothStateChange: up=true
08-10 08:50:28.720  6678  6694 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 08:50:28.736  6829  7288 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 08:50:28.736  6829  7288 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-10 08:50:28.745  6829  7354 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 08:50:28.745  6829  7354 W bt-smp  : Plain text(LSB ~ MSB) = ee 50 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 08:50:28.745  6829  7354 W bt-smp  : Encrypted text(LSB ~ MSB) = ad f9 c8 57 7d 6e 97 fe f4 c9 fd 93 68 a8 99 af 
08-10 08:50:28.745  6829  7354 W bt-btm  : Stopping oneshot timer
08-10 08:50:28.749  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 08:50:28.758  1036  1036 D BluetoothHeadset: Proxy object connected
08-10 08:50:28.760  6829  7284 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-10 08:50:28.767  6678  6678 D BluetoothMap: Proxy object connected
08-10 08:50:28.768  6678  6678 D MapProfile: Bluetooth service connected
08-10 08:50:28.768  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 08:50:28.768  6678  6678 D BluetoothMap: getConnectedDevices()
,08-10 08:50:28.769  6829  6844 V BluetoothMapService: getConnectedDevices()
08-10 08:50:28.770  6678  6678 D BluetoothInputDevice: Proxy object connected
08-10 08:50:28.770  6678  6678 D HidProfile: Bluetooth service connected
08-10 08:50:28.773  1850  1850 D BluetoothHeadset: Proxy object connected
08-10 08:50:28.773  1850  2402 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 08:50:28.783  6829  7354 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 08:50:28.783  6829  7354 W bt-smp  : Plain text(LSB ~ MSB) = 83 b3 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 08:50:28.783  6829  7354 W bt-smp  : Encrypted text(LSB ~ MSB) = 6f c5 5b b7 28 6a b7 6f bc 8c c2 cb a9 e6 45 e1 
08-10 08:50:28.783  6829  7354 W bt-btm  : Stopping oneshot timer
08-10 08:50:28.787  7398  7398 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-10 08:50:28.791  1850  1850 D BluetoothHeadset: Proxy object connected
08-10 08:50:28.791  6678  6693 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 08:50:28.792  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7385
08-10 08:50:28.793  6678  6694 D BluetoothPan: onBluetoothStateChange on: true
08-10 08:50:28.793  6678  6694 D BluetoothPan: onBluetoothStateChange call bindService
08-10 08:50:28.795  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 08:50:28.796  6678  6678 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 08:50:28.796  6678  6678 D PanProfile: Bluetooth service connected
08-10 08:50:28.798  1850  1850 D BluetoothHeadset: Proxy object connected
08-10 08:50:28.798  6829  7354 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 08:50:28.798  6829  7354 W bt-smp  : Plain text(LSB ~ MSB) = ea 50 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 08:50:28.798  6829  7354 W bt-smp  : Encrypted text(LSB ~ MSB) = 46 50 db 3c 09 df ea 24 3c 15 56 62 a1 d1 fc 3e 
08-10 08:50:28.798  6829  7354 W bt-btm  : Stopping oneshot timer
08-10 08:50:28.799  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-10 08:50:28.799  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-10 08:50:28.801  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-10 08:50:28.801  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 08:50:28.805  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:28.805  1939  2123 D LGBluetoothAPIService: Message: 1
08-10 08:50:28.805  1939  2123 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-10 08:50:28.810  6829  6829 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:28.810  6829  6829 D BluetoothMapService: STATE_ON
08-10 08:50:28.811  6829  7354 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 08:50:28.811  6829  7354 W bt-smp  : Plain text(LSB ~ MSB) = ed 80 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 08:50:28.811  6829  7354 W bt-smp  : Encrypted text(LSB ~ MSB) = fc 5a 9a ec 5d 34 8c ad 91 97 c3 1a f7 b6 b7 cc 
08-10 08:50:28.811  6829  7354 W bt-btm  : Stopping oneshot timer
08-10 08:50:28.812  1939  2123 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-10 08:50:28.813  6597  6597 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 08:50:28.815  1036  1118 D BluetoothManagerService: Message: 40
08-10 08:50:28.815  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-10 08:50:28.820  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:28.820  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:28.820  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:28.820  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:28.820  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:28.820  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:28.820  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:28.820  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 08:50:28.822  6678  6678 D LocalBluetoothProfileManager: Adding local A2DP profile
08-10 08:50:28.824  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:28.828  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:28.828  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:28.828  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:28.828  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:28.828  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:28.828  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:28.828  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:28.828  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 08:50:28.830  1036  1118 D BluetoothManagerService: Message: 30
08-10 08:50:28.832  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 08:50:28.833  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:28.833  6829  6829 V BluetoothPbapService: Pbap Service onCreate
08-10 08:50:28.833  6829  6829 V BluetoothPbapService: Starting PBAP service
08-10 08:50:28.834  6678  6678 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-10 08:50:28.835  6829  6829 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-10 08:50:28.835  6829  6829 V BluetoothMapService: Handler(): got msg=1
08-10 08:50:28.837  6829  6829 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-10 08:50:28.837  1036  1118 D BluetoothManagerService: Message: 30
08-10 08:50:28.837  6829  6829 V BluetoothPbapService: Pbap Service onBind
08-10 08:50:28.838  6829  7404 D BluetoothMapMasInstance: MAS initSocket()
08-10 08:50:28.838  6829  6829 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:28.838  6829  6829 V BluetoothPbapService: state: 12
08-10 08:50:28.840  6829  6829 D LGBluetoothAPIServer: [BTUI] onCreate()
08-10 08:50:28.840  6829  6829 D LGBluetoothAPIServer: [BTUI] onBind()
08-10 08:50:28.840  6678  6678 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-10 08:50:28.840  6829  7404 D BluetoothMapMasInstance:   masId = 00
08-10 08:50:28.840  6829  7404 D BluetoothMapMasInstance:   msgTypes = 0e
08-10 08:50:28.840  6829  7404 D BluetoothMapMasInstance:   masName = SMS/MMS
08-10 08:50:28.840  6829  7404 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-10 08:50:28.841  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-10 08:50:28.841  1939  2123 D LGBluetoothAPIService: Message: 100
08-10 08:50:28.841  1939  2123 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-10 08:50:28.841  1036  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:28.842  6829  6829 V BluetoothPbapService: Handler(): got msg=1
08-10 08:50:28.842  6678  6678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 08:50:28.842  6829  6829 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-10 08:50:28.844  6829  7404 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 08:50:28.844  6829  7405 V BluetoothPbapService: Pbap Service initSocket
08-10 08:50:28.845  1036  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:28.846  6678  6678 D BluetoothA2dp: Proxy object connected
,08-10 08:50:28.846  6829  6829 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 08:50:28.846  6829  6829 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:28.846  6829  6829 V BluetoothPbapReceiver: ***********state = 12
08-10 08:50:28.846  6678  6678 D A2dpProfile: Bluetooth service connected
08-10 08:50:28.847  6829  7405 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 08:50:28.848  6829  7404 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-10 08:50:28.848  6829  7404 V BluetoothMapMasInstance: Succeed to create listening socket 
08-10 08:50:28.848  6829  7404 D BluetoothMapMasInstance: Accepting socket connection...
08-10 08:50:28.849  6829  7288 D BluetoothAdapterProperties: Scan Mode:21
08-10 08:50:28.850  6829  7288 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-10 08:50:28.850  6829  7405 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-10 08:50:28.850  6829  7405 V BluetoothPbapService: Succeed to create listening socket 
08-10 08:50:28.850  6829  7405 V BluetoothPbapService: Accepting socket connection...
08-10 08:50:28.852  6678  6678 D BluetoothPbap: Proxy object connected
08-10 08:50:28.853  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:28.853  6678  6678 D PbapServerProfile: Bluetooth service connected
08-10 08:50:28.854  6678  6678 D BluetoothHeadset: Proxy object connected
08-10 08:50:28.855  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:28.855  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 08:50:28.856  2210  2210 D c       : Getting all permits...
08-10 08:50:28.856  2210  2210 D a       : Opening database...
,08-10 08:50:28.857  6678  6678 D HeadsetProfile: Bluetooth service connected
08-10 08:50:28.861  6678  6678 D DockEventReceiver: finishStartingService: stopping service
08-10 08:50:28.861  2210  2210 D a       : Opening database auth.proximity.permit_store...
08-10 08:50:28.862  2210  2210 D a       : Closing database...
08-10 08:50:28.871  6678  6678 D BluetoothPermissionRequest: onReceive
,08-10 08:50:28.873  6678  6678 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 08:50:28.874  6678  6678 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 08:50:28.878  6829  6829 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-10 08:50:28.879  6829  6829 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-10 08:50:28.883  6829  6829 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-10 08:50:28.902  6829  6829 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 08:50:28.902  6829  6829 V BtOppService: onCreate
,08-10 08:50:28.907  6829  6829 V BluetoothOppNotification: send message
08-10 08:50:28.910  6829  6829 V BtOppService: Starting RfcommListener
08-10 08:50:28.917  6829  6829 D BluetoothOppPreference: Dumping Names:  
08-10 08:50:28.917  6829  6829 D BluetoothOppPreference: {}
08-10 08:50:28.917  6829  6829 D BluetoothOppPreference: Dumping Channels:  
08-10 08:50:28.917  6829  6829 D BluetoothOppPreference: {}
08-10 08:50:28.920  6829  6829 V BtOppService: onStartCommand
,08-10 08:50:28.926  6829  7413 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 08:50:28.927  6829  6829 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:28.928  6829  6829 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 08:50:28.929  6829  7413 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 08:50:28.930  6829  7409 V BtOppService: Deleted complete outbound shares, number =  0
,08-10 08:50:28.932  6829  7409 V BtOppService: Deleted complete inbound failed shares, number = 0
08-10 08:50:28.932  6829  7409 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-10 08:50:28.933  6829  6829 V BluetoothOppNotification: new notify threadi!
08-10 08:50:28.934  6829  7409 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38bb46b5 on behalf of 
08-10 08:50:28.934  6829  7413 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@270fb2ec on behalf of 
08-10 08:50:28.935  6829  6829 V BluetoothOppNotification: send delay message
08-10 08:50:28.936  6829  6829 V BtOppService: start RfcommListener
08-10 08:50:28.937  6829  7414 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 08:50:28.939  6829  7414 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c46714a on behalf of 
08-10 08:50:28.939  6829  7413 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-10 08:50:28.941  6829  7414 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-10 08:50:28.943  6829  7414 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 08:50:28.944  6829  6829 V BtOppService: RfcommListener started
,08-10 08:50:28.945  6829  6829 V BtOppService: ContentObserver received notification
08-10 08:50:28.945  6829  7414 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29bef8bb on behalf of 
08-10 08:50:28.946  6829  7414 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 08:50:28.948  6829  7416 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 08:50:28.948  6829  7416 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 08:50:28.949  6829  7415 V BtOppRfcommListener: Starting RFCOMM listener....
08-10 08:50:28.951  1036  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:28.951  6829  7414 V BluetoothOppNotification: outbound notification was removed.
08-10 08:50:28.951  6829  7415 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 08:50:28.952  6829  7414 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 08:50:28.952  6829  7415 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-10 08:50:28.953  6829  7415 V BtOppRfcommListener: Started RFCOMM listener....
08-10 08:50:28.953  6829  7415 I BtOppRfcommListener: Accept thread started.
08-10 08:50:28.953  6829  7415 V BtOppRfcommListener: Accepting connection...
08-10 08:50:28.955  6829  7416 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11bb11d8 on behalf of 
08-10 08:50:28.957  6829  7416 V BluetoothOppNotification: update too frequent, put in queue
08-10 08:50:28.957  6829  7414 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31269931 on behalf of 
,08-10 08:50:28.957  6829  7414 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 08:50:28.960  6829  7416 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-10 08:50:28.961  6829  7414 V BluetoothOppNotification: inbound notification was removed.
08-10 08:50:28.961  6829  7414 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 08:50:28.962  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:28.962  6829  6829 V BluetoothFtpService: Ftp Service onCreate
08-10 08:50:28.962  6829  6829 I BluetoothFtpService: Ftp Service onCreate
08-10 08:50:28.962  6829  6829 V BluetoothFtpService: Ftp Service onStartCommand
08-10 08:50:28.963  6829  6829 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:28.963  6829  6829 V BluetoothFtpService: Starting Listening on sockets
08-10 08:50:28.963  6829  6829 V BtOppService: ContentObserver received notification
08-10 08:50:28.963  6829  7414 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7da6597 on behalf of 
08-10 08:50:28.963  6829  6829 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 08:50:28.963  6829  6829 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 08:50:28.964  6829  6829 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 08:50:28.964  6829  6829 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:28.964  6829  6829 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-10 08:50:28.964  6829  6829 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 08:50:28.966  6829  6829 V BluetoothFtpService: Handler(): got msg=1
08-10 08:50:28.966  6829  7417 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 08:50:28.966  6829  7417 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 08:50:28.968  6829  7417 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cbb7384 on behalf of 
08-10 08:50:28.969  6829  7417 V BluetoothOppNotification: update too frequent, put in queue
08-10 08:50:28.969  6829  6829 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-10 08:50:28.969  6829  6829 V BluetoothFtpService: Ftp Service initSocket
08-10 08:50:28.969  6829  7417 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-10 08:50:28.971  1036  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 08:50:28.972  6829  6829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 08:50:28.973  6829  6829 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-10 08:50:28.973  6829  6829 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-10 08:50:28.975  6829  7418 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-10 08:50:28.986  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
,08-10 08:50:28.986  6829  6829 V BluetoothSapService: Sap Service onCreate
08-10 08:50:28.987  6829  6829 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-10 08:50:28.987  6829  6829 V BluetoothSapService: state: 12
08-10 08:50:28.988  6829  6829 V BluetoothSapService: Starting SAP server process
08-10 08:50:28.989  6829  6829 V BluetoothSapService: SAP Service startRfcommListenerThread
08-10 08:50:28.983  7419  7419 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:28.983  7419  7419 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:28.991  6829  7420 V BluetoothSapService: Sap Service initRfcommSocket
08-10 08:50:28.991  1036  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:28.992  6829  7420 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 08:50:28.993  6829  7420 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-10 08:50:28.993  6829  7420 V BluetoothSapService: Succeed to create listening socket 
08-10 08:50:28.993  6829  7420 V BluetoothSapService: Accepting socket connection...
08-10 08:50:29.000  7419  7419 V BT_SAP  : Event pipe created
08-10 08:50:29.000  7419  7419 V BT_SAP  : create_server_socket qcom.sap.server
,08-10 08:50:29.000  7419  7419 V BT_SAP  : created socket fd 6
,08-10 08:50:29.163  7045  7083 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-10 08:50:29.752  1036  1536 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 08:50:29.752  1036  1536 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 08:50:29.813  1036  1537 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-10 08:50:29.815  1036  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-10 08:50:29.936  6829  6829 V BluetoothOppNotification: new notify threadi!
,08-10 08:50:29.937  6829  6829 V BluetoothOppNotification: send delay message
,08-10 08:50:29.950  6829  7432 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 08:50:29.960  6829  7432 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a3e43f0 on behalf of 
08-10 08:50:29.960  6829  7432 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-10 08:50:29.965  6829  7432 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 08:50:29.966  6829  7432 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20d63d69 on behalf of 
08-10 08:50:29.967  6829  7432 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 08:50:29.970  6829  7432 V BluetoothOppNotification: outbound notification was removed.
08-10 08:50:29.970  6829  7432 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 08:50:30.128  1036  2029 I art     : Explicit concurrent mark sweep GC freed 83805(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.666ms total 148.262ms
,08-10 08:50:30.131  6829  7432 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a2453ee on behalf of 
08-10 08:50:30.131  6829  7432 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 08:50:30.133  6829  7432 V BluetoothOppNotification: inbound notification was removed.
08-10 08:50:30.133  6829  7432 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 08:50:30.134  6829  7432 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b1e708f on behalf of 
08-10 08:50:30.142  1036  1972 I ActivityManager: Killing 7214:com.lge.bnr/1000 (adj 15): empty #17
,08-10 08:50:30.159  1036  1884 W libprocessgroup: failed to open /acct/uid_1000/pid_7214/cgroup.procs: No such file or directory
,08-10 08:50:30.341  1036  1780 I ActivityManager: Killing 6515:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-10 08:50:30.365  6746  6746 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-10 08:50:30.365  6746  6746 W System.err: android.os.DeadObjectException
08-10 08:50:30.366  6746  6746 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 08:50:30.366  6746  6746 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 08:50:30.366  6746  6746 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-10 08:50:30.366  6746  6746 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-10 08:50:30.366  6746  6746 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-10 08:50:30.366  6746  6746 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-10 08:50:30.366  6746  6746 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 08:50:30.366  6746  6746 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 08:50:30.366  6746  6746 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 08:50:30.366  6746  6746 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 08:50:30.366  6746  6746 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 08:50:30.366  6746  6746 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 08:50:30.366  6746  6746 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 08:50:30.366  6746  6746 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 08:50:30.367  6746  6746 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,08-10 08:50:30.372  6746  6746 W System.err: android.os.DeadObjectException
08-10 08:50:30.373  6746  6746 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 08:50:30.373  6746  6746 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 08:50:30.373  6746  6746 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-10 08:50:30.373  6746  6746 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-10 08:50:30.373  6746  6746 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-10 08:50:30.373  6746  6746 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-10 08:50:30.373  6746  6746 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 08:50:30.373  6746  6746 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 08:50:30.373  6746  6746 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 08:50:30.373  6746  6746 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 08:50:30.373  6746  6746 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 08:50:30.373  6746  6746 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 08:50:30.373  6746  6746 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 08:50:30.373  6746  6746 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 08:50:30.373  6746  6746 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-10 08:50:30.374  6746  6746 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-10 08:50:30.399  1036  1936 W libprocessgroup: failed to open /acct/uid_1000/pid_6515/cgroup.procs: No such file or directory
08-10 08:50:30.399  1036  1936 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-10 08:50:30.408  6746  6746 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-10 08:50:30.409  6746  6746 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 08:50:30.450  1036  1885 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7433 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 08:50:30.450  6746  6746 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-10 08:50:30.540  7433  7433 D UEI.SmartControl: Quickset Services start...
,08-10 08:50:30.544  7433  7433 I UEI.SmartControl: Manufacture = LGE
08-10 08:50:30.544  7433  7433 D UEI.SmartControl: Id = LGNevo
08-10 08:50:30.545  7433  7433 D UEI.SmartControl: File observer start...
08-10 08:50:30.546  7433  7433 E UEI.SmartControl: IR Port is disabled: false
08-10 08:50:30.546  7433  7433 D UEI.SmartControl: Starting file observer...
08-10 08:50:30.546  7433  7433 D UEI.SmartControl: Extracting JNI libs...
08-10 08:50:30.546  7433  7433 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-10 08:50:30.611  7433  7433 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-10 08:50:30.612  7433  7433 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-10 08:50:30.612  7433  7433 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-10 08:50:30.639  7433  7433 I UEI.SmartControl: --- Selecting new region: 6
08-10 08:50:30.641  7433  7433 I UEI.SmartControl: Model = LG-D855
08-10 08:50:30.642  7433  7433 D UEI.SmartControl: QS Service created
,08-10 08:50:30.654  7433  7433 I UEI.SmartControl: Service initServices...
,08-10 08:50:30.660  7433  7433 D UEI.SmartControl: QS start get config
,08-10 08:50:30.707  7433  7433 D UEI.SmartControl: Loading JNI Libs...
,08-10 08:50:30.720  1036  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:30.720  1036  1992 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@affc9ff mBinding = false
,08-10 08:50:30.732  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 08:50:30.733  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 08:50:30.733  1036  1118 D BluetoothManagerService: Message: 2
08-10 08:50:30.733  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-10 08:50:30.733  1036  1118 D BluetoothManagerService: Sending off request.
08-10 08:50:30.734  6829  7318 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-10 08:50:30.734  6829  7284 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-10 08:50:30.734  6829  7284 D BluetoothAdapterProperties: Setting state to 13
08-10 08:50:30.734  6829  7284 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 08:50:30.735  6829  7284 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 08:50:30.735  6829  7284 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-10 08:50:30.736  6829  7288 D BluetoothAdapterProperties: Scan Mode:20
08-10 08:50:30.736  6829  7284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-10 08:50:30.737  6829  7284 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 08:50:30.739  6829  7420 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 08:50:30.739  6829  7404 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-10 08:50:30.739  6829  7404 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 08:50:30.739  6829  7404 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-10 08:50:30.739  6829  7404 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-10 08:50:30.739  6829  7404 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-10 08:50:30.739  6829  7404 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-10 08:50:30.739  6829  7404 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-10 08:50:30.739  6829  7404 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-10 08:50:30.740  6829  7418 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 08:50:30.740  6829  7415 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 08:50:30.740  6829  7405 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-10 08:50:30.741  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-10 08:50:30.741  6829  7354 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-10 08:50:30.744  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 08:50:30.744  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 08:50:30.744  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 08:50:30.744  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 08:50:30.744  6829  7354 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 08:50:30.744  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 08:50:30.744  6829  7354 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 08:50:30.744  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 08:50:30.744  6829  7354 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 08:50:30.745  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-10 08:50:30.745  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-10 08:50:30.745  6829  7354 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 08:50:30.746  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:30.746  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:30.746  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:30.746  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:30.746  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:30.746  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:30.746  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:30.746  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:30.746  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 08:50:30.747  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:30.747  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:30.748  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:30.748  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:30.748  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:30.748  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:30.748  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:30.748  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 08:50:30.748  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:30.748  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:30.748  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 08:50:30.749  6597  6597 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advert,isement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 08:50:30.749  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:30.785  1036  1118 D BluetoothManagerService: Message: 60
08-10 08:50:30.785  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-10 08:50:30.785  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-10 08:50:30.788  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 08:50:30.792  6829  6829 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:30.792  6829  6829 D BluetoothMapService: STATE_TURNING_OFF
08-10 08:50:30.792  6829  6829 V BtOppService: Receiver DISABLED_ACTION 
08-10 08:50:30.792  6829  6829 V BluetoothMapService: Handler(): got msg=4
08-10 08:50:30.792  6829  6829 D BluetoothMapService: MAP Service closeService in
08-10 08:50:30.792  6678  6678 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-10 08:50:30.792  6829  6829 D BluetoothMapMasInstance: MAP Service shutdown
08-10 08:50:30.793  6829  6829 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 08:50:30.793  6829  6829 V BluetoothMapService: MAP Service closeService out
08-10 08:50:30.793  6829  6829 I BtOppRfcommListener: stopping Accept Thread
08-10 08:50:30.793  6829  6829 V BtOppRfcommListener: close mBtServerSocket
08-10 08:50:30.793  6829  6829 V BtOppRfcommListener: waiting for thread to terminate
08-10 08:50:30.794  6829  7415 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 08:50:30.794  6829  6829 V BtOppRfcommListener: done waiting for thread to terminate
08-10 08:50:30.795  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:30.797  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:30.804  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:30.806  6829  6829 V BtOppService: onDestroy
08-10 08:50:30.807  6829  6829 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-10 08:50:30.820  6678  6678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 08:50:30.825  6829  6829 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 08:50:30.825  6829  6829 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:30.825  6829  6829 V BluetoothPbapReceiver: ***********state = 13
08-10 08:50:30.827  6829  6829 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-10 08:50:30.838  6829  6829 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED,
08-10 08:50:30.838  6829  6829 V BluetoothPbapService: state: 13
08-10 08:50:30.838  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 08:50:30.839  6829  6829 V BluetoothPbapService: Pbap Service closeService in
,08-10 08:50:30.844  6829  6829 V BluetoothPbapService: successfully stopped pbap service
08-10 08:50:30.844  6829  6829 V BluetoothPbapService: Pbap Service closeService out
08-10 08:50:30.844  6829  6829 V BluetoothPbapService: Pbap Service onDestroy
08-10 08:50:30.845  6829  6829 V BluetoothPbapService: Pbap Service closeService in
08-10 08:50:30.845  6829  6829 V BluetoothPbapService: Pbap Service closeService out
08-10 08:50:30.845  6829  6829 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-10 08:50:30.855  6678  6678 D DockEventReceiver: finishStartingService: stopping service
08-10 08:50:30.857  6678  6678 D BluetoothPbap: Proxy object disconnected
08-10 08:50:30.857  6678  6678 D PbapServerProfile: Bluetooth service disconnected
08-10 08:50:30.862  6678  6678 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-10 08:50:30.869  6678  6678 D BluetoothPermissionRequest: onReceive
08-10 08:50:30.869  6678  6678 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-10 08:50:30.878  6678  6678 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 08:50:30.882  6829  6829 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-10 08:50:30.882  6829  6829 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-10 08:50:30.884  6829  6829 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-10 08:50:30.890  6829  6829 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:30.890  6829  6829 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 08:50:30.891  6829  6829 V BluetoothFtpService: Ftp Service onStartCommand
08-10 08:50:30.891  6829  6829 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:30.892  6829  6829 V BluetoothFtpService: Ftp Service closeService
08-10 08:50:30.892  6829  6829 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-10 08:50:30.894  6829  6829 V BluetoothFtpService: successfully stopped ftp service
08-10 08:50:30.895  6829  6829 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 08:50:30.895  6829  6829 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 08:50:30.895  6829  6829 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 08:50:30.895  6829  6829 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:30.895  6829  6829 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-10 08:50:30.895  6829  6829 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 08:50:30.897  6829  6829 V BluetoothFtpService: Ftp Service onDestroy
08-10 08:50:30.897  6829  6829 V BluetoothFtpService: Ftp Service closeService
08-10 08:50:30.900  6829  6829 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:30.900  6829  6829 V BluetoothSapService: state: 13
08-10 08:50:30.900  6829  6829 V BluetoothSapService: Stopping SAP server process
08-10 08:50:30.901  6829  6829 V BluetoothSapService: Sap Service closeSapService in
08-10 08:50:30.901  6829  6829 V BluetoothSapService: Close listen Socket : 
08-10 08:50:30.901  6829  6829 V BluetoothSapService: Close rfcomm Socket : 
08-10 08:50:30.901  6829  6829 V BluetoothSapService: Close sapd  Socket : 
,08-10 08:50:30.903  6829  6829 V BluetoothSapService: Sap Service closeSapService out
,08-10 08:50:30.904  6829  6829 V BluetoothSapService: Sap Service onDestroy
08-10 08:50:30.904  6829  6829 V BluetoothSapService: Sap Service closeSapService in
08-10 08:50:30.904  6829  6829 V BluetoothSapService: Close listen Socket : 
08-10 08:50:30.904  6829  6829 V BluetoothSapService: Close rfcomm Socket : 
08-10 08:50:30.904  6829  6829 V BluetoothSapService: Close sapd  Socket : 
08-10 08:50:30.904  6829  6829 V BluetoothSapService: Sap Service closeSapService out
08-10 08:50:31.068  7433  7433 I UEI.SmartControl: Supports setup maps: true
08-10 08:50:31.071  7433  7433 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 08:50:31.071  7433  7433 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-10 08:50:31.071  7433  7433 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 08:50:31.071  7433  7433 I UEI.SmartControl: ### init IR Blaster...
,08-10 08:50:31.077  7433  7433 D serial_port: Configuring serial port
,08-10 08:50:31.080  7433  7433 E UEI.SmartControl: UEIBLaster setting for 616
08-10 08:50:31.080  7433  7433 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 08:50:31.081  7433  7433 I UEI.SmartControl: configuring settings for MAXQ616
08-10 08:50:31.081  7433  7433 I UEI.SmartControl: Get version...
,08-10 08:50:31.098  7433  7471 D UEI.SmartControl: serial port data available: 21
,08-10 08:50:31.126  7433  7433 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-10 08:50:31.126  7433  7433 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 08:50:31.126  7433  7433 I UEI.SmartControl: QS saving settings...
08-10 08:50:31.127  7433  7433 D UEI.SmartControl: IR Blaster version: 25672567
,08-10 08:50:31.145  7433  7471 D UEI.SmartControl: serial port data available: 4
08-10 08:50:31.187  7433  7477 I UEI.SmartControl: Device manager: loading config....
,08-10 08:50:31.189  7433  7477 D UEI.SmartControl: ----------- loading internal config...
,08-10 08:50:31.190  7433  7433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-10 08:50:31.195  7433  7433 E UEI.SmartControl: Services init done
08-10 08:50:31.195  7433  7433 D UEI.SmartControl: QS Service init finished
08-10 08:50:31.197  7433  7433 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 08:50:31.198  7433  7433 D UEI.SmartControl: QS Service version code: 201091
08-10 08:50:31.200  7433  7433 D UEI.SmartControl: Service requested: Control
08-10 08:50:31.214  7433  7433 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-10 08:50:31.218  7433  7477 E UEI.SmartControl: Loading SETTINGS...
08-10 08:50:31.222  1036  2048 I ActivityManager: Killing 6746:com.lge.qremote/u0a112 (adj 15): empty #17
08-10 08:50:31.232  7433  7477 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-10 08:50:31.243  7433  7476 I UEI.SmartControl: Notify AllClients services are ready: 0
08-10 08:50:31.244  7433  7476 D UEI.SmartControl: -----service ready thread exits
08-10 08:50:31.251  1036  1936 W libprocessgroup: failed to open /acct/uid_10112/pid_6746/cgroup.procs: No such file or directory
08-10 08:50:31.251  7433  7433 D UEI.SmartControl: Internal service binding...
,08-10 08:50:31.648  6829  7288 D bt_hci_bdroid: cleanup
,08-10 08:50:31.655  6829  7356 I bt_lpm  : LPM is already off!!!
08-10 08:50:31.656  6829  7354 W bt-btif : ag scb idx 1 not allocated
08-10 08:50:31.656  6829  7354 E bt-btif : BTA AG is already disabled, ignoring ...
08-10 08:50:31.656  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 08:50:31.656  6829  7354 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 08:50:31.656  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 08:50:31.656  6829  7354 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 08:50:31.656  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 08:50:31.657  6829  7354 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 08:50:31.657  6829  7354 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 08:50:31.661  6829  7383 I bt_userial_mct: exiting userial_read_thread
08-10 08:50:31.661  6829  7383 D bt_userial_mct: Leaving userial_evt_read_thread()
08-10 08:50:31.661  6829  7288 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-10 08:50:31.661  6829  7356 I bt_vendor: hw_epilog_process
08-10 08:50:31.662  6829  7288 D bt_hci_bdroid: cleanup Finalizing cleanup
08-10 08:50:31.662  6829  7288 D bt_userial_mct: userial_close
08-10 08:50:31.662  6829  7288 E bt_userial_mct: pthread_join() FAILED result:3
08-10 08:50:31.662  6829  7288 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-10 08:50:31.669  6829  7288 D bt_hci_bdroid: set_power 0
08-10 08:50:31.669  6829  7288 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-10 08:50:31.669  6829  7288 I bt_vendor: bluetooth satus is on
08-10 08:50:31.669  6829  7288 I bt_vendor: bt-vendor : resetting BT status
08-10 08:50:31.669  6829  7288 I bt_vendor: Starting hciattach daemon
08-10 08:50:31.669  6829  7288 I bt_vendor: try to set false
,08-10 08:50:31.676  6829  7288 I bt_vendor: Starting hciattach daemon
08-10 08:50:31.676  6829  7288 I bt_vendor: try to set false
08-10 08:50:31.677  6829  7288 I bt_vendor: cleanup
08-10 08:50:31.678  6829  7354 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-10 08:50:31.679  6829  7288 I GKI_LINUX: GKI_exit_task 0 done
08-10 08:50:31.679  6829  7288 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-10 08:50:31.680  6829  7284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-10 08:50:31.685  6829  6829 D HeadsetService: Received stop request...Stopping profile...
,08-10 08:50:31.689  6829  7307 D HeadsetStateMachine: Exit Disconnected: -1
08-10 08:50:31.688  6829  6829 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 08:50:31.691  6829  6829 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 08:50:31.691  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:31.694  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-10 08:50:31.694  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-10 08:50:31.695  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-10 08:50:31.695  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-10 08:50:31.695  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-10 08:50:31.698  6829  6829 D A2dpService: Received stop request...Stopping profile...
,08-10 08:50:31.701  6829  7339 D A2dpStateMachine: Exit Disconnected: -1
08-10 08:50:31.705  6829  6829 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-10 08:50:31.706  6829  7284 D BluetoothAdapterState: Stopping profile services that were post enabled
08-10 08:50:31.707  6829  6829 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-10 08:50:31.707  6829  6829 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 08:50:31.707  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:31.710  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-10 08:50:31.710  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-10 08:50:31.712  6829  6829 D HidService: Received stop request...Stopping profile...
08-10 08:50:31.712  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:31.714  6829  6829 D HealthService: Received stop request...Stopping profile...
08-10 08:50:31.714  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:31.717  6829  6829 D HeadsetStateMachine: Unbinding service...
08-10 08:50:31.719  6829  6829 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 08:50:31.719  6829  6829 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 08:50:31.719  6829  6829 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 08:50:31.719  6829  6829 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 08:50:31.719  6829  6829 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 08:50:31.719  6829  6829 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 08:50:31.719  6829  6829 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 08:50:31.720  6829  6829 D PanService: Received stop request...Stopping profile...
08-10 08:50:31.720  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:31.721  6829  6829 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 08:50:31.724  6829  6829 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 08:50:31.724  6829  6829 D BtGatt.GattService: stop()
08-10 08:50:31.725  6829  6829 D BtGatt.AdvertiseManager: advertise clients cleared
08-10 08:50:31.726  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:31.729  6829  6829 D BluetoothMapService: Received stop request...Stopping profile...
08-10 08:50:31.729  6829  6829 D BluetoothMapService: stop()
08-10 08:50:31.730  6829  6829 D BluetoothMapEmailAppObserver: deinitObservers()
08-10 08:50:31.730  6829  6829 D BluetoothMapEmailAppObserver: removeReceiver()
08-10 08:50:31.731  6829  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a4ec73
08-10 08:50:31.732  6829  6829 I BluetoothA2dpServiceJni: cleanupNative
08-10 08:50:31.732  6829  7340 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-10 08:50:31.733  6829  6829 I GKI_LINUX: GKI_exit_task 2 done
08-10 08:50:31.733  6829  6829 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-10 08:50:31.733  6829  6829 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 08:50:31.733  6829  6829 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 08:50:31.733  6829  6829 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-10 08:50:31.736  6829  6829 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 08:50:31.736  6829  6829 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 08:50:31.737  6829  6829 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 08:50:31.737  6829  6829 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 08:50:31.740  6829  6829 V BluetoothMapService: Handler(): got msg=4
08-10 08:50:31.740  6829  6829 D BluetoothMapService: MAP Service closeService in
08-10 08:50:31.740  6829  6829 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 08:50:31.740  6829  6829 V BluetoothMapService: MAP Service closeService out
08-10 08:50:31.742  6829  7284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-10 08:50:31.742  6829  7284 D BluetoothAdapterProperties: Setting state to 10
08-10 08:50:31.742  6829  7284 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-10 08:50:31.742  6829  6829 D BluetoothMapService: cleanup()
08-10 08:50:31.742  6829  6829 D BluetoothMapService: MAP Service closeService in
08-10 08:50:31.742  6829  6829 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 08:50:31.742  6829  6829 V BluetoothMapService: MAP Service closeService out
08-10 08:50:31.744  1036  1118 D BluetoothManagerService: Message: 60
08-10 08:50:31.744  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-10 08:50:31.744  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-10 08:50:31.744  6829  7284 I BluetoothAdapterState: Entering OffState
08-10 08:50:31.744  6678  6693 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 08:50:31.747  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 08:50:31.751  6678  6693 D BluetoothMap: onBluetoothStateChange: up=false
08-10 08:50:31.751  6678  6693 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 08:50:31.752  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 08:50:31.753  6678  6693 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 08:50:31.754  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 08:50:31.754  1850  2405 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 08:50:31.755  6678  6693 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 08:50:31.756  6678  6693 D BluetoothPan: onBluetoothStateChange on: false
08-10 08:50:31.756  1850  2775 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 08:50:31.757  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-10 08:50:31.757  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-10 08:50:31.759  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-10 08:50:31.759  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-10 08:50:31.759  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@affc9ff mBinding = false
,08-10 08:50:31.762  1036  1118 D BluetoothManagerService: Sending unbind request.
08-10 08:50:31.766  6829  7288 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-10 08:50:31.768  6829  6829 I GKI_LINUX: GKI_exit_task 1 done
08-10 08:50:31.768  6829  6829 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-10 08:50:31.768  6829  6829 I BluetoothServiceJni: cleanupNative: return from cleanup
08-10 08:50:31.768  6829  6829 I art     : --- WEIRD: removing null entry 248
08-10 08:50:31.769  6829  6829 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-10 08:50:31.769  6829  6829 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-10 08:50:31.770  6829  6829 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-10 08:50:31.771  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-10 08:50:31.775  6829  6829 I art     : System.exit called, status: 0
08-10 08:50:31.775  6829  6829 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-10 08:50:31.794   315  2138 V AudioFlinger: 6829 died, releasing its sessions
08-10 08:50:31.794   315  2138 V AudioFlinger:  pid 1850 @ 0
08-10 08:50:31.794   315  2138 V AudioFlinger:  pid 3462 @ 1
08-10 08:50:31.794   315  2138 V AudioFlinger:  pid 3462 @ 2
,08-10 08:50:31.797  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-10 08:50:31.797  1939  2123 D LGBluetoothAPIService: Message: 101
08-10 08:50:31.798  1939  2123 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-10 08:50:31.798  1939  2123 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-10 08:50:31.798  1939  2123 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-10 08:50:31.802  6678  6678 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-10 08:50:31.849  1036  1972 I ActivityManager: Process com.android.bluetooth (pid 6829) has died
08-10 08:50:31.849  1036  1972 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-10 08:50:31.850  1036  1972 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 13999ms
,08-10 08:50:31.857  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 08:50:31.858  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:31.859  1939  2123 D LGBluetoothAPIService: Message: 2
08-10 08:50:31.859  1939  2123 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-10 08:50:31.860  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:31.861  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:31.865  6678  6678 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-10 08:50:31.865  6678  6678 D LGBluetoothEventManager: [BTUI] clear device connection state
08-10 08:50:31.868  6678  6678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-10 08:50:31.871  1602  1602 D BluetoothAdapter: 786584250: getState() :  mService = null. Returning STATE_OFF
,08-10 08:50:31.871  1602  1602 D BluetoothAdapter: 786584250: getState() :  mService = null. Returning STATE_OFF
08-10 08:50:31.916  1036  1885 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7504 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-10 08:50:31.917  6678  6678 D DockEventReceiver: finishStartingService: stopping service
,08-10 08:50:31.991  7504  7504 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-10 08:50:31.991  7504  7504 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 08:50:31.992  7504  7504 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-10 08:50:31.992  7504  7504 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-10 08:50:32.013  7504  7504 D BluetoothAdapterApp: Loading JNI Library
,08-10 08:50:32.050  7504  7504 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@200a58fb Instance Count = 1
,08-10 08:50:32.056  7504  7504 D BluetoothAdapterApp: onCreate
08-10 08:50:32.084  7504  7504 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-10 08:50:32.085  7504  7504 D ProfileConfigQcom: Adding HeadsetService
08-10 08:50:32.085  7504  7504 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-10 08:50:32.086  7504  7504 D ProfileConfigQcom: Adding A2dpService
08-10 08:50:32.086  7504  7504 D ProfileConfigQcom: [BTUI] HidService is supported
08-10 08:50:32.087  7504  7504 D ProfileConfigQcom: Adding HidService
08-10 08:50:32.088  7504  7504 D ProfileConfigQcom: [BTUI] HealthService is supported
08-10 08:50:32.088  7504  7504 D ProfileConfigQcom: Adding HealthService
08-10 08:50:32.089  7504  7504 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-10 08:50:32.090  7504  7504 D ProfileConfigQcom: [BTUI] PanService is supported
08-10 08:50:32.091  7504  7504 D ProfileConfigQcom: Adding PanService
08-10 08:50:32.091  7504  7504 D ProfileConfigQcom: [BTUI] GattService is supported
08-10 08:50:32.091  7504  7504 D ProfileConfigQcom: Adding GattService
08-10 08:50:32.091  7504  7504 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-10 08:50:32.091  7504  7504 D ProfileConfigQcom: Adding BluetoothMapService
08-10 08:50:32.092  7504  7504 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-10 08:50:32.093  7504  7504 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 08:50:32.094  7504  7504 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:32.095  7504  7504 V BluetoothPbapReceiver: ***********state = 10
08-10 08:50:32.097  7504  7504 V LGMDMManagerInternal: Create singleton instance
08-10 08:50:32.199  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 08:50:32.201  7504  7504 D LGBluetoothAPIServer: [BTUI] onCreate()
08-10 08:50:32.202  7504  7504 D LGBluetoothAPIServer: [BTUI] onBind()
08-10 08:50:32.203  6678  6678 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-10 08:50:32.208  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-10 08:50:32.208  1939  2123 D LGBluetoothAPIService: Message: 100
08-10 08:50:32.208  1939  2123 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-10 08:50:32.221  6678  6678 D BluetoothPermissionRequest: onReceive
,08-10 08:50:32.224  6678  6678 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-10 08:50:32.224  6678  6678 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-10 08:50:32.226  6678  6678 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 08:50:32.231  7504  7504 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-10 08:50:32.236  7504  7504 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-10 08:50:32.240  7504  7504 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-10 08:50:32.240  7504  7504 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 08:50:32.241  7504  7504 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 08:50:32.242  7504  7504 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:32.242  7504  7504 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-10 08:50:32.245  6765  6765 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-10 08:50:33.733  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop,
08-10 08:50:33.733  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-10 08:50:33.960  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-10 08:50:34.006  1036  1405 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 08:50:34.011  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-10 08:50:34.028  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-10 08:50:34.044  1036  1036 D administrator: Handling package changes for user 0
08-10 08:50:34.051  1036  1103 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7549 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-10 08:50:34.054  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-10 08:50:34.055  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-10 08:50:34.103  7549  7549 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-10 08:50:34.158  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-10 08:50:34.158  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-10 08:50:34.163  7549  7549 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:34.163  7549  7549 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 08:50:34.219  1036  1100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 08:50:34.225  1036  1100 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-10 08:50:34.235  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-10 08:50:34.239  2480  2480 V GmsNetworkLocationProvi: DISABLE
08-10 08:50:34.261  1036  1100 D LocationProviderProxy: applying state to connected service
,08-10 08:50:34.263  2480  2480 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-10 08:50:34.279  7549  7579 I Babel   : MmsConfig: mnc/mcc: 0/0
08-10 08:50:34.279  7549  7579 I Babel   : MmsConfig.loadMmsSettings
08-10 08:50:34.285  7549  7579 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-10 08:50:34.285  7549  7579 I Babel   : MmsConfig.loadFromDatabase
,08-10 08:50:34.299  7549  7549 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 08:50:34.302  7549  7579 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-10 08:50:34.302  7549  7579 I Babel   : MmsConfig.loadFromResources
,08-10 08:50:34.305  7549  7579 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-10 08:50:34.306  7549  7579 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-10 08:50:34.315  7549  7577 W AudioCapabilities: Unsupported mime audio/evrc
08-10 08:50:34.317  7549  7577 W AudioCapabilities: Unsupported mime audio/qcelp
08-10 08:50:34.319  7549  7577 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-10 08:50:34.322  1815  7580 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-10 08:50:34.322  1815  7580 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-10 08:50:34.324  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
,08-10 08:50:34.328  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@920f5ad
08-10 08:50:34.328  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 08:50:34.328  6880  6880 D AppUp4:CustFacade: isPhone : true
08-10 08:50:34.329  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-10 08:50:34.329  6880  6880 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-10 08:50:34.333  1815  4777 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-10 08:50:34.341  7549  7577 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-10 08:50:34.349  7549  7577 W AudioCapabilities: Unsupported mime audio/qcelp
08-10 08:50:34.350  7549  7577 W AudioCapabilities: Unsupported mime audio/evrc
08-10 08:50:34.357  7549  7577 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-10 08:50:34.368  7549  7577 W VideoCapabilities: Unsupported mime video/divx
,08-10 08:50:34.370  1036  1992 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7584 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-10 08:50:34.373  7549  7577 W VideoCapabilities: Unsupported mime video/divx311
08-10 08:50:34.374  1036  1051 I ActivityManager: Killing 6698:com.lge.sync/1000 (adj 15): empty #17
08-10 08:50:34.378  7549  7577 W VideoCapabilities: Unsupported mime video/divx4
08-10 08:50:34.387  1036  1542 D WifiService: Client connection lost with reason: 4
,08-10 08:50:34.396  7549  7577 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-10 08:50:34.408  7549  7577 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-10 08:50:34.412  7549  7577 W AudioCapabilities: Unsupported mime audio/eac3
08-10 08:50:34.413  7549  7577 W AudioCapabilities: Unsupported mime audio/ac3
08-10 08:50:34.413  7549  7577 W AudioCapabilities: Unsupported mime audio/g726
08-10 08:50:34.414  7549  7577 W AudioCapabilities: Unsupported mime audio/wma-voice
08-10 08:50:34.415  7549  7577 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-10 08:50:34.416  7549  7577 W AudioCapabilities: Unsupported mime audio/adpcm
08-10 08:50:34.417  7549  7577 W VideoCapabilities: Unsupported mime video/theora
08-10 08:50:34.419  1036  1780 W libprocessgroup: failed to open /acct/uid_1000/pid_6698/cgroup.procs: No such file or directory
08-10 08:50:34.419  7549  7577 W VideoCapabilities: Unsupported mime video/mjpg
,08-10 08:50:34.437  7584  7584 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 08:50:34.437  7584  7584 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 08:50:34.437  7584  7584 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-10 08:50:34.438  7584  7584 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-10 08:50:34.439  7584  7584 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-10 08:50:34.488  7584  7584 I SystemConfig: BUILD Country: EU
08-10 08:50:34.488  7584  7584 I SystemConfig: BUILD Operator: OPEN
,08-10 08:50:34.525  1036  1956 I ActivityManager: Killing 6908:com.lge.email/u0a23 (adj 15): empty #17
,08-10 08:50:34.593  1036  2030 W libprocessgroup: failed to open /acct/uid_10023/pid_6908/cgroup.procs: No such file or directory
,08-10 08:50:34.619  7584  7602 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-10 08:50:34.619  7584  7602 I SystemConfig: existFile = false
08-10 08:50:34.619  7584  7602 I SystemConfig: canReadFile = false
08-10 08:50:34.619  7584  7602 I SystemConfig: systemFeature RCS result false
,08-10 08:50:34.620  7584  7602 D SystemConfig: refreshRcsSupport() :false
08-10 08:50:34.673  1036  1956 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7604 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-10 08:50:34.737  7604  7604 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 08:50:34.737  7604  7604 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-10 08:50:34.738  7604  7604 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-10 08:50:34.738  7604  7604 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 08:50:34.821  7604  7604 I AppConfig: Total System Memory = 2995761152
,08-10 08:50:34.828  7604  7604 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-10 08:50:34.899  1036  1993 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7623 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 08:50:34.901  1036  1993 I ActivityManager: Killing 6790:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-10 08:50:34.949  1036  1920 W libprocessgroup: failed to open /acct/uid_10026/pid_6790/cgroup.procs: No such file or directory
,08-10 08:50:35.171  7623  7623 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-10 08:50:35.269  7623  7623 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 08:50:35.269  7623  7623 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:50:35.326  7623  7623 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-10 08:50:35.358  7623  7623 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-10 08:50:35.361  7623  7623 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-10 08:50:35.381  7623  7623 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-10 08:50:35.381  7623  7623 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-10 08:50:35.400  1036  1574 I ActivityManager: Killing 6279:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-10 08:50:35.474  1036  2030 W libprocessgroup: failed to open /acct/uid_1000/pid_6279/cgroup.procs: No such file or directory
,08-10 08:50:35.489  4631  7671 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-10 08:50:35.545  1036  1884 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7673 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-10 08:50:35.570  3523  3538 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-10 08:50:35.572  3523  3538 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1653bdc1 on behalf of 7623
08-10 08:50:35.587  7623  7623 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-10 08:50:35.598  7623  7623 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-10 08:50:35.651  7673  7673 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-10 08:50:35.676  7673  7673 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-10 08:50:35.677  7673  7673 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-10 08:50:35.677  7673  7673 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-10 08:50:35.677  7673  7673 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-10 08:50:35.677  7673  7673 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-10 08:50:35.677  7673  7673 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-10 08:50:35.703  1036  1972 I ActivityManager: Killing 6943:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-10 08:50:35.735  1036  1052 W libprocessgroup: failed to open /acct/uid_10046/pid_6943/cgroup.procs: No such file or directory
,08-10 08:50:35.862  1036  1992 V SIM_STK : Menu title from STK is T-Mobile
,08-10 08:50:35.909  4631  7671 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 420 ms] updated apps [took 419 ms] 
,08-10 08:50:36.186  7433  7478 D UEI.SmartControl: Internal timer expired: 1
,08-10 08:50:36.186  7433  7478 D UEI.SmartControl: unbind internal service
,08-10 08:50:36.205  7433  7433 D UEI.SmartControl: Service.onUnbind: IControl
,08-10 08:50:36.208  7433  7433 D UEI.SmartControl: Service.onDestroy
08-10 08:50:36.208  7433  7433 D UEI.SmartControl: Lock is in USE false
08-10 08:50:36.208  7433  7433 D UEI.SmartControl: unbind internal service
08-10 08:50:36.210  7433  7433 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@23843fa9
08-10 08:50:36.210  7433  7433 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-10 08:50:36.210  7433  7433 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-10 08:50:36.210  7433  7433 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-10 08:50:36.210  7433  7433 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-10 08:50:36.211  7433  7433 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-10 08:50:36.211  7433  7433 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-10 08:50:36.211  7433  7433 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-10 08:50:36.211  7433  7433 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-10 08:50:36.211  7433  7433 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 08:50:36.211  7433  7433 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 08:50:36.211  7433  7433 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 08:50:36.211  7433  7433 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 08:50:36.211  7433  7433 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 08:50:36.211  7433  7433 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 08:50:36.211  7433  7433 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 08:50:36.211  7433  7433 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@23843fa9
08-10 08:50:36.216  7433  7433 D serial_port: close(fd = 25)
08-10 08:50:36.219  7433  7433 I UEI.SmartControl: Serial port is closed.
08-10 08:50:36.219  7433  7433 I UEI.SmartControl: Serial port is closed.
08-10 08:50:36.219  7433  7433 D UEI.SmartControl: Blaster closed
08-10 08:50:36.219  7433  7433 D UEI.SmartControl: Shut down QS...
08-10 08:50:36.219  7433  7433 D UEI.SmartControl: Stopping QS lib
08-10 08:50:36.220  7433  7433 D UEI.SmartControl: QS lib stop result = true
08-10 08:50:36.220  7433  7433 D UEI.SmartControl: Stopped QS lib
,08-10 08:50:36.225  7433  7433 D UEI.SmartControl: Stopped file observer...
,08-10 08:50:36.225  7433  7433 D UEI.SmartControl: QS shutdown complete
08-10 08:50:36.753  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:36.753  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@190b3f67 added. We now have 6 listener(s)
08-10 08:50:36.754  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 08:50:36.764  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:36.764  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c59114 added. We now have 7 listener(s)
08-10 08:50:36.764  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:36.765  6597  6654 I System.out: IsBluetoothEnabled
08-10 08:50:36.766  1036  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:36.766  1036  1884 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-10 08:50:36.767  1036  1118 D BluetoothManagerService: Message: 2
08-10 08:50:36.770  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:36.772  1036  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:36.772  1036  1885 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-10 08:50:36.788  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-10 08:50:36.791  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 08:50:36.791  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-10 08:50:36.792  1036  1118 D BluetoothManagerService: Message: 1
08-10 08:50:36.792  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-10 08:50:36.819  1036  1118 D BluetoothManagerService: Message: 20
08-10 08:50:36.819  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27e8117f:true
08-10 08:50:36.821  7504  7504 D BluetoothAdapterState: make
,08-10 08:50:36.828  7504  7504 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-10 08:50:36.828  7504  7504 I bluedroid-qcom: init
08-10 08:50:36.829  7504  7712 I BluetoothAdapterState: Entering OffState
08-10 08:50:36.830  7504  7504 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-10 08:50:36.830  7504  7504 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-10 08:50:36.830  7504  7504 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 08:50:36.830  7504  7504 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 08:50:36.830  7504  7504 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-10 08:50:36.832  7504  7504 I bluedroid-qcom: get_profile_interface socket
08-10 08:50:36.832  7504  7504 I bluedroid-qcom: get_profile_interface map_client
08-10 08:50:36.834  7504  7716 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-10 08:50:36.836  7504  7716 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-10 08:50:36.833  7715  7715 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:36.833  7715  7715 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:36.848  7715  7715 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-10 08:50:36.848  7715  7715 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-10 08:50:36.853  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 08:50:36.853  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-10 08:50:36.857  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-10 08:50:36.857  1036  1118 D BluetoothManagerService: Message: 40
08-10 08:50:36.857  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-10 08:50:36.858  7504  7519 I bluedroid-qcom: config_hci_snoop_log
08-10 08:50:36.858  7715  7715 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-10 08:50:36.860  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-10 08:50:36.860  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-10 08:50:36.860  7504  7716 D BluetoothAdapterProperties: Name is: G3
08-10 08:50:36.861  7715  7715 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-10 08:50:36.867  7715  7715 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-10 08:50:36.867  7715  7715 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-10 08:50:36.874  7504  7712 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-10 08:50:36.874  7504  7712 D BluetoothAdapterProperties: Setting state to 11
08-10 08:50:36.874  7504  7712 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-10 08:50:36.876  7504  7712 I LGBluetoothServiceJni: classInitNative: succeeds
08-10 08:50:36.879  1036  1118 D BluetoothManagerService: Message: 60
08-10 08:50:36.879  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-10 08:50:36.879  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-10 08:50:36.882  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:36.886  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 08:50:36.888  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:36.892  6678  6678 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-10 08:50:36.904  7504  7504 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 08:50:36.904  7504  7504 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:36.904  7504  7504 V BluetoothPbapReceiver: ***********state = 11
08-10 08:50:36.917  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 08:50:36.923  7504  7712 D BluetoothBondStateMachine: make
,08-10 08:50:36.926  7504  7712 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
08-10 08:50:36.926  7504  7712 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-10 08:50:36.926  7504  7712 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
08-10 08:50:36.926  7504  7712 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-10 08:50:36.927  7504  7712 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-10 08:50:36.928  7504  7730 I BluetoothBondStateMachine: StableState(): Entering Off State
08-10 08:50:36.931  7504  7712 E BluetoothAdapterService: File transfer profiles supported!!
08-10 08:50:36.933  6678  6678 D BluetoothPermissionRequest: onReceive
,08-10 08:50:36.939  6678  6678 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-10 08:50:36.940  7504  7712 E BluetoothAdapterService: File transfer profiles supported!!
08-10 08:50:36.941  7504  7504 D HeadsetService: Received start request. Starting profile...
08-10 08:50:36.942  7504  7504 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 08:50:36.942  7504  7504 D LGBluetoothHfpAdapter: Version 1.6
08-10 08:50:36.945  7504  7504 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-10 08:50:36.946  7504  7504 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-10 08:50:36.947  7504  7504 D HeadsetStateMachine: make
08-10 08:50:36.948  7504  7712 E BluetoothAdapterService: File transfer profiles supported!!
08-10 08:50:36.953  7504  7712 E BluetoothAdapterService: File transfer profiles supported!!
08-10 08:50:36.959  7504  7712 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 08:50:36.966  7504  7712 E BluetoothAdapterService: File transfer profiles supported!!
08-10 08:50:36.971  7504  7712 E BluetoothAdapterService: File transfer profiles supported!!
08-10 08:50:36.982  7504  7504 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:36.982  7504  7504 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:50:36.986  7504  7504 D HeadsetStateMachine: max_hf_connections = 1
08-10 08:50:36.986  7504  7504 I bluedroid-qcom: get_profile_interface handsfree
08-10 08:50:36.987  7504  7712 V LGMDMManager: Create singleton instance
08-10 08:50:36.989  7504  7712 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-10 08:50:36.989  7504  7504 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-10 08:50:36.990   315   315 V AudioPolicyService: registerClient() client 0xb558a380, uid 1002
08-10 08:50:36.990   315  1385 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-10 08:50:36.990   315  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 08:50:36.990   315  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 08:50:36.990  7504  7504 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-10 08:50:36.990   315  2139 V AudioFlinger: registerClient() client 0xb14336b8, pid 7504
08-10 08:50:36.991   315  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:36.991   315  1380 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 08:50:36.991  1602  3129 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:36.991  1602  3129 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 08:50:36.991  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:36.991  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 08:50:36.991   315  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:36.991   315  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 08:50:36.991  1850  2405 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:36.991  1850  2405 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 08:50:36.991  7504  7519 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:36.991  1602  2077 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:36.991  1602  2077 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 08:50:36.992  1850  2775 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:36.992  1850  2775 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 08:50:36.992  1036  1920 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:36.992  1036  1920 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 08:50:36.992  3462  3480 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 08:50:36.992  3462  3480 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 08:50:36.992  3462  3480 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:36.992  3462  3480 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 08:50:36.992  7504  7519 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-10 08:50:36.992  7504  7519 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 08:50:36.992  7504  7519 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-10 08:50:36.992  7504  7504 V ToneGenerator: Create Track: 0xb4928080
08-10 08:50:36.993  7504  7504 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-10 08:50:36.993  7504  7504 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-10 08:50:36.993   315  2138 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 08:50:36.993   315  2138 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-10 08:50:36.993   315  2138 V AudioPolicyManagerEx: Aud,ioPolicyManagerEx: getOutputForDevice
08-10 08:50:36.993   315  2138 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 08:50:36.993   315   315 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 08:50:36.993   315  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 08:50:36.993   315  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-10 08:50:36.993   315  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 08:50:36.993   315  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 08:50:36.994  7504  7504 V AudioSystem: getLatency() output 2, latency 50
08-10 08:50:36.994  7504  7504 V AudioSystem: getFrameCount() output 2, frameCount 960
08-10 08:50:36.994  7504  7504 V AudioTrack: createTrack_l() output 2 afLatency 50
08-10 08:50:36.994   315  2139 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 08:50:36.994   315  2139 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 08:50:36.994   315  2139 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 08:50:36.994   315  2139 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 08:50:36.994   315  2139 V AudioFlinger: createTrack() lSessionId: 23
08-10 08:50:36.995  7504  7504 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-10 08:50:36.995   315  2139 V AudioFlinger: acquiring 23 from 7504, for 7504
08-10 08:50:36.995   315  2139 V AudioFlinger:  added new entry for 23
08-10 08:50:36.995  7504  7504 V ToneGenerator: ToneGenerator INIT OK, time: 324097
08-10 08:50:36.995  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
08-10 08:50:36.996  7504  7732 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-10 08:50:36.997  7504  7732 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 08:50:36.997  7504  7732 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 08:50:36.997  7504  7732 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-10 08:50:36.998   315  1386 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7504
08-10 08:50:36.998   315  1386 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-10 08:50:36.998   315  1386 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-10 08:50:36.998   315  1386 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-10 08:50:36.998   315  1386 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-10 08:50:36.998   315  1386 V voice   : voice_set_parameters: exit with code(0)
08-10 08:50:36.998   315  1386 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-10 08:50:36.998   315  1386 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-10 08:50:36.998   315  1386 V msm8974_platform: platform_set_parameters: exit with code(0)
08-10 08:50:36.998   315  1386 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-10 08:50:36.998   315  1386 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-10 08:50:36.998   315  1386 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-10 08:50:36.998  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
08-10 08:50:37.002  7504  7732 V ToneGenerator: ToneGenerator destructor
08-10 08:50:37.002  7504  7732 V ToneGenerator: stopTone
08-10 08:50:37.002  7504  7732 V ToneGenerator: Delete Track: 0xb4928080
08-10 08:50:37.003  7504  7732 V AudioTrack: ~AudioTrack, releasing session id from 7504 on behalf of 7504
08-10 08:50:37.003   315   315 V AudioPolicyService: AudioCommandThread() adding release output 2
08-10 08:50:37.003   315   315 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-10 08:50:37.003   315   315 V AudioFlinger: PlaybackThread::Track destructor
08-10 08:50:37.003   315   315 V AudioFlinger: removeClient_l() pid 7504, calling pid 315
08-10 08:50:37.003   315  1274 V AudioPolicyService: AudioCommandThread() waking up
08-10 08:50:37.003   315  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-10 08:50:37.003   315  1274 V AudioPolicyManager: releaseOutput() 2
08-10 08:50:37.003   315   315 V AudioFlinger: releasing 23 from 7504 for 7504
08-10 08:50:37.003   315   315 V AudioFlinger:  decremented refcount to 0
08-10 08:50:37.003   315   315 V AudioFlinger: purging stale effects
08-10 08:50:37.003   315  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-10 08:50:37.004  7504  7504 D A2dpService: Received start request. Starting profile...
08-10 08:50:37.005  7504  7504 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 08:50:37.007  7504  7504 V Avrcp   : make
08-10 08:50:37.008  7504  7504 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-10 08:50:37.008  7504  7504 I bluedroid-qcom: get_profile_interface avrcp
08-10 08:50:37.018  7504  7504 V AudioManager: registerRemoteController: size of Media player list: 0
08-10 08:50:37.020  7504  7504 E AudioManager: No RCC entry present to update
08-10 08:50:37.020  7504  7504 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-10 08:50:37.024  7504  7504 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-10 08:50:37.025  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-10 08:50:37.025  7504  7504 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-10 08:50:37.030  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-10 08:50:37.158  1036  2048 V SIM_STK : Menu title from STK is T-Mobile
08-10 08:50:37.158  1036  2048 V SIM_STK : Menu title from STK is T-Mobile
,08-10 08:50:37.231  1036  1972 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-10 08:50:37.240  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-10 08:50:37.243  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-10 08:50:37.244  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-10 08:50:37.244  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 08:50:37.244  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 08:50:37.244  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 08:50:37.244  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 08:50:37.244  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 08:50:37.244  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-10 08:50:37.244  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 08:50:37.244  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-10 08:50:37.245  7504  7504 I BluetoothA2dpServiceJni: classInitNative
08-10 08:50:37.245  7504  7504 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 08:50:37.245  7504  7504 D A2dpStateMachine: make
08-10 08:50:37.248  7504  7504 I bluedroid-qcom: get_profile_interface a2dp
,08-10 08:50:37.248  7504  7741 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-10 08:50:37.251  7504  7504 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-10 08:50:37.251  7504  7504 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-10 08:50:37.252  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
08-10 08:50:37.254  7504  7740 D A2dpStateMachine: Enter Disconnected: -2
08-10 08:50:37.256  7504  7504 I BluetoothHidServiceJni: classInitNative: succeeds
08-10 08:50:37.263  7504  7504 D HidService: Received start request. Starting profile...
08-10 08:50:37.263  7504  7504 I bluedroid-qcom: get_profile_interface hidhost
08-10 08:50:37.263  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
08-10 08:50:37.265  7504  7504 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-10 08:50:37.271  7504  7504 D HealthService: Received start request. Starting profile...
,08-10 08:50:37.274  7504  7504 I bluedroid-qcom: get_profile_interface health
08-10 08:50:37.274  7504  7504 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-10 08:50:37.275  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
08-10 08:50:37.276  7504  7504 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-10 08:50:37.278  7504  7504 D PanService: Received start request. Starting profile...
08-10 08:50:37.278  7504  7504 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 08:50:37.278  7504  7504 I bluedroid-qcom: get_profile_interface pan
08-10 08:50:37.287  7504  7504 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-10 08:50:37.287  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
08-10 08:50:37.289  7504  7504 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-10 08:50:37.295  7504  7504 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 08:50:37.296  7504  7504 D BtGatt.GattService: Received start request. Starting profile...
08-10 08:50:37.296  7504  7504 D BtGatt.GattService: start()
08-10 08:50:37.296  7504  7504 I bluedroid-qcom: get_profile_interface gatt
08-10 08:50:37.296  7504  7504 D BtGatt.AdvertiseManager: advertise manager created
08-10 08:50:37.306  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
,08-10 08:50:37.308  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
08-10 08:50:37.308  7504  7504 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-10 08:50:37.309  7504  7504 V BluetoothMapService: BluetoothMapBinder()
08-10 08:50:37.311  7504  7504 D BluetoothMapService: Received start request. Starting profile...
08-10 08:50:37.311  7504  7504 D BluetoothMapService: start()
08-10 08:50:37.316  7504  7504 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-10 08:50:37.316  7504  7504 D BluetoothMapEmailAppObserver: createReceiver()
08-10 08:50:37.317  7504  7504 D BluetoothMapEmailAppObserver: initObservers()
08-10 08:50:37.318  7504  7504 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-10 08:50:37.327  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
,08-10 08:50:37.328  7504  7504 D HeadsetStateMachine: Proxy object connected
08-10 08:50:37.329  7504  7504 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-10 08:50:37.329  7504  7504 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-10 08:50:37.333  7504  7732 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-10 08:50:37.335  7504  7732 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 08:50:37.336  7504  7732 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-10 08:50:37.338  7504  7504 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 08:50:37.342  7504  7504 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-10 08:50:37.350  7504  7504 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 08:50:37.354  7504  7504 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-10 08:50:37.358  7504  7504 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 08:50:37.359  7504  7504 V PanService: [BTUI] SIM Extra State :ABSENT
08-10 08:50:37.363  7504  7504 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 08:50:37.367  7504  7504 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-10 08:50:37.367  7504  7504 V BluetoothMapService: Handler(): got msg=1
,08-10 08:50:37.368  7504  7712 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-10 08:50:37.368  7504  7712 I bluedroid-qcom: enable
08-10 08:50:37.369  7504  7504 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 08:50:37.369  7504  7712 I bt_hci_bdroid: init
08-10 08:50:37.369  7504  7504 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 08:50:37.369  7504  7504 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 08:50:37.369  7504  7504 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:37.369  7504  7504 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-10 08:50:37.370  7504  7712 I bt_vendor: bt-vendor : init
08-10 08:50:37.371  7504  7712 I bt_vendor: bt-vendor : get_bt_soc_type
08-10 08:50:37.371  7504  7712 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-10 08:50:37.371  7504  7712 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-10 08:50:37.371  7504  7712 D bt_userial_mct: userial_init
08-10 08:50:37.371  7504  7751 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-10 08:50:37.371  7504  7751 I bt-btu  : btu_task pending for preload complete event
08-10 08:50:37.373  7504  7712 D bt_hci_bdroid: set_power 1
08-10 08:50:37.373  7504  7712 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-10 08:50:37.374  7504  7712 I bt_vendor: Starting hciattach daemon
08-10 08:50:37.374  7504  7712 I bt_vendor: try to set true
08-10 08:50:37.363  7754  7754 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:37.363  7754  7754 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:37.417  7755  7755 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-10 08:50:37.559  7761  7761 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-10 08:50:37.575  7762  7762 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-10 08:50:37.614  7765  7765 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 08:50:37.639  7766  7766 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-10 08:50:37.653  7767  7767 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 08:50:37.675  7768  7768 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-10 08:50:37.700  7773  7773 I libmdmdetect: ESOC framework not supported
08-10 08:50:37.704  7773  7773 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-10 08:50:37.714  7773  7773 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-10 08:50:37.715  7773  7773 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-10 08:50:37.715  7773  7773 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-10 08:50:37.715  7773  7773 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-10 08:50:37.715  7773  7773 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-10 08:50:37.715  7773  7773 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-10 08:50:37.715  7773  7773 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-10 08:50:37.761  7773  7774 E QC-QMI  : qmi_client [7773] 15: failed to locate client data
08-10 08:50:37.762   464   464 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-10 08:50:37.762   464   464 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-10 08:50:37.817  7778  7778 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-10 08:50:37.832  7779  7779 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-10 08:50:37.887  7504  7712 I bt_vendor: bluetooth satus is on
,08-10 08:50:37.888  7504  7712 D bt_hci_bdroid: preload
,08-10 08:50:37.895  7504  7753 D bt_userial_mct: userial_open(port:0)
,08-10 08:50:37.895  7504  7753 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-10 08:50:37.900  7504  7753 I bt_vendor: Done intiailizing UART
,08-10 08:50:37.903  7504  7753 I bt_vendor: Done intiailizing UART
,08-10 08:50:37.903  7504  7753 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-10 08:50:37.904  7504  7753 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-10 08:50:37.907  7504  7751 I bt-btu  : btu_task received preload complete event
08-10 08:50:37.908  7504  7751 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-10 08:50:37.908  7504  7751 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f,
,08-10 08:50:37.928  7504  7751 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-10 08:50:37.932  7504  7781 D bt_userial_mct: Entering userial_read_thread()
,08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_BTM
,08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_HID_HOST,
08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_GAP
,08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_PAN
,08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_SDP
,08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_GATT
,08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_SMP
,08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-10 08:50:37.938  7504  7751 I         : BTE_InitTraceLevels -- TRC_BTIF
08-10 08:50:38.049  7504  7751 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-10 08:50:38.049  7504  7751 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0234061 
08-10 08:50:38.049  7504  7751 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0234061 
,08-10 08:50:38.083  7504  7716 E bt-btif : Calling BTA_HhEnable
08-10 08:50:38.083  7504  7716 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-10 08:50:38.084  7504  7716 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-10 08:50:38.086  7504  7751 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-10 08:50:38.086  7504  7751 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-10 08:50:38.086  7504  7751 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-10 08:50:38.088  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 08:50:38.089  7504  7751 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-10 08:50:38.089  7504  7751 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-10 08:50:38.089  7504  7716 D BluetoothAdapterProperties: Name is: G3
08-10 08:50:38.090  7504  7716 D BluetoothAdapterProperties: Scan Mode:20
08-10 08:50:38.091  7504  7716 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 08:50:38.091  7504  7716 D bt_hci_bdroid: postload
08-10 08:50:38.091  7504  7753 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 08:50:38.092  7504  7753 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 08:50:38.093  7504  7716 D bte_conf: Device ID record 1 : primary
08-10 08:50:38.093  7504  7716 D bte_conf:   vendorId            = 00c4
08-10 08:50:38.093  7504  7716 D bte_conf:   vendorIdSource      = 0001
08-10 08:50:38.093  7504  7716 D bte_conf:   product             = 13a1
08-10 08:50:38.093  7504  7751 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-10 08:50:38.094  7504  7753 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 08:50:38.094  7504  7716 D bte_conf:   version             = 1000
08-10 08:50:38.094  7504  7716 D bte_conf:   clientExecutableURL = 
08-10 08:50:38.094  7504  7716 D bte_conf:   serviceDescription  = 
08-10 08:50:38.094  7504  7716 D bte_conf:   documentationURL    = 
08-10 08:50:38.094  7504  7716 D bte_conf: bte_load_did_conf no section named DID2.
08-10 08:50:38.098  7504  7712 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-10 08:50:38.098  7504  7712 D BluetoothAdapterProperties: ScanMode =  20
08-10 08:50:38.098  7504  7712 D BluetoothAdapterProperties: State =  11
08-10 08:50:38.098  7504  7712 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-10 08:50:38.098  7504  7712 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-10 08:50:38.099  7504  7712 D BluetoothAdapterProperties: Setting state to 12
08-10 08:50:38.099  7504  7712 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-10 08:50:38.104  7504  7716 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-10 08:50:38.093  7784  7784 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:38.107  1036  1118 D BluetoothManagerService: Message: 60
08-10 08:50:38.107  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-10 08:50:38.107  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-10 08:50:38.108  7504  7751 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 08:50:38.108  7504  7751 W bt-smp  : Plain text(LSB ~ MSB) = 1e f0 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 08:50:38.108  7504  7751 W bt-smp  : Encrypted text(LSB ~ MSB) = a1 e9 af a7 be de b2 df f4 bb fa cd 8d 21 72 f0 
08-10 08:50:38.108  7504  7753 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 08:50:38.108  7504  7751 W bt-btm  : Stopping oneshot timer
08-10 08:50:38.108  7504  7716 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 08:50:38.103  7784  7784 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:38.112  7504  7781 E bt_mct  : hci lib postload completed
08-10 08:50:38.134  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-10 08:50:38.139  7504  7716 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 08:50:38.139  7504  7716 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-10 08:50:38.140  7504  7712 I BluetoothAdapterState: Entering On State
08-10 08:50:38.152  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:38.152  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:38.152  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:38.152  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:38.152  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:38.152  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:38.152  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:38.152  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 08:50:38.169  7504  7751 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 08:50:38.169  7504  7751 W bt-smp  : Plain text(LSB ~ MSB) = 7f 73 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 08:50:38.169  7504  7751 W bt-smp  : Encrypted text(LSB ~ MSB) = c5 05 aa cd 24 26 30 a1 b6 6a df b9 14 7d c3 42 
,08-10 08:50:38.171  7504  7751 W bt-btm  : Stopping oneshot timer
08-10 08:50:38.173  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:38.197  7504  7751 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 08:50:38.197  7504  7751 W bt-smp  : Plain text(LSB ~ MSB) = c9 e7 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 08:50:38.197  7504  7751 W bt-smp  : Encrypted text(LSB ~ MSB) = c9 09 bd b6 58 7b 3d a8 27 ad 7b ac 42 f9 ca dc 
,08-10 08:50:38.199  7504  7751 W bt-btm  : Stopping oneshot timer
08-10 08:50:38.216  7504  7712 D LGBluetoothServiceAdapter: [BTUI] OnState
08-10 08:50:38.216  7504  7712 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-10 08:50:38.216  7504  7712 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-10 08:50:38.226  7789  7789 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-10 08:50:38.228  7504  7751 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 08:50:38.229  7504  7751 W bt-smp  : Plain text(LSB ~ MSB) = fa 39 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 08:50:38.229  7504  7751 W bt-smp  : Encrypted text(LSB ~ MSB) = f5 81 b9 2d ed 03 fd 99 68 5d 03 ac a8 e9 f5 eb 
,08-10 08:50:38.231  7504  7751 W bt-btm  : Stopping oneshot timer
,08-10 08:50:38.232  7504  7712 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-10 08:50:38.232  7504  7712 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-10 08:50:38.237  6678  6693 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 08:50:38.245  7504  7751 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 08:50:38.245  7504  7751 W bt-smp  : Plain text(LSB ~ MSB) = 3b 7a 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-10 08:50:38.245  7504  7751 W bt-smp  : Encrypted text(LSB ~ MSB) = 86 d8 da fd 1e 1b 2c 95 35 87 e4 ff 04 4d b1 de 
08-10 08:50:38.247  7504  7751 W bt-btm  : Stopping oneshot timer
,08-10 08:50:38.253  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 08:50:38.253  1036  1036 D BluetoothA2dp: Proxy object connected
08-10 08:50:38.253  6678  6678 D BluetoothA2dp: Proxy object connected
08-10 08:50:38.253  6678  6678 D A2dpProfile: Bluetooth service connected
08-10 08:50:38.254  6678  6694 D BluetoothMap: onBluetoothStateChange: up=true
08-10 08:50:38.257  6678  6693 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 08:50:38.258  6678  6678 D BluetoothMap: Proxy object connected
08-10 08:50:38.258  6678  6678 D MapProfile: Bluetooth service connected
08-10 08:50:38.258  6678  6678 D BluetoothMap: getConnectedDevices()
08-10 08:50:38.260  7504  7803 V BluetoothMapService: getConnectedDevices()
08-10 08:50:38.260  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 08:50:38.261  6678  6694 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 08:50:38.261  6678  6678 D BluetoothInputDevice: Proxy object connected
08-10 08:50:38.261  6678  6678 D HidProfile: Bluetooth service connected
08-10 08:50:38.267  1036  1036 D BluetoothHeadset: Proxy object connected
08-10 08:50:38.268  1850  2402 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 08:50:38.270  1850  1850 D BluetoothHeadset: Proxy object connected
08-10 08:50:38.271  6678  6678 D BluetoothHeadset: Proxy object connected
08-10 08:50:38.271  6678  6678 D HeadsetProfile: Bluetooth service connected
08-10 08:50:38.271  1850  2405 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 08:50:38.274  1850  1850 D BluetoothHeadset: Proxy object connected
08-10 08:50:38.274  6678  6693 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 08:50:38.276  6678  7182 D BluetoothPan: onBluetoothStateChange on: true
08-10 08:50:38.276  6678  7182 D BluetoothPan: onBluetoothStateChange call bindService
08-10 08:50:38.277  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 08:50:38.278  6678  6678 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 08:50:38.279  6678  6678 D PanProfile: Bluetooth service connected
,08-10 08:50:38.280  1850  1850 D BluetoothHeadset: Proxy object connected
08-10 08:50:38.282  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-10 08:50:38.282  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-10 08:50:38.282  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-10 08:50:38.282  1036  1118 D BluetoothManagerService: Message: 40
08-10 08:50:38.282  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-10 08:50:38.283  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:38.283  1939  2123 D LGBluetoothAPIService: Message: 1
08-10 08:50:38.283  1939  2123 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-10 08:50:38.283  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 08:50:38.283  1939  2123 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-10 08:50:38.284  1939  2123 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-10 08:50:38.287  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:38.287  7504  7504 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:38.287  7504  7504 D BluetoothMapService: STATE_ON
08-10 08:50:38.291  6678  6678 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-10 08:50:38.292  6678  6678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 08:50:38.297  6678  6678 D DockEventReceiver: finishStartingService: stopping service
08-10 08:50:38.299  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
08-10 08:50:38.299  7504  7504 V BluetoothPbapService: Pbap Service onCreate
08-10 08:50:38.299  7504  7504 V BluetoothPbapService: Starting PBAP service
08-10 08:50:38.301  7504  7504 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-10 08:50:38.301  7504  7504 V BluetoothPbapService: Pbap Service onBind
08-10 08:50:38.301  7504  7504 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:38.302  7504  7504 V BluetoothPbapService: state: 12
08-10 08:50:38.302  6678  6678 D BluetoothPbap: Proxy object connected
08-10 08:50:38.302  7504  7504 V BluetoothMapService: Handler(): got msg=1
08-10 08:50:38.302  6678  6678 D PbapServerProfile: Bluetooth service connected
08-10 08:50:38.302  7504  7504 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-10 08:50:38.302  7504  7504 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 08:50:38.303  7504  7504 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:38.303  7504  7504 V BluetoothPbapReceiver: ***********state = 12
,08-10 08:50:38.305  7504  7808 D BluetoothMapMasInstance: MAS initSocket()
,08-10 08:50:38.305  7504  7504 V BluetoothPbapService: Handler(): got msg=1
08-10 08:50:38.305  7504  7808 D BluetoothMapMasInstance:   masId = 00
08-10 08:50:38.305  7504  7808 D BluetoothMapMasInstance:   msgTypes = 0e
08-10 08:50:38.305  7504  7808 D BluetoothMapMasInstance:   masName = SMS/MMS
08-10 08:50:38.305  7504  7808 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-10 08:50:38.306  7504  7504 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-10 08:50:38.307  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 08:50:38.307  2210  2210 D c       : Getting all permits...
08-10 08:50:38.307  2210  2210 D a       : Opening database...
08-10 08:50:38.307  1036  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:38.308  7504  7808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 08:50:38.309  7504  7809 V BluetoothPbapService: Pbap Service initSocket
08-10 08:50:38.309  1036  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:38.309  7504  7808 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-10 08:50:38.310  7504  7808 V BluetoothMapMasInstance: Succeed to create listening socket 
08-10 08:50:38.310  7504  7808 D BluetoothMapMasInstance: Accepting socket connection...
08-10 08:50:38.310  7504  7716 D BluetoothAdapterProperties: Scan Mode:21
08-10 08:50:38.310  7504  7716 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-10 08:50:38.311  7504  7809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 08:50:38.312  7504  7809 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-10 08:50:38.312  7504  7809 V BluetoothPbapService: Succeed to create listening socket 
08-10 08:50:38.312  7504  7809 V BluetoothPbapService: Accepting socket connection...
08-10 08:50:38.312  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:38.315  2210  2210 D a       : Opening database auth.proximity.permit_store...
08-10 08:50:38.316  2210  2210 D a       : Closing database...
08-10 08:50:38.327  6678  6678 D BluetoothPermissionRequest: onReceive
08-10 08:50:38.330  6678  6678 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-10 08:50:38.331  6678  6678 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-10 08:50:38.335  7504  7504 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-10 08:50:38.336  7504  7504 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-10 08:50:38.340  7504  7504 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-10 08:50:38.354  7504  7504 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 08:50:38.354  7504  7504 V BtOppService: onCreate
,08-10 08:50:38.357  7504  7504 V BluetoothOppNotification: send message
08-10 08:50:38.360  7504  7504 V BtOppService: Starting RfcommListener
08-10 08:50:38.367  7504  7504 D BluetoothOppPreference: Dumping Names:  
08-10 08:50:38.367  7504  7504 D BluetoothOppPreference: {}
08-10 08:50:38.367  7504  7504 D BluetoothOppPreference: Dumping Channels:  
08-10 08:50:38.367  7504  7504 D BluetoothOppPreference: {}
08-10 08:50:38.368  7504  7504 V BtOppService: onStartCommand
,08-10 08:50:38.375  7504  7504 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:38.375  7504  7504 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 08:50:38.378  7504  7817 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 08:50:38.379  7504  7814 V BtOppService: Deleted complete outbound shares, number =  0
,08-10 08:50:38.380  7504  7817 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-10 08:50:38.381  7504  7814 V BtOppService: Deleted complete inbound failed shares, number = 0
08-10 08:50:38.382  7504  7814 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-10 08:50:38.382  7504  7817 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@270fb2ec on behalf of 
08-10 08:50:38.383  7504  7817 V BluetoothOppNotification: update too frequent, put in queue
08-10 08:50:38.392  7504  7814 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38bb46b5 on behalf of 
08-10 08:50:38.392  7504  7817 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-10 08:50:38.517  1036  1780 I art     : Explicit concurrent mark sweep GC freed 27085(1318KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.326ms total 139.018ms
,08-10 08:50:38.520  7504  7504 V BluetoothOppNotification: new notify threadi!
08-10 08:50:38.521  7504  7504 V BluetoothOppNotification: send delay message
08-10 08:50:38.522  7504  7818 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 08:50:38.522  7504  7504 V BtOppService: start RfcommListener
08-10 08:50:38.523  7504  7818 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c46714a on behalf of 
08-10 08:50:38.524  7504  7818 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-10 08:50:38.524  7504  7818 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 08:50:38.526  7504  7818 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29bef8bb on behalf of 
08-10 08:50:38.526  7504  7818 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 08:50:38.527  7504  7818 V BluetoothOppNotification: outbound notification was removed.
08-10 08:50:38.527  7504  7818 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 08:50:38.529  7504  7818 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11bb11d8 on behalf of 
08-10 08:50:38.529  7504  7818 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 08:50:38.530  7504  7504 V BtOppService: RfcommListener started
08-10 08:50:38.531  7504  7504 V BtOppService: ContentObserver received notification
08-10 08:50:38.531  7504  7504 V BtOppService: ContentObserver received notification
,08-10 08:50:38.534  7504  7818 V BluetoothOppNotification: inbound notification was removed.
08-10 08:50:38.534  7504  7819 V BtOppRfcommListener: Starting RFCOMM listener....
08-10 08:50:38.535  1036  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:38.537  7504  7819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 08:50:38.539  7504  7819 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-10 08:50:38.540  7504  7818 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 08:50:38.540  7504  7819 V BtOppRfcommListener: Started RFCOMM listener....
08-10 08:50:38.540  7504  7819 I BtOppRfcommListener: Accept thread started.
08-10 08:50:38.540  7504  7819 V BtOppRfcommListener: Accepting connection...
08-10 08:50:38.549  7504  7820 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 08:50:38.549  7504  7818 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31269931 on behalf of 
08-10 08:50:38.549  7504  7820 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-10 08:50:38.551  7504  7820 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d025816 on behalf of 
08-10 08:50:38.554  7504  7820 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-10 08:50:38.564  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
,08-10 08:50:38.564  7504  7504 V BluetoothFtpService: Ftp Service onCreate
,08-10 08:50:38.564  7504  7504 I BluetoothFtpService: Ftp Service onCreate
08-10 08:50:38.564  7504  7504 V BluetoothFtpService: Ftp Service onStartCommand
08-10 08:50:38.564  7504  7504 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:38.565  7504  7504 V BluetoothFtpService: Starting Listening on sockets
08-10 08:50:38.565  7504  7504 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 08:50:38.565  7504  7504 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 08:50:38.565  7504  7504 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 08:50:38.566  7504  7504 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:38.566  7504  7504 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-10 08:50:38.566  7504  7504 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 08:50:38.568  7504  7504 V BluetoothFtpService: Handler(): got msg=1
08-10 08:50:38.568  7504  7504 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-10 08:50:38.568  7504  7504 V BluetoothFtpService: Ftp Service initSocket
08-10 08:50:38.572  1036  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:38.573  7504  7504 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 08:50:38.574  7504  7504 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-10 08:50:38.574  7504  7504 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-10 08:50:38.575  7504  7821 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-10 08:50:38.591  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@535e730
,08-10 08:50:38.592  7504  7504 V BluetoothSapService: Sap Service onCreate
,08-10 08:50:38.593  7504  7504 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 08:50:38.593  7504  7504 V BluetoothSapService: state: 12
08-10 08:50:38.594  7504  7504 V BluetoothSapService: Starting SAP server process
08-10 08:50:38.583  7822  7822 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:38.596  7504  7504 V BluetoothSapService: SAP Service startRfcommListenerThread
08-10 08:50:38.583  7822  7822 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:38.597  7504  7823 V BluetoothSapService: Sap Service initRfcommSocket
08-10 08:50:38.598  1036  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:38.599  7504  7823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 08:50:38.600  7504  7823 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-10 08:50:38.600  7504  7823 V BluetoothSapService: Succeed to create listening socket 
08-10 08:50:38.601  7504  7823 V BluetoothSapService: Accepting socket connection...
08-10 08:50:38.619  7822  7822 V BT_SAP  : Event pipe created
08-10 08:50:38.619  7822  7822 V BT_SAP  : create_server_socket qcom.sap.server
,08-10 08:50:38.619  7822  7822 V BT_SAP  : created socket fd 6
,08-10 08:50:38.834  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:38.834  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:38.834  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:38.834  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 08:50:38.834  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:38.834  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:38.834  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:38.834  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 08:50:38.840  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:38.843  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:38.843  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@acb0dbd added. We now have 8 listener(s)
08-10 08:50:38.843  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:38.849  1036  2030 D WifiServiceImplEx: setWifiEnabled: false pid=6597, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-10 08:50:38.849  1036  2030 D WifiService: setWifiEnabled: false pid=6597, uid=10118
08-10 08:50:38.849  1036  2030 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 08:50:38.866  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:38.871  1036  1574 D WifiServiceImplEx: setWifiEnabled: true pid=6597, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 08:50:38.872  1036  1574 D WifiService: setWifiEnabled: true pid=6597, uid=10118
08-10 08:50:38.872  1036  1574 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 08:50:38.887  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 08:50:38.887  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 08:50:38.887  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-10 08:50:38.894  1036  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-10 08:50:38.894  1036  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-10 08:50:38.897  1036  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-10 08:50:38.897  1036  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 08:50:38.897  1036  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-10 08:50:38.897  1036  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 08:50:38.897  1036  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-10 08:50:38.897  1036  1537 E WifiHW  : unknown target_country: EU , set to default
08-10 08:50:38.897  1036  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-10 08:50:38.897  1036  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-10 08:50:38.897  1036  1537 I WifiUtil: gEnableBmps=1
08-10 08:50:39.484   311   905 D SoftapController: Softap fwReload - Ok
,08-10 08:50:39.582  7504  7504 V BluetoothOppNotification: new notify threadi!
08-10 08:50:39.583  7504  7504 V BluetoothOppNotification: send delay message
08-10 08:50:39.589  7504  7851 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-10 08:50:39.591  7504  7851 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37d5c433 on behalf of 
,08-10 08:50:39.593  7504  7851 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-10 08:50:39.595  7504  7851 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-10 08:50:39.596  7504  7851 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a3e43f0 on behalf of 
,08-10 08:50:39.598  7504  7851 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 08:50:39.599  1036  1537 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (698ms)
08-10 08:50:39.600  7504  7851 V BluetoothOppNotification: outbound notification was removed.
08-10 08:50:39.600  7504  7851 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 08:50:39.601  7504  7851 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20d63d69 on behalf of 
08-10 08:50:39.602  7504  7851 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 08:50:39.603  7504  7851 V BluetoothOppNotification: inbound notification was removed.
08-10 08:50:39.604  7504  7851 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 08:50:39.605  7504  7851 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a2453ee on behalf of 
08-10 08:50:39.609   311   905 D CommandListener: Setting iface cfg
08-10 08:50:39.609   311   905 D CommandListener: Trying to bring down wlan0
,08-10 08:50:39.610   311   905 D CommandListener: Clearing all IP addresses on wlan0
08-10 08:50:39.612  1036  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-10 08:50:39.619  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 08:50:39.619  1036  1118 D Tethering: InitialState.processMessage what=4
08-10 08:50:39.613  7859  7859 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:39.621  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-10 08:50:39.628  1036  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 08:50:39.628  1036  1537 E WifiStateMachine: useWiFiOffloading() : false
08-10 08:50:39.628  1036  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 08:50:39.613  7859  7859 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:39.631  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:39.632  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-10 08:50:39.633  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-10 08:50:39.633  1036  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-10 08:50:39.633  1036  1537 D WifiMonitor: connecting to supplicant
,08-10 08:50:39.636  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 08:50:39.636  6678  6678 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 08:50:39.636  6678  6678 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 08:50:39.636  6678  6678 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 08:50:39.636  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 08:50:39.637  6678  6678 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 08:50:39.637  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 08:50:39.638  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 08:50:39.638  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 08:50:39.638  6678  6678 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 08:50:39.638  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:39.638  6678  6678 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 08:50:39.640  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 08:50:39.640  6678  6678 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 08:50:39.640  6678  6678 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 08:50:39.640  6678  6678 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 08:50:39.640  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 08:50:39.641  6678  6678 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 08:50:39.641  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 08:50:39.641  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 08:50:39.641  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 08:50:39.641  7859  7859 I wpa_supplicant: Successfully initialized wpa_supplicant
08-10 08:50:39.641  6678  6678 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 08:50:39.641  6678  6678 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 08:50:39.677  7859  7859 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-10 08:50:39.677  7859  7859 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-10 08:50:39.680  1036  1051 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7862 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-10 08:50:39.729  7859  7859 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-10 08:50:39.780  7859  7859 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-10 08:50:39.784  1036  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-10 08:50:39.785  1036  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-10 08:50:39.785  1036  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-10 08:50:39.785  1036  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-10 08:50:39.785  1036  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:39.786  1036  2030 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7884 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 08:50:39.786  1036  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:39.786  1036  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:39.786  1036  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:39.787  1036  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-10 08:50:39.787  1036  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-10 08:50:39.787  7859  7859 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-10 08:50:39.787  1036  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-10 08:50:39.787  1036  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-10 08:50:39.788  1036  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-10 08:50:39.788  1036  7889 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-10 08:50:39.788  1036  7889 D WifiMonitor: Dropping event because (p2p0) is stopped
08-10 08:50:39.788  1036  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 08:50:39.788  1036  1537 E WifiStateMachine: useWiFiOffloading() : false
08-10 08:50:39.788  1036  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 08:50:39.789  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:39.789  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:39.789  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:39.789  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:39.789  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 08:50:39.790  1036  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
08-10 08:50:39.791  1036  1537 D WifiNative-wlan0: SET update_config 1: returned true
08-10 08:50:39.791  1036  1537 D WifiConfigStore: Loading config and enabling all networks 
08-10 08:50:39.791  1036  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-10 08:50:39.791  1036  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-10 08:50:39.795  1036  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-10 08:50:39.798  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:39.799  1939  1939 D WfdService: Waiting for WifiP2p enabling
08-10 08:50:39.799  7859  7859 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-10 08:50:39.800  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-10 08:50:39.800  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-10 08:50:39.800  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-10 08:50:39.800  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-10 08:50:39.800  1036  7889 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-10 08:50:39.800  1036  7889 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-10 08:50:39.801   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 354us total 15.525ms
,08-10 08:50:39.802  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:39.802  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:39.802  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:39.802  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:39.802  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:39.802  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:39.802  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:39.802  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 08:50:39.803  1036  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-10 08:50:39.803  1036  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-10 08:50:39.803  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:39.805  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-10 08:50:39.805  1036  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-10 08:50:39.805  1036  1537 D WifiStateMachine: enableVerboseLogging : level 2
08-10 08:50:39.805  1036  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-10 08:50:39.805  1036  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-10 08:50:39.806  1036  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-10 08:50:39.806  1036  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-10 08:50:39.806  1036  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-10 08:50:39.807  1036  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-10 08:50:39.807  1036  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-10 08:50:39.807  1036  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
,08-10 08:50:39.807  1036  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-10 08:50:39.807  1036  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-10 08:50:39.807  1036  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-10 08:50:39.807  1036  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
,08-10 08:50:39.807  1036  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-10 08:50:39.808  1036  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-10 08:50:39.808  1036  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 08:50:39.808  1036  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-10 08:50:39.812  1036  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-10 08:50:39.812  1939  1939 D WfdsService: Supplicant Connection state is changed : true
08-10 08:50:39.812  1939  2327 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-10 08:50:39.812  1939  2327 D WfdsService: Set the WFDS Monitor: true
08-10 08:50:39.812  1939  2327 D WfdsMonitor: WfdsMonitorThread create
08-10 08:50:39.812  1939  2327 D WfdsMonitor: WFDS Monitor is created and started
08-10 08:50:39.812  1939  2327 D WfdsService: WiFi: Supplicant connection re-established
08-10 08:50:39.812  1036  1537 D WifiNative-HAL: Setting external_sim to 1
08-10 08:50:39.812  1036  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-10 08:50:39.812  1036  1537 D WifiNative-wlan0: SET external_sim 1: returned true
08-10 08:50:39.812  1036  1537 I WifiNative-HAL: startHal
08-10 08:50:39.812  1036  1537 D wifi    : setting scan oui 0xaf6560a0
,08-10 08:50:39.813  1036  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 08:50:39.813  1036  1537 I WifiNative-HAL: startHal
08-10 08:50:39.813  1036  1537 D wifi    : setting scan oui 0xaf6560a0
08-10 08:50:39.813  1036  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-10 08:50:39.813  7862  7882 W FormManager: Network not available. Please check & try again.
08-10 08:50:39.813  7549  7549 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:39.814  1036  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-10 08:50:39.814  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-10 08:50:39.814  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-10 08:50:39.814  1036  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-10 08:50:39.814  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 08:50:39.814  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-10 08:50:39.814  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-10 08:50:39.814  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-10 08:50:39.815  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-10 08:50:39.815   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 281us total 13.208ms
08-10 08:50:39.815  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-10 08:50:39.815  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 08:50:39.815  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-10 08:50:39.815  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 08:50:39.815  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 08:50:39.816  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 08:50:39.816  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 08:50:39.816  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-10 08:50:39.816  7859  7859 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,08-10 08:50:39.816  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-10 08:50:39.816  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 08:50:39.816  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 08:50:39.817  1036  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 08:50:39.817  1036  1537 E WifiNative: : [326,904,866 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
,08-10 08:50:39.817  1036  1537 D WifiNative-wlan0: doBoolean: RECONNECT
08-10 08:50:39.817  1036  1537 D WifiNative-wlan0: RECONNECT: returned true
08-10 08:50:39.817  1036  1537 D WifiNative-wlan0: doString: [STATUS]
08-10 08:50:39.818  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-10 08:50:39.818  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,08-10 08:50:39.818  1036  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 08:50:39.818  1036  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 08:50:39.819  1939  7900 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-10 08:50:39.819  1939  7900 E CtrlSupplicant: Succeed to open control connection
08-10 08:50:39.819  1939  7900 E CtrlSupplicant: Succeed to open monitor connection
,08-10 08:50:39.819  1036  1537 D WifiNative-wlan0: SET ps 1: returned true
08-10 08:50:39.819  1036  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.821   311   905 D CommandListener: Setting iface cfg
08-10 08:50:39.821   311   905 D CommandListener: Trying to bring up p2p0
08-10 08:50:39.821  1036  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-10 08:50:39.821  1036  1536 D LGWifiP2pService: P2pEnablingState
08-10 08:50:39.821  1036  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.821  1036  1536 D LGWifiP2pService: P2p socket connection successful
08-10 08:50:39.821  1036  1536 D LGWifiP2pService: P2pEnabledState
08-10 08:50:39.821  1036  1536 D LGWifiP2pService: sending p2p connection changed broadcast
,08-10 08:50:39.823  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-10 08:50:39.823  1939  1939 D WfdsService: WifiP2pState is changed : true
08-10 08:50:39.823  1939  2327 D WfdsService: Receive the WFDS_ENABLE Method
08-10 08:50:39.823  1939  2327 D WfdsService: Set the WFDS Monitor: true
08-10 08:50:39.823  1939  2327 D WfdsService: Connected to the supplicant for wfds
08-10 08:50:39.823  1939  2327 D WfdsJNI : doCommand: WFDS_SET TRUE
08-10 08:50:39.823  7859  7859 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-10 08:50:39.824  1939  2327 D WfdsService: selectPreferredScanChannel [36]
08-10 08:50:39.824  1939  2327 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-10 08:50:39.824  1036  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-10 08:50:39.824  1036  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-10 08:50:39.824  1036  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
,08-10 08:50:39.825  1036  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-10 08:50:39.825  1036  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-10 08:50:39.825  1036  1536 D LGWifiP2pService: before postfix = G3
08-10 08:50:39.825  1036  1536 D WifiServerServiceExt: postfix byte check : 2
08-10 08:50:39.825  1036  1536 D LGWifiP2pService: after postfix = G3
08-10 08:50:39.825  1036  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-10 08:50:39.826  1036  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-10 08:50:39.826  1036  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-10 08:50:39.827  1036  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-10 08:50:39.827  1036  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-10 08:50:39.827  1036  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-10 08:50:39.828  1036  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-10 08:50:39.828  1036  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-10 08:50:39.828  1036  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-10 08:50:39.828  1036  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-10 08:50:39.828   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 12.629ms
08-10 08:50:39.829  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-10 08:50:39.829  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-10 08:50:39.829  1036  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.829  1036  1555 I WifiNative-HAL: startHal
08-10 08:50:39.829  1036  1556 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.830  1036  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-10 08:50:39.830  1036  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-10 08:50:39.830  1036  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-10 08:50:39.830  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-10 08:50:39.830  1939  7900 D WfdsMonitor: Supplicant connection established
08-10 08:50:39.830  1939  1939 D WfdsService: isConnected: false
08-10 08:50:39.830  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=326918  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 08:50:39.830  1939  2327 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-10 08:50:39.831  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=326919  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 08:50:39.833  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:39.833  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:39.833  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 08:50:39.833  7862  7883 V FormManager: Network unavailable.
08-10 08:50:39.833  1036  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6560a0
08-10 08:50:39.833  1036  1555 D wifi    : failed to get capabilities : -3
08-10 08:50:39.833  1036  1555 E WifiScanningService: could not get scan capabilities
08-10 08:50:39.833  1036  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-10 08:50:39.834  1036  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-10 08:50:39.834  1036  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-10 08:50:39.834  1939  1939 I WfdStateT,racker: handleP2pThisDeviceChanged
08-10 08:50:39.834  1939  1939 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-10 08:50:39.834  1939  1939 D WfdsService: Update P2p Interface State: 3
08-10 08:50:39.834  1036  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-10 08:50:39.834  1036  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-10 08:50:39.835  1036  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-10 08:50:39.835  1036  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-10 08:50:39.835  1036  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-10 08:50:39.835  1036  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-10 08:50:39.835  7862  7883 V FormManager: Network unavailable.
08-10 08:50:39.836  1036  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
,08-10 08:50:39.837  1036  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-10 08:50:39.837  1036  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-10 08:50:39.837  1036  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-10 08:50:39.842  7859  7859 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-10 08:50:39.843  1036  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-10 08:50:39.843  1036  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-10 08:50:39.843  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:39.843  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:39.843  1036  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-10 08:50:39.843  1036  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-10 08:50:39.843  7859  7859 E wpa_supplicant: disconnect_rssi_lvl: -100
08-10 08:50:39.844  1036  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-10 08:50:39.844  1036  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-10 08:50:39.844  1036  1536 D LGWifiP2pService: InactiveState
08-10 08:50:39.844  1036  1536 D LGWifiP2pService: InactiveState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.844  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.844  1036  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-10 08:50:39.845  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-10 08:50:39.845  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:39.845  7859  7859 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:39.845  1939  7900 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 08:50:39.846  1036  7889 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 08:50:39.846  1036  7889 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:39.846  7859  7859 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 08:50:39.846  1036  7889 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:39.846  1036  7889 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:39.846  7859  7859 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.846  1939  7900 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:39.846  1036  7889 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:39.846  1036  7889 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.847  1036  7889 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.847  7859  7859 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.847  1036  7889 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.847  1939  7900 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:39.847  1036  7889 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:39.847  1036  7889 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.847  1036  7889 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.847  1036  7889 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.847  1036  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
,08-10 08:50:39.847  1036  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.848  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.848  1036  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.848  1036  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.848  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.848  1036  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.848  1036  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.848  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.848  1036  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.849  1036  1536 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.849  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.849  1036  1536 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.849  1036  1036 E WifiServerServiceExt: No p2p device connected
08-10 08:50:39.849  1939  2327 W WfdsService: DefaultState - msg [9441285] is not handled
08-10 08:50:39.853  1036  1051 I ActivityManager: Killing 6968:com.android.chrome/u0a57 (adj 15): empty #17
08-10 08:50:39.853  1036  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-10 08:50:39.853  1036  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-10 08:50:39.854  1036  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-10 08:50:39.854  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-10 08:50:39.855  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 08:50:39.855  7859  7859 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:39.855  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 08:50:39.855  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:39.855  1036  7889 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:39.855  1036  7889 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 08:50:39.856  7859  7859 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 08:50:39.856  7859  7859 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.856  1939  7900 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:39.856  1036  7889 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:39.856  1036  7889 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.856  1036  7889 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.856  1036  7889 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.856  1036  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned tr,ue
08-10 08:50:39.856  7859  7859 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.856  1036  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.856  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:39.857  1939  7900 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:39.857  1036  7889 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 08:50:39.857  1036  7889 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.857  1036  7889 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.857  1036  7889 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 08:50:39.858  1036  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-10 08:50:39.858  1036  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-10 08:50:39.858  1036  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
,08-10 08:50:39.859  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-10 08:50:39.859  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-10 08:50:39.859  7859  7859 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 08:50:39.860  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-10 08:50:39.860  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 08:50:39.860  1036  7889 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 08:50:39.860  1036  7889 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 08:50:39.860  1036  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-10 08:50:39.860  1036  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-10 08:50:39.861  1036  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-10 08:50:39.861  1036  1537 D WifiNative-wlan0: doBoolean: SCAN
08-10 08:50:39.862  1036  1537 D WifiNative-wlan0: SCAN: returned false
08-10 08:50:39.863  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=326951  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 08:50:39.880  1036  1780 W libprocessgroup: failed to open /acct/uid_10057/pid_6968/cgroup.procs: No such file or directory
08-10 08:50:39.880  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=326968  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 08:50:39.881  1036  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 08:50:39.881  1036  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 08:50:39.882  1036  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-10 08:50:39.882  1036  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-10 08:50:39.882  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:39.882  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:39.882  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 08:50:39.882  1036  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 08:50:39.883  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:39.883  7884  7884 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:39.883  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:39.883  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:39.885  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:39.885  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-10 08:50:39.885  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 08:50:39.885  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:39.885  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-10 08:50:39.889  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:39.890  1036  1574 I ActivityManager: Killing 6987:com.lge.drmservice/u0a62 (adj 15): empty #17
08-10 08:50:39.904  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:39.904  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:39.904  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:39.904  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:39.904  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:39.904  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 08:50:39.904  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 08:50:39.904  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 08:50:39.905  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 08:50:39.911  6597  6654 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-10 08:50:39.912  6597  6654 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-10 08:50:39.914  6597  6654 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2f7c96c7 Bundle[{}]
08-10 08:50:39.915  6597  6654 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-10 08:50:39.916  6597  6654 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-10 08:50:39.916  6597  6654 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-10 08:50:39.917  6597  6654 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-10 08:50:39.918  6597  6654 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-10 08:50:39.919  6597  6654 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-10 08:50:39.926  6597  6654 I System.out: Running OutgoingSocketThread
08-10 08:50:39.927  6597  7906 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 861)
,08-10 08:50:39.928  6597  7906 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 36580
08-10 08:50:39.928  6597  7906 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-10 08:50:39.934  1036  1920 W libprocessgroup: failed to open /acct/uid_10062/pid_6987/cgroup.procs: No such file or directory
08-10 08:50:39.947  7884  7884 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 08:50:39.950  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 08:50:39.957  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:39.970  7862  7908 W FormManager: Network not available. Please check & try again.
,08-10 08:50:39.980  7862  7909 V FormManager: Network unavailable.
08-10 08:50:39.985  7862  7909 V FormManager: Network unavailable.
,08-10 08:50:39.996  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 08:50:39.996  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 08:50:40.000  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 08:50:40.005  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:40.012  4353  7910 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-10 08:50:40.014  4353  7911 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-10 08:50:40.014  4353  7911 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 08:50:40.056  1036  1884 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7912 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-10 08:50:40.183  7912  7912 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-10 08:50:40.183  7912  7912 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-10 08:50:40.192  7912  7912 V [BNRBootReceiver]: Boot Receiver Return
08-10 08:50:40.193  7912  7912 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-10 08:50:40.274  1036  1885 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7930 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 08:50:40.276  1036  1885 I ActivityManager: Killing 7007:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-10 08:50:40.340  1036  2048 W libprocessgroup: failed to open /acct/uid_10085/pid_7007/cgroup.procs: No such file or directory
,08-10 08:50:40.371  7930  7930 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 08:50:40.405  7930  7930 D PluginManager: init()
,08-10 08:50:40.442  7859  7859 E wpa_supplicant: USIM:  scard_init function
08-10 08:50:40.443  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-10 08:50:40.443  7859  7859 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-10 08:50:40.443  1036  7889 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-10 08:50:40.443  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-10 08:50:40.443  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
,08-10 08:50:40.443  1036  7889 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-10 08:50:40.444  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-10 08:50:40.444  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-10 08:50:40.451  1036  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-10 08:50:40.452  1036  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-10 08:50:40.453  1036  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-10 08:50:40.454  1036  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-10 08:50:40.454  1036  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-10 08:50:40.464  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=327552  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-10 08:50:40.467  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=327555  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-10 08:50:40.472  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:40.472  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:40.475  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.475  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.475  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 08:50:40.476  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:40.478  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:40.478  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-10 08:50:40.555  7859  7859 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 08:50:40.559  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-10 08:50:40.559  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-10 08:50:40.559  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-10 08:50:40.559  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-10 08:50:40.560  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 08:50:40.560  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 08:50:40.561  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=327649  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 08:50:40.566  7859  7859 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 08:50:40.566  7859  7859 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 08:50:40.572  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=327659  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-10 08:50:40.573  1036  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=327661
08-10 08:50:40.574  1036  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=327662
08-10 08:50:40.575  1036  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=327662
08-10 08:50:40.576  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=327663
08-10 08:50:40.576  1036  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=327664
08-10 08:50:40.577  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=327665  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 08:50:40.579  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 08:50:40.579  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 08:50:40.580  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-10 08:50:40.580  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 08:50:40.580  1036  7889 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 08:50:40.580  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-10 08:50:40.580  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 08:50:40.580  1036  7889 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 08:50:40.580  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 08:50:40.580  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 08:50:40.583  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-10 08:50:40.584  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=327672  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 08:50:40.585  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.586  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.586  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-10 08:50:40.591  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:40.591  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:40.593  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:40.596  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.596  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.597  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-10 08:50:40.597  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:40.597  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-10 08:50:40.600  1036  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=327688  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 08:50:40.601  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=327688  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 08:50:40.601  1036  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=327689
08-10 08:50:40.602  1036  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=327689
08-10 08:50:40.602  1036  1537 D WifiNative-wlan0: doString: [STATUS]
,08-10 08:50:40.604  1036  7889 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 08:50:40.604  1036  7889 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 08:50:40.604  1036  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 08:50:40.606  1036  1537 I WifiServiceExtension: setVHTCapabilityType  : false
08-10 08:50:40.612  1036  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-10 08:50:40.612  1036  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-10 08:50:40.613  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:40.613  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:40.614  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 08:50:40.626  1036  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-10 08:50:40.626  1036  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 08:50:40.626  1036  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 08:50:40.626  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.626  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.626  1036  1543 D ConnectivityService: Got NetworkAgent Messenger
08-10 08:50:40.626  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 08:50:40.626  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-10 08:50:40.626  1036  1543 D ConnectivityService: NetworkAgent connected
08-10 08:50:40.627  1036  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 08:50:40.627  1036  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-10 08:50:40.633  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.633  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.633  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 08:50:40.635  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:40.635  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:40.636  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:40.637  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:40.637  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:40.638  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:40.648  1036  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 08:50:40.648  1036  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 08:50:40.648  1036  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-10 08:50:40.650  1036  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 08:50:40.650  1036  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 08:50:40.659  1036  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 08:50:40.662   311   905 D CommandListener: Setting iface cfg
,08-10 08:50:40.669  1036  1537 E WifiStateMachine: Start Dhcp Watchdog 3
08-10 08:50:40.669  1036  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=327757  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 08:50:40.669  1036  7963 D DhcpStateMachine: StoppedState
08-10 08:50:40.669  1036  7963 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:40.669  1036  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=327757  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 08:50:40.669  1036  7963 D DhcpStateMachine: WaitBeforeStartState
08-10 08:50:40.670  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=327757  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 08:50:40.670  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:40.671  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:40.671  1036  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:40.671  1036  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:40.671  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:40.672  1036  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 08:50:40.672  1036  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=327760  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 08:50:40.672  1036  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=327760  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 08:50:40.673  1036  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=327760  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 08:50:40.673  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13978] from screen [on:0 period:1933025441] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 08:50:40.674  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1933025442] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 08:50:40.674  1036  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 08:50:40.676  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:40.676  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-10 08:50:40.678  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:40.678  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:40.679  1036  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-10 08:50:40.680  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 08:50:40.685  1036  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:40.685  1036  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:40.686  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:40.686  1036  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 08:50:40.686  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-10 08:50:40.686  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
08-10 08:50:40.687  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
08-10 08:50:40.687  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-10 08:50:40.687  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-10 08:50:40.687  1036  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-10 08:50:40.687  1036  1537 D WifiNative-wlan0: doBoolean: SET ps 0
08-10 08:50:40.688  1036  1537 D WifiNative-wlan0: SET ps 0: returned true
08-10 08:50:40.688  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-10 08:50:40.688  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-10 08:50:40.688  1036  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-10 08:50:40.688  1036  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@275e0534 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:40.688  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@275e0534 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:40.688  1036  7963 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:40.688  1036  7963 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-10 08:50:40.689  1036  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-10 08:50:40.689  1036  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 08:50:40.689  1036  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 08:50:40.690   311   905 D CommandListener: Setting iface cfg
08-10 08:50:40.690   311   905 D CommandListener: Trying to bring up wlan0
08-10 08:50:40.691  1036  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-10 08:50:40.692  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:40.692  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-10 08:50:40.693  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 08:50:40.693  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-10 08:50:40.694  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-10 08:50:40.694  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-10 08:50:40.694  1036  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:40.694  1036  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:40.694  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 08:50:40.694  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 08:50:40.695  1036  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 08:50:40.695  1036  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-10 08:50:40.695  7859  7859 I wpa_supplicant: wpa_driver_nl80211_ext_dr,iver_cmd SETSUSPENDMODE 1
08-10 08:50:40.695  1036  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-10 08:50:40.695  1036  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 08:50:40.715  1036  1537 D WifiNative-wlan0: SET ps 1: returned true
08-10 08:50:40.715  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:40.715  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:40.716  1036  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:40.716  1036  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:40.716  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:40.716  1036  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:40.717  1036  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 08:50:40.717  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 08:50:40.717  1036  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-10 08:50:40.719  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-10 08:50:40.719  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-10 08:50:40.719  1036  1543 D ConnectivityService: ignoring duplicate network state non-change
,08-10 08:50:40.722  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:40.722  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:40.723  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:40.724  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.724  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.724  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 08:50:40.724  1036  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-10 08:50:40.724  1036  1543 D ConnectivityService: Adding iface wlan0 to network 102
08-10 08:50:40.727  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.727  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.727  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 08:50:40.728  1036  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-10 08:50:40.728  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:40.728  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 08:50:40.729  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:40.729  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-10 08:50:40.732  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-10 08:50:40.735  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.735  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.735  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 08:50:40.736  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-10 08:50:40.740  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.740  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 08:50:40.740  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 08:50:40.742  1036  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-10 08:50:40.742  1036  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-10 08:50:40.743  1036  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-10 08:50:40.744   311   905 E Netd    : netlink response contains error (File exists)
08-10 08:50:40.744  1036  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-10 08:50:40.745  1036  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-10 08:50:40.745  1036  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-10 08:50:40.745  1036  1543 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-10 08:50:40.745  1036  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-10 08:50:40.745  1036  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-10 08:50:40.746  1036  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-10 08:50:40.746  1036  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-10 08:50:40.746  1036  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 08:50:40.746  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:40.746  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 08:50:40.746  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:40.746  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-10 08:50:40.746  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:40.746  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-10 08:50:40.746  1036  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-10 08:50:40.746  1036  1543 D ConnectivityService:    accepting network in place of null
08-10 08:50:40.746  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:40.746  1036  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:40.746  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-10 08:50:40.747  1036  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:40.747  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:40.747  1602  1602 I StatusBar.NetworkController: mWifiConnected = tru,e, mWifiLevel = 3
08-10 08:50:40.747  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:40.747  1036  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 08:50:40.747  1036  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-10 08:50:40.747  1036  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-10 08:50:40.748  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 08:50:40.749  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:40.749  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-10 08:50:40.752  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-10 08:50:40.752  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 08:50:40.752  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 08:50:40.752  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 08:50:40.754   311  7970 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-10 08:50:40.754  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:40.754  1036  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:40.754  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 08:50:40.754  1036  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-10 08:50:40.754  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:40.754  1036  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-10 08:50:40.756  1036  1543 D ConnectivityService: validation of new default Network = false
08-10 08:50:40.756  1036  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-10 08:50:40.756  1036  1543 D DSQN    : enableDataServiceNotify 
08-10 08:50:40.756  1036  1543 D DSQN    : start dsqn bin
08-10 08:50:40.764  1036  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-10 08:50:40.769  1036  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-10 08:50:40.769  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:40.769  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:40.770  1036  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:40.770  1602  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 08:50:40.763  7971  7971 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:40.763  7971  7971 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 08:50:40.781  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-10 08:50:40.782  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:40.782  7971  7971 E DSQN    : DSQN ssw
08-10 08:50:40.782  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:40.828   311  7970 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-10 08:50:40.862   311  7970 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-10 08:50:40.876   311   904 D LGDataListener: argv[0]=dsqncommand
,08-10 08:50:40.876   311   904 D LGDataListener: argv[1]=wlan0
,08-10 08:50:40.876   311   904 D LGDataListener: argv[2]=1
08-10 08:50:40.876   311   904 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-10 08:50:40.876  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
,08-10 08:50:40.877  1036  1116 D DSQN    : start to monitor internet connection
,08-10 08:50:40.886  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 06:50:40 GMT], X-Android-Received-Millis=[1470811840885], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470811840875]}
,08-10 08:50:40.886  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.,
08-10 08:50:40.886  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated,
08-10 08:50:40.887  1036  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-10 08:50:40.887  1036  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,08-10 08:50:40.887  1036  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-10 08:50:40.888  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ],
08-10 08:50:40.888  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-10 08:50:40.888  1036  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-10 08:50:40.888  1036  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,08-10 08:50:40.888  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 08:50:40.888  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:40.889  1036  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ],
,08-10 08:50:40.892  1602  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 08:50:40.892  1036  7963 D DhcpStateMachine: DHCPV4 request on wlan0
08-10 08:50:40.893  1036  7963 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-10 08:50:40.893  1036  7963 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-10 08:50:40.894  1036  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:40.894  1036  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:40.895  1036  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 08:50:40.895  7930  7930 W ExternalStrings: load override strings
08-10 08:50:40.895  7930  7930 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 08:50:40.895  7930  7930 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 08:50:40.896  7930  7930 D StatusProvider: onCreate
08-10 08:50:40.896  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:40.897  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 08:50:40.883  7977  7977 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 08:50:40.898  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 08:50:40.883  7977  7977 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 08:50:40.903  7977  7977 I dhcpcd  : version 5.5.6 starting
08-10 08:50:40.905  7977  7977 E dhcpcd  : get_duid: m
08-10 08:50:40.905  7977  7977 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-10 08:50:40.905  7977  7977 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-10 08:50:40.918  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-10 08:50:40.919  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 08:50:40.919  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 08:50:40.927  6597  6654 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 862)
08-10 08:50:40.927  6597  6654 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 862)
08-10 08:50:40.931  6597  6654 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 867)
08-10 08:50:40.932  6597  6654 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-10 08:50:40.932  6597  6654 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 868)
,08-10 08:50:40.935  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 08:50:40.935  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13d29fb2 added. We now have 2 listener(s)
08-10 08:50:40.936  1036  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:40.938  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 08:50:40.938  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 08:50:40.938  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:40.939  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:40.939  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13026b03 added. We now have 9 listener(s)
08-10 08:50:40.939  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:40.948  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 08:50:40.950  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:40.954  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:40.954  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:40.954  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:40.954  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:40.954  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:40.954  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:40.954  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:40.954  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:40.955  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:40.955  6597  6654 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 08:50:40.956  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 08:50:40.956  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fc8b9 added. We now have 3 listener(s)
08-10 08:50:40.956  1036  1717 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:40.957  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:40.958  7930  7930 V Signer  : override build config not found
08-10 08:50:40.958  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:40.958  7930  7930 D Signer  : value of property debug is false
08-10 08:50:40.959  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-10 08:50:40.959  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 08:50:40.959  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:40.959  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:40.959  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec704fe added. We now have 10 listener(s)
08-10 08:50:40.959  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:40.959  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:40.959  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:40.959  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:40.959  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:40.959  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:40.959  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:40.959  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 08:50:40.960  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13d29fb2 removed from the list
08-10 08:50:40.960  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:40.960  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13026b03 removed from the list
08-10 08:50:40.960  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:40.960  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:40.960  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:40.961  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:40.961  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:40.961  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:40.961  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:40.961  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13026b03 not in the list
08-10 08:50:40.961  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:40.961  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:40.962  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:40.962  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:40.962  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08,-10 08:50:40.962  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec704fe removed from the list
08-10 08:50:40.962  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:40.962  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:40.962  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:40.964  7977  7977 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 08:50:40.964  7977  7977 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 08:50:40.964  7977  7977 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-10 08:50:40.964  7977  7977 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-10 08:50:40.964  7977  7977 D dhcpcd  : wlan0: sending REQUEST (xid 0xd4eaa923), next in 3.67 seconds
08-10 08:50:40.964  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 08:50:40.964  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fc8b9 removed from the list
08-10 08:50:40.965  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 08:50:40.965  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18b6b45f added. We now have 2 listener(s)
08-10 08:50:40.965  1036  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:40.967  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 08:50:40.967  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 08:50:40.967  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:40.968  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:40.968  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1139eeac added. We now have 9 listener(s)
08-10 08:50:40.968  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:40.968  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 08:50:40.970  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:40.972  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:40.972  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:40.972  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:40.972  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:40.972  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:40.972  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:40.972  6597  6654 V io.jxcore.node.ConnectivityMonitor:     -, is connected/connecting to active network: true
08-10 08:50:40.972  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:40.973  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:40.974  6597  6654 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 08:50:40.975  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:40.976  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 08:50:40.976  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f0a730a added. We now have 3 listener(s)
08-10 08:50:40.976  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:40.977  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:40.979  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 08:50:40.979  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 08:50:40.979  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:40.979  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:40.979  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a3c377b added. We now have 10 listener(s)
08-10 08:50:40.979  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:40.979  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 08:50:40.979  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 08:50:40.979  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 08:50:40.979  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:40.979  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 08:50:40.981  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 08:50:40.981  1036  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:40.984  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 08:50:40.985  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 08:50:40.986  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 08:50:40.986  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:40.988  6597  6654 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 08:50:40.988  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:40.988  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:40.989  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:40.989  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:40.989  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:40.990  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:40.990  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:40.990  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:40.990  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 08:50:40.990  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18b6b45f removed from the list
08-10 08:50:40.990  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:40.990  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1139eeac removed from the list
08-10 08:50:40.990  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:40.990  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:40.990  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:40.991  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:40.991  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:40.991  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:40.991  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:40.991  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1139eeac not in the list
08-10 08:50:40.991  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:40.991  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:40.992  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:40.993  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:40.993  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:40.993  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:40.993  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:40.993  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a3c377b removed from the list
08-10 08:50:40.993  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:40.993  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:40.993  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:40.993  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 08:50:40.993  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f0a730a removed from the list
08-10 08:50:40.994  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 08:50:40.994  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1364b5d6 added. We now have 2 listener(s)
08-10 08:50:40.994  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:40.996  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 08:50:40.996  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 08:50:40.996  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:40.996  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:40.996  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2accd057 added. We now have 9 listener(s)
08-10 08:50:40.996  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:40.997  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 08:50:40.999  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:41.002  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-10 08:50:41.002  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-10 08:50:41.002  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-10 08:50:41.003  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-10 08:50:41.003  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:41.003  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:41.003  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:41.003  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:41.003  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:41.003  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:41.003  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:41.003  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:41.003  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-10 08:50:41.003  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-10 08:50:41.003  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-10 08:50:41.004  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-10 08:50:41.004  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-10 08:50:41.004  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:41.004  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-10 08:50:41.004  6597  6654 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 08:50:41.004  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-10 08:50:41.004  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-10 08:50:41.005  7930  7930 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-10 08:50:41.005  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 08:50:41.005  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c3fe02d added. We now have 3 listener(s)
08-10 08:50:41.005  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:41.005  7977  7977 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-10 08:50:41.007  1036  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:41.007  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:41.010  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 08:50:41.010  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 08:50:41.010  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:41.010  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:41.010  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4e5962 added. We now have 10 listener(s)
08-10 08:50:41.011  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:41.011  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 08:50:41.012  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 08:50:41.012  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 08:50:41.012  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 08:50:41.012  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:41.012  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 08:50:41.014  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 08:50:41.015  1036  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:41.016  7930  7930 V LGMDMManager: Create singleton instance
08-10 08:50:41.018  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 08:50:41.018  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 08:50:41.019  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 08:50:41.020  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:41.021  6597  6654 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 08:50:41.021  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:41.021  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:41.021  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:41.022  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:41.022  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.022  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:41.022  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 08:50:41.022  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1364b5d6 removed from the list
08-10 08:50:41.022  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:41.022  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2accd057 removed from the list
08-10 08:50:41.022  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:41.022  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.022  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.023  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.023  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:41.023  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:41.023  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:41.023  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2accd057 not in the list
08-10 08:50:41.023  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.023  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.024  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:41.025  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:41.025  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:41.025  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:41.025  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:41.025  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4e5962 removed from the list
08-10 08:50:41.025  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:41.025  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.025  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.025  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 08:50:41.025  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c3fe02d removed from the list
08-10 08:50:41.026  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 08:50:41.026  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3de75229 added. We now have 2 listener(s)
08-10 08:50:41.026  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:41.028  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 08:50:41.028  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 08:50:41.028  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:41.028  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:41.028  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3ca9ae added. We now have 9 listener(s)
08-10 08:50:41.028  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:41.029  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 08:50:41.032  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:41.034  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:41.034  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:41.034  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:41.034  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:41.034  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:41.034  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:41.034  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:41.034  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:41.035  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:41.035  6597  6654 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 08:50:41.037  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:41.037  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 08:50:41.037  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29ec5adc added. We now have 3 listener(s)
08-10 08:50:41.038  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:41.039  7977  7977 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-10 08:50:41.039  7977  7977 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-10 08:50:41.039  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 08:50:41.039  7977  7977 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-10 08:50:41.039  7977  7977 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-10 08:50:41.040  7977  7977 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-10 08:50:41.040  7977  7977 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 08:50:41.040  7977  7977 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 08:50:41.040  7977  7977 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-10 08:50:41.042  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 08:50:41.042  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 08:50:41.042  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:41.042  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:41.042  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f79e7e5 added. We now have 10 listener(s)
08-10 08:50:41.042  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:41.042  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 08:50:41.042  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 08:50:41.042  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 08:50:41.042  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:41.042  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 08:50:41.045  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 08:50:41.045  1036  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:41.048  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 08:50:41.049  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 08:50:41.050  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 08:50:41.050  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:41.051  6597  6654 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 08:50:41.053  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:41.053  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:41.053  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:41.053  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:41.053  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.053  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:41.053  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 08:50:41.053  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3de75229 removed from the list
08-10 08:50:41.053  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:41.053  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3ca9ae removed from the list
08-10 08:50:41.053  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:41.053  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.054  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.054  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.054  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:41.055  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:41.055  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:41.055  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3ca9ae not in the list
08-10 08:50:41.055  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.055  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.056  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:41.056  6597  6654 D BluetoothLeScanner: could not find callback wrapper
08-10 08:50:41.056  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 08:50:41.056  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:41.056  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:41.056  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f79e7e5 removed from the list
08-10 08:50:41.056  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:41.056  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.056  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.056  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 08:50:41.056  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29ec5adc removed from the list
08-10 08:50:41.057  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 08:50:41.057  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95248c8 added. We now have 2 listener(s)
08-10 08:50:41.057  1036  1717 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:41.059  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 08:50:41.059  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 08:50:41.059  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:41.059  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:41.059  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ce61d61 added. We now have 9 listener(s)
08-10 08:50:41.059  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:41.060  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 08:50:41.062  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 08:50:41.064  6597  6654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 08:50:41.064  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:41.064  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:41.064  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:41.064  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:41.064  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:41.064  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:41.064  6597  6654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:41.065  6597  6654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:41.065  6597  6654 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 08:50:41.066  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:41.067  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 08:50:41.068  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 08:50:41.068  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@354c7d47 added. We now have 3 listener(s)
08-10 08:50:41.068  1036  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 08:50:41.070  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 08:50:41.070  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 08:50:41.070  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 08:50:41.070  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 08:50:41.070  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ba72974 added. We now have 10 listener(s)
08-10 08:50:41.070  6597  6654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 08:50:41.070  6597  6654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 08:50:41.070  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 08:50:41.070  6597  6654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 08:50:41.070  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:41.070  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.071  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 08:50:41.071  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 08:50:41.071  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95248c8 removed from the list
08-10 08:50:41.071  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:41.071  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ce61d61 removed from the list
08-10 08:50:41.071  6597  6654 D io.jxcore.node.ConnectivityMonitor: stop
08-10 08:50:41.071  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.071  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.071  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.072  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:41.072  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:41.072  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:41.072  6597  6654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ce61d61 not in the list
08-10 08:50:41.072  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.072  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.073  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 08:50:41.073  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 08:50:41.073  6597  6654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 08:50:41.073  6597  6654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ba72974 removed from the list
08-10 08:50:41.073  6597  6654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 08:50:41.073  6597  6654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 08:50:41.073  6597  6654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 08:50:41.073  6597  6654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 08:50:41.073  6597  6654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@354c7d47 removed from the list
08-10 08:50:41.074  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-10 08:50:41.074  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-10 08:50:41.074  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-10 08:50:41.074  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 08:50:41.074  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-10 08:50:41.074  6597  6654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-10 08:50:41.078  7930  7930 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-10 08:50:41.082  6597  7989 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: My test thread name)
08-10 08:50:41.082  6597  7989 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 875, thread name: My test thread name)
08-10 08:50:41.082  6597  7989 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 875, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-10 08:50:41.084  6597  7990 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 877, name: My test thread name)
08-10 08:50:41.084  6597  7990 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 877, thread name: My test thread name)
08-10 08:50:41.084  6597  7990 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 877, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-10 08:50:41.086  6597  6654 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-10 08:50:41.086  6597  6654 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-10 08:50:41.086  6597  6654 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-10 08:50:41.086  6597  6654 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-10 08:50:41.086  6597  6654 D com.test.thalitest.ThaliTestRunner: Total duration: 22743 ms
08-10 08:50:41.087  6597  6654 I jxcore-log: Total number of executed tests:  80
08-10 08:50:41.087  6597  6654 I jxcore-log: 
08-10 08:50:41.087  6597  6654 I jxcore-log: Number of passed tests:  80
08-10 08:50:41.087  6597  6654 I jxcore-log: 
08-10 08:50:41.087  6597  6654 I jxcore-log: Number of failed tests:  0
08-10 08:50:41.087  6597  6654 I jxcore-log: 
08-10 08:50:41.088  6597  6654 I jxcore-log: Number of ignored tests:  0
08-10 08:50:41.088  6597  6654 I jxcore-log: 
08-10 08:50:41.088  6597  6654 I jxcore-log: Total duration:  22743
08-10 08:50:41.088  6597  6654 I jxcore-log: 
08-10 08:50:41.091  6597  6654 I jxcore-log: Unit Test app is loaded
08-10 08:50:41.091  6597  6654 I jxcore-log: 
08-10 08:50:41.098  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 08:50:41.098  6597  6654 I jxcore-log: 
08-10 08:50:41.105  6597  6597 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-10 08:50:41.108  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 08:50:41.108  6597  6654 I jxcore-log: 
08-10 08:50:41.109  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 08:50:41.109  6597  6654 I jxcore-log: 
08-10 08:50:41.110  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 08:50:41.110  6597  6654 I jxcore-log: 
08-10 08:50:41.111  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 08:50:41.111  6597  6654 I jxcore-log: 
08-10 08:50:41.112  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 08:50:41.112  6597  6654 I jxcore-log: 
08-10 08:50:41.113  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 08:50:41.113  6597  6654 I jxcore-log: 
08-10 08:50:41.115  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 08:50:41.115  6597  6654 I jxcore-log: 
,08-10 08:50:41.115  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-10 08:50:41.115  6597  6654 I jxcore-log: 
08-10 08:50:41.116  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 08:50:41.116  6597  6654 I jxcore-log: 
08-10 08:50:41.117  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 08:50:41.117  6597  6654 I jxcore-log: 
08-10 08:50:41.118  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 08:50:41.118  6597  6654 I jxcore-log: 
08-10 08:50:41.119  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 08:50:41.119  6597  6654 I jxcore-log: 
08-10 08:50:41.119  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 08:50:41.119  6597  6654 I jxcore-log: 
08-10 08:50:41.120  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 08:50:41.120  6597  6654 I jxcore-log: 
08-10 08:50:41.120  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 08:50:41.120  6597  6654 I jxcore-log: 
08-10 08:50:41.121  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 08:50:41.121  6597  6654 I jxcore-log: 
08-10 08:50:41.121  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:41.121  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 08:50:41.121  6597  6654 I jxcore-log: 
08-10 08:50:41.122  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 08:50:41.122  6597  6654 I jxcore-log: 
08-10 08:50:41.122  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 08:50:41.122  6597  6654 I jxcore-log: 
,08-10 08:50:41.123  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 08:50:41.123  6597  6654 I jxcore-log: 
08-10 08:50:41.123  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 08:50:41.123  6597  6654 I jxcore-log: 
08-10 08:50:41.124  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 08:50:41.124  6597  6654 I jxcore-log: 
08-10 08:50:41.124  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 08:50:41.124  6597  6654 I jxcore-log: 
08-10 08:50:41.125  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 08:50:41.125  6597  6654 I jxcore-log: 
08-10 08:50:41.125  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 08:50:41.125  6597  6654 I jxcore-log: 
08-10 08:50:41.126  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 08:50:41.126  6597  6654 I jxcore-log: 
08-10 08:50:41.127  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 08:50:41.128  6597  6654 I jxcore-log: My device name is: LGE-LG-D855
08-10 08:50:41.128  6597  6654 I jxcore-log: 
08-10 08:50:41.128  6597  6654 I jxcore-log: WARN testUtils: myNameCallback not set!
08-10 08:50:41.128  6597  6654 I jxcore-log: 
08-10 08:50:41.130  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:41.135  7930  7997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 08:50:41.164  1036  2030 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8004 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-10 08:50:41.166  1036  2030 I ActivityManager: Killing 7045:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-10 08:50:41.284  7930  7995 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-10 08:50:41.295  1036  7963 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-10 08:50:41.296  1036  7963 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-10 08:50:41.296  1036  7963 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 08:50:41.297  1036  7963 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-10 08:50:41.297  1036  7963 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-10 08:50:41.297  1036  7963 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 08:50:41.297  1036  7963 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-10 08:50:41.297  1036  7963 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-10 08:50:41.297  1036  7963 D DhcpStateMachine: RunningState
08-10 08:50:41.375  1036  2030 E libprocessgroup: failed to kill 1 processes for processgroup 7045
,08-10 08:50:41.547  8004  8004 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 08:50:41.577  8004  8004 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-10 08:50:41.612  8004  8004 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-10 08:50:41.612  8004  8004 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-10 08:50:41.613  8004  8004 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-10 08:50:41.613  8004  8004 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-10 08:50:41.614  8004  8004 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-10 08:50:41.615  8004  8004 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-10 08:50:41.620  8004  8004 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-10 08:50:41.626  8004  8004 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:41.628  8004  8004 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 08:50:41.633  7930  7995 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:41.633  7930  7995 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 08:50:41.643  8004  8004 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 08:50:41.645  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:41.645  7930  7997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 08:50:41.650  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:41.654  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:41.655  8004  8004 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-10 08:50:41.660  8004  8004 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-10 08:50:41.661  8004  8004 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:41.661  8004  8004 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:41.662  8004  8004 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-10 08:50:41.664  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-10 08:50:41.666  6678  6678 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-10 08:50:41.668  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:41.668  7930  7997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 08:50:41.673  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:41.676  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:41.680  8004  8004 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:41.681  8004  8004 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:41.681  8004  8004 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 08:50:41.683  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:41.683  7930  7997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 08:50:41.688  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:41.692  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:41.695  8004  8004 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:41.695  8004  8004 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:41.695  8004  8004 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 08:50:41.697  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 08:50:41.697  6678  6678 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 08:50:41.697  6678  6678 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 08:50:41.697  6678  6678 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 08:50:41.697  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 08:50:41.697  6678  6678 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 08:50:41.697  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-10 08:50:41.697  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 08:50:41.697  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 08:50:41.697  6678  6678 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 08:50:41.697  6678  6678 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-10 08:50:41.698  6678  6678 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 08:50:41.700  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:41.700  7930  7997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-10 08:50:41.705  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 08:50:41.707  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:41.712  8004  8004 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:41.712  8004  8004 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:41.712  8004  8004 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 08:50:41.716  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:41.716  7930  7997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 08:50:41.718  7930  7995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-10 08:50:41.723  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:41.728  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:41.742  8004  8004 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:41.742  8004  8004 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:41.742  8004  8004 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 08:50:41.744  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:41.746  7930  7997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 08:50:41.747  7930  7995 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-10 08:50:41.748  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 08:50:41.753  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:41.755  7930  7995 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-10 08:50:41.756  7930  7995 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-10 08:50:41.757  8004  8004 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:41.757  8004  8004 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:41.757  8004  8004 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 08:50:41.758  7930  7995 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-10 08:50:41.759  7930  7995 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-10 08:50:41.759  7930  7995 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-10 08:50:41.769  7930  7995 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-10 08:50:41.770  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:41.771  7930  7997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-10 08:50:41.774  7930  7995 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-10 08:50:41.781  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:41.786  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:41.792  8004  8004 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:41.792  8004  8004 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 08:50:41.796  8004  8004 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 08:50:41.799  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:41.800  7930  7997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 08:50:41.804  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:41.809  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:41.813  8004  8004 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:41.814  8004  8004 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:41.815  8004  8004 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 08:50:41.818  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:41.819  7930  7997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 08:50:41.822  7884  7884 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-10 08:50:41.825  7884  7884 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:41.827  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 08:50:41.833  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 08:50:41.842  8004  8004 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:41.843  8004  8004 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:41.843  8004  8004 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 08:50:41.844  8004  8004 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-10 08:50:41.845  8004  8004 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-10 08:50:41.850  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:41.851  7930  7997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 08:50:41.854  7884  7884 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-10 08:50:41.855  7884  7884 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-10 08:50:41.859  6678  6678 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 08:50:41.865  6678  6678 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 08:50:41.869  8004  8004 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 08:50:41.870  8004  8004 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 08:50:41.870  8004  8004 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 08:50:41.871  8004  8004 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-10 08:50:41.871  8004  8004 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-10 08:50:41.876  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-10 08:50:41.883  8004  8004 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 08:50:41.884  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 08:50:41.884  8004  8004 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-10 08:50:41.919  8004  8004 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 08:50:41.919  8004  8004 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 08:50:41.924  8004  8004 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-10 08:50:41.925  8004  8004 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-10 08:50:41.925  8004  8004 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-10 08:50:41.925  8004  8004 V SoundPool: doLoad: loading sample sampleID=1
08-10 08:50:41.926  8004  8004 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 08:50:41.926  8004  8054 V SoundPool: Start decode
08-10 08:50:41.926  8004  8054 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-10 08:50:41.927   315  1386 V MediaPlayerService: decode(23, 10857164, 17813)
08-10 08:50:41.927   315  1386 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-10 08:50:41.927   315  1386 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-10 08:50:41.927   315  1386 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-10 08:50:41.927   315  1386 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-10 08:50:41.927   315  1386 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-10 08:50:41.927   315  1386 V MediaPlayerService: player type = 3
08-10 08:50:41.927   315  1386 V AwesomePlayer: AwesomePlayer create()
08-10 08:50:41.927   315  1386 V AwesomePlayer: reset_l() 
08-10 08:50:41.927   315  1386 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:41.927   315  1386 V AwesomePlayer: setAudioSink() 
08-10 08:50:41.927   315  1386 V AwesomePlayer: reset_l() 
08-10 08:50:41.928   315  1386 V AudioCache: notify(0xb5474a80, 8, 0, 0)
08-10 08:50:41.928   315  1386 V AudioCache: ignored
08-10 08:50:41.928   315  1386 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:41.928   315  1386 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-10 08:50:41.928   315  1386 V AwesomePlayer: setDataSource_l dataSource
08-10 08:50:41.928   315  1386 V LGParserOSAL: SniffLGParser start
08-10 08:50:41.928   315  1386 V LGParserOSAL: MainType:5, SubType=0
08-10 08:50:41.928   315  1386 V LGParserOSAL: #### check Mime : application/ogg
08-10 08:50:41.928   315  1386 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-10 08:50:41.928   315  1386 E MediaExtractor: Use LGExtractor :application/ogg 
08-10 08:50:41.929  7433  7433 D UEI.SmartControl: QS Service created
08-10 08:50:41.937  8004  8004 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-10 08:50:41.950  7433  7433 I UEI.SmartControl: Service initServices...
08-10 08:50:41.950  7433  7433 D UEI.SmartControl: QS start get config
08-10 08:50:41.951  8004  8004 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 08:50:41.951  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-10 08:50:41.971   315  1386 V LGParserOSAL: supported mime: application/ogg
08-10 08:50:41.971   315  1386 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-10 08:50:41.971   315  1386 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-10 08:50:41.971   315  1386 V AwesomePlayer: mBitrate = -1 bits/sec
08-10 08:50:41.971   315  1386 V AwesomePlayer: AudioTrack Setting
08-10 08:50:41.971   315  1386 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-10 08:50:41.971   315  1386 V AwesomePlayer: setAudioSource() 
,08-10 08:50:41.971   315  1386 V MediaPlayerService: prepare
08-10 08:50:41.971   315  1386 V AwesomePlayer: prepareAsync_l() 
08-10 08:50:41.971   315  1386 V MediaPlayerService: wait for prepare
08-10 08:50:41.973   315  8056 V AwesomePlayer: onPrepareAsyncEvent() 
08-10 08:50:41.973   315  8056 V AwesomePlayer: initAudioDecoder() 
08-10 08:50:41.973   315  8056 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 08:50:41.973   315  8056 V AudioSystem: isOffloadSupported()
08-10 08:50:41.973   315  8056 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 08:50:41.973   315  8056 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 08:50:41.973   315  8056 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 08:50:41.973   315  8056 V AwesomePlayer: getUseOffload() = 0 
08-10 08:50:41.973   315  8056 V OMXCodec: OMXCodec::Create
08-10 08:50:41.973   315  8056 V OMXCodec: findMatchingCodecs()
08-10 08:50:41.974   315  8056 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-10 08:50:41.974   315  8056 V OMXCodec: matchingCodecs.size()=1
08-10 08:50:41.974   315  8056 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-10 08:50:41.975   315  8056 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-10 08:50:41.975   315  8056 V LGCodecAdapter: LG Codec Adapter start
08-10 08:50:41.975   315  8056 V OMXCodec: OMXCodec Createtor
08-10 08:50:41.975   315  8056 V OMXCodec: setComponentRole
08-10 08:50:41.975   315  8056 V OMXCodec: configureCodec protected=0
08-10 08:50:41.975   315  8056 V LGCodecAdapter: called getLGCodecSpecificData
08-10 08:50:41.975   315  8056 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-10 08:50:41.975   315  8056 V LGCodecOSAL: Called LGconfigureCodecMETA
08-10 08:50:41.975   315  8056 V LGCodecOSAL: Called LGconfigureCodecMSG
08-10 08:50:41.975   315  8056 V LGCodecOSAL: Not support LGCodec
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 08:50:41.976   315  8056 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-10 08:50:41.976   315  8056 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-10 08:50:41.976   315  8056 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-10 08:50:41.976   315  8056 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 08:50:41.976   315  8056 V AudioSystem: isOffloadSupported()
08-10 08:50:41.976   315  8056 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 08:50:41.976   315  8056 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-10 08:50:41.976   315  8056 V OMXCodec: init()
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-10 08:50:41.976   315  8056 V OMXCodec: allocateBuffers
08-10 08:50:41.976   315  8056 V OMXCodec: allocateBuffersOnPort portIndex=0
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.goo,gle.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-10 08:50:41.976   315  8056 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-10 08:50:41.976   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-10 08:50:41.977   315  8056 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-10 08:50:41.977   315  8056 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 08:50:41.977   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 08:50:41.977   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 08:50:41.977   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-10 08:50:41.977   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-10 08:50:41.977   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-10 08:50:41.977   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-10 08:50:41.977   315  8056 V OMXCodec: init() mAsyncCompletion wait free! 
08-10 08:50:41.977   315  8056 V AwesomePlayer: finishAsyncPrepare_l() 
08-10 08:50:41.977   315  8056 V AudioCache: notify(0xb5474a80, 5, 0, 0)
08-10 08:50:41.977   315  8056 V AudioCache: ignored
08-10 08:50:41.977   315  8056 V AudioCache: notify(0xb5474a80, 1, 0, 0)
08-10 08:50:41.977   315  8056 V AudioCache: prepared
08-10 08:50:41.977   315  1386 V AudioCache: wait - success
08-10 08:50:41.977   315  1386 V MediaPlayerService: start
08-10 08:50:41.977   315  1386 V AwesomePlayer: play_l() 
08-10 08:50:41.977   315  1386 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-10 08:50:41.977   315  1386 V AwesomePlayer: createAudioPlayer_l
08-10 08:50:41.977   315  1386 V AwesomePlayer: seekAudioIfNecessary_l() 
08-10 08:50:41.977   315  1386 V AwesomePlayer: startAudioPlayer_l() 
08-10 08:50:41.977   315  1386 D AudioPlayer: start of Playback, useOffload 0
08-10 08:50:41.977   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 08:50:41.977   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 08:50:41.979  8004  8004 V LGMDMManager: Create singleton instance
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-10 08:50:41.979   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-10 08:50:41.980   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 08:50:41.980   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-10 08:50:41.980   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-10 08:50:41.980   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-10 08:50:41.980   315  8058 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 08:50:41.980   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 08:50:41.980   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-10 08:50:41.980   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-10 08:50:41.980   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
,08-10 08:50:41.980   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on output port
08-10 08:50:41.980   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-10 08:50:41.980   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-10 08:50:41.981   315  1386 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-10 08:50:41.981   315  1386 V AudioCache: notify(0xb5474a80, 6, 0, 0)
08-10 08:50:41.981   315  1386 V AudioCache: ignored
08-10 08:50:41.981   315  1386 V MediaPlayerService: wait for playback complete
08-10 08:50:41.984   315  8059 V AudioCache: write(0xb16b6000, 4096)
,08-10 08:50:41.984   315  8059 V AudioCache: memcpy(0xaf006000, 0xb16b6000, 4096)
08-10 08:50:41.985   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.985   315  8059 V AudioCache: memcpy(0xaf007000, 0xb16b6000, 4096)
08-10 08:50:41.985   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.985   315  8059 V AudioCache: memcpy(0xaf008000, 0xb16b6000, 4096)
08-10 08:50:41.986   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.986   315  8059 V AudioCache: memcpy(0xaf009000, 0xb16b6000, 4096)
08-10 08:50:41.986   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.986   315  8059 V AudioCache: memcpy(0xaf00a000, 0xb16b6000, 4096)
,08-10 08:50:41.987   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.987   315  8059 V AudioCache: memcpy(0xaf00b000, 0xb16b6000, 4096)
08-10 08:50:41.987   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.987   315  8059 V AudioCache: memcpy(0xaf00c000, 0xb16b6000, 4096)
08-10 08:50:41.988   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.988   315  8059 V AudioCache: memcpy(0xaf00d000, 0xb16b6000, 4096)
08-10 08:50:41.988   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.988   315  8059 V AudioCache: memcpy(0xaf00e000, 0xb16b6000, 4096)
,08-10 08:50:41.989   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.989   315  8059 V AudioCache: memcpy(0xaf00f000, 0xb16b6000, 4096)
,08-10 08:50:41.991   315  8059 V AudioCache: write(0xb16b6000, 4096)
,08-10 08:50:41.992   315  8059 V AudioCache: memcpy(0xaf010000, 0xb16b6000, 4096)
08-10 08:50:41.992   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.992   315  8059 V AudioCache: memcpy(0xaf011000, 0xb16b6000, 4096)
08-10 08:50:41.999   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.999   315  8059 V AudioCache: memcpy(0xaf012000, 0xb16b6000, 4096)
08-10 08:50:41.999   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:41.999   315  8059 V AudioCache: memcpy(0xaf013000, 0xb16b6000, 4096)
08-10 08:50:42.000   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.000   315  8059 V AudioCache: memcpy(0xaf014000, 0xb16b6000, 4096)
08-10 08:50:42.000   315  8059 V AudioCache: write(0xb16b6000, 4096)
,08-10 08:50:42.000   315  8059 V AudioCache: memcpy(0xaf015000, 0xb16b6000, 4096)
08-10 08:50:42.001   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.001   315  8059 V AudioCache: memcpy(0xaf016000, 0xb16b6000, 4096)
08-10 08:50:42.001   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.001   315  8059 V AudioCache: memcpy(0xaf017000, 0xb16b6000, 4096)
,08-10 08:50:42.003   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.003   315  8059 V AudioCache: memcpy(0xaf018000, 0xb16b6000, 4096)
08-10 08:50:42.004   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.004   315  8059 V AudioCache: memcpy(0xaf019000, 0xb16b6000, 4096)
08-10 08:50:42.004   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.004   315  8059 V AudioCache: memcpy(0xaf01a000, 0xb16b6000, 4096)
08-10 08:50:42.005   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.005   315  8059 V AudioCache: memcpy(0xaf01b000, 0xb16b6000, 4096)
08-10 08:50:42.006   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.006   315  8059 V AudioCache: memcpy(0xaf01c000, 0xb16b6000, 4096)
08-10 08:50:42.006   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.006   315  8059 V AudioCache: memcpy(0xaf01d000, 0xb16b6000, 4096)
08-10 08:50:42.007   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.007   315  8059 V AudioCache: memcpy(0xaf01e000, 0xb16b6000, 4096)
08-10 08:50:42.008   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.008   315  8059 V AudioCache: memcpy(0xaf01f000, 0xb16b6000, 4096)
08-10 08:50:42.008   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.008   315  8059 V AudioCache: memcpy(0xaf020000, 0xb16b6000, 4096)
08-10 08:50:42.009   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.009   315  8059 V AudioCache: memcpy(0xaf021000, 0xb16b6000, 4096)
08-10 08:50:42.010   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.010   315  8059 V AudioCache: memcpy(0xaf022000, 0xb16b6000, 4096)
08-10 08:50:42.010   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.010   315  8059 V AudioCache: memcpy(0xaf023000, 0xb16b6000, 4096)
08-10 08:50:42.011   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.011   315  8059 V AudioCache: memcpy(0xaf024000, 0xb16b6000, 4096)
08-10 08:50:42.011   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.011   315  8059 V AudioCache: memcpy(0xaf025000, 0xb16b6000, 4096)
08-10 08:50:42.012   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.012   315  8059 V AudioCache: memcpy(0xaf026000, 0xb16b6000, 4096)
08-10 08:50:42.012   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.012   315  8059 V AudioCache: memcpy(0xaf027000, 0xb16b6000, 4096)
08-10 08:50:42.013   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.013   315  8059 V AudioCache: memcpy(0xaf028000, 0xb16b6000, 4096)
,08-10 08:50:42.014   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.014   315  8059 V AudioCache: memcpy(0xaf029000, 0xb16b6000, 4096)
08-10 08:50:42.015   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.015   315  8059 V AudioCache: memcpy(0xaf02a000, 0xb16b6000, 4096)
08-10 08:50:42.015   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.015   315  8059 V AudioCache: memcpy(0xaf02b000, 0xb16b6000, 4096)
08-10 08:50:42.016   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.016   315  8059 V AudioCache: memcpy(0xaf02c000, 0xb16b6000, 4096)
08-10 08:50:42.017   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.017   315  8059 V AudioCache: memcpy(0xaf02d000, 0xb16b6000, 4096)
08-10 08:50:42.017   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.017   315  8059 V AudioCache: memcpy(0xaf02e000, 0xb16b6000, 4096)
08-10 08:50:42.018   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.018   315  8059 V AudioCache: memcpy(0xaf02f000, 0xb16b6000, 4096)
08-10 08:50:42.018   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.018   315  8059 V AudioCache: memcpy(0xaf030000, 0xb16b6000, 4096)
,08-10 08:50:42.019   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.019   315  8059 V AudioCache: memcpy(0xaf031000, 0xb16b6000, 4096)
08-10 08:50:42.019   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.019   315  8059 V AudioCache: memcpy(0xaf032000, 0xb16b6000, 4096)
08-10 08:50:42.020   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.020   315  8059 V AudioCache: memcpy(0xaf033000, 0xb16b6000, 4096)
08-10 08:50:42.021   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.021   315  8059 V AudioCache: memcpy(0xaf034000, 0xb16b6000, 4096)
08-10 08:50:42.021   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.021   315  8059 V AudioCache: memcpy(0xaf035000, 0xb16b6000, 4096)
08-10 08:50:42.022   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.022   315  8059 V AudioCache: memcpy(0xaf036000, 0xb16b6000, 4096)
08-10 08:50:42.022   315  8059 V AudioCache: write(0xb16b6000, 4096)
08-10 08:50:42.022   315  8059 V AudioCache: memcpy(0xaf037000, 0xb16b6000, 4096)
08-10 08:50:42.022   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-10 08:50:42.022   315  8059 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-10 08:50:42.022   315  8059 V AwesomePlayer: postAudioEOS() 
08-10 08:50:42.022   315  8059 V AudioCache: write(0xb16b6000, 280)
08-10 08:50:42.022   315  8059 V AudioCache: memcpy(0xaf038000, 0xb16b6000, 280)
08-10 08:50:42.024   315  8056 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-10 08:50:42.024   315  8056 V AwesomePlayer: onStreamDone
08-10 08:50:42.024   315  8056 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-10 08:50:42.024   315  8056 V AudioCache: notify(0xb5474a80, 2, 0, 0)
08-10 08:50:42.024   315  8056 V AudioCache: playback complete
08-10 08:50:42.024   315  8056 V AwesomePlayer: pause_l() 
08-10 08:50:42.024   315  1386 V AudioCache: wait - success
08-10 08:50:42.024   315  8056 V AudioCache: notify(0xb5474a80, 7, 0, 0)
08-10 08:50:42.024   315  1386 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-10 08:50:42.024   315  8056 V AudioCache: ignored
08-10 08:50:42.024   315  8056 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:42.024   315  8056 D AudioPlayer: Pause Playback at 1068125
08-10 08:50:42.025   315  1386 V AwesomePlayer: reset_l() 
08-10 08:50:42.025   315  1386 V AudioCache: notify(0xb5474a80, 8, 0, 0)
08-10 08:50:42.025   315  1386 V AudioCache: ignored
08-10 08:50:42.025   315  1386 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:42.025   315  1386 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-10 08:50:42.025   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-10 08:50:42.025   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-10 08:50:42.025   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-10 08:50:42.025   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 08:50:42.027   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 08:50:42.027   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 08:50:42.027   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-10 08:50:42.027   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-10 08:50:42.027   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
,08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 1
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 08:50:42.029   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-10 08:50:42.029   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 08:50:42.029   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 08:50:42.030   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-10 08:50:42.030   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-10 08:50:42.030   315  8058 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-10 08:50:42.030   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 08:50:42.030   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-10 08:50:42.030   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-10 08:50:42.030   315  1386 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-10 08:50:42.031   315  1386 D AudioPlayer: AudioPlayer releasing audio source
08-10 08:50:42.031   315  1386 D AudioPlayer: AudioPlayer done releasing audio source
08-10 08:50:42.031   315  1386 V AwesomePlayer: reset_l() 
08-10 08:50:42.031   315  1386 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:42.031   315  1386 V AwesomePlayer: ~AwesomePlayer call
08-10 08:50:42.031   315  1386 V AwesomePlayer: reset_l() 
08-10 08:50:42.031   315  1386 V AwesomePlayer: cancelPlayerEvents
08-10 08:50:42.031  8004  8054 V SoundPool: close(31)
08-10 08:50:42.031  8004  8054 V SoundPool: pointer = 0xa0026000, size = 205080, sampleRate = 48000, numChannels = 2
,08-10 08:50:42.040  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 08:50:42.041  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-10 08:50:42.042  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3591
08-10 08:50:42.045  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:42.062  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:42.066  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:42.068  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:42.070  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:42.073  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:42.075  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 08:50:42.079  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:42.082  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:42.084  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 08:50:42.238  7433  7433 I UEI.SmartControl: Supports setup maps: true
08-10 08:50:42.241  7433  7433 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 08:50:42.241  7433  7433 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-10 08:50:42.241  7433  7433 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 08:50:42.241  7433  7433 I UEI.SmartControl: ### init IR Blaster...
,08-10 08:50:42.244  7433  7433 D serial_port: Configuring serial port
08-10 08:50:42.245  7433  7433 E UEI.SmartControl: UEIBLaster setting for 616
08-10 08:50:42.245  7433  7433 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 08:50:42.245  7433  7433 I UEI.SmartControl: configuring settings for MAXQ616
08-10 08:50:42.245  7433  7433 I UEI.SmartControl: Get version...
08-10 08:50:42.263  7433  8061 D UEI.SmartControl: serial port data available: 21
,08-10 08:50:42.290  7433  7433 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-10 08:50:42.290  7433  7433 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 08:50:42.290  7433  7433 I UEI.SmartControl: QS saving settings...
08-10 08:50:42.292  7433  7433 D UEI.SmartControl: IR Blaster version: 25672567
,08-10 08:50:42.309  7433  8061 D UEI.SmartControl: serial port data available: 4
,08-10 08:50:42.340  7433  8067 I UEI.SmartControl: Device manager: loading config....
08-10 08:50:42.344  7433  7433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-10 08:50:42.346  7433  7433 E UEI.SmartControl: Services init done
,08-10 08:50:42.346  7433  7433 D UEI.SmartControl: QS Service init finished
08-10 08:50:42.347  7433  7433 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 08:50:42.347  7433  7433 D UEI.SmartControl: QS Service version code: 201091
08-10 08:50:42.348  7433  7433 D UEI.SmartControl: Service requested: Control
08-10 08:50:42.348  7433  8067 D UEI.SmartControl: ----------- loading internal config...
08-10 08:50:42.356  7433  8067 E UEI.SmartControl: Loading SETTINGS...
08-10 08:50:42.358  7433  7433 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-10 08:50:42.361  8004  8004 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-10 08:50:42.361  7433  7448 I UEI.SmartControl: ------ IControl API: 11
08-10 08:50:42.362  7433  7448 D UEI.SmartControl: File observer start...
08-10 08:50:42.362  7433  7433 D UEI.SmartControl: Internal service binding...
08-10 08:50:42.362  7433  7448 E UEI.SmartControl: IR Port is disabled: false
08-10 08:50:42.362  7433  7448 D UEI.SmartControl: Starting file observer...
08-10 08:50:42.363  7433  7448 I UEI.SmartControl: Registering callback...
08-10 08:50:42.363  7433  7449 I UEI.SmartControl: ------ IControl API: 19
08-10 08:50:42.365  7433  7449 I UEI.SmartControl: Registering Services Ready callback...
08-10 08:50:42.369  7433  8067 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-10 08:50:42.380  7433  8066 I UEI.SmartControl: Notify AllClients services are ready: 0
08-10 08:50:42.381  8004  8020 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-10 08:50:42.381  8004  8052 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-10 08:50:42.382  8004  8052 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-10 08:50:42.382  8004  8004 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-10 08:50:42.383  8004  8004 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-10 08:50:42.383  7433  7448 I UEI.SmartControl: ------ IControl API: 8
08-10 08:50:42.384  7433  8066 D UEI.SmartControl: -----service ready thread exits
08-10 08:50:42.385  8004  8004 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-10 08:50:42.385  8004  8004 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-10 08:50:42.385  8004  8004 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-10 08:50:42.386  8004  8004 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-10 08:50:42.386  8004  8004 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-10 08:50:42.387  8004  8004 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-10 08:50:42.388  8004  8004 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-10 08:50:42.390  8004  8004 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 08:50:42.390  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-10 08:50:42.391  8004  8004 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 08:50:42.391  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-10 08:50:42.392  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 08:50:42.393  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-10 08:50:42.393  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-10 08:50:42.394  8004  8004 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470811842393]
,08-10 08:50:42.396  8004  8004 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-10 08:50:42.398  1036  1052 I ActivityManager: Killing 7088:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-10 08:50:42.416  8004  8069 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-10 08:50:42.492  1036  2029 W libprocessgroup: failed to open /acct/uid_10005/pid_7088/cgroup.procs: No such file or directory
,08-10 08:50:42.508  8004  8004 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-10 08:50:42.510  8004  8004 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 08:50:42.512  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-10 08:50:42.513  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-10 08:50:42.514  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-10 08:50:42.514  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-10 08:50:42.515  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-10 08:50:42.534  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-10 08:50:42.633  1036  1537 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:42.634  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 08:50:42.635  1036  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:42.636  1036  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:42.637  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 08:50:42.638  1036  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 08:50:42.640  1036  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-10 08:50:42.640  1036  1543 D ConnectivityService: identical MTU - not setting
08-10 08:50:42.641  1036  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-10 08:50:42.641  1036  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-10 08:50:42.641  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:42.641  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:42.643  1036  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:42.644  1602  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-10 08:50:43.681  1036  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=72.5, 0.0, 0.0  rx=70.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1933028449] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 08:50:43.684  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=72.5, 0.0, 0.0  rx=70.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1933028452] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 08:50:43.684  1036  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 08:50:43.707  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 08:50:43.731  1036  1538 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-10 08:50:43.755  1036  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:43.765  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-10 08:50:43.782  1036  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:43.786  1036  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 08:50:43.788  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-10 08:50:43.790  6597  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 08:50:43.790  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 08:50:43.790  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 08:50:43.790  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 08:50:43.790  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 08:50:43.790  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:43.790  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 08:50:43.790  6597  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 08:50:43.791  6597  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 08:50:43.791  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 08:50:43.796  7930  7995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-10 08:50:43.809  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 08:50:43.818  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 08:50:43.819  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:43.819  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 08:50:43.819  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-10 08:50:43.822   311  8084 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 08:50:43.822   311  8084 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-10 08:50:43.823  1036  1051 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-10 08:50:43.824  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:43.824  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:43.824  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-10 08:50:43.824  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:50:43.824  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-10 08:50:43.830  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
,08-10 08:50:43.839  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 06:50:43 GMT], X-Android-Received-Millis=[1470811843838], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470811843824]}
08-10 08:50:43.839  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-10 08:50:43.839  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-10 08:50:43.839  1036  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-10 08:50:43.839  1036  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-10 08:50:43.839  1036  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 08:50:43.839  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:43.839  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 08:50:43.839  1036  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-10 08:50:43.840  1036  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-10 08:50:43.840  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:50:43.840  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:43.840  1036  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:50:43.840  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@920f5ad
08-10 08:50:43.840  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 08:50:43.840  6880  6880 D AppUp4:CustFacade: isPhone : true
08-10 08:50:43.840  1602  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 08:50:43.844  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-10 08:50:43.844  6880  6880 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 08:50:43.848  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:43.848  4353  4353 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 08:50:43.850  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 08:50:43.852  4353  4353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 08:50:43.860  3523  3523 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:43.861   311  8084 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-10 08:50:43.864  3523  3523 V DownloadManager: DownloadService onCreate
08-10 08:50:43.865  4353  8095 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 08:50:43.867  4353  8095 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-10 08:50:43.868  3523  8096 I DownloadManager: in removeSpuriousFiles
08-10 08:50:43.868  3523  8096 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-10 08:50:43.870  3523  8096 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@9bec966 on behalf of 3523
08-10 08:50:43.871  4353  8098 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:43.871  4353  8098 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 08:50:43.871  3523  8096 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-10 08:50:43.871  3523  8096 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-10 08:50:43.872  3523  8096 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-10 08:50:43.872  3523  8096 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-10 08:50:43.872  3523  8096 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-10 08:50:43.872  3523  8096 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-10 08:50:43.872  3523  8096 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-10 08:50:43.872  3523  8096 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-10 08:50:43.872  3523  8096 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-10 08:50:43.872  3523  8096 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-10 08:50:43.872  3523  8096 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-10 08:50:43.873  3523  8096 I DownloadManager: in trimDatabase
08-10 08:50:43.873  3523  8096 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,08-10 08:50:43.876  3523  8096 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@327d04a7 on behalf of 3523
08-10 08:50:43.894  1036  1992 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8100 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-10 08:50:43.908  4353  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,08-10 08:50:43.909  3523  3523 V DownloadManager: DownloadService onStartCommand
08-10 08:50:43.910  4353  4353 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-10 08:50:43.920  4353  4353 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-10 08:50:43.920  4353  4353 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,08-10 08:50:43.921  4353  4353 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-10 08:50:43.924  4353  4353 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-10 08:50:43.926  3523  8097 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-10 08:50:43.928  3523  8097 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2e5e15f2 on behalf of 3523
08-10 08:50:43.931  3523  8097 V DownloadManager: processing inserted download 1
08-10 08:50:43.932  3523  8097 V DownloadManager: processing inserted download 4
,08-10 08:50:43.933  3523  8097 V DownloadManager: processing inserted download 7
08-10 08:50:43.934  3523  8097 V DownloadManager: processing inserted download 8
08-10 08:50:43.935  3523  8097 V DownloadManager: processing inserted download 9
08-10 08:50:43.936  3523  8097 V DownloadManager: processing inserted download 10
08-10 08:50:43.939  3523  8097 V DownloadManager: processing inserted download 11
08-10 08:50:43.940  3523  8097 V DownloadManager: processing inserted download 12
08-10 08:50:43.941  3523  8097 V DownloadManager: processing inserted download 13
08-10 08:50:43.942  3523  8097 V DownloadManager: processing inserted download 14
08-10 08:50:43.944  3523  8097 V DownloadManager: processing inserted download 16
,08-10 08:50:43.947  3523  3523 V DownloadManager: DownloadService onDestroy
08-10 08:50:43.958  8100  8100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 08:50:43.959  8100  8100 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 08:50:43.960  8100  8100 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 08:50:43.960  8100  8100 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-10 08:50:44.019  8100  8100 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-10 08:50:44.029  8100  8100 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-10 08:50:44.058  8100  8100 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-10 08:50:44.081  8100  8100 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:44.081  8100  8100 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:50:44.140  1036  1376 V AlarmManager: ELAPSED_WAKEUP set : Alarm{7145d48 type 2 when 331227 com.google.android.gms} when 331227
,08-10 08:50:44.234  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-10 08:50:44.234  6597  6654 I jxcore-log: 
,08-10 08:50:44.243  8100  8100 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
08-10 08:50:44.304  3462  3462 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 08:50:44.304  3462  3462 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 08:50:44.304  3462  3462 I LgeMiscReceiver: networkInfo.isConnected() = true
08-10 08:50:44.304  3462  3462 D PhoneState: setPdpRejectCasuse : false
,08-10 08:50:44.310  8100  8100 I HubEmail: JNI_OnLoad()
08-10 08:50:44.310  8100  8100 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 08:50:44.310  8100  8100 I HubEmail: registerNatives()
08-10 08:50:44.310  8100  8100 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 08:50:44.310  8100  8100 I HubEmail: registerNativeMethods()
08-10 08:50:44.310  8100  8100 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 08:50:44.312  8100  8100 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-10 08:50:44.315   311  8133 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 08:50:44.315   311  8133 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-10 08:50:44.349   311  8133 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
08-10 08:50:44.349  1036  1993 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8135 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-10 08:50:44.355  8100  8134 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 08:50:44.450  8135  8135 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:44.450  8135  8135 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 08:50:44.453  8135  8135 D PhoneMonitor: Register our PhoneStateListener
,08-10 08:50:44.474  8135  8135 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-10 08:50:44.478  8135  8135 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-10 08:50:44.492  8135  8135 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-10 08:50:44.493  8135  8135 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-10 08:50:44.493  8135  8135 D TelephonyAutoProfiling: [parse] Load xml
08-10 08:50:44.496  8135  8135 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-10 08:50:44.496  8135  8135 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-10 08:50:44.496  8135  8135 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-10 08:50:44.509  8135  8135 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-10 08:50:44.524  1036  1051 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8154 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-10 08:50:44.527  1036  1051 I ActivityManager: Killing 7549:com.google.android.talk/u0a72 (adj 15): empty #17
,08-10 08:50:44.553  7862  8130 V FormManager: There are no updated forms. The schedule will be deleted.
,08-10 08:50:44.557  7862  8130 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,08-10 08:50:44.679  1036  1956 W libprocessgroup: failed to open /acct/uid_10072/pid_7549/cgroup.procs: No such file or directory
08-10 08:50:44.708  1036  1956 I ActivityManager: Killing 7584:com.android.contacts/u0a19 (adj 15): empty #17
,08-10 08:50:44.830  1036  1052 W libprocessgroup: failed to open /acct/uid_10019/pid_7584/cgroup.procs: No such file or directory
,08-10 08:50:44.853  1815  8178 I CheckinService: active receiver: enabled
,08-10 08:50:44.880  1815  8178 I CheckinService: Preparing to send checkin request
,08-10 08:50:44.881  1815  8178 I EventLogService: Accumulating logs since 1470811823827
08-10 08:50:44.888  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-10 08:50:44.888  6597  6654 I jxcore-log: 
08-10 08:50:44.911  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-10 08:50:44.911  6597  6654 I jxcore-log: 
,08-10 08:50:44.931  1036  1993 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8180 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-10 08:50:44.933  1036  1993 I ActivityManager: Killing 7604:com.android.gallery3d/u0a27 (adj 15): empty #17
08-10 08:50:44.940   311  8195 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 08:50:44.940   311  8195 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-10 08:50:44.971   311  8195 D libc-netbsd: res_queryN name = www.google.com succeed
,08-10 08:50:44.976   311  8199 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-10 08:50:44.976   311  8199 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-10 08:50:44.976   311  8199 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-10 08:50:44.986  1036  1539 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-10 08:50:45.033  1036  1574 W libprocessgroup: failed to open /acct/uid_10027/pid_7604/cgroup.procs: No such file or directory
,08-10 08:50:45.053  1815  8178 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-10 08:50:45.159  1036  1717 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8201 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 08:50:45.162  1036  1717 I ActivityManager: Killing 7623:com.android.vending/u0a44 (adj 15): empty #17
,08-10 08:50:45.351  1036  2030 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8218 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a,
,08-10 08:50:45.360  1036  2048 W libprocessgroup: failed to open /acct/uid_10044/pid_7623/cgroup.procs: No such file or directory
,08-10 08:50:45.430  8218  8218 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-10 08:50:45.430  8201  8201 I art     : Almond Protected OAT
08-10 08:50:45.430  8218  8218 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-10 08:50:45.459  8218  8218 I MultiDex: VM with version 2.1.0 has multidex support
08-10 08:50:45.459  8218  8218 I MultiDex: install
08-10 08:50:45.459  8218  8218 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-10 08:50:45.469  8218  8218 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-10 08:50:45.504  8201  8201 D WeatherApplication: removeAccount
08-10 08:50:45.505  8201  8201 D WeatherApplication: Account.length = 0
,08-10 08:50:45.505  8201  8201 E WeatherApplication: OPERATOR:OPEN
08-10 08:50:45.509  8201  8201 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:45
08-10 08:50:45.512  8201  8201 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 08:50:45.512  8201  8201 D Weather.Utils: 2 : All the weather widget is gone.
08-10 08:50:45.514  8201  8201 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 08:50:45.516  8201  8201 D WeatherAncestor: connectivity changed - connection : true
08-10 08:50:45.517  8201  8201 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-10 08:50:45.525  8201  8201 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 08:50:45.525  8201  8201 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 08:50:45.525  8201  8201 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-10 08:50:45.542  8201  8201 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 08:50:45.542  8201  8201 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:50:45
,08-10 08:50:45.571  1036  2030 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8245 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 08:50:45.571  1036  2030 I ActivityManager: Killing 7673:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-10 08:50:45.659  1036  1972 W libprocessgroup: failed to open /acct/uid_10080/pid_7673/cgroup.procs: No such file or directory
,08-10 08:50:45.739   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 08:50:45.739   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 08:50:45.739   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
,08-10 08:50:45.739  8245  8264 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 08:50:45.744   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 08:50:45.744   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 08:50:45.745   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 08:50:45.745  8245  8264 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 08:50:45.752   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-10 08:50:45.752   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 08:50:45.752   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 08:50:45.754  8245  8268 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 08:50:45.756   278   352 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 08:50:45.756   278   352 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 08:50:45.756   278   352 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 08:50:45.756  8245  8268 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 08:50:45.761  8218  8237 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:45.761  8218  8237 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:50:45.816  8270  8270 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-10 08:50:45.895  8270  8270 I dex2oat : dex2oat took 78.649ms (threads: 4)
,08-10 08:50:45.905  8218  8237 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 08:50:45.905  8218  8237 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 08:50:45.905  8218  8237 I Adreno-EGL: Build Date: 12/12/14 금
08-10 08:50:45.905  8218  8237 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 08:50:45.905  8218  8237 I Adreno-EGL: Remote Branch: 
08-10 08:50:45.905  8218  8237 I Adreno-EGL: Local Patches: 
08-10 08:50:45.905  8218  8237 I Adreno-EGL: Reconstruct Branch: 
08-10 08:50:45.932  1036  1972 I art     : Explicit concurrent mark sweep GC freed 80298(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.626ms total 99.074ms
,08-10 08:50:45.960  8245  8245 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 08:50:45.980  8245  8245 I LibraryLoader: Loading: webviewchromium
08-10 08:50:45.986  8245  8245 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 3079-3087)
08-10 08:50:45.986  8245  8245 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 08:50:45.988  8218  8237 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 08:50:45.988  8218  8237 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 08:50:45.988  8218  8237 I Adreno-EGL: Build Date: 12/12/14 금
08-10 08:50:45.988  8218  8237 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 08:50:45.988  8218  8237 I Adreno-EGL: Remote Branch: 
08-10 08:50:45.988  8218  8237 I Adreno-EGL: Local Patches: 
08-10 08:50:45.988  8218  8237 I Adreno-EGL: Reconstruct Branch: 
,08-10 08:50:45.994  8245  8245 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cd9fe8c}
08-10 08:50:45.996  8245  8245 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 08:50:45.997  8245  8245 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 08:50:46.009  8245  8245 I BrowserStartupController: Initializing chromium process, renderers=0
08-10 08:50:46.010  8245  8245 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 08:50:46.025  8245  8245 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 08:50:46.026  8245  8245 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-10 08:50:46.027  8245  8245 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-10 08:50:46.029  8218  8237 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 08:50:46.029  8218  8237 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 08:50:46.029  8218  8237 I Adreno-EGL: Build Date: 12/12/14 금
08-10 08:50:46.029  8218  8237 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 08:50:46.029  8218  8237 I Adreno-EGL: Remote Branch: 
08-10 08:50:46.029  8218  8237 I Adreno-EGL: Local Patches: 
08-10 08:50:46.029  8218  8237 I Adreno-EGL: Reconstruct Branch: 
08-10 08:50:46.030   315   315 V AudioPolicyService: registerClient() client 0xb558aba0, uid 10093
08-10 08:50:46.032  8245  8296 W AudioManagerAndroid: Requires BLUETOOTH permission
08-10 08:50:46.050  8245  8245 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 08:50:46.050  8245  8245 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 08:50:46.050  8245  8245 I Adreno-EGL: Build Date: 12/12/14 금
08-10 08:50:46.050  8245  8245 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 08:50:46.050  8245  8245 I Adreno-EGL: Remote Branch: 
08-10 08:50:46.050  8245  8245 I Adreno-EGL: Local Patches: 
08-10 08:50:46.050  8245  8245 I Adreno-EGL: Reconstruct Branch: 
,08-10 08:50:46.122  8245  8245 I NSApplication: Starting up...
,08-10 08:50:46.142  1036  1052 I ActivityManager: Killing 7308:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-10 08:50:46.314  1036  1717 W libprocessgroup: failed to open /acct/uid_10037/pid_7308/cgroup.procs: No such file or directory
,08-10 08:50:46.334  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-10 08:50:46.334  6597  6654 I jxcore-log: 
,08-10 08:50:46.343   311  8311 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 08:50:46.343   311  8311 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-10 08:50:46.343   311  8311 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-10 08:50:46.344  8004  8004 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-10 08:50:46.345  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3591
08-10 08:50:46.350   311  8313 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 08:50:46.350   311  8313 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-10 08:50:46.357  2210  2210 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-10 08:50:46.372  2210  2210 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-10 08:50:46.373  2210  2210 D c       : Getting all permits...
08-10 08:50:46.373  2210  2210 D a       : Opening database...
08-10 08:50:46.379  2210  2210 D a       : Opening database auth.proximity.permit_store...
08-10 08:50:46.380  2210  2210 D a       : Closing database...
08-10 08:50:46.383   311  8313 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-10 08:50:46.545  1815  8178 I CheckinTask: Sending checkin request (7927 bytes)
,08-10 08:50:46.567  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-10 08:50:46.567  6597  6654 I jxcore-log: 
,08-10 08:50:46.572  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-10 08:50:46.572  6597  6654 I jxcore-log: 
08-10 08:50:46.587  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-10 08:50:46.587  6597  6654 I jxcore-log: 
,08-10 08:50:46.590  2210  8320 D GCM     : Connected
08-10 08:50:46.591  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-10 08:50:46.591  6597  6654 I jxcore-log: 
,08-10 08:50:46.615  2210  8320 D GCM     : Message class com.google.e.a.a.q
,08-10 08:50:46.713  1036  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=41.2, 0.0, 0.0  rx=38.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1933031481] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 08:50:46.714  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=41.2, 0.0, 0.0  rx=38.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1933031482] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 08:50:46.714  1036  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 08:50:46.763  1815  8178 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-10 08:50:46.770  1815  8178 I CheckinService: active receiver: disabled
,08-10 08:50:46.798  2210  2210 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-10 08:50:46.810  2210  2210 I GCM     : GCM config loaded
,08-10 08:50:46.827  8135  8135 V SetupWizard: Connected to Gservices successfully
,08-10 08:50:47.349  7433  8068 D UEI.SmartControl: Internal timer expired: 2
08-10 08:50:47.349  7433  8068 D UEI.SmartControl: unbind internal service
,08-10 08:50:47.435  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-10 08:50:47.435  6597  6654 I jxcore-log: 
,08-10 08:50:47.453  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-10 08:50:47.453  6597  6654 I jxcore-log: 
,08-10 08:50:47.467  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-10 08:50:47.467  6597  6654 I jxcore-log: 
08-10 08:50:47.475  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-10 08:50:47.475  6597  6654 I jxcore-log: 
,08-10 08:50:47.499  7433  8062 D serial_port: close(fd = 24)
,08-10 08:50:47.529  7433  8062 I UEI.SmartControl: Serial port is closed.
,08-10 08:50:47.537  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-10 08:50:47.537  6597  6654 I jxcore-log: 
08-10 08:50:47.614  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-10 08:50:47.614  6597  6654 I jxcore-log: 
,08-10 08:50:47.627  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-10 08:50:47.627  6597  6654 I jxcore-log: 
,08-10 08:50:47.751  1036  3587 I LocationManagerService: remove 31a72119
,08-10 08:50:47.758  1036  3587 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-10 08:50:47.758  1036  3587 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 08:50:47.759  1036  3587 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-10 08:50:47.760  1036  3587 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-10 08:50:47.761  1036  3587 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-10 08:50:47.852  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-10 08:50:47.852  6597  6654 I jxcore-log: 
,08-10 08:50:47.879  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-10 08:50:47.879  6597  6654 I jxcore-log: 
,08-10 08:50:47.885  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-10 08:50:47.885  6597  6654 I jxcore-log: 
,08-10 08:50:47.890  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-10 08:50:47.890  6597  6654 I jxcore-log: 
,08-10 08:50:47.908  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-10 08:50:47.908  6597  6654 I jxcore-log: 
,08-10 08:50:47.989  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-10 08:50:47.989  6597  6654 I jxcore-log: 
,08-10 08:50:48.003  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-10 08:50:48.003  6597  6654 I jxcore-log: 
,08-10 08:50:48.032  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-10 08:50:48.032  6597  6654 I jxcore-log: 
,08-10 08:50:48.045  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-10 08:50:48.045  6597  6654 I jxcore-log: 
,08-10 08:50:48.062  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-10 08:50:48.062  6597  6654 I jxcore-log: 
,08-10 08:50:48.097  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-10 08:50:48.097  6597  6654 I jxcore-log: 
,08-10 08:50:48.103  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-10 08:50:48.103  6597  6654 I jxcore-log: 
08-10 08:50:48.307  6597  6654 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-10 08:50:48.307  6597  6654 I jxcore-log: 
,08-10 08:50:48.316  6597  6654 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-10 08:50:48.317  6597  6654 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-10 08:50:48.317  6597  6654 I jxcore-log: 
08-10 08:50:48.361  6597  6654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 08:50:48.361  6597  6654 I jxcore-log: 
,08-10 08:50:49.721  1036  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=43.1, 0.0, 0.0  rx=37.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1933034489] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 08:50:49.722  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=43.1, 0.0, 0.0  rx=37.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1933034490] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 08:50:49.722  1036  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 08:50:50.756  8245  8266 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-10 08:50:51.321  1036  1051 I ActivityManager: Killing 6765:com.lge.settings.easy/1000 (adj 15): empty #17
,08-10 08:50:51.353  1036  1574 W libprocessgroup: failed to open /acct/uid_1000/pid_6765/cgroup.procs: No such file or directory
,08-10 08:50:52.744  1036  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=26.6, 0.0, 0.0  rx=22.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1933037512] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 08:50:52.747  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=26.6, 0.0, 0.0  rx=22.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1933037515] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 08:50:52.747  1036  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 08:50:54.955  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-10 08:50:54.999  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-10 08:50:55.013  1036  1036 D administrator: Handling package changes for user 0
,08-10 08:50:55.077  1036  1405 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 08:50:55.099  1036  1103 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8348 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-10 08:50:55.105  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-10 08:50:55.107  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-10 08:50:55.109   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 9.719ms
08-10 08:50:55.118   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 8.777ms
08-10 08:50:55.127   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 180us total 8.623ms
,08-10 08:50:55.131  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 08:50:55.155  8348  8348 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-10 08:50:55.166  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-10 08:50:55.167  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-10 08:50:55.202  1036  1100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 08:50:55.206  1036  1100 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-10 08:50:55.212  2480  2480 V GmsNetworkLocationProvi: DISABLE
08-10 08:50:55.219  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-10 08:50:55.242  2480  2480 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-10 08:50:55.247  8348  8348 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:55.247  8348  8348 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:50:55.296  1036  1100 D LocationProviderProxy: applying state to connected service
08-10 08:50:55.312  2210  2366 I art     : Explicit concurrent mark sweep GC freed 7234(471KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 1.464ms total 32.336ms
,08-10 08:50:55.402  8348  8392 I Babel   : MmsConfig: mnc/mcc: 0/0
08-10 08:50:55.402  8348  8392 I Babel   : MmsConfig.loadMmsSettings
08-10 08:50:55.409  8348  8392 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-10 08:50:55.409  8348  8392 I Babel   : MmsConfig.loadFromDatabase
,08-10 08:50:55.433  8348  8392 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-10 08:50:55.433  8348  8392 I Babel   : MmsConfig.loadFromResources
08-10 08:50:55.435  8348  8392 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-10 08:50:55.436  8348  8392 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-10 08:50:55.437  8348  8348 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 08:50:55.459  8348  8390 W AudioCapabilities: Unsupported mime audio/evrc
,08-10 08:50:55.461  8348  8390 W AudioCapabilities: Unsupported mime audio/qcelp
08-10 08:50:55.467  8348  8390 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-10 08:50:55.471  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
08-10 08:50:55.472  1815  8394 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-10 08:50:55.473  1815  8394 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-10 08:50:55.475  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@920f5ad
08-10 08:50:55.475  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 08:50:55.475  6880  6880 D AppUp4:CustFacade: isPhone : true
08-10 08:50:55.475  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-10 08:50:55.475  6880  6880 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-10 08:50:55.510  8348  8390 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-10 08:50:55.514  8348  8390 W AudioCapabilities: Unsupported mime audio/qcelp
,08-10 08:50:55.514  1036  1992 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8397 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-10 08:50:55.520  8348  8390 W AudioCapabilities: Unsupported mime audio/evrc
08-10 08:50:55.522  1036  2030 I ActivityManager: Killing 7912:com.lge.bnr/1000 (adj 15): empty #17
08-10 08:50:55.529  1815  4777 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-10 08:50:55.542  8348  8390 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-10 08:50:55.545  8348  8390 W VideoCapabilities: Unsupported mime video/divx
08-10 08:50:55.548  8348  8390 W VideoCapabilities: Unsupported mime video/divx311
08-10 08:50:55.550  8348  8390 W VideoCapabilities: Unsupported mime video/divx4
08-10 08:50:55.556  8348  8390 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-10 08:50:55.573  8348  8390 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-10 08:50:55.576  8348  8390 W AudioCapabilities: Unsupported mime audio/eac3
08-10 08:50:55.577  8348  8390 W AudioCapabilities: Unsupported mime audio/ac3
08-10 08:50:55.578  8348  8390 W AudioCapabilities: Unsupported mime audio/g726
08-10 08:50:55.579  8348  8390 W AudioCapabilities: Unsupported mime audio/wma-voice
08-10 08:50:55.580  8348  8390 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-10 08:50:55.581  8348  8390 W AudioCapabilities: Unsupported mime audio/adpcm
08-10 08:50:55.584  8348  8390 W VideoCapabilities: Unsupported mime video/theora
,08-10 08:50:55.585  8348  8390 W VideoCapabilities: Unsupported mime video/mjpg
,08-10 08:50:55.604  1036  1717 W libprocessgroup: failed to open /acct/uid_1000/pid_7912/cgroup.procs: No such file or directory
08-10 08:50:55.640  8397  8397 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 08:50:55.641  8397  8397 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 08:50:55.641  8397  8397 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-10 08:50:55.642  8397  8397 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-10 08:50:55.643  8397  8397 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 08:50:55.699  8397  8397 I SystemConfig: BUILD Country: EU
08-10 08:50:55.700  8397  8397 I SystemConfig: BUILD Operator: OPEN
,08-10 08:50:55.764  1036  1993 I ActivityManager: Killing 7884:com.lge.sync/1000 (adj 15): empty #17
,08-10 08:50:55.772  1036  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=13.8, 0.0, 0.0  rx=11.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1933040540] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 08:50:55.773  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=13.8, 0.0, 0.0  rx=11.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1933040541] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 08:50:55.773  1036  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 08:50:55.831  1036  1992 W libprocessgroup: failed to open /acct/uid_1000/pid_7884/cgroup.procs: No such file or directory
,08-10 08:50:55.841  8397  8418 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-10 08:50:55.841  8397  8418 I SystemConfig: existFile = false
08-10 08:50:55.841  8397  8418 I SystemConfig: canReadFile = false
08-10 08:50:55.841  8397  8418 I SystemConfig: systemFeature RCS result false
08-10 08:50:55.841  8397  8418 D SystemConfig: refreshRcsSupport() :false
08-10 08:50:55.908  1036  1052 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8420 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-10 08:50:55.983  8420  8420 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 08:50:55.983  8420  8420 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-10 08:50:55.983  8420  8420 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-10 08:50:55.984  8420  8420 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 08:50:56.090  8420  8420 I AppConfig: Total System Memory = 2995761152
,08-10 08:50:56.102  8420  8420 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-10 08:50:56.225  1036  1717 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8442 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 08:50:56.226  1036  1717 I ActivityManager: Killing 6678:com.android.settings/1000 (adj 15): empty #17
,08-10 08:50:56.294  1036  1574 W libprocessgroup: failed to open /acct/uid_1000/pid_6678/cgroup.procs: No such file or directory
,08-10 08:50:56.536  8442  8442 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-10 08:50:56.654  8442  8442 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:50:56.654  8442  8442 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:50:56.723  8442  8442 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-10 08:50:56.746  8442  8442 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-10 08:50:56.747  8442  8442 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-10 08:50:56.763  8442  8442 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-10 08:50:56.763  8442  8442 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-10 08:50:56.786  1036  1936 I ActivityManager: Killing 8100:com.lge.email/u0a23 (adj 15): empty #17
,08-10 08:50:56.896  1036  1972 W libprocessgroup: failed to open /acct/uid_10023/pid_8100/cgroup.procs: No such file or directory
,08-10 08:50:56.908  3523  3539 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-10 08:50:56.914  4631  8488 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-10 08:50:56.914  3523  3539 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@38caaac0 on behalf of 8442
,08-10 08:50:56.969  1036  1936 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8489 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-10 08:50:56.999  8442  8442 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-10 08:50:57.026  8442  8442 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-10 08:50:57.050  8489  8489 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-10 08:50:57.081  8489  8489 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-10 08:50:57.082  8489  8489 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-10 08:50:57.082  8489  8489 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-10 08:50:57.082  8489  8489 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-10 08:50:57.082  8489  8489 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-10 08:50:57.082  8489  8489 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-10 08:50:57.101  1036  1936 I ActivityManager: Killing 7862:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-10 08:50:57.132  1036  1972 W libprocessgroup: failed to open /acct/uid_10026/pid_7862/cgroup.procs: No such file or directory
,08-10 08:50:57.309  1036  1956 V SIM_STK : Menu title from STK is T-Mobile
,08-10 08:50:57.322  4631  8488 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 408 ms] updated apps [took 408 ms] 
,08-10 08:50:58.786  1036  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=6.9, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1933043554] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 08:50:58.797  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=6.9, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1933043564] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 08:50:58.797  1036  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 08:50:59.724  8004  8004 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-10 08:50:59.725  8004  8004 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3591
,08-10 08:51:00.039  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 08:51:00.040  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 08:51:00.042  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-10 08:51:00.042  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-10 08:51:00.044  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 08:51:00.044  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-10 08:51:00.044  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-10 08:51:00.045  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 08:51:01.816  1036  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1933046584] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 08:51:01.833  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:1933046599] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 08:51:01.833  1036  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 08:51:03.673  1036  1537 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 08:51:03.674  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 08:51:03.675  1036  1537 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 08:51:03.677  1036  1537 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 08:51:03.678  1036  1537 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-10 08:51:03.690  1036  1537 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 08:51:04.008  1036  2048 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-10 08:51:04.012  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:51:04.012  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:51:04.012  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-10 08:51:04.012  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 08:51:04.012  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-10 08:51:04.027  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 06:51:04 GMT], X-Android-Received-Millis=[1470811864026], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470811864022]}
08-10 08:51:04.027  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-10 08:51:04.027  1036  7953 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-10 08:51:04.032  1036  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-10 08:51:04.032  1036  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,08-10 08:51:04.032  1036  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 08:51:04.032  1036  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:51:04.032  1036  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 08:51:04.032  1036  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-10 08:51:04.033  1036  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-10 08:51:04.033  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 08:51:04.033  1036  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:51:04.033  1036  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 08:51:04.034  1602  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 08:51:04.852  1036  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1933049619] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 08:51:04.855  1036  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1933049622] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 08:51:04.855  1036  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 08:51:05.694  6597  6654 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-10 08:51:05.694  6597  6654 I jxcore-log: 
,08-10 08:51:06.034  8530  8530 D AndroidRuntime: 
08-10 08:51:06.034  8530  8530 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-10 08:51:06.040  8530  8530 D AndroidRuntime: CheckJNI is OFF
08-10 08:51:06.166  8530  8530 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-10 08:51:06.177  1036  1103 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-10 08:51:06.177  1036  1103 I ActivityManager: Killing 6597:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-10 08:51:06.249  1036  1717 I WindowState: WIN DEATH: Window{3927aca4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 08:51:06.249  1036  1542 D WifiService: Client connection lost with reason: 4
08-10 08:51:06.256  1036  1717 D InputDispatcher: Window went away: Window{3927aca4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 08:51:06.412  1036  1103 I ActivityManager:   Force finishing activity ActivityRecord{387e9329 u0 com.test.thalitest/.MainActivity t6}
,08-10 08:51:06.460   338   356 E GBMv2   : DFP En is all cleared set to be enabled
08-10 08:51:06.462  1036  1920 W ActivityManager: Spurious death for ProcessRecord{33781696 6597:com.test.thalitest/u0a118}, curProc for 6597: null
,08-10 08:51:06.463  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-10 08:51:06.475  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{387e9329 u0 com.test.thalitest/.MainActivity t6 f}
08-10 08:51:06.476  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{387e9329 u0 com.test.thalitest/.MainActivity t6 f}
,08-10 08:51:06.520  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-10 08:51:06.520  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{30b9b9fe co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-10 08:51:06.523  2031  2031 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-10 08:51:06.524  1939  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-10 08:51:06.524  1939  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2e33c55f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-10 08:51:06.524  2031  2031 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-10 08:51:06.529  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-10 08:51:06.531  1036  1100 W InputMethodInfo: Duplicated subtype definition found: , voice
08-10 08:51:06.533  1036  1405 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 08:51:06.561  3838  3838 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-10 08:51:06.562  7504  7504 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-10 08:51:06.562  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-10 08:51:06.563  1994  1994 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-10 08:51:06.569  2480  2679 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-10 08:51:06.579  4631  4631 I art     : Explicit concurrent mark sweep GC freed 15491(888KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 554us total 58.412ms
,08-10 08:51:06.624  1036  1885 V SIM_STK : Menu title from STK is T-Mobile
,08-10 08:51:06.628  1036  1036 I art     : Explicit concurrent mark sweep GC freed 43923(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.711ms total 126.048ms
08-10 08:51:06.629  1036  1124 I art     : WaitForGcToComplete blocked for 109.180ms for cause Explicit
08-10 08:51:06.634  4528  4528 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-10 08:51:06.634  7930  7930 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-10 08:51:06.635  4528  4528 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-10 08:51:06.635  4528  4528 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-10 08:51:06.635  4528  4528 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-10 08:51:06.635  4528  4528 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 08:51:06.635  4528  4528 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 08:51:06.635  4528  4528 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 08:51:06.635  4528  4528 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 08:51:06.635  4528  4528 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 08:51:06.635  4528  4528 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 08:51:06.635  4528  4528 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 08:51:06.635  4528  4528 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 08:51:06.636  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-10 08:51:06.636  2031  2137 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-10 08:51:06.671  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-10 08:51:06.682  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-10 08:51:06.686  1903  1903 D ActionManagerService: notifyUserLog: 1000003
08-10 08:51:06.686  3838  4517 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-10 08:51:06.687  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-10 08:51:06.693  2031  2031 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-10 08:51:06.699  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-10 08:51:06.699  2210  2210 I ConfigService: onCreate
08-10 08:51:06.700  1867  1867 D SplitUIService: removed split : 
,08-10 08:51:06.702  2031  2031 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-10 08:51:06.704  2210  2210 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-10 08:51:06.704  2031  2031 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-10 08:51:06.704  1602  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 08:51:06.704  1602  1652 D KeyguardModel: createShortcutInfo...
08-10 08:51:06.706  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-10 08:51:06.710  2210  2210 I ConfigService: onBind returning update interface
,08-10 08:51:06.716  1036  2048 V SIM_STK : Menu title from STK is T-Mobile
08-10 08:51:06.716  1036  2048 V SIM_STK : Menu title from STK is T-Mobile
08-10 08:51:06.717  1903  1903 D ActionManagerService: notifyUserLog: 1000004
08-10 08:51:06.717  3838  4517 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-10 08:51:06.717  1602  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 08:51:06.717  1602  1652 D KeyguardModel: createShortcutInfo...
08-10 08:51:06.718  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-10 08:51:06.719  2210  2210 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-10 08:51:06.719  2210  2210 I ConfigService: onBind returning config service
,08-10 08:51:06.720  3838  3854 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 08:51:06.723  2210  2210 I ConfigService: onDestroy
08-10 08:51:06.725  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-10 08:51:06.725  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , create_time: 1430832262123
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , expire_time: 0
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , display: false
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , animation: false }
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , create_time: 1430832262287
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , expire_time: 0
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , display: false
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , animation: false }
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , create_time: 1470393743569
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , expire_time: 0
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , display: false
08-10 08:51:06.726  2031  2031 I GBoardWebViewUtils: , animation: false }
,08-10 08:51:06.733  2031  8564 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-10 08:51:06.742  1036  1036 D administrator: Handling package changes for user 0
,08-10 08:51:06.747  1815  8565 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-10 08:51:06.754  1602  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-10 08:51:06.754  1602  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 08:51:06.755  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-10 08:51:06.755  1867  1867 I SplitUIService: split app #11
,08-10 08:51:06.758  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-10 08:51:06.759  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-10 08:51:06.759  1036  1936 V SIM_STK : Menu title from STK is T-Mobile
08-10 08:51:06.760  1602  1652 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-10 08:51:06.761  1602  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 08:51:06.770  1602  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 08:51:06.770  1602  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-10 08:51:06.773  1602  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 08:51:06.773  1602  1652 D KeyguardModel: createShortcutInfo...
08-10 08:51:06.778  1602  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-10 08:51:06.778  1602  1652 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 08:51:06.783  1602  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 08:51:06.783  1602  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-10 08:51:06.784  1036  1993 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-10 08:51:06.784  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-10 08:51:06.784  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-10 08:51:06.784  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-10 08:51:06.784  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 08:51:06.784  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 08:51:06.784  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 08:51:06.784  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 08:51:06.784  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 08:51:06.785  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-10 08:51:06.785  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 08:51:06.785  7504  7504 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-10 08:51:06.786  1602  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 08:51:06.786  1602  1652 D KeyguardModel: createShortcutInfo...
08-10 08:51:06.798  1602  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 08:51:06.798  1602  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-10 08:51:06.798  1602  1652 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-10 08:51:06.798  1602  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 08:51:06.799  1602  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 08:51:06.800  1602  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-10 08:51:06.801  1602  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 08:51:06.801  1602  1652 D KeyguardModel: createShortcutInfo...
08-10 08:51:06.808  1815  8573 I PeopleContactsSync: CP2 sync disabled
08-10 08:51:06.813  5930  8572 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-10 08:51:06.813  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-10 08:51:06.813  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-10 08:51:06.833  1815  4777 I Icing   : doRemovePackageData com.test.thalitest
,08-10 08:51:06.843  2031  2031 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-10 08:51:06.845   330   418 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-10 08:51:06.846  3208  8575 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-10 08:51:06.849  1602  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 08:51:06.849  1602  1652 D KeyguardModel: createShortcutInfo...
08-10 08:51:06.850  1602  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 08:51:06.850  1602  1652 D KeyguardModel: createShortcutInfo...
08-10 08:51:06.851  1602  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 08:51:06.851  1602  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-10 08:51:06.852  1602  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 08:51:06.852  1602  1652 D KeyguardModel: createShortcutInfo...
08-10 08:51:06.853  1602  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 08:51:06.853  1602  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-10 08:51:06.854  1602  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 08:51:06.854  1602  1652 D KeyguardModel: createShortcutInfo...
08-10 08:51:06.855  1602  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 08:51:06.855  1602  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-10 08:51:06.856  1602  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 08:51:06.856  1602  1652 D KeyguardModel: createShortcutInfo...
08-10 08:51:06.860  6880  6880 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-10 08:51:06.867  1815  8571 W GmsApplication: Using Auth Proxy for data requests.
08-10 08:51:06.873  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-10 08:51:06.873  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-10 08:51:06.874  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 08:51:06.875  2338  8577 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-10 08:51:06.898  1036  1780 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8578 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-10 08:51:06.907  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-10 08:51:06.907  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-10 08:51:06.907  1036  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-10 08:51:06.913  1815  8571 W GmsApplication: Using Auth Proxy for data requests.
,08-10 08:51:06.930  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-10 08:51:06.933  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 08:51:06.934  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-10 08:51:06.936  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-10 08:51:06.937  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-10 08:51:06.938  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-10 08:51:06.955  8578  8578 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 08:51:06.956  8578  8578 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 08:51:06.956  8578  8578 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 08:51:06.957  8578  8578 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-10 08:51:06.968  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-10 08:51:06.968  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 08:51:06.969  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{905ed29 u0 com.lge.launcher2/.Launcher t5} time:354070
,08-10 08:51:06.975  2031  2160 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-10 08:51:06.975  2031  2160 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-10 08:51:06.979  1036  1124 I art     : Explicit concurrent mark sweep GC freed 11406(766KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.028ms total 332.052ms
08-10 08:51:06.983  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-10 08:51:06.983  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-10 08:51:06.984  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-10 08:51:06.991  2031  2031 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-10 08:51:06.992  2594  2594 D [Concierge]Service: onStartCommand(). Type : 8
08-10 08:51:06.992  2594  2594 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-10 08:51:06.992  2594  2594 D [Concierge]Service: Update widget ID : 11
08-10 08:51:06.995  2031  2031 D [Concierge]WidgetView: change position of spinner
08-10 08:51:06.996  2594  2594 D [Concierge]Service: onStartCommand(). Type : 0
,08-10 08:51:06.997  2031  2031 I [Concierge]WidgetView: initWebView(). Time : 1470811866997
08-10 08:51:07.009  8578  8578 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-10 08:51:07.016  2031  2031 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 762326910
08-10 08:51:07.016  2031  2031 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-10 08:51:07.016  2031  2031 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-10 08:51:07.019  2031  2031 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@30053114
08-10 08:51:07.019  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-10 08:51:07.020  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-10 08:51:07.020  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 08:51:07.024  8578  8578 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-10 08:51:07.024  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-10 08:51:07.025  2031  2031 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-10 08:51:07.025  2031  2031 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-10 08:51:07.025  2031  2031 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470811540757, New one : 1470811866997
08-10 08:51:07.025  2031  2031 D [Concierge]WidgetView: Unregister all receivers
08-10 08:51:07.025  2031  2031 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-10 08:51:07.026  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 08:51:07.027  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-10 08:51:07.029  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-10 08:51:07.030  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-10 08:51:07.031  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-10 08:51:07.032  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-10 08:51:07.037  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 08:51:07.037  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 08:51:07.047  8578  8578 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-10 08:51:07.057  1815  8596 I art     : Explicit concurrent mark sweep GC freed 39960(2MB) AllocSpace objects, 27(424KB) LOS objects, 51% free, 30MB/62MB, paused 1.319ms total 55.438ms
08-10 08:51:07.061  1815  1826 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-10 08:51:07.062  1815  1826 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-10 08:51:07.062  1815  1826 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-10 08:51:07.074  2031  2031 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-10 08:51:07.080  1036  1100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 08:51:07.082  2031  2031 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-10 08:51:07.084  1036  1100 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-10 08:51:07.087  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-10 08:51:07.089  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 08:51:07.101  8578  8578 D LgDataFeature: LgDataFeature() Constructor: none
08-10 08:51:07.101  8578  8578 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 08:51:07.106  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-10 08:51:07.109  2031  2031 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@75ef2c6 time:354210
08-10 08:51:07.115  8530  8530 D AndroidRuntime: Shutting down VM
,08-10 08:51:07.151  8578  8578 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-10 08:51:07.159  1036  1956 I ActivityManager: Killing 8154:com.android.chrome/u0a57 (adj 15): empty #17
08-10 08:51:07.222  2031  2031 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-10 08:51:07.240  1994  1994 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-10 08:51:07.240  1994  1994 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-10 08:51:07.240  1036  1780 W libprocessgroup: failed to open /acct/uid_10057/pid_8154/cgroup.procs: No such file or directory
,08-10 08:51:07.242  1994  1994 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-10 08:51:07.244  7930  7930 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-10 08:51:07.260  2031  2884 I GBoardtInterface: onReloaded()
,08-10 08:51:07.262  2031  2031 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-10 08:51:07.264  1036  1717 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8603 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-10 08:51:07.266  3838  3854 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 08:51:07.268  3838  4513 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 08:51:07.273  1903  1903 D ActionManagerService: notifyUserLog: 1000001
,08-10 08:51:07.274  3838  4517 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-10 08:51:07.275  3838  4517 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-10 08:51:07.277  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-10 08:51:07.278  3838  4517 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-10 08:51:07.278  3838  4517 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-10 08:51:07.278  3838  4517 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-10 08:51:07.278  3838  4517 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-10 08:51:07.279  3838  3854 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 08:51:07.281  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-10 08:51:07.281  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-10 08:51:07.282  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-10 08:51:07.282  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-10 08:51:07.285  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-10 08:51:07.285  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-10 08:51:07.321  8603  8603 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-10 08:51:07.322  8603  8603 W LG Account v2.2: No ProfileInfo entries
08-10 08:51:07.322  8603  8603 I LG Account v2.2: isEnabled: false
,08-10 08:51:07.322  8603  8603 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-10 08:51:07.322  8603  8603 I Feature : [Lifetracker]Country: EU
08-10 08:51:07.322  8603  8603 I Feature : [Lifetracker]Operator: OPEN
08-10 08:51:07.322  8603  8603 I Feature : [Lifetracker]Ranking support: false
08-10 08:51:07.322  8603  8603 I Feature : [Lifetracker]Comfort support: false
08-10 08:51:07.322  8603  8603 I Feature : [Lifetracker]Accessory: true
08-10 08:51:07.322  8603  8603 I Feature : [Lifetracker]Health device: true
08-10 08:51:07.322  8603  8603 I Feature : [Lifetracker]Extra Pedometer: false
08-10 08:51:07.322  8603  8603 I Feature : [Lifetracker]Blood glucose device: false
08-10 08:51:07.322  8603  8603 I Feature : [Lifetracker]Device Number: 3
08-10 08:51:07.324  8603  8603 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-10 08:51:07.353  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8625 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-10 08:51:07.382  1036  1956 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8643 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 08:51:07.383  1036  1956 I ActivityManager: Killing 8180:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-10 08:51:07.467  1036  1993 W libprocessgroup: failed to open /acct/uid_10062/pid_8180/cgroup.procs: No such file or directory
08-10 08:51:07.491  8643  8643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 08:51:07.491  8643  8643 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-10 08:51:07.491  8643  8643 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 08:51:07.491  8643  8643 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-10 08:51:07.493  8643  8643 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 08:51:07.493  8643  8643 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.

```
