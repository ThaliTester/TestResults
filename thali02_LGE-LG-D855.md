#### Test 79751015a5ad772_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-10 17:07:00.107  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
08-10 17:07:00.116  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:07:00.117  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:07:00.119  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:07:00.121  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 17:07:08.723  6674  6674 D AndroidRuntime: 
08-10 17:07:08.723  6674  6674 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-10 17:07:08.729  6674  6674 D AndroidRuntime: CheckJNI is OFF
08-10 17:07:08.850  6674  6674 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 17:07:08.855  1030  1045 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 17:07:08.865  1943  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-10 17:07:08.869  1030  1045 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-10 17:07:08.870  1030  1045 D ActivityManager: setTaskToReturnTo : TaskRecord{1c8431a4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 17:07:08.870  1030  1045 D ActivityManager: setTaskToReturnTo : TaskRecord{1c8431a4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 17:07:08.872  1030  1045 D WindowStateEx: AppWindowTokenEx init.. 
08-10 17:07:08.872   336   386 E GBMv2   : DFP En is all cleared set to be enabled
08-10 17:07:08.893  1030  1045 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6689 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-10 17:07:08.894  6674  6674 D AndroidRuntime: Shutting down VM
08-10 17:07:08.953  1943  2895 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-10 17:07:08.953  1943  2895 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ac1b6c5 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-10 17:07:08.954  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-10 17:07:08.954  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b89081a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-10 17:07:08.994  6689  6689 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-10 17:07:09.098  6689  6689 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-10 17:07:09.106  6689  6689 I LibraryLoader: Loading: webviewchromium
08-10 17:07:09.109  6689  6689 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1740-1744)
08-10 17:07:09.109  6689  6689 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 17:07:09.127  6689  6689 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d0761bb}
,08-10 17:07:09.129  6689  6689 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 17:07:09.129  6689  6689 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 17:07:09.139  6689  6689 I BrowserStartupController: Initializing chromium process, renderers=0
,08-10 17:07:09.140  6689  6689 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 17:07:09.152  6689  6689 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 17:07:09.153  6689  6689 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-10 17:07:09.154  6689  6689 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-10 17:07:09.159   318   318 V AudioPolicyService: registerClient() client 0xb0010380, uid 10118
08-10 17:07:09.164  1030  1095 D BluetoothManagerService: Message: 20
08-10 17:07:09.164  1030  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@82210e:true
08-10 17:07:09.170  6689  6689 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 17:07:09.170  6689  6689 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 17:07:09.170  6689  6689 I Adreno-EGL: Build Date: 12/12/14 금
08-10 17:07:09.170  6689  6689 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 17:07:09.170  6689  6689 I Adreno-EGL: Remote Branch: 
08-10 17:07:09.170  6689  6689 I Adreno-EGL: Local Patches: 
08-10 17:07:09.170  6689  6689 I Adreno-EGL: Reconstruct Branch: 
,08-10 17:07:09.269  6689  6735 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-10 17:07:09.278  6689  6689 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-10 17:07:09.297  6689  6689 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 17:07:09.303  6689  6689 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-10 17:07:09.311  6689  6689 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-10 17:07:09.320  6689  6689 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-10 17:07:09.320  6689  6689 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-10 17:07:09.339  6689  6689 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-10 17:07:09.347  6689  6689 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 17:07:09.347  6689  6689 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 17:07:09.386  6689  6753 D OpenGLRenderer: Render dirty regions requested: true
08-10 17:07:09.386  6689  6753 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 17:07:09.393  6689  6753 D OpenGLRenderer: Enabling debug mode 0
08-10 17:07:09.403  6689  6689 D Atlas   : Validating map...
,08-10 17:07:09.407  1030  2014 D SplitWindow: check instance of lgWin Window{29080858 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 17:07:09.454  6689  6751 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 17:07:09.454  6689  6751 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 17:07:09.563  1030  1096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +611ms (total +690ms)
,08-10 17:07:09.565  1030  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34414b0d u0 com.test.thalitest/.MainActivity t6} time:302200
08-10 17:07:09.571  6689  6689 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e366fc6 time:302206
08-10 17:07:09.683  6689  6689 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-10 17:07:09.683  6689  6689 I chromium: 
,08-10 17:07:09.713  6689  6689 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 17:07:09.869  6689  6764 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435155968
,08-10 17:07:09.882  6689  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 17:07:09.882  6689  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 17:07:09.882  6689  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 17:07:09.882  6689  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 17:07:09.882  6689  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-10 17:07:09.882  6689  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7f49aa added. We now have 1 listener(s)
08-10 17:07:09.888  1030  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 17:07:09.891  6689  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-10 17:07:09.893  6689  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 17:07:09.894  6689  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 17:07:09.895  6689  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 17:07:09.903  6689  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a1e1511 added. We now have 1 listener(s)
08-10 17:07:09.904  6689  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 17:07:09.909  1030  1543 D WifiService: New client listening to asynchronous messages
08-10 17:07:09.913  6689  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 17:07:09.914  6689  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 17:07:09.914  6689  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-10 17:07:09.914  6689  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 17:07:09.914  6689  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 17:07:09.918  6689  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:07:09.919  1030  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 17:07:09.920  6689  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-10 17:07:09.931  6689  6764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 17:07:09.931  6689  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:07:09.931  6689  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:09.931  6689  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:09.931  6689  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:07:09.931  6689  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:07:09.931  6689  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:09.931  6689  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 17:07:09.931  6689  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 17:07:09.931  6689  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 17:07:09.931  6689  6764 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 17:07:09.934  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:09.936  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:09.938  6689  6764 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-10 17:07:09.977  6689  6751 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-10 17:07:09.977  6689  6751 I chromium: 
,08-10 17:07:10.036  6689  6689 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 17:07:10.317   336   389 E GBMv2   : DFP En is all cleared set to be enabled
,08-10 17:07:10.317   336   389 E GBMv2   : Set value is all cleared set the max
08-10 17:07:10.317   336   389 I GBMv2   : DFP Enabled. Ignore VFP set
08-10 17:07:10.876  6689  6767 W jxcore-log: Initializing JXcore engine
08-10 17:07:10.876  6689  6767 W jxcore-log: JXcore engine is ready
,08-10 17:07:10.896  6767  6767 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7558]" dev="sockfs" ino=7558 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-10 17:07:10.896  6767  6767 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-10 17:07:10.896  6767  6767 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10347]" dev="sockfs" ino=10347 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-10 17:07:10.896  6767  6767 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-10 17:07:10.896  6767  6767 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33034]" dev="sockfs" ino=33034 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-10 17:07:10.921  6689  6767 W jxcore-log: Starting JXcore engine
08-10 17:07:10.996  6689  6767 W jxcore-log: Platform android
08-10 17:07:10.996  6689  6767 W jxcore-log: 
08-10 17:07:10.996  6689  6767 W jxcore-log: Process ARCH arm
08-10 17:07:10.996  6689  6767 W jxcore-log: 
,08-10 17:07:11.207  6689  6767 I jxcore-log: JXcore Cordova bridge is ready!
08-10 17:07:11.207  6689  6767 I jxcore-log: 
08-10 17:07:11.207  6689  6767 W jxcore-log: JXcore engine is started
,08-10 17:07:11.219  6689  6764 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-10 17:07:11.221  6689  6689 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 17:07:27.007  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 17:07:27.007  6689  6767 I jxcore-log: 
,08-10 17:07:27.009  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 17:07:27.009  6689  6767 I jxcore-log: 
,08-10 17:07:27.012  6689  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:07:27.012  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:27.012  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:27.012  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:07:27.012  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:07:27.012  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:27.012  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 17:07:27.012  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 17:07:27.014  6689  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 17:07:27.016  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 17:07:27.016  6689  6767 I jxcore-log: 
,08-10 17:07:27.018  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 17:07:27.018  6689  6767 I jxcore-log: 
,08-10 17:07:27.347  6689  6767 I jxcore-log: Running unit tests
08-10 17:07:27.347  6689  6767 I jxcore-log: ,
08-10 17:07:27.349  6689  6767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 17:07:27.349  6689  6767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0f9e6b added. We now have 2 listener(s)
08-10 17:07:27.349  1030  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-10 17:07:27.351  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-10 17:07:27.351  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 17:07:27.351  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-10 17:07:27.351  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-10 17:07:27.351  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19ad3dc8 added. We now have 2 listener(s),
08-10 17:07:27.351  6689  6767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-10 17:07:27.352  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 17:07:27.354  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 17:07:27.356  6689  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:07:27.356  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-10 17:07:27.356  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:27.356  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-10 17:07:27.356  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:07:27.356  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:27.356  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 17:07:27.356  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 17:07:27.357  6689  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:27.357  6689  6767 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 17:07:27.358  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:27.359  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:07:27.360  6689  6767 D ExecuteNativeTests: Running unit tests,
,08-10 17:07:27.438  6689  6767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 17:07:27.438  6689  6767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 added. We now have 3 listener(s)
,08-10 17:07:27.439  1030  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 17:07:27.441  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 17:07:27.441  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 17:07:27.441  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 17:07:27.441  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:07:27.441  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 added. We now have 3 listener(s)
08-10 17:07:27.441  6689  6767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 17:07:27.442  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 17:07:27.444  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:07:27.447  6689  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:07:27.447  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:27.447  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:27.447  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:07:27.447  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:07:27.447  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:27.447  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 17:07:27.447  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 17:07:27.447  6689  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:27.448  6689  6767 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 17:07:27.449  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:27.450  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:27.453  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 17:07:27.453  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 17:07:27.453  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 17:07:27.453  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 17:07:27.454  6689  6767 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-10 17:07:27.459  6689  6767 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 17:07:27.459  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 17:07:27.459  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:07:27.460  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:07:27.460  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:07:27.463  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:27.465  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:27.465  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:27.465  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:27.466  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:27.466  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 17:07:27.466  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 17:07:27.466  6689  6767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 removed from the list
08-10 17:07:27.466  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:27.466  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 removed from the list
08-10 17:07:27.466  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:27.466  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:27.467  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:27.467  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:27.469  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:27.469  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:27.469  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:27.469  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:27.470  6689  6767 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-10 17:07:27.470  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:27.471  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:27.471  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:27.471  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:27.471  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:27.471  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:27.471  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:27.471  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:27.471  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:27.471  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:27.471  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:27.471  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:27.471  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:27.471  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:27.473  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:27.473  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:27.473  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:27.473  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 17:07:27.477  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 17:07:27.478  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 17:07:27.478  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 17:07:27.478  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 17:07:27.478  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 17:07:27.478  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 17:07:27.478  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:27.478  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:27.478  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:27.480  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:27.480  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:27.480  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:27.480  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:27.480  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:27.480  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:27.480  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:27.480  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:27.480  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:27.480  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:27.480  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:27.481  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:27.481  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:27.481  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:27.481  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:27.482  6689  6767 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 17:07:27.483  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:07:27.485  6689  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:07:27.485  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:27.485  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:27.485  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:07:27.485  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:07:27.485  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:27.485  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 17:07:27.485  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 17:07:27.486  6689  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:27.486  6689  6767 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 17:07:27.487  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:27.488  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:27.488  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 17:07:27.488  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 17:07:27.488  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 17:07:27.489  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:07:27.489  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 17:07:27.491  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 17:07:27.492  1030  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 17:07:27.503  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 17:07:27.514  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 17:07:27.518  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-10 17:07:27.520  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 17:07:27.521  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 17:07:27.522  6689  6767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 17:07:27.522  6689  6767 I io.jxcore.node.ConnectionHelper: start: OK
08-10 17:07:32.534  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:32.534  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:32.535  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 17:07:32.540  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:32.540  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:32.540  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 17:07:32.540  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:32.540  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:32.541  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:32.541  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:32.541  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:37.542  6689  6767 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-10 17:07:37.556  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:07:37.561  6689  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:07:37.561  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:37.561  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:37.561  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:07:37.561  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:07:37.561  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:37.561  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 17:07:37.561  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 17:07:37.564  6689  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:37.565  6689  6767 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 17:07:37.567  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:37.568  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:37.569  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 17:07:37.569  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 17:07:37.570  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 17:07:37.570  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:07:37.570  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 17:07:37.575  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 17:07:37.577  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 17:07:37.579  6689  6767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 17:07:37.580  6689  6767 I io.jxcore.node.ConnectionHelper: start: OK
08-10 17:07:37.582  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:37.582  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:37.582  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:37.583  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:37.583  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:37.583  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 17:07:37.583  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:37.583  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:37.583  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:37.583  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:37.583  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:37.584  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:37.584  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:37.585  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:37.585  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:37.587  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:37.587  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:37.587  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:37.587  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:37.588  6689  6767 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-10 17:07:37.594  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:07:37.598  6689  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:07:37.598  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:37.598  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:37.598  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:07:37.598  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:07:37.598  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:37.598  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 17:07:37.598  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 17:07:37.600  6689  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 17:07:37.600  6689  6767 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 17:07:37.602  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:07:37.606  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:37.607  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 17:07:37.607  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 17:07:37.607  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 17:07:37.607  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:07:37.607  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 17:07:37.745  1030  1888 I art     : Explicit concurrent mark sweep GC freed 28504(1367KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.292ms total 127.888ms
,08-10 17:07:37.750  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 17:07:37.750  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 17:07:37.751  6689  6767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 17:07:37.751  6689  6767 I io.jxcore.node.ConnectionHelper: start: OK
08-10 17:07:42.251  1030  3547 I LocationManagerService: remove 1fb90425
08-10 17:07:42.252  1030  3547 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-10 17:07:42.253  1030  3547 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 17:07:42.254  1030  3547 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-10 17:07:42.263  1030  3547 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-10 17:07:42.264  1030  3547 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-10 17:07:42.752  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:42.752  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:42.752  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 17:07:47.760  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:47.761  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:47.761  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 17:07:47.767  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:47.767  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.767  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 17:07:47.768  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:47.768  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.768  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.768  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:47.768  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.771  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.771  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.774  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:47.774  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:47.777  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:47.777  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:47.777  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.777  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.778  6689  6767 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-10 17:07:47.778  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:47.778  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:47.778  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 17:07:47.781  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:47.781  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.781  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.781  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:47.781  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.781  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.781  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:47.782  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.782  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.782  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.782  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.784  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:47.784  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:47.784  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:47.784  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:47.784  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.784  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.786  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 17:07:47.787  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:47.787  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:47.787  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:47.788  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:47.788  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.788  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.788  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:47.788  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.788  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.788  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:47.788  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.788  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.788  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.788  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.790  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:47.790  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 17:07:47.794  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:47.794  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:47.794  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.794  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.796  6689  6767 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-10 17:07:47.797  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:47.797  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:47.797  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:47.797  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:47.797  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.798  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.798  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:47.798  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.798  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.798  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:47.798  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.798  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.798  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.798  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.799  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:47.799  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:47.801  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:47.801  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:47.801  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.801  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.802  6689  6767 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-10 17:07:47.802  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:47.802  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:47.802  6689  6767 V io.jxcore.node.StartStopOperationHa,ndler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:47.803  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:47.803  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.803  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.803  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:47.803  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.803  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.803  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:47.803  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.803  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.803  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.803  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:07:47.809  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:47.809  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:47.810  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:47.810  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:47.810  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.810  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.811  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 17:07:47.813  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 17:07:47.813  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 17:07:47.813  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 17:07:47.813  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:07:47.814  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:07:47.814  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 17:07:47.814  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 17:07:47.814  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 17:07:47.814  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:47.814  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:47.814  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:47.816  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 17:07:47.819  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.819  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.819  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:47.819  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.819  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.820  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:47.820  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.820  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.820  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.820  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.824  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:47.824  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:47.827  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:47.827  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:47.827  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.827  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.830  6689  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 17:07:47.830  6689  6767 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 17:07:47.830  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 17:07:47.834  6689  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 17:07:47.835  6689  6767 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-10 17:07:47.838  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 17:07:47.838  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 17:07:47.838  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 17:07:47.838  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 17:07:47.838  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 17:07:47.838  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 17:07:47.838  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 17:07:47.838  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 17:07:47.839  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 17:07:47.840  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 17:07:47.840  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
08-10 17:07:47.840  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 17:07:47.840  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 17:07:47.840  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 17:07:47.840  6689  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 17:07:47.840  6689  6767 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 17:07:47.840  6689  6767 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 17:07:47.840  6689  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 17:07:47.840  6689  6767 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 17:07:47.841  6689  6767 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 17:07:47.841  6689  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-10 17:07:47.841  6689  6767 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 17:07:47.841  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 17:07:47.845  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-10 17:07:47.847  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 17:07:47.847  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-10 17:07:47.848  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-10 17:07:47.848  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-10 17:07:47.848  6689  6767 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-10 17:07:47.848  6689  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 17:07:47.848  6689  6767 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-10 17:07:47.849  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:47.849  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 17:07:47.849  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:47.851  6689  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
,08-10 17:07:47.861  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:47.861  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.861  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.862  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-10 17:07:47.864  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:47.864  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.864  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.864  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:47.864  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.864  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.864  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.864  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.865  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:47.866  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:47.866  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:47.866  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:47.866  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.866  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.867  6689  6767 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-10 17:07:47.868  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:47.868  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:47.868  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:47.870  6689  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-10 17:07:47.870  6689  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
08-10 17:07:47.870  6689  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
,08-10 17:07:47.873  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:47.873  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.873  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.874  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:47.874  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.874  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.874  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:47.874  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.874  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.885  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:07:47.888  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.889  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:47.889  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:47.889  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:47.890  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:47.890  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.890  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.891  6689  6767 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-10 17:07:47.891  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:47.891  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:47.891  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:47.892  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:47.892  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.892  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.892  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:47.893  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.893  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.893  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:47.893  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.893  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.893  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.893  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.894  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:47.894  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:47.895  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:47.895  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:47.895  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.895  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.896  6689  6767 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 17:07:47.896  6689  6767 E io.jxcore.node.ConnectionModel,: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-10 17:07:47.896  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 17:07:47.896  6689  6767 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 17:07:47.896  6689  6767 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 17:07:47.896  6689  6767 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 17:07:47.896  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 17:07:47.896  6689  6767 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 17:07:47.897  6689  6767 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 17:07:47.897  6689  6767 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 17:07:47.897  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 17:07:47.897  6689  6767 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-10 17:07:47.897  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:47.897  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:47.897  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-10 17:07:47.898  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:47.898  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.898  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.898  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:47.898  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.898  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.898  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:47.898  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.898  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.898  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.898  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:07:47.906  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:47.906  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:47.907  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:47.907  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:47.907  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.907  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.907  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:47.907  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.907  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:47.908  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:47.908  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:47.908  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:47.908  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:47.908  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:47.908  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:48.002  6689  6772 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-10 17:07:48.004  6689  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
,08-10 17:07:52.634  1030  1385 D PowerManagerServiceEx: acquireWakeLockInternal: lock=522380000, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030,
,08-10 17:07:52.684  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 17:07:52.728  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=522380000 [*alarm*], flags=0x0
,08-10 17:07:52.908  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.909  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.909  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:52.909  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.909  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:07:52.911  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:52.911  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:52.911  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:52.911  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:52.912  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:52.912  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.912  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.912  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:52.912  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.912  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.912  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:52.912  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.912  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.912  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.912  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.913  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:52.913  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:52.914  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:52.914  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:52.914  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.914  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.916  6689  6767 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 17:07:52.916  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:07:52.917  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-10 17:07:52.917  6689  6767 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-10 17:07:52.918  6689  6767 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-10 17:07:52.918  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-10 17:07:52.918  6689  6689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-10 17:07:52.918  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 17:07:52.919  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:52.919  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 17:07:52.919  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-10 17:07:52.919  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-10 17:07:52.919  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.919  6689  6767 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-10 17:07:52.919  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:52.919  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.919  6689  6689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 17:07:52.919  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 17:07:52.919  6689  6767 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 17:07:52.920  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 17:07:52.922  6689  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-10 17:07:52.923  6689  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-10 17:07:52.926  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 17:07:52.927  6689  6767 D BluetoothLeScanner: could not find callback wrapper
08-10 17:07:52.927  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 17:07:52.927  6689  6767 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 17:07:52.927  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.927  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.928  6689  6767 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 17:07:52.929  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.929  6689  6689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 17:07:52.929  6689  6689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-10 17:07:52.929  6689  6689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 17:07:52.929  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:52.929  6689  6689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 17:07:52.929  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:52.929  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:52.929  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:52.929  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.929  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.929  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:52.929  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.929  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.929  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:52.930  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.930  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.930  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.930  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 1,7:07:52.931  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:52.931  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:52.931  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.931  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.932  6689  6767 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-10 17:07:52.932  6689  6767 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 17:07:52.932  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 17:07:52.933  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:07:52.933  6689  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:07:52.933  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:52.933  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:52.933  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:52.933  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:52.933  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.933  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.934  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:52.934  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.934  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.934  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:52.934  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.934  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.934  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.934  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.935  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:52.935  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 17:07:52.935  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.940  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.942  1030  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 17:07:52.943  1030  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 17:07:52.944  1030  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 17:07:52.945  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 17:07:52.945  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:52.945  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:52.945  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 17:07:52.945  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.945  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.945  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:52.945  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.945  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.945  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:52.945  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.945  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.945  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.946  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.946  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:52.946  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:52.946  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.946  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.947  6689  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:07:52.947  6689  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:07:52.947  6689  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:07:52.948  6689  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:07:52.948  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.948  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.948  6689  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdd9436 not in the list
08-10 17:07:52.948  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:07:52.948  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.948  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:52.948  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.948  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.948  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.948  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.949  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:07:52.949  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:07:52.949  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.949  6689  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1544bf37 not in the list
08-10 17:07:52.950  6689  6767 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-10 17:07:52.951  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 17:07:52.951  6689  6767 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 17:07:52.951  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 17:07:52.951  6689  6767 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-10 17:07:52.951  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 17:07:52.953  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 17:07:52.953  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-10 17:07:52.954  6689  6767 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-10 17:07:52.954  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 17:07:52.954  6689  6767 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-10 17:07:52.955  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 17:07:52.955  6689  6767 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-10 17:07:52.955  6689  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-10 17:07:52.956  6689  6767 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-10 17:07:52.956  6689  6767 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-10 17:07:52.957  6689  6767 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-10 17:07:52.957  6689  6767 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 17:07:52.957  6689  6767 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-10 17:07:52.957  6689  6767 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-10 17:07:52.958  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:07:52.958  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fc29c3c added. We now have 3 listener(s)
08-10 17:07:52.958  6689  6767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 17:07:52.959  6689  6767 D BluetoothAdapter: enable(): BT is already enabled..!
08-10 17:07:52.961  1030  1960 D WifiServiceImplEx: setWifiEnabled: true pid=6689, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 17:07:52.961  1030  1960 D WifiService: setWifiEnabled: true pid=6689, uid=10118
08-10 17:07:52.961  1030  1960 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 17:07:52.963  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:07:52.963  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3defdc5 added. We now have 4 listener(s)
08-10 17:07:52.963  6689  6767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 17:07:52.966  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.966  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3defdc5 removed from the list
08-10 17:07:52.966  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:52.966  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.966  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.967  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:07:52.967  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22a2431a added. We now have 4 listener(s)
08-10 17:07:52.967  6689  6767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 17:07:52.969  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:52.969  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22a2431a removed from the list
08-10 17:07:52.969  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:52.969  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:52.969  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:52.970  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:07:52.970  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fa4ae4b added. We now have 4 listener(s)
08-10 17:07:52.970  6689  6767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 17:07:52.972  1030  1941 D WifiServiceImplEx: setWifiEnabled: false pid=6689, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 17:07:52.972  1030  1941 D WifiService: setWifiEnabled: false pid=6689, uid=10118
08-10 17:07:52.972  1030  1941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 17:07:52.979  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 17:07:52.979  1030  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 17:07:52.979  1030  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 17:07:52.979  1030  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 17:07:52.979  1030  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,08-10 17:07:52.981  1030  1980 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@928f3f6 mBinding = false
08-10 17:07:52.981  1030  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-10 17:07:52.982  1030  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-10 17:07:52.982  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 17:07:52.982  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-10 17:07:52.982  1030  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 17:07:52.982  1030  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 17:07:52.982  1030  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 17:07:52.983  1030  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 17:07:52.983  1030  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 17:07:52.988  1030  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 17:07:52.988  1030  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 17:07:52.988  1030  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 17:07:52.988  1030  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 17:07:52.989  2747  2747 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 17:07:52.990  1030  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 17:07:52.990  1030  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 17:07:52.990  1030  1537 D WifiNative-wlan0: SET ps 1: returned true
08-10 17:07:52.991   312   893 D CommandListener: Clearing all IP addresses on wlan0
08-10 17:07:52.995  1030  2860 D DhcpStateMachine: RunningState{ when=-5ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 17:07:53.001  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 17:07:53.001  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 17:07:53.001  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-10 17:07:53.005  1030  1095 D BluetoothManagerService: Message: 2
08-10 17:07:53.007  6689  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:07:53.008  1030  1095 D BluetoothManagerService: Sending off request.
,08-10 17:07:53.008  3866  3883 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-10 17:07:53.009  3866  3958 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-10 17:07:53.009  3866  3958 D BluetoothAdapterProperties: Setting state to 13
08-10 17:07:53.009  3866  3958 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 17:07:53.010  3866  3958 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 17:07:53.010  3866  3958 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-10 17:07:53.012  1030  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 17:07:53.012  1030  1544 D ConnectivityService: ignoring duplicate network state non-change
08-10 17:07:53.012  1030  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-10 17:07:53.013  3866  3968 D BluetoothAdapterProperties: Scan Mode:20
08-10 17:07:53.013  3866  3958 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-10 17:07:53.014  3866  4289 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-10 17:07:53.014  3866  4289 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 17:07:53.014  3866  4289 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-10 17:07:53.014  3866  4289 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-10 17:07:53.014  3866  4289 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-10 17:07:53.014  3866  4289 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-10 17:07:53.014  3866  4289 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-10 17:07:53.014  3866  4289 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-10 17:07:53.014  3866  3958 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 17:07:53.014  3866  4350 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 17:07:53.015  3866  4290 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 17:07:53.015  3866  4354 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 17:07:53.015  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-10 17:07:53.015  3866  4349 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 17:07:53.016  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-10 17:07:53.016  3866  4056 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-10 17:07:53.021  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-10 17:07:53.021  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-10 17:07:53.021  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 17:07:53.021  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 17:07:53.021  3866  4056 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 17:07:53.021  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 17:07:53.021  3866  4056 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 17:07:53.021  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 17:07:53.021  3866  4056 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 17:07:53.021  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-10 17:07:53.021  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-10 17:07:53.021  3866  4056 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 17:07:53.025  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-10 17:07:53.026  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 17:07:53.026  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 17:07:53.027  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 17:07:53.028  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-10 17:07:53.030  1030  1536 D LGWifiP2pService: InactiveState{ when=-18ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 17:07:53.030  1030  1536 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 17:07:53.030  1030  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@be10d1
08-10 17:07:53.032  1030  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 17:07:53.032  1030  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 17:07:53.032  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 17:07:53.032  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 17:07:53.032  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 17:07:53.033  1030  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 17:07:53.033  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 1
,08-10 17:07:53.034  1030  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-10 17:07:53.034  1030  1030 D RttService: SCAN_AVAILABLE : 1
08-10 17:07:53.034  1030  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 17:07:53.035  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:53.035  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fa4ae4b removed from the list
08-10 17:07:53.035  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:53.035  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:53.037  1030  1558 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-10 17:07:53.038  1030  1536 D LGWifiP2pService: P2pDisablingState
08-10 17:07:53.038  1030  1536 D LGWifiP2pService: P2pDisablingState{ when=-8ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-10 17:07:53.038  1030  1536 D LGWifiP2pService: p2p socket connection lost
08-10 17:07:53.038  1030  1536 D LGWifiP2pService: P2pDisabledState
08-10 17:07:53.039  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:07:53.040  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10b6b141 added. We now have 4 listener(s)
08-10 17:07:53.040  6689  6767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 17:07:53.040  6689  6689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:07:53.040  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:07:53.040  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:53.040  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:53.040  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:07:53.040  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:07:53.040  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:07:53.040  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:07:53.040  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 17:07:53.041  6689  6689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:07:53.041  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:07:53.043  1030  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 17:07:53.043  1030  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 17:07:53.044  1030  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 17:07:53.044  1030  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-10 17:07:53.044  1030  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 17:07:53.044  1030  1536 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 17:07:53.046  1030  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 17:07:53.046  2747  2747 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 17:07:53.050  1030  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 17:07:53.050  1030  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 17:07:53.050  1030  1537 D WifiNative-wlan0: SET ps 1: returned true
08-10 17:07:53.052  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 17:07:53.052  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 17:07:53.052   312   893 D CommandListener: Clearing all IP addresses on wlan0
08-10 17:07:53.052  1030  1544 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-10 17:07:53.052  1030  1544 D DSQN    : disableDataServiceNotify
08-10 17:07:53.054  1030  1537 D WifiNative-p2p0: doBoolean: TERMINATE
08-10 17:07:53.053  1030  1544 D DSQN    : stop dsqn bin
08-10 17:07:53.055  1030  1030 D WifiHS20: hidePasspointNotification off =false
,08-10 17:07:53.057  1030  1537 D WifiNative-p2p0: TERMINATE: returned true
08-10 17:07:53.057  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 17:07:53.057  1030  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 17:07:53.057  1030  1537 E WifiStateMachine: useWiFiOffloading() : false
08-10 17:07:53.057  1030  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 17:07:53.057  1943  1943 D WfdsService: WifiP2pState is changed : false
08-10 17:07:53.057  1943  2308 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-10 17:07:53.057  1943  2308 D WfdsService: Set the WFDS Monitor: false
08-10 17:07:53.059  6689  6689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:07:53.059  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:07:53.059  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:53.059  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:53.059  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:07:53.059  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:07:53.059  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:07:53.059  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:07:53.059  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 17:07:53.059  1030  1544 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-10 17:07:53.059  1030  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 17:07:53.059  1030  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 17:07:53.059  1030  1544 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 17:07:53.060  1030  1544 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-10 17:07:53.060  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 17:07:53.060  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 17:07:53.060  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 17:07:53.060  1030  1544 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-10 17:07:53.060  1030  1544 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-10 17:07:53.060  1030  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 17:07:53.060  1604  1604 ,D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 17:07:53.061  1030  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 17:07:53.062  1030  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 17:07:53.062  6689  6689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:07:53.062  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:07:53.062  1030  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-10 17:07:53.063  1943  2308 D WfdsMonitor: WFDS Monitor is stopped
08-10 17:07:53.063  1943  2308 D WfdsService: STATE : WfdsDisabledState - enter
08-10 17:07:53.063  1943  2770 D CtrlSupplicant: Received on exit socket, terminate
08-10 17:07:53.063  1943  2770 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-10 17:07:53.063  1943  2770 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-10 17:07:53.063  1943  2770 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-10 17:07:53.063  1943  2310 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-10 17:07:53.064  1604  1835 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-10 17:07:53.065  1943  2308 W WfdsService: DefaultState - msg [9445378] is not handled
08-10 17:07:53.065  1030  1095 D BluetoothManagerService: Message: 60
08-10 17:07:53.065  1030  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-10 17:07:53.065  1030  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-10 17:07:53.066  6689  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:07:53.066  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10b6b141 removed from the list
08-10 17:07:53.066  6689  6767 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:07:53.066  6689  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:07:53.066  6689  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:07:53.067  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:07:53.067  6689  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@211176e6 added. We now have 4 listener(s)
08-10 17:07:53.067  6689  6767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 17:07:53.068  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-10 17:07:53.069  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:07:53.072  3866  3866 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:07:53.072  3866  3866 D BluetoothMapService: STATE_TURNING_OFF
08-10 17:07:53.072  3866  3866 V BluetoothMapService: Handler(): got msg=4
08-10 17:07:53.072  3866  3866 D BluetoothMapService: MAP Service closeService in
08-10 17:07:53.072  3866  3866 D BluetoothMapMasInstance: MAP Service shutdown
08-10 17:07:53.073  3866  3866 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 17:07:53.073  3866  3866 V BluetoothMapService: MAP Service closeService out
08-10 17:07:53.073  3866  3866 V BtOppService: Receiver DISABLED_ACTION 
08-10 17:07:53.073  3866  3866 I BtOppRfcommListener: stopping Accept Thread
08-10 17:07:53.073  3866  3866 V BtOppRfcommListener: close mBtServerSocket
08-10 17:07:53.073  3866  3866 V BtOppRfcommListener: waiting for thread to terminate
08-10 17:07:53.074  3866  4349 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 17:07:53.074  3866  3866 V BtOppRfcommListener: done waiting for thread to terminate
08-10 17:07:53.075  6689  6689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:07:53.075  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:07:53.075  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:53.075  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:53.075  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:07:53.075  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:07:53.075  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:07:53.075  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:07:53.075  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 17:07:53.076  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 17:07:53.076  6689  6689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:07:53.076  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 17:07:53.076  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:07:53.076  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 17:07:53.079  6689  6767 I System.out: IsBluetoothEnabled
08-10 17:07:53.080  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-10 17:07:53.080  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 17:07:53.081  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 17:07:53.086  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 17:07:53.088  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 17:07:53.090  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 17:07:53.107  1030  1090 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6815 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 17:07:53.107  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-10 17:07:53.107  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 17:07:53.107  1030  1030 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-10 17:07:53.108  1030  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 17:07:53.109  1030  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 17:07:53.109  1030  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 17:07:53.109  1030  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 17:07:53.109  1030  1888 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@928f3f6 mBinding = false
08-10 17:07:53.109  1030  1544 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 17:07:53.109  1030  1544 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 17:07:53.109  1030  1095 D BluetoothManagerService: Message: 2
08-10 17:07:53.109  1030  1095 D BluetoothManagerService: Sending off request.
08-10 17:07:53.109  1030  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 17:07:53.109  1030  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 17:07:53.110  3866  3866 V BtOppService: onDestroy
08-10 17:07:53.110  1030  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 17:07:53.111  1030  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 17:07:53.112  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 17:07:53.112  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 17:07:53.112  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 17:07:53.112  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 17:07:53.112  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 17:07:53.112  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 17:07:53.112  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 17:07:53.112  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 17:07:53.113  1030  1544 D NetworkManagementService: Removing idletimer
08-10 17:07:53.113  1854  1854 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 17:07:53.113  1030  1544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 17:07:53.113  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 17:07:53.114  3866  6809 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-10 17:07:53.115  3866  6809 D BluetoothAdapterService: disable() : BT State is not STATE_ON. Can't disable BT
08-10 17:07:53.115  1030  1095 E BluetoothManagerService: IBluetooth.disable() returned false
08-10 17:07:53.117  6689  6689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:07:53.117  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:07:53.117  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:53.117  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:53.117  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:07:53.117  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:07:53.117  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:07:53.117  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:07:53.117  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 17:07:53.118  6689  6689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:07:53.118  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:07:53.120  6689  6689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:07:53.120  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:07:53.120  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:53.120  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:53.120  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:07:53.120  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:07:53.120  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:07:53.120  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:07:53.120  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:07:53.121  6689  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:53.123  6689  6689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:07:53.123  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:07:53.123  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:07:53.123  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 17:07:53.123  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:07:53.123  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:07:53.123  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:07:53.123  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:07:53.123  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:07:53.124  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:53.145  1030  2053 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6834 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 17:07:53.147  1030  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 17:07:53.147  3866  3866 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-10 17:07:53.147  1030  2014 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@928f3f6 mBinding = false
08-10 17:07:53.156  2747  2747 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-10 17:07:53.156  2747  2747 I wpa_supplicant: monitor socket send errors count : 1
08-10 17:07:53.156  2747  2747 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-2\x00 that cannot receive messages
08-10 17:07:53.156  1030  2766 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-10 17:07:53.156  1030  2766 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-10 17:07:53.157  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 17:07:53.157  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 17:07:53.157  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-10 17:07:53.158  1030  1095 D BluetoothManagerService: Message: 1
08-10 17:07:53.158  1030  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@928f3f6
08-10 17:07:53.167  3866  3884 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
,08-10 17:07:53.172  1030  1095 E BluetoothManagerService: IBluetooth.enable() returned false
08-10 17:07:53.176  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 17:07:53.177  6815  6815 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 17:07:53.177  6815  6815 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-10 17:07:53.177  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 17:07:53.177  6815  6815 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 17:07:53.177  6815  6815 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-10 17:07:53.178  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 17:07:53.178  6815  6815 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 17:07:53.179  6815  6815 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-10 17:07:53.192  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 17:07:53.193  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 17:07:53.193  2747  2747 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 17:07:53.194  1030  2766 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-10 17:07:53.194  1030  2766 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 17:07:53.194  1030  2766 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 17:07:53.194  2747  2747 W wpa_supplicant: USIM:  scard_deinit function
08-10 17:07:53.194  1030  1095 D Tethering: InitialState.processMessage what=4
08-10 17:07:53.194  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 17:07:53.194  1030  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 17:07:53.195  1030  2766 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-10 17:07:53.195  1030  2766 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 17:07:53.195  1030  2766 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 17:07:53.195  1030  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-10 17:07:53.196  1030  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 17:07:53.196  1030  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=345821
08-10 17:07:53.196  1030  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=345821
08-10 17:07:53.196  1030  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=345821  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 17:07:53.197  1030  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=345821  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 17:07:53.209  1030  2860 D DhcpStateMachine: StoppedState
08-10 17:07:53.209  1030  2860 D DhcpStateMachine: StoppedState{ when=-159ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 17:07:53.210  1030  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-10 17:07:53.210  1030  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-10 17:07:53.216  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 17:07:53.218  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 17:07:53.219  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 17:07:53.220  1030  1942 I ActivityManager: Killing 6155:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-10 17:07:53.246  2747  2747 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-10 17:07:53.246  1030  1980 W libprocessgroup: failed to open /acct/uid_10014/pid_6155/cgroup.procs: No such file or directory
08-10 17:07:53.247  1030  2766 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-10 17:07:53.247  1030  2766 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-10 17:07:53.247  1030  2766 D WifiMonitor: Disconnecting from the supplicant, no more events
08-10 17:07:53.247  1030  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-10 17:07:53.284  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-10 17:07:53.289  3866  3866 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 17:07:53.289  3866  3866 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:07:53.289  3866  3866 V BluetoothPbapReceiver: ***********state = 13
08-10 17:07:53.291  3866  3866 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-10 17:07:53.292  3866  3866 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:07:53.292  3866  3866 V BluetoothPbapService: state: 13
08-10 17:07:53.292  3866  3866 V BluetoothPbapService: Pbap Service closeService in
,08-10 17:07:53.293  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 17:07:53.296  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 17:07:53.297  3866  3866 V BluetoothPbapService: successfully stopped pbap service
08-10 17:07:53.297  3866  3866 V BluetoothPbapService: Pbap Service closeService out
08-10 17:07:53.297  3866  3866 V BluetoothPbapService: Pbap Service onDestroy
08-10 17:07:53.297  3866  3866 V BluetoothPbapService: Pbap Service closeService in
08-10 17:07:53.297  3866  3866 V BluetoothPbapService: Pbap Service closeService out
08-10 17:07:53.297  3866  3866 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-10 17:07:53.321  6815  6815 D LgDataFeature: LgDataFeature() Constructor: none
08-10 17:07:53.321  6815  6815 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 17:07:53.326  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 17:07:53.331  1030  1095 D BluetoothManagerService: Message: 20
08-10 17:07:53.332  1030  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f4500d0:true
08-10 17:07:53.372  1030  2052 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6858 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-10 17:07:53.375  1030  1537 D WifiOffDelayIfNotUsed: stopMonitoring
,08-10 17:07:53.375  1030  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 17:07:53.375  1030  1537 E WifiStateMachine: useWiFiOffloading() : false
08-10 17:07:53.375  1030  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 17:07:53.376  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-10 17:07:53.376  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 17:07:53.376  1943  2308 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-10 17:07:53.376  1943  2308 D WfdsService: Set the WFDS Monitor: false
08-10 17:07:53.376  1943  2308 D WfdsMonitor: WFDS Monitor is stopped
08-10 17:07:53.377  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-10 17:07:53.377  1030  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-10 17:07:53.377  1030  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-10 17:07:53.378  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 17:07:53.379  2464  2464 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 17:07:53.380  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:53.383  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:53.385  1030  1095 D BluetoothManagerService: Message: 30
08-10 17:07:53.398  1030  1095 D BluetoothManagerService: Message: 30
,08-10 17:07:53.400  6815  6815 D LocalBluetoothProfileManager: Adding local MAP profile
08-10 17:07:53.401  6815  6815 D BluetoothMap: Create BluetoothMap proxy object
08-10 17:07:53.402  1030  1095 D BluetoothManagerService: Message: 30
08-10 17:07:53.409  1030  1095 D BluetoothManagerService: Message: 30
08-10 17:07:53.415  6815  6815 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-10 17:07:53.417  6815  6815 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-10 17:07:53.430  6689  6689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 17:07:53.444  6815  6815 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-10 17:07:53.449  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-10 17:07:53.462  6815  6815 D DockEventReceiver: finishStartingService: stopping service
,08-10 17:07:53.466  6858  6858 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-10 17:07:53.466  6858  6858 W LG Account v2.2: No ProfileInfo entries
08-10 17:07:53.466  6858  6858 I LG Account v2.2: isEnabled: false
08-10 17:07:53.466  6858  6858 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-10 17:07:53.466  6858  6858 I Feature : [Lifetracker]Country: EU
08-10 17:07:53.466  6858  6858 I Feature : [Lifetracker]Operator: OPEN
08-10 17:07:53.466  6858  6858 I Feature : [Lifetracker]Ranking support: false
08-10 17:07:53.466  6858  6858 I Feature : [Lifetracker]Comfort support: false
08-10 17:07:53.466  6858  6858 I Feature : [Lifetracker]Accessory: true
08-10 17:07:53.467  6858  6858 I Feature : [Lifetracker]Health device: true
08-10 17:07:53.467  6858  6858 I Feature : [Lifetracker]Extra Pedometer: false
08-10 17:07:53.467  6858  6858 I Feature : [Lifetracker]Blood glucose device: false
08-10 17:07:53.467  6858  6858 I Feature : [Lifetracker]Device Number: 3
08-10 17:07:53.469  1030  1906 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
08-10 17:07:53.472  6815  6815 D BluetoothInputDevice: Proxy object connected
08-10 17:07:53.473  6815  6815 D HidProfile: Bluetooth service connected
08-10 17:07:53.474  6815  6815 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 17:07:53.475  6815  6815 D PanProfile: Bluetooth service connected
08-10 17:07:53.476  6815  6815 D BluetoothMap: Proxy object connected
08-10 17:07:53.476  6815  6815 D MapProfile: Bluetooth service connected
08-10 17:07:53.476  6815  6815 D BluetoothMap: getConnectedDevices()
08-10 17:07:53.477  6815  6815 D BluetoothMap: Bluetooth is Not enabled
08-10 17:07:53.477  6815  6815 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-10 17:07:53.499   318  1383 V AudioFlinger: 2127 died, releasing its sessions
08-10 17:07:53.499   318  1383 V AudioFlinger:  pid 1854 @ 0
08-10 17:07:53.499   318  1383 V AudioFlinger:  pid 3479 @ 1
,08-10 17:07:53.499   318  1383 V AudioFlinger:  pid 3479 @ 2
08-10 17:07:53.584  1030  1707 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
,08-10 17:07:53.605  6815  6815 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-10 17:07:53.621  6815  6815 D BluetoothPermissionRequest: onReceive
,08-10 17:07:53.628  6815  6815 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-10 17:07:53.644  1030  1707 I ActivityManager: Killing 6299:com.android.defcontainer/u0a4 (adj 15): empty #17
08-10 17:07:53.645  6815  6815 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-10 17:07:53.779  1030  1760 W libprocessgroup: failed to open /acct/uid_10004/pid_6299/cgroup.procs: No such file or directory
08-10 17:07:53.781  3866  3866 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-10 17:07:53.782  3866  3866 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-10 17:07:53.783  3866  3866 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-10 17:07:53.879  1030  1707 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6891 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-10 17:07:53.896  3866  3866 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:07:53.896  3866  3866 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-10 17:07:53.900  3866  3866 V BluetoothFtpService: Ftp Service onStartCommand
08-10 17:07:53.900  3866  3866 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:07:53.900  3866  3866 V BluetoothFtpService: Ftp Service closeService
08-10 17:07:53.900  3866  3866 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-10 17:07:53.902  3866  3866 V BluetoothFtpService: successfully stopped ftp service
08-10 17:07:53.902  3866  3866 V BluetoothFtpService: Ftp Service onDestroy
08-10 17:07:53.902  3866  3866 V BluetoothFtpService: Ftp Service closeService
08-10 17:07:53.910   340   340 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 31.075ms
,08-10 17:07:53.911  3866  3866 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 17:07:53.911  3866  3866 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 17:07:53.911  3866  3866 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 17:07:53.911  3866  3866 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:07:53.911  3866  3866 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-10 17:07:53.911  3866  3866 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 17:07:53.914  3866  3866 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:07:53.914  3866  3866 V BluetoothSapService: state: 13
08-10 17:07:53.915  3866  3866 V BluetoothSapService: Stopping SAP server process
08-10 17:07:53.918  3866  3866 V BluetoothSapService: Sap Service closeSapService in
08-10 17:07:53.918  3866  3866 V BluetoothSapService: Close listen Socket : 
08-10 17:07:53.918  3866  3866 V BluetoothSapService: Close rfcomm Socket : 
08-10 17:07:53.918  3866  3866 V BluetoothSapService: Close sapd  Socket : 
08-10 17:07:53.919  3866  3866 V BluetoothSapService: Sap Service closeSapService out
08-10 17:07:53.920  3866  3866 V BluetoothSapService: Sap Service onDestroy
08-10 17:07:53.920  3866  3866 V BluetoothSapService: Sap Service closeSapService in
08-10 17:07:53.920  3866  3866 V BluetoothSapService: Close listen Socket : 
08-10 17:07:53.920  3866  3866 V BluetoothSapService: Close rfcomm Socket : 
08-10 17:07:53.920  3866  3866 V BluetoothSapService: Close sapd  Socket : 
08-10 17:07:53.921  3866  3866 V BluetoothSapService: Sap Service closeSapService out
08-10 17:07:53.932   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 19.571ms
,08-10 17:07:53.955   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 20.467ms
,08-10 17:07:54.016  1030  1707 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6916 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 17:07:54.023  3866  3968 D bt_hci_bdroid: cleanup
08-10 17:07:54.023  3866  4056 W bt-btif : ag scb idx 1 not allocated
08-10 17:07:54.023  3866  4058 I bt_lpm  : LPM is already off!!!
08-10 17:07:54.023  3866  4056 E bt-btif : BTA AG is already disabled, ignoring ...
08-10 17:07:54.023  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 17:07:54.023  3866  4056 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 17:07:54.023  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 17:07:54.023  3866  4056 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 17:07:54.023  3866  4244 I bt_userial_mct: exiting userial_read_thread
08-10 17:07:54.023  3866  4244 D bt_userial_mct: Leaving userial_evt_read_thread()
08-10 17:07:54.023  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 17:07:54.024  3866  3968 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 17:07:54.024  3866  4058 I bt_vendor: hw_epilog_process
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 17:07:54.024  3866  3968 D bt_hci_bdroid: cleanup Finalizing cleanup
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 17:07:54.024  3866  3968 D bt_userial_mct: userial_close
08-10 17:07:54.024  3866  3968 E bt_userial_mct: pthread_join() FAILED result:3
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 17:07:54.024  3866  3968 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 17:07:54.024  3866  4056 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 17:07:54.024  3866  4056 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 17:07:54.046  6891  6891 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 17:07:54.082  6916  6916 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 17:07:54.096  6891  6891 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-10 17:07:54.106  1030  1942 I ActivityManager: Killing 6412:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-10 17:07:54.115  3866  3968 D bt_hci_bdroid: set_power 0
08-10 17:07:54.115  3866  3968 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-10 17:07:54.115  3866  3968 I bt_vendor: bluetooth satus is on
08-10 17:07:54.115  3866  3968 I bt_vendor: bt-vendor : resetting BT status
08-10 17:07:54.115  3866  3968 I bt_vendor: Starting hciattach daemon
08-10 17:07:54.115  3866  3968 I bt_vendor: try to set false
,08-10 17:07:54.116  3866  3968 I bt_vendor: Starting hciattach daemon
08-10 17:07:54.116  3866  3968 I bt_vendor: try to set false
08-10 17:07:54.117  3866  3968 I bt_vendor: cleanup
08-10 17:07:54.117  3866  4056 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-10 17:07:54.118  3866  3968 I GKI_LINUX: GKI_exit_task 0 done
08-10 17:07:54.118  3866  3968 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-10 17:07:54.120  3866  3958 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-10 17:07:54.144  6891  6891 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-10 17:07:54.145  6891  6891 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-10 17:07:54.145  6891  6891 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-10 17:07:54.146  6891  6891 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-10 17:07:54.146  6891  6891 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-10 17:07:54.151  6891  6891 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-10 17:07:54.162  6891  6891 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-10 17:07:54.174  1030  1046 W libprocessgroup: failed to open /acct/uid_10008/pid_6412/cgroup.procs: No such file or directory
08-10 17:07:54.175  3866  3866 D HeadsetService: Received stop request...Stopping profile...
,08-10 17:07:54.182  3866  3866 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 17:07:54.182  3866  3866 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 17:07:54.183  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8dc6d8
08-10 17:07:54.184  3866  3989 D HeadsetStateMachine: Exit Disconnected: -1
08-10 17:07:54.184  1030  1030 D BluetoothHeadset: Proxy object disconnected
08-10 17:07:54.184  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-10 17:07:54.184  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-10 17:07:54.184  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-10 17:07:54.185  3866  3866 D A2dpService: Received stop request...Stopping profile...
08-10 17:07:54.185  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-10 17:07:54.185  3866  4040 D A2dpStateMachine: Exit Disconnected: -1
08-10 17:07:54.186  6891  6891 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 17:07:54.188  3866  3866 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-10 17:07:54.191  3866  3866 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-10 17:07:54.191  3866  3866 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 17:07:54.191  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8dc6d8
08-10 17:07:54.193  1030  1030 D BluetoothA2dp: Proxy object disconnected
08-10 17:07:54.193  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-10 17:07:54.194  3866  3866 D HidService: Received stop request...Stopping profile...
08-10 17:07:54.194  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8dc6d8
08-10 17:07:54.194  3866  3958 D BluetoothAdapterState: Stopping profile services that were post enabled
08-10 17:07:54.195  3866  3866 D HeadsetStateMachine: Unbinding service...
08-10 17:07:54.195  6891  6891 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 17:07:54.196  3866  3866 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 17:07:54.196  3866  3866 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 17:07:54.196  3866  3866 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 17:07:54.196  3866  3866 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 17:07:54.196  3866  3866 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 17:07:54.196  3866  3866 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 17:07:54.196  3866  3866 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 17:07:54.197  3866  3866 D HealthService: Received stop request...Stopping profile...
08-10 17:07:54.197  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8dc6d8
08-10 17:07:54.199  3866  3866 D PanService: Received stop request...Stopping profile...
08-10 17:07:54.199  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8dc6d8
08-10 17:07:54.201  6815  6815 D BluetoothInputDevice: Proxy object disconnected
08-10 17:07:54.201  6815  6815 D HidProfile: Bluetooth service disconnected
08-10 17:07:54.201  3866  3866 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 17:07:54.201  6815  6815 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 17:07:54.201  6815  6815 D PanProfile: Bluetooth service disconnected
08-10 17:07:54.202  3866  3866 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 17:07:54.202  3866  3866 D BtGatt.GattService: stop()
08-10 17:07:54.203  3866  3866 D BtGatt.AdvertiseManager: advertise clients cleared
08-10 17:07:54.204  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8dc6d8
08-10 17:07:54.205  3866  3866 I BluetoothA2dpServiceJni: cleanupNative
,08-10 17:07:54.205  3866  4041 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-10 17:07:54.206  3866  3866 I GKI_LINUX: GKI_exit_task 2 done
08-10 17:07:54.206  3866  3866 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-10 17:07:54.207  3866  3866 D BluetoothMapService: Received stop request...Stopping profile...
08-10 17:07:54.207  3866  3866 D BluetoothMapService: stop()
08-10 17:07:54.207  3866  3866 D BluetoothMapEmailAppObserver: deinitObservers()
08-10 17:07:54.207  3866  3866 D BluetoothMapEmailAppObserver: removeReceiver()
08-10 17:07:54.208  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8dc6d8
08-10 17:07:54.209  3866  3866 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 17:07:54.209  3866  3866 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 17:07:54.209  3866  3866 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 17:07:54.209  3866  3866 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 17:07:54.209  3866  3866 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 17:07:54.210  3866  3866 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 17:07:54.210  3866  3866 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 17:07:54.211  6815  6815 D BluetoothMap: Proxy object disconnected
08-10 17:07:54.211  6815  6815 D MapProfile: Bluetooth service disconnected
08-10 17:07:54.213  3866  3866 V BluetoothMapService: Handler(): got msg=4
08-10 17:07:54.213  3866  3866 D BluetoothMapService: MAP Service closeService in
08-10 17:07:54.214  3866  3866 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 17:07:54.214  3866  3866 V BluetoothMapService: MAP Service closeService out
08-10 17:07:54.215  3866  3958 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-10 17:07:54.215  3866  3866 D BluetoothMapService: cleanup()
08-10 17:07:54.215  3866  3866 D BluetoothMapService: MAP Service closeService in
08-10 17:07:54.215  3866  3866 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 17:07:54.215  3866  3866 V BluetoothMapService: MAP Service closeService out
08-10 17:07:54.215  3866  3958 D BluetoothAdapterProperties: Setting state to 10
08-10 17:07:54.215  3866  3958 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-10 17:07:54.216  1030  1095 D BluetoothManagerService: Message: 60
08-10 17:07:54.216  1030  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-10 17:07:54.216  1030  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-10 17:07:54.216  3866  3958 I BluetoothAdapterState: Entering OffState
08-10 17:07:54.216  6815  6939 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 17:07:54.217  6891  6891 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 17:07:54.217  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:07:54.222  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 17:07:54.222  1030  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 17:07:54.223  6815  6831 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-10 17:07:54.225  1854  2456 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:07:54.226  6815  6833 D BluetoothPan: onBluetoothStateChange on: false
08-10 17:07:54.227  6815  6939 D BluetoothMap: onBluetoothStateChange: up=false
08-10 17:07:54.228  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:07:54.228  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 17:07:54.229  1030  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:07:54.229  1030  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-10 17:07:54.231  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:07:54.231  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 17:07:54.231  1943  2126 D LGBluetoothAPIService: Message: 2
08-10 17:07:54.232  1943  2126 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@27ec8f4b mBinding = false
08-10 17:07:54.232  1943  2126 D LGBluetoothAPIService: Sending unbind request.
08-10 17:07:54.234  3866  3866 D LGBluetoothAPIServer: [BTUI] onUnbind()
08-10 17:07:54.234  3866  3866 D LGBluetoothAPIServer: [BTUI] cleanup() done
08-10 17:07:54.235  3866  3866 D LGBluetoothAPIServer: [BTUI] onDestroy()
08-10 17:07:54.235  6815  6815 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 17:07:54.236  6815  6815 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-10 17:07:54.236  6815  6815 D LGBluetoothEventManager: [BTUI] clear device connection state
08-10 17:07:54.236  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:07:54.238  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 17:07:54.239  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:54.240  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 17:07:54.240  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 17:07:54.241  6891  6891 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-10 17:07:54.248  6891  6891 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-10 17:07:54.250  3866  3866 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 17:07:54.250  3866  3866 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:07:54.250  3866  3866 V BluetoothPbapReceiver: ***********state = 10
08-10 17:07:54.250  6815  6815 D DockEventReceiver: finishStartingService: stopping service
,08-10 17:07:54.251  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 17:07:54.257  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 17:07:54.259  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 17:07:54.270  6891  6891 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 17:07:54.271  6891  6891 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 17:07:54.276  6891  6891 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 17:07:54.289  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 17:07:54.293  6815  6815 D BluetoothPermissionRequest: onReceive
08-10 17:07:54.297  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-10 17:07:54.297  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 17:07:54.297  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 17:07:54.301  6815  6815 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 17:07:54.301  6815  6815 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-10 17:07:54.309  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 17:07:54.315  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 17:07:54.315  6815  6815 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 17:07:54.331  6891  6891 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 17:07:54.332  6891  6891 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 17:07:54.332  3866  3866 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-10 17:07:54.336  3866  3866 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 17:07:54.337  3866  3866 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 17:07:54.337  3866  3866 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 17:07:54.337  3866  3866 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:07:54.337  3866  3866 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-10 17:07:54.338  6891  6891 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 17:07:54.349  6916  6916 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-10 17:07:54.420  1030  1980 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6944 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-10 17:07:54.536  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 17:07:54.546  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 17:07:54.558  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 17:07:54.569  6944  6966 W FormManager: Network not available. Please check & try again.
,08-10 17:07:54.581  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-10 17:07:54.581  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 17:07:54.581  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 17:07:54.581  6815  6815 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 17:07:54.582  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 17:07:54.590  6944  6967 V FormManager: Network unavailable.
08-10 17:07:54.594  6944  6967 V FormManager: Network unavailable.
,08-10 17:07:54.596  6815  6815 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 17:07:54.597  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 17:07:54.597  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 17:07:54.597  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 17:07:54.597  6815  6815 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 17:07:54.598  6815  6815 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 17:07:54.601  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 17:07:54.601  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 17:07:54.603  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 17:07:54.605  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 17:07:54.613  6834  6834 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-10 17:07:54.613  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 17:07:54.613  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 17:07:54.613  4297  6970 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 17:07:54.617  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 17:07:54.621  4297  6971 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 17:07:54.621  4297  6971 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 17:07:54.628  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 17:07:54.632  6944  6972 W FormManager: Network not available. Please check & try again.
08-10 17:07:54.637  6944  6973 V FormManager: Network unavailable.
08-10 17:07:54.640  6944  6973 V FormManager: Network unavailable.
,08-10 17:07:54.647  1030  2052 I ActivityManager: Killing 5970:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-10 17:07:54.648  6891  6891 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 17:07:54.649  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 17:07:54.649  6891  6891 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-10 17:07:54.687  6891  6891 D LgDataFeature: LgDataFeature() Constructor: none
08-10 17:07:54.688  6891  6891 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 17:07:54.696  6891  6891 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-10 17:07:54.698  1030  1888 W libprocessgroup: failed to open /acct/uid_10011/pid_5970/cgroup.procs: No such file or directory
08-10 17:07:54.702  6891  6891 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-10 17:07:54.702  6891  6891 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-10 17:07:54.703  6891  6891 V SoundPool: doLoad: loading sample sampleID=1
08-10 17:07:54.703  6891  6976 V SoundPool: Start decode
,08-10 17:07:54.703  6891  6976 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-10 17:07:54.705   318   318 V MediaPlayerService: decode(23, 10857164, 17813)
08-10 17:07:54.705   318   318 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-10 17:07:54.705   318   318 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-10 17:07:54.705   318   318 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-10 17:07:54.705   318   318 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-10 17:07:54.705   318   318 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-10 17:07:54.705   318   318 V MediaPlayerService: player type = 3
08-10 17:07:54.705   318   318 V AwesomePlayer: AwesomePlayer create()
08-10 17:07:54.706   318   318 V AwesomePlayer: reset_l() 
08-10 17:07:54.706   318   318 V AwesomePlayer: cancelPlayerEvents
08-10 17:07:54.706   318   318 V AwesomePlayer: setAudioSink() 
08-10 17:07:54.706   318   318 V AwesomePlayer: reset_l() 
08-10 17:07:54.706   318   318 V AudioCache: notify(0xb100a1c0, 8, 0, 0)
08-10 17:07:54.706   318   318 V AudioCache: ignored
08-10 17:07:54.706   318   318 V AwesomePlayer: cancelPlayerEvents
08-10 17:07:54.706   318   318 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-10 17:07:54.706   318   318 V AwesomePlayer: setDataSource_l dataSource
08-10 17:07:54.706   318   318 V LGParserOSAL: SniffLGParser start
08-10 17:07:54.706   318   318 V LGParserOSAL: MainType:5, SubType=0
08-10 17:07:54.706   318   318 V LGParserOSAL: #### check Mime : application/ogg
08-10 17:07:54.706   318   318 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-10 17:07:54.706   318   318 E MediaExtractor: Use LGExtractor :application/ogg 
08-10 17:07:54.707  6891  6891 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 17:07:54.716  6891  6891 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-10 17:07:54.716  6572  6572 D UEI.SmartControl: QS Service created
,08-10 17:07:54.722  6891  6891 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 17:07:54.722  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-10 17:07:54.739  6572  6572 I UEI.SmartControl: Service initServices...
08-10 17:07:54.739  6572  6572 D UEI.SmartControl: QS start get config
08-10 17:07:54.743  6891  6891 V LGMDMManager: Create singleton instance
08-10 17:07:54.747   318   318 V LGParserOSAL: supported mime: application/ogg
08-10 17:07:54.747   318   318 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-10 17:07:54.747   318   318 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-10 17:07:54.747   318   318 V AwesomePlayer: mBitrate = -1 bits/sec
,08-10 17:07:54.747   318   318 V AwesomePlayer: AudioTrack Setting
08-10 17:07:54.747   318   318 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-10 17:07:54.747   318   318 V AwesomePlayer: setAudioSource() 
08-10 17:07:54.747   318   318 V MediaPlayerService: prepare
08-10 17:07:54.747   318   318 V AwesomePlayer: prepareAsync_l() 
08-10 17:07:54.747   318   318 V MediaPlayerService: wait for prepare
08-10 17:07:54.749   318  6977 V AwesomePlayer: onPrepareAsyncEvent() 
08-10 17:07:54.749   318  6977 V AwesomePlayer: initAudioDecoder() 
08-10 17:07:54.749   318  6977 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 17:07:54.749   318  6977 V AudioSystem: isOffloadSupported()
,08-10 17:07:54.749   318  6977 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 17:07:54.749   318  6977 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 17:07:54.749   318  6977 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 17:07:54.749   318  6977 V AwesomePlayer: getUseOffload() = 0 
08-10 17:07:54.749   318  6977 V OMXCodec: OMXCodec::Create
08-10 17:07:54.749   318  6977 V OMXCodec: findMatchingCodecs()
08-10 17:07:54.749   318  6977 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-10 17:07:54.749   318  6977 V OMXCodec: matchingCodecs.size()=1
08-10 17:07:54.749   318  6977 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-10 17:07:54.751   318  6977 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-10 17:07:54.751   318  6977 V LGCodecAdapter: LG Codec Adapter start
08-10 17:07:54.751   318  6977 V OMXCodec: OMXCodec Createtor
08-10 17:07:54.751   318  6977 V OMXCodec: setComponentRole
08-10 17:07:54.751   318  6977 V OMXCodec: configureCodec protected=0
08-10 17:07:54.751   318  6977 V LGCodecAdapter: called getLGCodecSpecificData
08-10 17:07:54.751   318  6977 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
,08-10 17:07:54.751   318  6977 V LGCodecOSAL: Called LGconfigureCodecMETA
08-10 17:07:54.751   318  6977 V LGCodecOSAL: Called LGconfigureCodecMSG
08-10 17:07:54.751   318  6977 V LGCodecOSAL: Not support LGCodec
08-10 17:07:54.751   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 17:07:54.751   318  6977 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
,08-10 17:07:54.751   318  6977 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-10 17:07:54.751   318  6977 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-10 17:07:54.752   318  6977 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 17:07:54.752   318  6977 V AudioSystem: isOffloadSupported()
08-10 17:07:54.752   318  6977 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 17:07:54.752   318  6977 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-10 17:07:54.752   318  6977 V OMXCodec: init()
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-10 17:07:54.752   318  6977 V OMXCodec: allocateBuffers
08-10 17:07:54.752   318  6977 V OMXCodec: allocateBuffersOnPort portIndex=0
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f1f0 on input port
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f8d0 on input port
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f920 on input port
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f970 on input port
08-10 17:07:54.752   318  6977 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f9c0 on output port
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fa60 on output port
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fab0 on output port
08-10 17:07:54.752   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fb50 on output port
08-10 17:07:54.753   318  6977 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 17:07:54.753   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 17:07:54.753   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 17:07:54.753   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-10 17:07:54.753   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-10 17:07:54.753   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-10 17:07:54.753   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-10 17:07:54.753   318  6977 V OMXCodec: init() mAsyncCompletion wait free! 
08-10 17:07:54.753   318  6977 V AwesomePlayer: finishAsyncPrepare_l() 
08-10 17:07:54.753   318  6977 V AudioCache: notify(0xb100a1c0, 5, 0, 0)
08-10 17:07:54.753   318  6977 V AudioCache: ignored
08-10 17:07:54.753   318  6977 V AudioCache: notify(0xb100a1c0, 1, 0, 0)
08-10 17:07:54.753   318  6977 V AudioCache: prepared
08-10 17:07:54.753   318   318 V AudioCache: wait - success
08-10 17:07:54.753   318   318 V MediaPlayerService: start
08-10 17:07:54.753   318   318 V AwesomePlayer: play_l() 
08-10 17:07:54.753   318   318 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-10 17:07:54.753   318   318 V AwesomePlayer: createAudioPlayer_l
08-10 17:07:54.753   318   318 V AwesomePlayer: seekAudioIfNecessary_l() 
08-10 17:07:54.753   318   318 V AwesomePlayer: startAudioPlayer_l() 
08-10 17:07:54.753   318   318 D AudioPlayer: start of Playback, useOffload 0
08-10 17:07:54.753   318   318 V OM,XCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 17:07:54.753   318   318 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952853952
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952854112
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952854192
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952854352
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 17:07:54.756   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-10 17:07:54.757   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-10 17:07:54.757   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-10 17:07:54.757   318  6979 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 17:07:54.757   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 17:07:54.757   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fab0 on output port
08-10 17:07:54.757   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fa60 on output port
08-10 17:07:54.757   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f9c0 on output port
08-10 17:07:54.757   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on output port
08-10 17:07:54.758   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-10 17:07:54.758   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-10 17:07:54.759   318   318 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-10 17:07:54.759   318   318 V AudioCache: notify(0xb100a1c0, 6, 0, 0)
08-10 17:07:54.759   318   318 V AudioCache: ignored
08-10 17:07:54.760   318  6980 V AudioCache: write(0xb57d2000, 4096)
,08-10 17:07:54.760   318  6980 V AudioCache: memcpy(0xb047c000, 0xb57d2000, 4096)
08-10 17:07:54.760   318   318 V MediaPlayerService: wait for playback complete
08-10 17:07:54.761   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.761   318  6980 V AudioCache: memcpy(0xb047d000, 0xb57d2000, 4096)
08-10 17:07:54.761   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.761   318  6980 V AudioCache: memcpy(0xb047e000, 0xb57d2000, 4096)
08-10 17:07:54.762   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.762   318  6980 V AudioCache: memcpy(0xb047f000, 0xb57d2000, 4096)
08-10 17:07:54.763   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.763   318  6980 V AudioCache: memcpy(0xb0480000, 0xb57d2000, 4096)
08-10 17:07:54.763   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.763   318  6980 V AudioCache: memcpy(0xb0481000, 0xb57d2000, 4096)
08-10 17:07:54.764   318  6980 V AudioCache: write(0xb57d2000, 4096)
,08-10 17:07:54.764   318  6980 V AudioCache: memcpy(0xb0482000, 0xb57d2000, 4096)
,08-10 17:07:54.764   318  6980 V AudioCache: write(0xb57d2000, 4096),
08-10 17:07:54.764   318  6980 V AudioCache: memcpy(0xb0483000, 0xb57d2000, 4096)
08-10 17:07:54.765   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.765   318  6980 V AudioCache: memcpy(0xb0484000, 0xb57d2000, 4096)
08-10 17:07:54.766   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.766   318  6980 V AudioCache: memcpy(0xb0485000, 0xb57d2000, 4096)
,08-10 17:07:54.766   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.766   318  6980 V AudioCache: memcpy(0xb0486000, 0xb57d2000, 4096)
08-10 17:07:54.767   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.767   318  6980 V AudioCache: memcpy(0xb0487000, 0xb57d2000, 4096)
08-10 17:07:54.767   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.767   318  6980 V AudioCache: memcpy(0xb0488000, 0xb57d2000, 4096)
,08-10 17:07:54.775   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.775   318  6980 V AudioCache: memcpy(0xb0489000, 0xb57d2000, 4096)
,08-10 17:07:54.777   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.777   318  6980 V AudioCache: memcpy(0xb048a000, 0xb57d2000, 4096)
08-10 17:07:54.777   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.777   318  6980 V AudioCache: memcpy(0xb048b000, 0xb57d2000, 4096)
08-10 17:07:54.778   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.778   318  6980 V AudioCache: memcpy(0xb048c000, 0xb57d2000, 4096)
08-10 17:07:54.778   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.778   318  6980 V AudioCache: memcpy(0xb048d000, 0xb57d2000, 4096)
08-10 17:07:54.778   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.778   318  6980 V AudioCache: memcpy(0xb048e000, 0xb57d2000, 4096)
08-10 17:07:54.779   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.779   318  6980 V AudioCache: memcpy(0xb048f000, 0xb57d2000, 4096)
08-10 17:07:54.779   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.779   318  6980 V AudioCache: memcpy(0xb0490000, 0xb57d2000, 4096)
08-10 17:07:54.779   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.779   318  6980 V AudioCache: memcpy(0xb0491000, 0xb57d2000, 4096)
08-10 17:07:54.780   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.780   318  6980 V AudioCache: memcpy(0xb0492000, 0xb57d2000, 4096)
08-10 17:07:54.780   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.780   318  6980 V AudioCache: memcpy(0xb0493000, 0xb57d2000, 4096)
08-10 17:07:54.781   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.781   318  6980 V AudioCache: memcpy(0xb0494000, 0xb57d2000, 4096)
08-10 17:07:54.781   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.781   318  6980 V AudioCache: memcpy(0xb0495000, 0xb57d2000, 4096)
08-10 17:07:54.781   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.781   318  6980 V AudioCache: memcpy(0xb0496000, 0xb57d2000, 4096)
08-10 17:07:54.782   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.782   318  6980 V AudioCache: memcpy(0xb0497000, 0xb57d2000, 4096)
08-10 17:07:54.782   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.782   318  6980 V AudioCache: memcpy(0xb0498000, 0xb57d2000, 4096)
08-10 17:07:54.783   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.783   318  6980 V AudioCache: memcpy(0xb0499000, 0xb57d2000, 4096)
08-10 17:07:54.783   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.783   318  6980 V AudioCache: memcpy(0xb049a000, 0xb57d2000, 4096)
08-10 17:07:54.783   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.783   318  6980 V AudioCache: memcpy(0xb049b000, 0xb57d2000, 4096)
08-10 17:07:54.784   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.784   318  6980 V AudioCache: memcpy(0xb049c000, 0xb57d2000, 4096)
08-10 17:07:54.784   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.784   318  6980 V AudioCache: memcpy(0xb049d000, 0xb57d2000, 4096)
08-10 17:07:54.785   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.785   318  6980 V AudioCache: memcpy(0xb049e000, 0xb57d2000, 4096)
08-10 17:07:54.788   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.788   318  6980 V AudioCache: memcpy(0xb049f000, 0xb57d2000, 4096)
08-10 17:07:54.788   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.788   318  6980 V AudioCache: memcpy(0xb04a0000, 0xb57d2000, 4096)
08-10 17:07:54.789   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.789   318  6980 V AudioCache: memcpy(0xb04a1000, 0xb57d2000, 4096)
,08-10 17:07:54.794   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.794   318  6980 V AudioCache: memcpy(0xb04a2000, 0xb57d2000, 4096)
08-10 17:07:54.795   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.795   318  6980 V AudioCache: memcpy(0xb04a3000, 0xb57d2000, 4096)
08-10 17:07:54.796   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.796   318  6980 V AudioCache: memcpy(0xb04a4000, 0xb57d2000, 4096)
08-10 17:07:54.797   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.797   318  6980 V AudioCache: memcpy(0xb04a5000, 0xb57d2000, 4096)
,08-10 17:07:54.797   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.797   318  6980 V AudioCache: memcpy(0xb04a6000, 0xb57d2000, 4096)
08-10 17:07:54.798   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.798   318  6980 V AudioCache: memcpy(0xb04a7000, 0xb57d2000, 4096)
08-10 17:07:54.799   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.799   318  6980 V AudioCache: memcpy(0xb04a8000, 0xb57d2000, 4096)
08-10 17:07:54.800   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.800   318  6980 V AudioCache: memcpy(0xb04a9000, 0xb57d2000, 4096)
08-10 17:07:54.800   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.800   318  6980 V AudioCache: memcpy(0xb04aa000, 0xb57d2000, 4096)
08-10 17:07:54.801   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.801   318  6980 V AudioCache: memcpy(0xb04ab000, 0xb57d2000, 4096)
08-10 17:07:54.802   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.802   318  6980 V AudioCache: memcpy(0xb04ac000, 0xb57d2000, 4096)
08-10 17:07:54.802   318  6980 V AudioCache: write(0xb57d2000, 4096)
08-10 17:07:54.802   318  6980 V AudioCache: memcpy(0xb04ad000, 0xb57d2000, 4096)
08-10 17:07:54.803   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-10 17:07:54.803   318  6980 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-10 17:07:54.803   318  6980 V AwesomePlayer: postAudioEOS() 
08-10 17:07:54.803   318  6980 V AudioCache: write(0xb57d2000, 280)
08-10 17:07:54.803   318  6980 V AudioCache: memcpy(0xb04ae000, 0xb57d2000, 280)
08-10 17:07:54.807   318  6977 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-10 17:07:54.807   318  6977 V AwesomePlayer: onStreamDone
08-10 17:07:54.807   318  6977 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-10 17:07:54.807   318  6977 V AudioCache: notify(0xb100a1c0, 2, 0, 0)
08-10 17:07:54.807   318  6977 V AudioCache: playback complete
08-10 17:07:54.807   318  6977 V AwesomePlayer: pause_l() 
08-10 17:07:54.807   318  6977 V AudioCache: notify(0xb100a1c0, 7, 0, 0)
08-10 17:07:54.807   318  6977 V AudioCache: ignored
08-10 17:07:54.807   318  6977 V AwesomePlayer: cancelPlayerEvents
08-10 17:07:54.807   318   318 V AudioCache: wait - success
08-10 17:07:54.807   318   318 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-10 17:07:54.807   318  6977 D AudioPlayer: Pause Playback at 1068125
08-10 17:07:54.809   318   318 V AwesomePlayer: reset_l() 
08-10 17:07:54.809   318   318 V AudioCache: notify(0xb100a1c0, 8, 0, 0)
08-10 17:07:54.809   318   318 V AudioCache: ignored
08-10 17:07:54.809   318   318 V AwesomePlayer: cancelPlayerEvents
08-10 17:07:54.809   318   318 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-10 17:07:54.809   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-10 17:07:54.809   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-10 17:07:54.809   318   318 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-10 17:07:54.809   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f970 on port 0
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f920 on port 0
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f8d0 on port 0
08,-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f1f0 on port 0
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 1
08-10 17:07:54.809   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-10 17:07:54.810   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f9c0 on port 1
08-10 17:07:54.810   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-10 17:07:54.810   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fa60 on port 1
08-10 17:07:54.810   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-10 17:07:54.810   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fab0 on port 1
08-10 17:07:54.810   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 17:07:54.810   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-10 17:07:54.810   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 17:07:54.810   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 17:07:54.810   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-10 17:07:54.810   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-10 17:07:54.810   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-10 17:07:54.810   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 17:07:54.810   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-10 17:07:54.810   318   318 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-10 17:07:54.811   318   318 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-10 17:07:54.811   318   318 D AudioPlayer: AudioPlayer releasing audio source
08-10 17:07:54.811   318   318 D AudioPlayer: AudioPlayer done releasing audio source
08-10 17:07:54.811   318   318 V AwesomePlayer: reset_l() 
08-10 17:07:54.812   318   318 V AwesomePlayer: cancelPlayerEvents
08-10 17:07:54.812   318   318 V AwesomePlayer: ~AwesomePlayer call
08-10 17:07:54.812   318   318 V AwesomePlayer: reset_l() 
08-10 17:07:54.812   318   318 V AwesomePlayer: cancelPlayerEvents
08-10 17:07:54.812  6891  6976 V SoundPool: close(31)
08-10 17:07:54.812  6891  6976 V SoundPool: pointer = 0x9ffd6000, size = 205080, sampleRate = 48000, numChannels = 2
08-10 17:07:54.832  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-10 17:07:54.835  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-10 17:07:54.840  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4371
,08-10 17:07:55.050  6572  6572 I UEI.SmartControl: Supports setup maps: true
08-10 17:07:55.053  6572  6572 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 17:07:55.053  6572  6572 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-10 17:07:55.053  6572  6572 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 17:07:55.053  6572  6572 I UEI.SmartControl: ### init IR Blaster...
,08-10 17:07:55.057  6572  6572 D serial_port: Configuring serial port
,08-10 17:07:55.057  6572  6572 E UEI.SmartControl: UEIBLaster setting for 616
08-10 17:07:55.057  6572  6572 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 17:07:55.057  6572  6572 I UEI.SmartControl: configuring settings for MAXQ616
08-10 17:07:55.057  6572  6572 I UEI.SmartControl: Get version...
08-10 17:07:55.076  6572  6986 D UEI.SmartControl: serial port data available: 21
,08-10 17:07:55.102  6572  6572 D UEI.SmartControl: MAXQ616 A2-X4 software.,
,08-10 17:07:55.102  6572  6572 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 17:07:55.102  6572  6572 I UEI.SmartControl: QS saving settings...
,08-10 17:07:55.103  6572  6572 D UEI.SmartControl: IR Blaster version: 25672567,
,08-10 17:07:55.119  6572  6986 D UEI.SmartControl: serial port data available: 4,
,08-10 17:07:55.152  6572  6572 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-10 17:07:55.155  6572  6572 E UEI.SmartControl: Services init done
08-10 17:07:55.155  6572  6572 D UEI.SmartControl: QS Service init finished
08-10 17:07:55.160  6572  6995 I UEI.SmartControl: Device manager: loading config....
,08-10 17:07:55.161  6572  6995 D UEI.SmartControl: ----------- loading internal config...
08-10 17:07:55.162  6572  6572 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 17:07:55.162  6572  6572 D UEI.SmartControl: QS Service version code: 201091
08-10 17:07:55.166  6572  6572 D UEI.SmartControl: Service requested: Control
08-10 17:07:55.171  6572  6995 E UEI.SmartControl: Loading SETTINGS...
08-10 17:07:55.172  6572  6572 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-10 17:07:55.176  6572  6572 D UEI.SmartControl: Internal service binding...
08-10 17:07:55.177  6891  6891 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-10 17:07:55.178  6572  6588 I UEI.SmartControl: ------ IControl API: 11
08-10 17:07:55.178  6572  6588 D UEI.SmartControl: File observer start...
08-10 17:07:55.179  6572  6588 E UEI.SmartControl: IR Port is disabled: false
08-10 17:07:55.179  6572  6588 D UEI.SmartControl: Starting file observer...
08-10 17:07:55.179  6572  6588 I UEI.SmartControl: Registering callback...
08-10 17:07:55.182  6572  6587 I UEI.SmartControl: ------ IControl API: 19
08-10 17:07:55.183  6572  6587 I UEI.SmartControl: Registering Services Ready callback...
08-10 17:07:55.186  6572  6995 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-10 17:07:55.208  6572  6994 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-10 17:07:55.209  6891  6906 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-10 17:07:55.210  6572  6994 D UEI.SmartControl: -----service ready thread exits
08-10 17:07:55.210  6891  6974 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-10 17:07:55.211  6891  6974 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-10 17:07:55.212  6891  6891 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-10 17:07:55.213  6891  6891 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-10 17:07:55.214  6572  6588 I UEI.SmartControl: ------ IControl API: 8
08-10 17:07:55.217  6891  6891 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-10 17:07:55.218  6891  6891 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-10 17:07:55.218  6891  6891 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-10 17:07:55.219  6891  6891 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-10 17:07:55.221  6891  6891 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,08-10 17:07:55.222  6891  6891 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-10 17:07:55.225  6891  6891 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-10 17:07:55.229  6891  6891 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 17:07:55.231  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 17:07:55.236  6891  6891 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 17:07:55.237  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-10 17:07:55.242  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 17:07:55.244  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-10 17:07:55.247  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-10 17:07:55.248  6891  6891 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470841675248]
08-10 17:07:55.252  6891  6891 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-10 17:07:55.255  1030  1576 I ActivityManager: Killing 5993:com.android.contacts/u0a19 (adj 15): empty #17
08-10 17:07:55.279  6891  6997 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-10 17:07:55.348  1030  1760 W libprocessgroup: failed to open /acct/uid_10019/pid_5993/cgroup.procs: No such file or directory
,08-10 17:07:55.365  6891  6891 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-10 17:07:55.367  6891  6891 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-10 17:07:55.367  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-10 17:07:55.368  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-10 17:07:55.368  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-10 17:07:55.369  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-10 17:07:55.369  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-10 17:07:55.388  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-10 17:07:56.113  1030  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 17:07:56.129  1030  1095 D Tethering: MasterInitialState.processMessage what=3
08-10 17:07:56.133  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:07:56.140  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:56.145  1030  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 17:07:56.148  1030  1095 D Tethering: MasterInitialState.processMessage what=3
08-10 17:07:56.157  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:07:56.161  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:07:56.162  1030  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 17:07:56.164  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 17:07:56.168  6359  6811 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 17:07:56.179  5236  5236 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-10 17:07:56.188  5236  5236 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-10 17:07:56.205  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 17:07:56.245  1030  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-10 17:07:56.264  1030  1941 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7010 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-10 17:07:56.282  1030  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 17:07:56.282  1030  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 17:07:56.390  7010  7010 I AppUp4:AppBoxCP: onCreate
,08-10 17:07:56.391  7010  7010 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-10 17:07:56.402  7010  7010 I AppUp4:DB:  setFingerPrint start
08-10 17:07:56.403  7010  7010 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-10 17:07:56.412  7010  7010 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-10 17:07:56.412  7010  7010 I AppUp4:DB:  SDK version = 21
08-10 17:07:56.412  7010  7010 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-10 17:07:56.415  7010  7010 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-10 17:07:56.416  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 17:07:56.417  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-10 17:07:56.420  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-10 17:07:56.420  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 17:07:56.427  7010  7010 I AppUp4:CustModeStarterReceiver: onReceive
08-10 17:07:56.474  7010  7010 D LgDataFeature: LgDataFeature() Constructor: none
08-10 17:07:56.474  7010  7010 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 17:07:56.483  7010  7010 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d0761bb
08-10 17:07:56.483  7010  7010 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 17:07:56.483  7010  7010 D AppUp4:CustFacade: isPhone : true
08-10 17:07:56.483  7010  7010 D AppUp4:CustModeStarterReceiver: begin check event
08-10 17:07:56.484  7010  7010 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-10 17:07:56.484  7010  7010 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-10 17:07:56.485  7010  7044 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-10 17:07:56.485  7010  7044 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-10 17:07:56.486  7010  7044 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-10 17:07:56.488  1030  1960 I ActivityManager: Killing 6456:com.lge.email/u0a23 (adj 15): empty #17
08-10 17:07:56.527  1030  1906 W libprocessgroup: failed to open /acct/uid_10023/pid_6456/cgroup.procs: No such file or directory
08-10 17:07:56.529  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 17:07:56.529  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-10 17:07:56.534  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 17:07:56.537  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 17:07:56.545  4297  7046 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-10 17:07:56.550  4297  7047 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-10 17:07:56.550  4297  7047 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 17:07:56.601  1030  1045 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7052 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-10 17:07:56.681  7052  7052 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 17:07:56.682  7052  7052 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 17:07:56.684  7052  7052 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 17:07:56.684  7052  7052 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 17:07:56.781  7052  7052 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-10 17:07:56.797  7052  7052 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-10 17:07:56.856  7052  7052 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-10 17:07:56.911  7052  7052 D LgDataFeature: LgDataFeature() Constructor: none
08-10 17:07:56.911  7052  7052 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 17:07:57.042  7052  7052 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 17:07:57.075  7052  7052 I HubEmail: JNI_OnLoad()
08-10 17:07:57.075  7052  7052 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 17:07:57.075  7052  7052 I HubEmail: registerNatives()
08-10 17:07:57.075  7052  7052 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 17:07:57.075  7052  7052 I HubEmail: registerNativeMethods()
08-10 17:07:57.075  7052  7052 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 17:07:57.076  7052  7052 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-10 17:07:57.090  7052  7076 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 17:07:57.099  3479  3479 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 17:07:57.099  3479  3479 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 17:07:57.099  3479  3479 I LgeMiscReceiver: networkInfo.isConnected() = false
08-10 17:07:57.137  1030  1707 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7081 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-10 17:07:57.148  6944  7079 V FormManager: Network unavailable.
08-10 17:07:57.151  6944  7079 V FormManager: Network unavailable.
08-10 17:07:57.155  6944  7078 W FormManager: Network not available. Please check & try again.
,08-10 17:07:57.159  1030  2053 I ActivityManager: Killing 6016:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-10 17:07:57.259  1030  1960 W libprocessgroup: failed to open /acct/uid_10027/pid_6016/cgroup.procs: No such file or directory
,08-10 17:07:57.363  7081  7081 D LgDataFeature: LgDataFeature() Constructor: none
08-10 17:07:57.363  7081  7081 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 17:07:57.367  7081  7081 D PhoneMonitor: Register our PhoneStateListener
,08-10 17:07:57.396  7081  7081 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-10 17:07:57.401  7081  7081 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-10 17:07:57.423  7081  7081 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-10 17:07:57.424  7081  7081 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-10 17:07:57.425  7081  7081 D TelephonyAutoProfiling: [parse] Load xml
,08-10 17:07:57.431  7081  7081 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
,08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-10 17:07:57.432  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-10 17:07:57.432  7081  7081 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-10 17:07:57.449  7081  7081 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-10 17:07:57.457  1030  1960 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7100 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-10 17:07:57.460  1030  1960 I ActivityManager: Killing 6085:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-10 17:07:57.508  1030  2016 W libprocessgroup: failed to open /acct/uid_10080/pid_6085/cgroup.procs: No such file or directory
,08-10 17:07:57.701  1030  1960 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7118 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-10 17:07:57.702  1030  1960 I ActivityManager: Killing 6487:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-10 17:07:57.776  1030  1961 W libprocessgroup: failed to open /acct/uid_10061/pid_6487/cgroup.procs: No such file or directory
,08-10 17:07:57.877  1030  1942 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7140 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-10 17:07:57.880  1030  1942 I ActivityManager: Killing 6108:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-10 17:07:57.937  1030  1961 W libprocessgroup: failed to open /acct/uid_10097/pid_6108/cgroup.procs: No such file or directory
,08-10 17:07:57.982  7140  7140 I art     : Almond Protected OAT
,08-10 17:07:58.043  7140  7140 D WeatherApplication: removeAccount
08-10 17:07:58.044  1030  1536 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 17:07:58.044  1030  1536 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 17:07:58.048  7140  7140 D WeatherApplication: Account.length = 0
08-10 17:07:58.048  7140  7140 E WeatherApplication: OPERATOR:OPEN
08-10 17:07:58.054  7140  7140 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:58
08-10 17:07:58.058  7140  7140 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 17:07:58.058  7140  7140 D Weather.Utils: 2 : All the weather widget is gone.
,08-10 17:07:58.061  1030  1537 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 17:07:58.062  1030  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 17:07:58.065  7140  7140 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 17:07:58.071  7140  7140 D WeatherAncestor: connectivity changed - connection : true
,08-10 17:07:58.074  7140  7140 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-10 17:07:58.083  7140  7140 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 17:07:58.083  7140  7140 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 17:07:58.084  7140  7140 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-10 17:07:58.104  7140  7140 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-10 17:07:58.105  7140  7140 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:58
,08-10 17:07:58.149  1030  2052 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7162 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 17:07:58.150  1030  2052 I ActivityManager: Killing 6528:com.lge.eula/1000 (adj 15): empty #17
,08-10 17:07:58.232  1030  1980 W libprocessgroup: failed to open /acct/uid_1000/pid_6528/cgroup.procs: No such file or directory
08-10 17:07:58.331   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 17:07:58.331   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 17:07:58.331   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
,08-10 17:07:58.333  7162  7185 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 17:07:58.341   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 17:07:58.341   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 17:07:58.341   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
,08-10 17:07:58.342  7162  7185 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 17:07:58.350   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 17:07:58.350   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 17:07:58.350   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 17:07:58.351  7162  7189 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 17:07:58.354   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 17:07:58.354   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 17:07:58.354   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 17:07:58.355  7162  7189 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-10 17:07:58.620  7162  7162 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 17:07:58.632  7162  7162 I LibraryLoader: Loading: webviewchromium
08-10 17:07:58.636  7162  7162 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 1265-1271)
,08-10 17:07:58.636  7162  7162 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 17:07:58.647  7162  7162 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {eb90ab4}
08-10 17:07:58.648  7162  7162 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 17:07:58.649  7162  7162 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 17:07:58.665  7162  7162 I BrowserStartupController: Initializing chromium process, renderers=0
,08-10 17:07:58.666  7162  7162 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 17:07:58.686   318  1750 V AudioPolicyService: registerClient() client 0xb0010520, uid 10093
,08-10 17:07:58.689  7162  7162 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 17:07:58.690  7162  7162 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-10 17:07:58.690  7162  7162 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-10 17:07:58.692  7162  7213 W AudioManagerAndroid: Requires BLUETOOTH permission
08-10 17:07:58.719  7162  7162 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 17:07:58.719  7162  7162 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 17:07:58.719  7162  7162 I Adreno-EGL: Build Date: 12/12/14 금
08-10 17:07:58.719  7162  7162 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 17:07:58.719  7162  7162 I Adreno-EGL: Remote Branch: 
08-10 17:07:58.719  7162  7162 I Adreno-EGL: Local Patches: 
08-10 17:07:58.719  7162  7162 I Adreno-EGL: Reconstruct Branch: 
,08-10 17:07:58.802  7162  7162 I NSApplication: Starting up...
,08-10 17:07:58.855  1030  1760 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7226 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-10 17:07:58.861  1030  1760 I ActivityManager: Killing 6038:com.android.vending/u0a44 (adj 15): empty #17
08-10 17:07:58.915  1030  1760 I ActivityManager: Killing 6546:com.lge.bnr/1000 (adj 15): empty #18
,08-10 17:07:58.970  1030  1888 W libprocessgroup: failed to open /acct/uid_10044/pid_6038/cgroup.procs: No such file or directory
08-10 17:07:58.973  1030  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_6546/cgroup.procs: No such file or directory
08-10 17:07:59.003  7226  7226 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 17:07:59.251  1030  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1d48d931 type 2 when 351874 com.google.android.gms} when 351874
,08-10 17:07:59.352  1030  1906 I art     : Explicit concurrent mark sweep GC freed 57365(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.645ms total 155.337ms
,08-10 17:07:59.409  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 17:07:59.410  6359  6811 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-10 17:07:59.431  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 17:07:59.446  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 17:07:59.446  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 17:07:59.446  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 17:07:59.446  7010  7010 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 17:07:59.449  7010  7010 I AppUp4:CustModeStarterReceiver: onReceive
,08-10 17:07:59.452  7010  7010 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d0761bb
08-10 17:07:59.452  7010  7010 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 17:07:59.452  7010  7010 D AppUp4:CustFacade: isPhone : true
08-10 17:07:59.453  7010  7010 D AppUp4:CustModeStarterReceiver: begin check event
08-10 17:07:59.453  7010  7010 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 17:07:59.456  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 17:07:59.456  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 17:07:59.460  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 17:07:59.463  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 17:07:59.469  7052  7052 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-10 17:07:59.480  3479  3479 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 17:07:59.480  3479  3479 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 17:07:59.480  3479  3479 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-10 17:07:59.481  7081  7081 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 17:07:59.481  7081  7081 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 17:07:59.496  7140  7140 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:59
,08-10 17:07:59.499  7140  7140 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 17:07:59.499  7140  7140 D Weather.Utils: 2 : All the weather widget is gone.
08-10 17:07:59.499  7140  7140 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 17:07:59.500  7140  7140 D WeatherAncestor: connectivity changed - connection : true
08-10 17:07:59.500  7140  7140 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3b03aa31
08-10 17:07:59.501  7052  7261 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 17:07:59.502  7140  7140 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 17:07:59.502  7140  7140 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 17:07:59.502  4297  7262 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 17:07:59.502  7140  7140 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 17:07:59.502  7140  7140 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 17:07:59.502  7140  7140 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:59
08-10 17:07:59.504  4297  7264 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 17:07:59.504  4297  7264 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 17:07:59.522  6944  7259 W FormManager: Network not available. Please check & try again.
,08-10 17:07:59.527  6944  7260 V FormManager: Network unavailable.
08-10 17:07:59.532  6944  7260 V FormManager: Network unavailable.
08-10 17:07:59.541   312  7274 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-10 17:07:59.542  1030  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-10 17:08:00.003  1030  1385 D PowerManagerServiceEx: acquireWakeLockInternal: lock=522380000, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,08-10 17:08:00.024  6891  6891 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-10 17:08:00.037  6891  6891 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4371
08-10 17:08:00.063  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 17:08:00.074  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:08:00.074  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:08:00.075  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:08:00.076  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:08:00.080  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:08:00.080  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:08:00.080  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:08:00.084  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:08:00.129  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=522380000 [*alarm*], flags=0x0
,08-10 17:08:00.150  6572  6996 D UEI.SmartControl: Internal timer expired: 2
08-10 17:08:00.150  6572  6996 D UEI.SmartControl: unbind internal service
,08-10 17:08:00.196  6572  6990 D serial_port: close(fd = 24)
,08-10 17:08:00.207  6572  6990 I UEI.SmartControl: Serial port is closed.
,08-10 17:08:01.099  1030  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{cf2b08f type 2 when 353718 com.google.android.gms} when 353718
,08-10 17:08:03.120  1030  1544 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-10 17:08:03.377  7162  7187 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-10 17:08:04.210  1030  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{114432c6 type 2 when 356830 com.google.android.gms} when 356830
,08-10 17:08:04.231   312  7289 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-10 17:08:04.238  1030  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 17:08:10.425  1030  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2ca62287 type 2 when 363044 com.google.android.gms} when 363044
,08-10 17:08:10.448   312  7291 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-10 17:08:10.457  1030  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 17:08:22.968  1030  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1cac05b4 type 2 when 375445 com.google.android.gms} when 375445
,08-10 17:08:22.995   312  7293 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-10 17:08:22.999  1030  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 17:08:50.931  1030  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3c3375dd type 2 when 400362 com.google.android.gms} when 400362
,08-10 17:08:50.965   312  7295 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-10 17:08:50.969  1030  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 17:09:00.100  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:09:00.100  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:09:00.101  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:09:00.101  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:09:00.116  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:09:00.116  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:09:00.118  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:09:00.120  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 17:09:52.755  1030  1385 D PowerManagerServiceEx: acquireWakeLockInternal: lock=522380000, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,08-10 17:09:52.770  1030  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{15c0b552 type 2 when 453068 com.google.android.gms} when 453068
08-10 17:09:52.795   312  7298 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-10 17:09:52.800  1030  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 17:09:52.812  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 17:09:52.841  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=522380000 [*alarm*], flags=0x0
,08-10 17:10:00.061  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:10:00.061  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:10:00.061  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:10:00.062  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:10:00.076  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:10:00.076  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:10:00.078  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:10:00.079  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:11:00.112  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:11:00.112  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:11:00.112  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:11:00.113  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:11:00.127  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:11:00.127  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:11:00.128  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:11:00.128  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:11:16.689  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-10 17:11:16.689  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-10 17:11:16.706  1030  1543 D WifiController: battery changed pluggedType: 2
,08-10 17:11:16.710  1943  2119 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-10 17:11:16.710  1943  2119 D LEDHandler: Battery Level Remaining: 100%
08-10 17:11:16.710  1943  2119 D LEDHandler: Battery Temp: 278, mChargingStatus=5, mChargingStop=false
08-10 17:11:16.715  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
08-10 17:11:16.715  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-10 17:11:16.716  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-10 17:12:00.093  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:12:00.093  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:12:00.093  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:12:00.094  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:12:00.108  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:12:00.108  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:12:00.109  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:12:00.110  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:12:22.107  1030  1385 D PowerManagerServiceEx: acquireWakeLockInternal: lock=522380000, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,08-10 17:12:22.123  1030  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{9b86023 type 2 when 564416 com.google.android.gms} when 564416
08-10 17:12:22.145   312  7300 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-10 17:12:22.150  1030  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 17:12:22.162  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 17:12:22.189  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=522380000 [*alarm*], flags=0x0
,08-10 17:13:00.088  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:13:00.089  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:13:00.089  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:13:00.089  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:13:00.103  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:13:00.103  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:13:00.107  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:13:00.110  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 17:14:00.113  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:14:00.114  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:14:00.114  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:14:00.114  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:14:00.128  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:14:00.128  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:14:00.129  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:14:00.129  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:15:00.109  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:15:00.109  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:15:00.109  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:15:00.110  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:15:00.124  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:15:00.124  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:15:00.127  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:15:00.129  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 17:15:01.246  1030  1385 D PowerManagerServiceEx: acquireWakeLockInternal: lock=522380000, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,08-10 17:15:01.345  1030  1090 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7311 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-10 17:15:01.365   340   340 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 484us total 42.884ms
,08-10 17:15:01.399  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 17:15:01.411   340   340 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 37.617ms
08-10 17:15:01.455   340   340 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 41.662ms
,08-10 17:15:01.522  7311  7311 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-10 17:15:01.526  7311  7311 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@29b117ec
,08-10 17:15:01.526  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=522380000 [*alarm*], flags=0x0
08-10 17:15:01.526  1030  1046 I ActivityManager: Killing 6858:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-10 17:15:01.588  1030  1942 W libprocessgroup: failed to open /acct/uid_10037/pid_6858/cgroup.procs: No such file or directory
,08-10 17:15:03.521  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-10 17:15:03.522  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-10 17:15:03.542  1943  2119 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-10 17:15:03.542  1943  2119 D LEDHandler: Battery Level Remaining: 100%
08-10 17:15:03.542  1943  2119 D LEDHandler: Battery Temp: 274, mChargingStatus=5, mChargingStop=false
,08-10 17:15:03.546  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
08-10 17:15:03.546  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-10 17:15:03.548  1030  1543 D WifiController: battery changed pluggedType: 2
08-10 17:15:03.550  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-10 17:16:00.110  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:16:00.110  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:16:00.110  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:16:00.111  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:16:00.126  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:16:00.126  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:16:00.127  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:16:00.128  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 17:16:21.499  1030  1385 D PowerManagerServiceEx: acquireWakeLockInternal: lock=522380000, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,08-10 17:16:21.514  1030  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{eddc920 type 2 when 812709 com.google.android.gms} when 812709
08-10 17:16:21.535   312  7357 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-10 17:16:21.540  1030  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 17:16:21.552  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 17:16:21.579  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=522380000 [*alarm*], flags=0x0
,08-10 17:16:38.669  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-10 17:16:38.669  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-10 17:17:00.073  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:17:00.073  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:17:00.073  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:17:00.074  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:17:00.088  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:17:00.088  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:17:00.089  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:17:00.089  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:17:49.938  1030  1385 D PowerManagerServiceEx: acquireWakeLockInternal: lock=522380000, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,08-10 17:17:49.957  1030  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{167692d9 type 2 when 942561 com.android.bluetooth} when 942561
,08-10 17:17:49.993  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 17:17:50.019  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=522380000 [*alarm*], flags=0x0
,08-10 17:18:00.055  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-10 17:18:00.055  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:18:00.055  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-10 17:18:00.056  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:18:00.070  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:18:00.071  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:18:00.072  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:18:00.074  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:19:00.111  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:19:00.111  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:19:00.112  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:19:00.112  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:19:00.127  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:19:00.127  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:19:00.128  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:19:00.129  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:20:00.112  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:20:00.112  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:20:00.112  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:20:00.113  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:20:00.127  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:20:00.127  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:20:00.128  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:20:00.128  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:21:00.109  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:21:00.110  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:21:00.110  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:21:00.110  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:21:00.125  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:21:00.126  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:21:00.127  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:21:00.129  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 17:22:00.112  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:22:00.112  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:22:00.112  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:22:00.113  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:22:00.127  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:22:00.127  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:22:00.128  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:22:00.128  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:22:27.486  1030  1089 I UsageStatsService: User[0] Flushing usage stats to disk
,08-10 17:23:00.071  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:23:00.072  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:23:00.072  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:23:00.072  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:23:00.087  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:23:00.087  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:23:00.089  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:23:00.091  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 17:24:00.112  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:24:00.112  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:24:00.113  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:24:00.113  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:24:00.127  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:24:00.127  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:24:00.128  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:24:00.128  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:25:00.110  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:25:00.110  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:25:00.110  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:25:00.110  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:25:00.126  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:25:00.126  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:25:00.127  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:25:00.129  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 17:26:00.074  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:26:00.075  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-10 17:26:00.083  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:26:00.084  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
08-10 17:26:00.088  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:26:00.088  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:26:00.089  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:26:00.090  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:27:00.108  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:27:00.108  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:27:00.108  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:27:00.109  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:27:00.124  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:27:00.124  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:27:00.127  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:27:00.128  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 17:27:20.430  1030  1385 D PowerManagerServiceEx: acquireWakeLockInternal: lock=522380000, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,08-10 17:27:20.446  1030  1385 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1e10d49e type 2 when 1249986 com.google.android.gms} when 1249986
08-10 17:27:20.465   312  7372 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-10 17:27:20.470  1030  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 17:27:20.482  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 17:27:20.509  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=522380000 [*alarm*], flags=0x0
,08-10 17:28:00.092  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:28:00.092  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:28:00.092  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:28:00.093  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:28:00.107  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:28:00.107  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:28:00.108  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:28:00.108  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:29:00.109  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:29:00.109  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:29:00.109  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:29:00.110  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:29:00.124  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:29:00.125  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:29:00.127  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:29:00.130  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 17:30:00.115  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 17:30:00.116  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 17:30:00.116  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 17:30:00.116  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-10 17:30:00.129  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 17:30:00.129  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:30:00.130  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-10 17:30:00.130  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 17:30:01.526  1030  1385 D PowerManagerServiceEx: acquireWakeLockInternal: lock=522380000, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,08-10 17:30:01.542  7311  7311 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
08-10 17:30:01.554  7311  7311 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@29b117ec
,08-10 17:30:01.583  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 17:30:01.607  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=522380000 [*alarm*], flags=0x0
,TIME-OUT KILL (timeout was 1400000ms)
```
