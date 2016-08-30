#### Test 82883341e52143e_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 09:35:00.091  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
08-30 09:35:00.101  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 09:35:00.101  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-30 09:35:00.103  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-30 09:35:00.105  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 09:35:04.356  6802  6802 D AndroidRuntime: 
08-30 09:35:04.356  6802  6802 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 09:35:04.362  6802  6802 D AndroidRuntime: CheckJNI is OFF
08-30 09:35:04.562  6802  6802 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 09:35:04.572  1027  2096 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 09:35:04.588  1958  1980 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 09:35:04.594  1027  2096 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 09:35:04.596  1027  2096 D ActivityManager: setTaskToReturnTo : TaskRecord{17a5c482 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 09:35:04.596  1027  2096 D ActivityManager: setTaskToReturnTo : TaskRecord{17a5c482 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 09:35:04.598  1027  2096 D WindowStateEx: AppWindowTokenEx init.. 
08-30 09:35:04.599   335   358 E GBMv2   : DFP En is all cleared set to be enabled
08-30 09:35:04.628  1027  2096 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6817 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 09:35:04.631  6802  6802 D AndroidRuntime: Shutting down VM
08-30 09:35:04.682  1958  3977 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 09:35:04.682  1958  3977 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3c8a0f37 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 09:35:04.687  1958  1981 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 09:35:04.687  1958  1981 D SplitWindowPolicy: topRunningActivity=ActivityInfo{12f56ca4 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 09:35:04.733  6817  6817 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 09:35:04.815  6817  6817 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 09:35:04.822  6817  6817 I LibraryLoader: Loading: webviewchromium
,08-30 09:35:04.824  6817  6817 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9493-9496)
08-30 09:35:04.824  6817  6817 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 09:35:04.841  6817  6817 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b634cfd}
08-30 09:35:04.842  6817  6817 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 09:35:04.843  6817  6817 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 09:35:04.853  6817  6817 I BrowserStartupController: Initializing chromium process, renderers=0
,08-30 09:35:04.854  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 09:35:04.866  6817  6817 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 09:35:04.866   318  1377 V AudioPolicyService: registerClient() client 0xb14b7960, uid 10118
,08-30 09:35:04.866  6817  6817 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 09:35:04.867  6817  6817 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-30 09:35:04.870  1027  1089 D BluetoothManagerService: Message: 20
08-30 09:35:04.870  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ddb6cfc:true
08-30 09:35:04.883  6817  6817 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 09:35:04.883  6817  6817 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 09:35:04.883  6817  6817 I Adreno-EGL: Build Date: 12/12/14 금
08-30 09:35:04.883  6817  6817 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 09:35:04.883  6817  6817 I Adreno-EGL: Remote Branch: 
08-30 09:35:04.883  6817  6817 I Adreno-EGL: Local Patches: 
08-30 09:35:04.883  6817  6817 I Adreno-EGL: Reconstruct Branch: 
,08-30 09:35:04.954  6817  6861 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-30 09:35:04.956  6817  6817 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-30 09:35:04.972  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 09:35:04.977  6817  6817 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 09:35:04.980  6817  6817 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 09:35:04.983  6817  6817 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 09:35:04.983  6817  6817 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 09:35:04.997  6817  6817 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 09:35:05.003  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 09:35:05.003  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 09:35:05.048  6817  6876 D OpenGLRenderer: Render dirty regions requested: true
08-30 09:35:05.048  6817  6876 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 09:35:05.071  6817  6876 D OpenGLRenderer: Enabling debug mode 0
,08-30 09:35:05.080  6817  6817 D Atlas   : Validating map...
08-30 09:35:05.084  1027  1044 D SplitWindow: check instance of lgWin Window{2f37e056 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 09:35:05.148  6817  6874 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:35:05.148  6817  6874 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:35:05.191  1027  1090 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +509ms (total +590ms)
,08-30 09:35:05.191  6817  6817 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@299dfbf0 time:159863
08-30 09:35:05.192  1027  1090 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12007793 u0 com.test.thalitest/.MainActivity t6} time:159864
08-30 09:35:05.309  6817  6817 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 09:35:05.309  6817  6817 I chromium: 
,08-30 09:35:05.357  6817  6817 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 09:35:05.430  6817  6874 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 09:35:05.430  6817  6874 I chromium: 
,08-30 09:35:05.579  6817  6893 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435150848
,08-30 09:35:05.597  6817  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 09:35:05.597  6817  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 09:35:05.597  6817  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 09:35:05.597  6817  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 09:35:05.597  6817  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 09:35:05.599  6817  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f6fdb4 added. We now have 1 listener(s)
08-30 09:35:05.606  1027  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:35:05.611  6817  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-30 09:35:05.614  6817  6893 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 09:35:05.615  6817  6893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:35:05.615  6817  6893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 09:35:05.623  6817  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d9b823 added. We now have 1 listener(s)
08-30 09:35:05.624  6817  6893 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:35:05.629  1027  1536 D WifiService: New client listening to asynchronous messages
08-30 09:35:05.633  6817  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 09:35:05.633  6817  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 09:35:05.634  6817  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 09:35:05.634  6817  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 09:35:05.634  6817  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 09:35:05.640  6817  6893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:35:05.640  1027  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 09:35:05.643  6817  6893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-30 09:35:05.652  6817  6893 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 09:35:05.653  6817  6893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:35:05.653  6817  6893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:05.653  6817  6893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:35:05.653  6817  6893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:05.653  6817  6893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:05.653  6817  6893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:05.653  6817  6893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:05.653  6817  6893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:35:05.653  6817  6893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-30 09:35:05.653  6817  6893 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:35:05.656  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:05.658  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:05.659  6817  6893 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 09:35:05.695  6817  6817 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 09:35:06.202   335   360 E GBMv2   : DFP En is all cleared set to be enabled
08-30 09:35:06.202   335   360 E GBMv2   : Set value is all cleared set the max
08-30 09:35:06.202   335   360 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 09:35:06.755  6817  6896 W jxcore-log: Initializing JXcore engine
08-30 09:35:06.755  6817  6896 W jxcore-log: JXcore engine is ready
,08-30 09:35:06.845  6896  6896 W Thread-777: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9420]" dev="sockfs" ino=9420 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 09:35:06.845  6896  6896 W Thread-777: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 09:35:06.845  6896  6896 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9513]" dev="sockfs" ino=9513 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 09:35:06.845  6896  6896 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 09:35:06.845  6896  6896 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31785]" dev="sockfs" ino=31785 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 09:35:06.882  6817  6896 W jxcore-log: Starting JXcore engine
,08-30 09:35:07.086  6817  6896 W jxcore-log: Platform android
08-30 09:35:07.086  6817  6896 W jxcore-log: 
08-30 09:35:07.086  6817  6896 W jxcore-log: Process ARCH arm
08-30 09:35:07.086  6817  6896 W jxcore-log: 
,08-30 09:35:07.429  6817  6896 I jxcore-log: JXcore Cordova bridge is ready!
08-30 09:35:07.429  6817  6896 I jxcore-log: 
08-30 09:35:07.429  6817  6896 W jxcore-log: JXcore engine is started
,08-30 09:35:07.439  6817  6893 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 09:35:07.442  6817  6817 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 09:35:21.088  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 09:35:21.088  6817  6896 I jxcore-log: 
08-30 09:35:21.092  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 09:35:21.092  6817  6896 I jxcore-log: 
,08-30 09:35:21.099  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:35:21.099  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:21.099  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:35:21.099  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:21.099  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:21.099  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:21.099  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:21.099  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:35:21.102  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:21.106  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 09:35:21.106  6817  6896 I jxcore-log: 
,08-30 09:35:21.111  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 09:35:21.111  6817  6896 I jxcore-log: 
08-30 09:35:22.078  6817  6896 I jxcore-log: Unit Test app is loaded
08-30 09:35:22.078  6817  6896 I jxcore-log: 
,08-30 09:35:22.095  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:35:22.095  6817  6896 I jxcore-log: 
,08-30 09:35:22.105  6817  6817 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 09:35:22.110  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 09:35:22.110  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b310fd added. We now have 2 listener(s)
,08-30 09:35:22.112  1027  2096 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:35:22.115  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 09:35:22.115  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:35:22.115  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:35:22.115  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:35:22.115  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c1981f2 added. We now have 2 listener(s)
08-30 09:35:22.115  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:35:22.116  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 09:35:22.118  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:22.122  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:35:22.122  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:22.122  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:35:22.122  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:22.122  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:22.122  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:22.122  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:22.122  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:35:22.126  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:22.126  6817  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:35:22.128  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:22.130  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:22.131  6817  6896 D ExecuteNativeTests: Running unit tests
08-30 09:35:22.268  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 09:35:22.268  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 added. We now have 3 listener(s)
,08-30 09:35:22.271  1027  1593 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:35:22.274  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 09:35:22.274  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:35:22.274  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:35:22.274  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:35:22.274  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 added. We now have 3 listener(s)
08-30 09:35:22.275  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:35:22.275  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 09:35:22.279  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:22.283  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:35:22.283  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:22.283  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:35:22.283  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:22.283  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:22.283  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:22.283  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:22.283  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:35:22.287  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:22.287  6817  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:35:22.289  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:22.291  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:22.295  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 09:35:22.299  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 09:35:22.299  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 09:35:22.299  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 09:35:22.303  6817  6896 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 09:35:22.304  6817  6896 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 09:35:22.304  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 09:35:22.304  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 09:35:22.305  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 09:35:22.305  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 09:35:22.306  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:22.306  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:22.306  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:22.306  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 09:35:22.307  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 removed from the list
08-30 09:35:22.307  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:22.307  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 removed from the list
08-30 09:35:22.307  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:22.307  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:22.313  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:22.313  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:22.317  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:22.317  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:22.317  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:22.317  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:22.319  6817  6896 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 09:35:22.320  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:22.320  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:22.320  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:22.320  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:22.320  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:22.320  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:22.320  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:22.320  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:22.320  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:22.320  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:22.320  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:22.324  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:22.324  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:22.324  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:22.324  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:22.331  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 09:35:22.331  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 09:35:22.331  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 09:35:22.331  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 09:35:22.331  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 09:35:22.331  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 09:35:22.331  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 09:35:22.331  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 09:35:22.331  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 09:35:22.331  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 09:35:22.331  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 09:35:22.332  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 09:35:22.332  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:22.332  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:22.332  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:22.333  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:22.333  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:22.333  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:22.333  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:22.333  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:22.333  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:22.333  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:22.333  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:22.336  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:22.336  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:22.336  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:22.336  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
,08-30 09:35:22.344  6817  6896 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 09:35:22.347  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:22.351  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:35:22.351  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:22.351  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:35:22.351  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:22.351  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:22.351  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:22.351  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:22.351  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:35:22.354  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:22.354  6817  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:35:22.356  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:22.357  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:22.359  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 09:35:22.359  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 09:35:22.360  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 09:35:22.360  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:22.360  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 09:35:22.365  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 09:35:22.367  1027  1593 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:35:22.373  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 09:35:22.381  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 09:35:22.385  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 09:35:22.386  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 09:35:22.387  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:22.389  6817  6896 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 09:35:22.391  6817  6896 I io.jxcore.node.ConnectionHelper: start: OK
08-30 09:35:27.406  6817  6896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 09:35:27.407  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 09:35:27.407  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 09:35:32.417  6817  6896 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 09:35:32.422  6817  6896 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-30 09:35:32.423  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 09:35:32.424  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 09:35:32.424  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 09:35:32.424  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:32.424  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 09:35:32.434  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 09:35:32.437  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:32.439  6817  6896 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 09:35:32.439  6817  6896 I io.jxcore.node.ConnectionHelper: start: OK
08-30 09:35:33.698  1596  1596 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-30 09:35:33.699  1596  1596 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-30 09:35:33.714  1958  2133 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 09:35:33.714  1958  2133 D LEDHandler: Battery Level Remaining: 100%
08-30 09:35:33.714  1958  2133 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
,08-30 09:35:33.717  1596  1596 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
08-30 09:35:33.717  1596  1596 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 09:35:33.718  1027  1536 D WifiController: battery changed pluggedType: 2
08-30 09:35:33.722  1596  1596 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 09:35:33.725  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:35:33.725  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:35:33.726  3875  4014 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-30 09:35:33.734  6697  6697 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 09:35:37.445  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:37.445  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:37.445  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:37.446  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:37.446  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:37.446  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:37.446  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:37.446  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:37.456  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:37.456  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:37.459  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:37.459  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:37.461  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:37.462  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:37.462  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:37.462  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:37.464  6817  6896 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 09:35:37.469  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:37.472  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:35:37.472  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:37.472  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:35:37.472  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:37.472  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:37.472  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:37.472  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:37.472  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:35:37.474  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:37.474  6817  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:35:37.477  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:37.480  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:37.480  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 09:35:37.480  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 09:35:37.481  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 09:35:37.481  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:37.481  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 09:35:37.486  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 09:35:37.487  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:37.489  6817  6896 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 09:35:37.491  6817  6896 I io.jxcore.node.ConnectionHelper: start: OK
08-30 09:35:42.491  6817  6896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 09:35:42.491  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 09:35:42.491  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 09:35:42.987   310   310 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
08-30 09:35:42.988   310   310 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-30 09:35:42.988   310   310 I rmt_storage: wakelock acquired: 1, error no: 42
,08-30 09:35:42.989   310   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
08-30 09:35:43.094   310   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
08-30 09:35:43.094   310   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-30 09:35:43.094   310   905 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
08-30 09:35:43.094   310   905 I rmt_storage: 
,08-30 09:35:43.097   310   310 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
08-30 09:35:43.098   894   907 E Diag_Lib: [IMS_FATAL]| 3347 | 907 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-30 09:35:47.501  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:47.502  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.502  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:47.502  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:47.502  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.502  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.502  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:47.503  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:47.512  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.512  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.515  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:47.515  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:47.518  6817  6896 D BluetoothLeScanner: could not find callback wrapper
,08-30 09:35:47.520  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:47.520  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.520  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.522  6817  6896 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 09:35:47.523  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:47.523  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.523  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.523  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:47.523  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.523  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.523  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:47.523  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.523  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.523  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.523  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.524  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:47.524  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:47.525  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:47.525  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:47.525  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.525  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.527  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 09:35:47.527  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:47.527  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.527  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.527  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:47.527  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.527  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.527  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:47.527  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.527  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.527  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.527  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.529  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:47.529  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:47.529  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:47.530  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:47.530  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.530  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.530  6817  6896 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 09:35:47.531  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:47.531  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.531  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.531  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:47.531  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.531  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.531  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:47.531  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.531  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.531  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.531  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.534  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:47.534  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:35:47.540  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:47.540  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:47.540  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.541  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.542  6817  6896 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 09:35:47.542  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:47.542  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.542  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.542  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:47.542  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.542  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.542  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:47.542  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.542  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.542  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.542  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.544  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:47.544  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:47.545  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:47.545  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:47.545  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.545  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.546  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 09:35:47.552  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 09:35:47.552  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 09:35:47.552  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 09:35:47.552  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 09:35:47.552  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 09:35:47.553  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 09:35:47.553  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 09:35:47.553  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 09:35:47.553  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:47.554  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.554  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.554  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:47.554  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.554  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.554  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:47.555  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.555  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.555  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.555  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.556  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:47.556  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:47.562  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:47.562  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:47.562  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:35:47.565  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.569  6817  6896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 09:35:47.570  6817  6896 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 09:35:47.570  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 09:35:47.575  6817  6896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 09:35:47.575  6817  6896 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 09:35:47.576  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 09:35:47.577  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 09:35:47.577  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 09:35:47.577  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 09:35:47.577  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 09:35:47.577  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 09:35:47.577  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 09:35:47.577  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 09:35:47.577  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 09:35:47.577  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 09:35:47.577  6817  6896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 09:35:47.577  6817  6896 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 09:35:47.577  6817  6896 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 09:35:47.578  6817  6896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 09:35:47.578  6817  6896 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-30 09:35:47.584  6817  6896 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 09:35:47.584  6817  6896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 09:35:47.584  6817  6896 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 09:35:47.585  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 09:35:47.587  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 09:35:47.589  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 09:35:47.589  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 09:35:47.590  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 09:35:47.590  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 09:35:47.591  6817  6896 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 09:35:47.591  6817  6896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 09:35:47.591  6817  6896 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 09:35:47.591  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:47.591  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.591  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.592  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 09:35:47.592  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:47.592  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.592  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.592  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:47.592  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.592  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.592  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.592  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.595  6817  6900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 841)
,08-30 09:35:47.602  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:47.602  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:47.603  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:47.604  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:47.604  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.604  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.606  6817  6896 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 09:35:47.607  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:47.607  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.607  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.607  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:47.607  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.608  6817  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 841
08-30 09:35:47.608  6817  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 841)
08-30 09:35:47.608  6817  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 841)
08-30 09:35:47.609  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.609  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:47.609  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.609  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.609  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.609  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.610  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:47.610  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:35:47.613  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:47.613  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:47.613  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.613  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.614  6817  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 09:35:47.615  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:47.615  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.615  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.615  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:47.615  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.615  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.615  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:47.615  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.615  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.615  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.615  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.629  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:47.629  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:35:47.632  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:47.632  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:47.632  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.632  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.633  6817  6896 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 09:35:47.633  6817  6896 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 09:35:47.634  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 09:35:47.634  6817  6896 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 09:35:47.634  6817  6896 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 09:35:47.634  6817  6896 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 09:35:47.634  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 09:35:47.635  6817  6896 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 09:35:47.635  6817  6896 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 09:35:47.635  6817  6896 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 09:35:47.635  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 09:35:47.635  6817  6896 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 09:35:47.635  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:47.635  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.635  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.635  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:47.635  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.635  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.635  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:47.635  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.635  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.635  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:47.635  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:47.637  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:47.637  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:47.638  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:47.638  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:47.638  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:47.638  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:47.640  6817  6896 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 09:35:47.643  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:35:47.650  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:35:47.650  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:47.650  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:35:47.650  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:47.650  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:47.650  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:47.650  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:47.650  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:35:47.652  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:47.652  6817  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:35:47.655  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:47.660  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 09:35:47.660  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 09:35:47.660  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 09:35:47.660  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:47.661  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 09:35:47.659  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:47.675  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 09:35:47.678  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:47.680  6817  6896 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 09:35:47.681  6817  6896 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 09:35:47.829  6817  6900 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-30 09:35:47.831  6817  6900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 841)
,08-30 09:35:52.681  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:52.682  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:52.682  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:52.682  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:52.682  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:52.682  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:52.682  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:52.682  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:57.695  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.695  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.695  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:57.695  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.695  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.696  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:57.696  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:57.696  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.696  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.696  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:57.696  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.696  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.697  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:57.697  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.697  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.697  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.697  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:57.711  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:57.711  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:57.711  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:57.711  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:57.711  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.711  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.714  6817  6896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 09:35:57.714  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:57.716  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 09:35:57.717  6817  6896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 09:35:57.717  6817  6896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 09:35:57.721  6817  6817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 09:35:57.738  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 09:35:57.738  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 09:35:57.739  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:57.740  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 09:35:57.740  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 09:35:57.740  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 09:35:57.740  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.740  6817  6896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-30 09:35:57.744  6817  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 09:35:57.744  6817  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 09:35:57.745  6817  6817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 09:35:57.745  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:57.745  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.745  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 09:35:57.745  6817  6896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 09:35:57.746  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 09:35:57.758  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 09:35:57.761  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:57.761  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:57.762  6817  6896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 09:35:57.762  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.762  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.763  6817  6896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 09:35:57.763  6817  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:35:57.764  6817  6817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 09:35:57.764  6817  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:35:57.764  6817  6817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 09:35:57.764  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.764  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:57.764  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.764  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.764  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:57.764  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.764  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.764  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:57.764  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.765  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.765  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.765  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.766  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:57.766  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:57.766  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.766  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.767  6817  6896 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 09:35:57.768  6817  6896 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:,55" removed
08-30 09:35:57.769  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 09:35:57.771  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 09:35:57.771  6817  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 09:35:57.775  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:57.775  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.775  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.775  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:57.776  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.776  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.776  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:57.776  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.776  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.776  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.777  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.779  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:57.779  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:57.779  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.779  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.781  1027  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:35:57.782  1027  1727 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:35:57.784  1027  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 09:35:57.787  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:57.787  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.787  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.787  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:57.787  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.787  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.787  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:57.787  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.787  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.787  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.787  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.789  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:57.789  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:57.789  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.789  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.790  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:57.790  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.790  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.790  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d808ff0 not in the list
08-30 09:35:57.790  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.790  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.790  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:57.790  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.790  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.790  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:57.790  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:57.792  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:57.792  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:57.792  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:57.792  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f389969 not in the list
08-30 09:35:57.793  6817  6896 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 09:35:57.793  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 09:35:57.794  6817  6896 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 09:35:57.794  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 09:35:57.794  6817  6896 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 09:35:57.794  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 09:35:57.796  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 09:35:57.796  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 09:35:57.797  6817  6896 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 09:35:57.797  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 09:35:57.797  6817  6896 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 09:35:57.797  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 09:35:57.797  6817  6896 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 09:35:57.797  6817  6896 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 09:35:57.803  6817  6896 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 09:35:57.803  6817  6896 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 09:35:57.804  6817  6896 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 09:35:57.804  6817  6896 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 09:35:57.804  6817  6896 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 09:35:57.804  6817  6896 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 09:35:57.806  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:35:57.806  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cf51e87 added. We now have 3 listener(s),
08-30 09:35:57.806  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:35:57.815  6817  6896 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 09:35:57.816  1027  1991 D WifiServiceImplEx: setWifiEnabled: true pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 09:35:57.816  1027  1991 D WifiService: setWifiEnabled: true pid=6817, uid=10118
08-30 09:35:57.817  1027  1991 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 09:35:58.266  6817  6817 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 09:36:00.074  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 09:36:00.075  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 09:36:00.075  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 09:36:00.075  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,08-30 09:36:00.086  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 09:36:00.087  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-30 09:36:00.090  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-30 09:36:00.090  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 09:36:02.825  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:36:02.825  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@371551b4 added. We now have 4 listener(s)
08-30 09:36:02.825  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:36:02.841  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:36:02.842  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@371551b4 removed from the list
08-30 09:36:02.842  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:36:02.842  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:36:02.842  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:36:02.842  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:36:02.843  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1830d1dd added. We now have 4 listener(s)
08-30 09:36:02.843  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:36:02.847  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:36:02.847  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1830d1dd removed from the list
08-30 09:36:02.847  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:36:02.847  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:36:02.847  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:36:02.848  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:36:02.848  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1aa8e152 added. We now have 4 listener(s)
08-30 09:36:02.848  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:36:02.852  1027  1968 D WifiServiceImplEx: setWifiEnabled: false pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 09:36:02.852  1027  1968 D WifiService: setWifiEnabled: false pid=6817, uid=10118
08-30 09:36:02.852  1027  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 09:36:02.875  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 09:36:02.876  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 09:36:02.876  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-30 09:36:02.877  1027  1531 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 09:36:02.878  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 09:36:02.879  1027  1531 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 09:36:02.879  1027  1531 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 09:36:02.879  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 09:36:02.880  1027  1531 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 09:36:02.880  1027  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 09:36:02.880  1027  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 09:36:02.881  1027  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 09:36:02.881  1027  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 09:36:02.883  1027  1567 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:02.883  1027  1567 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1e416f53 mBinding = false
,08-30 09:36:02.891  1027  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 09:36:02.891  1027  1529 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:02.891  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:02.891  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 09:36:02.892  2637  2637 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 09:36:02.892  1027  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 09:36:02.892  1027  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 09:36:02.893  1027  1531 D WifiNative-wlan0: SET ps 1: returned true
08-30 09:36:02.894  1027  2786 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:02.899   313   887 D CommandListener: Clearing all IP addresses on wlan0
,08-30 09:36:02.945  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 09:36:02.945  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 09:36:02.945  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-30 09:36:02.948  1027  1089 D BluetoothManagerService: Message: 2
08-30 09:36:02.959  1027  1089 D BluetoothManagerService: Sending off request.
,08-30 09:36:02.962  3875  3902 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-30 09:36:02.963  3875  3983 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 09:36:02.963  3875  3983 D BluetoothAdapterProperties: Setting state to 13
08-30 09:36:02.963  3875  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 09:36:02.964  3875  3983 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 09:36:02.964  3875  3983 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 09:36:02.985  1027  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 09:36:02.994  1027  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 09:36:02.995  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:02.996  1027  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:03.000  1027  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:03.001  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:03.001  1027  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:03.004  1027  1537 D ConnectivityService: ignoring duplicate network state non-change
08-30 09:36:03.004  1027  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-30 09:36:03.005  1027  1089 D BluetoothManagerService: Message: 60
08-30 09:36:03.005  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,08-30 09:36:03.009  1027  1529 D LGWifiP2pService: InactiveState{ when=-16ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:03.009  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:03.009  1027  1529 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2fbbe5e3
08-30 09:36:03.010  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 09:36:03.011  1958  1958 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 09:36:03.012  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:03.012  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:03.015  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:03.015  1027  1529 D LGWifiP2pService: P2pDisablingState
08-30 09:36:03.016  1027  1529 D LGWifiP2pService: P2pDisablingState{ when=-7ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:03.016  1027  1529 D LGWifiP2pService: p2p socket connection lost
08-30 09:36:03.016  1027  1529 D LGWifiP2pService: P2pDisabledState
08-30 09:36:03.017  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 09:36:03.018  1958  1958 D WfdsService: WifiP2pState is changed : false
08-30 09:36:03.018  1958  2300 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 09:36:03.018  1958  2300 D WfdsService: Set the WFDS Monitor: false
,08-30 09:36:03.021  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:03.021  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:03.022  1958  2300 D WfdsMonitor: WFDS Monitor is stopped
08-30 09:36:03.022  1958  2300 D WfdsService: STATE : WfdsDisabledState - enter
08-30 09:36:03.022  1958  2732 D CtrlSupplicant: Received on exit socket, terminate
08-30 09:36:03.023  1958  2732 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 09:36:03.023  1958  2732 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 09:36:03.023  1958  2732 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 09:36:03.023  1958  2305 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 09:36:03.024  1958  2300 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 09:36:03.025  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 09:36:03.030  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-30 09:36:03.030  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:03.030  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:03.030  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 09:36:03.031  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-30 09:36:03.032  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:03.032  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:03.032  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 09:36:03.032  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 09:36:03.033  1027  1548 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:03.033  1027  1027 D RttService: SCAN_AVAILABLE : 1
08-30 09:36:03.033  1027  1549 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:03.034  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:03.034  1027  1531 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 09:36:03.035  1027  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 09:36:03.035  1027  1529 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:03.035  1027  1529 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:03.035  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 09:36:03.036  2637  2637 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 09:36:03.036  1027  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 09:36:03.036  1027  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 09:36:03.037  1027  1531 D WifiNative-wlan0: SET ps 1: returned true
08-30 09:36:03.037  3875  3875 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:03.037  3875  3875 D BluetoothMapService: STATE_TURNING_OFF
08-30 09:36:03.038  3875  3875 V BtOppService: Receiver DISABLED_ACTION 
08-30 09:36:03.038  3875  3875 V BluetoothMapService: Handler(): got msg=4
08-30 09:36:03.039  3875  3875 D BluetoothMapService: MAP Service closeService in
08-30 09:36:03.039  3875  3875 D BluetoothMapMasInstance: MAP Service shutdown
08-30 09:36:03.039  3875  4246 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 09:36:03.039  3875  4246 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 09:36:03.039  3875  4246 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 09:36:03.039  3875  4246 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 09:36:03.039  3875  4246 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 09:36:03.039  3875  4246 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 09:36:03.039  3875  4246 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 09:36:03.039  3875  4246 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 09:36:03.040  3875  3875 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 09:36:03.040  3875  3875 V BluetoothMapService: MAP Service closeService out
08-30 09:36:03.041  3875  3875 I BtOppRfcommListener: stopping Accept Thread
08-30 09:36:03.041  3875  3875 V BtOppRfcommListener: close mBtServerSocket
08-30 09:36:03.042  3875  3875 V BtOppRfcommListener: waiting for thread to terminate
08-30 09:36:03.047  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 09:36:03.052  3875  4300 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 09:36:03.052  3875  4300 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 09:36:03.058  3875  3875 V BtOppRfcommListener: done waiting for thread to terminate
08-30 09:36:03.062  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:03.062  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:03.062  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:03.062  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:03.062  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:03.062  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:03.062  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:03.062  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:03.062  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:36:03.064  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:03.064  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:03.066  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:03.066  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:03.066  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:03.066  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:03.066  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:03.066  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:03.066  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:03.066  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:03.066  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:36:03.067  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:03.067  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:03.076   313   887 D CommandListener: Clearing all IP addresses on wlan0
,08-30 09:36:03.077  1027  1537 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 09:36:03.077  1027  1537 D DSQN    : disableDataServiceNotify
08-30 09:36:03.077  1027  1537 D DSQN    : stop dsqn bin
08-30 09:36:03.082  1027  1537 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 09:36:03.082  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:03.082  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:03.082  1027  1537 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:03.082  1027  1537 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 09:36:03.083  1027  1537 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 09:36:03.083  1027  1537 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 09:36:03.083  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 09:36:03.083  1596  1806 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 09:36:03.084  1027  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:03.084  1027  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:03.084  1027  2785 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 09:36:03.087  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:03.092  1027  1085 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6945 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 09:36:03.093  1027  1531 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 09:36:03.094  1027  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:03.094  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 09:36:03.094  1027  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:03.094  1027  1537 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:03.094  1027  1537 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:03.095  3875  3875 V BtOppService: onDestroy
08-30 09:36:03.095  1027  1531 D WifiNative-p2p0: TERMINATE: returned true
08-30 09:36:03.095  1027  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 09:36:03.095  1027  1531 E WifiStateMachine: useWiFiOffloading() : false
08-30 09:36:03.095  1027  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 09:36:03.095  1027  1537 D NetworkManagementService: Removing idletimer
08-30 09:36:03.095  1027  1531 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:03.095  1027  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 09:36:03.095  1871  1871 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:03.096  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 09:36:03.096  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-30 09:36:03.095  1027  1537 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:03.097  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:03.097  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:03.097  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 09:36:03.097  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 09:36:03.097  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 09:36:03.098  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 09:36:03.098  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 09:36:03.098  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 09:36:03.098  1027  1528 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 09:36:03.098  1027  1528 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 09:36:03.099  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 09:36:03.099  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 09:36,:03.099  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 09:36:03.100  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 09:36:03.102  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:03.102  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:03.102  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:03.102  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:03.102  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:03.102  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:03.102  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:03.102  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:03.102  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:03.103  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:03.103  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:03.103  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 09:36:03.103  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:03.103  1027  1027 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 09:36:03.105  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:03.105  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:03.105  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:03.105  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:03.105  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:03.105  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:03.105  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:03.105  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:03.105  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:03.105  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:03.106  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:03.107  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 09:36:03.107  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:03.108  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:03.138  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 09:36:03.138  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:03.139  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 09:36:03.153  1027  1943 I art     : Explicit concurrent mark sweep GC freed 48276(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.049ms total 213.505ms
08-30 09:36:03.159  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 09:36:03.160  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:03.160  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:03.160  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:03.178  1027  1758 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6963 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 09:36:03.180  3875  3986 D BluetoothAdapterProperties: Scan Mode:20
08-30 09:36:03.180  3875  3875 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 09:36:03.181  2637  2637 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 09:36:03.181  3875  3983 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 09:36:03.181  2637  2637 I wpa_supplicant: monitor socket send errors count : 1
08-30 09:36:03.181  2637  2637 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1958-2\x00 that cannot receive messages
08-30 09:36:03.182  3875  4302 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 09:36:03.182  3875  3983 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 09:36:03.182  1027  2726 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 09:36:03.182  1027  2726 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 09:36:03.183  3875  4247 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 09:36:03.183  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 09:36:03.183  3875  4098 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 09:36:03.184  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 09:36:03.184  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 09:36:03.184  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 09:36:03.184  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 09:36:03.184  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 09:36:03.184  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 09:36:03.184  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 09:36:03.184  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 09:36:03.184  3875  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 09:36:03.184  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 09:36:03.184  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 09:36:03.184  3875  4098 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 09:36:03.184  3875  4305 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 09:36:03.185  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:36:03.187  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:03.188  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:36:03.188  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:03.188  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:03.188  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:03.188  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:03.188  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:03.188  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:03.188  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:03.189  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:03.189  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:03.189  6817  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:36:03.191  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:36:03.193  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:03.194  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:03.195  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:03.195  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:03.196  6945  6945 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 09:36:03.196  6945  6945 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 09:36:03.197  6945  6945 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 09:36:03.197  6945  6945 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 09:36:03.197  6945  6945 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 09:36:03.198  6945  6945 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 09:36:03.219  1027  2786 D DhcpStateMachine: StoppedState
,08-30 09:36:03.219  1027  2786 D DhcpStateMachine: StoppedState{ when=-183ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:03.220  1027  1531 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 09:36:03.221  1027  1531 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 09:36:03.221  2637  2637 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 09:36:03.222  2637  2637 W wpa_supplicant: USIM:  scard_deinit function
08-30 09:36:03.223  1027  2726 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 09:36:03.223  1027  2726 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 09:36:03.224  1027  2726 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 09:36:03.224  1027  2726 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 09:36:03.224  1027  2726 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 09:36:03.224  1027  2726 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 09:36:03.225  1027  1089 D Tethering: InitialState.processMessage what=4
08-30 09:36:03.226  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 09:36:03.227  1027  1531 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=217885
08-30 09:36:03.227  1027  1531 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=217885
08-30 09:36:03.227  1027  1531 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=217886  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 09:36:03.228  1027  1531 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=217886  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 09:36:03.228  1027  1531 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:03.228  1027  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:03.232  6963  6963 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-30 09:36:03.239  6963  6963 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 09:36:03.239  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 09:36:03.240  1027  1043 I ActivityManager: Killing 6271:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 09:36:03.270  6945  6945 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 09:36:03.301  2637  2637 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 09:36:03.301  1027  2726 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 09:36:03.302  1027  2726 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 09:36:03.302  1027  2726 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 09:36:03.303  1027  1531 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-30 09:36:03.320  1027  1758 W libprocessgroup: failed to open /acct/uid_10014/pid_6271/cgroup.procs: No such file or directory
,08-30 09:36:03.329  3875  3875 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 09:36:03.330  3875  3875 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:03.330  3875  3875 V BluetoothPbapReceiver: ***********state = 13
08-30 09:36:03.333  3875  3875 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 09:36:03.335  3875  3875 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:03.335  3875  3875 V BluetoothPbapService: state: 13
08-30 09:36:03.336  3875  3875 V BluetoothPbapService: Pbap Service closeService in
,08-30 09:36:03.337  2251  2251 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 09:36:03.337  3875  3875 V BluetoothPbapService: successfully stopped pbap service
08-30 09:36:03.337  3875  3875 V BluetoothPbapService: Pbap Service closeService out
08-30 09:36:03.339  3875  3875 V BluetoothPbapService: Pbap Service onDestroy
08-30 09:36:03.339  3875  3875 V BluetoothPbapService: Pbap Service closeService in
08-30 09:36:03.339  3875  3875 V BluetoothPbapService: Pbap Service closeService out
08-30 09:36:03.339  3875  3875 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 09:36:03.361  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:03.396  1027  1567 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6984 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 09:36:03.407  1958  1958 D WfdsService: Supplicant Connection state is changed : false
08-30 09:36:03.408  1958  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 09:36:03.408  1958  2300 D WfdsService: Set the WFDS Monitor: false
08-30 09:36:03.408  1958  2300 D WfdsMonitor: WFDS Monitor is stopped
08-30 09:36:03.408  1027  1531 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 09:36:03.408  1027  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 09:36:03.408  1027  1531 E WifiStateMachine: useWiFiOffloading() : false
08-30 09:36:03.408  1027  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 09:36:03.409  6945  6945 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:03.410  6945  6945 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 09:36:03.410   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 373us total 18.342ms
08-30 09:36:03.411  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:03.412  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 09:36:03.414  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:36:03.417  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 09:36:03.419  1027  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 09:36:03.419  1027  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 09:36:03.422  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:03.424  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:03.426  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:03.427   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 299us total 16.617ms
,08-30 09:36:03.437  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:03.441   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 257us total 13.355ms
,08-30 09:36:03.448  1027  1089 D BluetoothManagerService: Message: 20
08-30 09:36:03.448  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed9945:true
,08-30 09:36:03.460  1027  1089 D BluetoothManagerService: Message: 30
08-30 09:36:03.464  1027  1089 D BluetoothManagerService: Message: 30
08-30 09:36:03.466  6945  6945 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 09:36:03.467  6945  6945 D BluetoothMap: Create BluetoothMap proxy object
08-30 09:36:03.467  1027  1089 D BluetoothManagerService: Message: 30
,08-30 09:36:03.486  1027  1089 D BluetoothManagerService: Message: 30
,08-30 09:36:03.489  6945  6945 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 09:36:03.490  6945  6945 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 09:36:03.508  6945  6945 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-30 09:36:03.513  6945  6945 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-30 09:36:03.527  6945  6945 D DockEventReceiver: finishStartingService: stopping service
,08-30 09:36:03.535  6984  6984 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 09:36:03.536  6984  6984 W LG Account v2.2: No ProfileInfo entries
08-30 09:36:03.536  6984  6984 I LG Account v2.2: isEnabled: false
08-30 09:36:03.536  6984  6984 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 09:36:03.536  6984  6984 I Feature : [Lifetracker]Country: EU
08-30 09:36:03.536  6984  6984 I Feature : [Lifetracker]Operator: OPEN
08-30 09:36:03.536  6984  6984 I Feature : [Lifetracker]Ranking support: false
08-30 09:36:03.537  6984  6984 I Feature : [Lifetracker]Comfort support: false
08-30 09:36:03.537  6984  6984 I Feature : [Lifetracker]Accessory: true
08-30 09:36:03.537  6984  6984 I Feature : [Lifetracker]Health device: true
08-30 09:36:03.537  6984  6984 I Feature : [Lifetracker]Extra Pedometer: false
08-30 09:36:03.537  6984  6984 I Feature : [Lifetracker]Blood glucose device: false
08-30 09:36:03.537  6984  6984 I Feature : [Lifetracker]Device Number: 3
08-30 09:36:03.543  1027  1567 I ActivityManager: Killing 6386:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-30 09:36:03.551  6945  6945 D BluetoothInputDevice: Proxy object connected
08-30 09:36:03.553  6945  6945 D HidProfile: Bluetooth service connected
08-30 09:36:03.555  6945  6945 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 09:36:03.557  6945  6945 D PanProfile: Bluetooth service connected
08-30 09:36:03.561  6945  6945 D BluetoothMap: Proxy object connected
08-30 09:36:03.561  6945  6945 D MapProfile: Bluetooth service connected
08-30 09:36:03.562  6945  6945 D BluetoothMap: getConnectedDevices()
08-30 09:36:03.562  6945  6945 D BluetoothMap: Bluetooth is Not enabled
08-30 09:36:03.563  6945  6945 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 09:36:03.580  1027  1943 W libprocessgroup: failed to open /acct/uid_10004/pid_6386/cgroup.procs: No such file or directory
,08-30 09:36:03.593  6945  6945 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 09:36:03.600  6945  6945 D BluetoothPermissionRequest: onReceive
08-30 09:36:03.603  6945  6945 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 09:36:03.615  1027  1567 I ActivityManager: Killing 6514:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-30 09:36:03.617  6945  6945 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 09:36:03.652  3875  3875 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 09:36:03.652  1027  2063 W libprocessgroup: failed to open /acct/uid_10008/pid_6514/cgroup.procs: No such file or directory
08-30 09:36:03.652  3875  3875 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 09:36:03.653  3875  3875 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-30 09:36:03.737  1027  1567 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7010 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 09:36:03.748  3875  3875 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:03.748  3875  3875 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 09:36:03.753  3875  3875 V BluetoothFtpService: Ftp Service onStartCommand
08-30 09:36:03.753  3875  3875 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:03.753  3875  3875 V BluetoothFtpService: Ftp Service closeService
08-30 09:36:03.753  3875  3875 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-30 09:36:03.755  3875  3875 V BluetoothFtpService: successfully stopped ftp service
08-30 09:36:03.756  3875  3875 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 09:36:03.756  3875  3875 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 09:36:03.756  3875  3875 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 09:36:03.756  3875  3875 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:03.756  3875  3875 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 09:36:03.756  3875  3875 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 09:36:03.758  3875  3875 V BluetoothFtpService: Ftp Service onDestroy
08-30 09:36:03.758  3875  3875 V BluetoothFtpService: Ftp Service closeService
08-30 09:36:03.759  3875  3875 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:03.759  3875  3875 V BluetoothSapService: state: 13
08-30 09:36:03.759  3875  3875 V BluetoothSapService: Stopping SAP server process
08-30 09:36:03.760  3875  3875 V BluetoothSapService: Sap Service closeSapService in
08-30 09:36:03.760  3875  3875 V BluetoothSapService: Close listen Socket : 
08-30 09:36:03.760  3875  3875 V BluetoothSapService: Close rfcomm Socket : 
08-30 09:36:03.761  3875  3875 V BluetoothSapService: Close sapd  Socket : 
,08-30 09:36:03.813  1027  1968 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7030 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 09:36:03.819  3875  3875 V BluetoothSapService: Sap Service closeSapService out
08-30 09:36:03.820  3875  3875 V BluetoothSapService: Sap Service onDestroy
08-30 09:36:03.820  3875  3875 V BluetoothSapService: Sap Service closeSapService in
08-30 09:36:03.820  3875  3875 V BluetoothSapService: Close listen Socket : 
08-30 09:36:03.820  3875  3875 V BluetoothSapService: Close rfcomm Socket : 
08-30 09:36:03.820  3875  3875 V BluetoothSapService: Close sapd  Socket : 
08-30 09:36:03.821  3875  3875 V BluetoothSapService: Sap Service closeSapService out
08-30 09:36:03.847  7010  7010 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 09:36:03.881  7010  7010 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-30 09:36:03.888  7030  7030 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 09:36:03.907  1027  2009 I ActivityManager: Killing 6046:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-30 09:36:03.915  7010  7010 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-30 09:36:03.915  7010  7010 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 09:36:03.915  7010  7010 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 09:36:03.916  7010  7010 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 09:36:03.916  7010  7010 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 09:36:03.918  7010  7010 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 09:36:03.922  7010  7010 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-30 09:36:03.966  1027  2005 W libprocessgroup: failed to open /acct/uid_10011/pid_6046/cgroup.procs: No such file or directory
,08-30 09:36:03.979  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 09:36:03.987  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:04.012  7010  7010 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 09:36:04.016  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:04.017  7010  7010 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 09:36:04.020  7010  7010 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 09:36:04.021  6963  6963 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 09:36:04.021  6963  6963 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 09:36:04.021  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 09:36:04.026  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:04.032  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:04.039  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:04.040  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 09:36:04.043  7010  7010 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 09:36:04.046  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:04.052  6963  6963 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-30 09:36:04.052  6963  6963 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 09:36:04.052  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 09:36:04.055  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:04.061  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:04.068  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 09:36:04.069  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:04.071  7010  7010 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 09:36:04.149  1027  1757 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7050 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 09:36:04.187  3875  3986 D bt_hci_bdroid: cleanup
08-30 09:36:04.187  3875  4101 I bt_lpm  : LPM is already off!!!
08-30 09:36:04.188  3875  4235 I bt_userial_mct: exiting userial_read_thread
08-30 09:36:04.188  3875  4235 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 09:36:04.188  3875  4098 W bt-btif : ag scb idx 1 not allocated
08-30 09:36:04.188  3875  3986 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 09:36:04.188  3875  4098 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 09:36:04.188  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 09:36:04.188  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 09:36:04.188  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 09:36:04.188  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 09:36:04.188  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 09:36:04.188  3875  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 09:36:04.188  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 09:36:04.189  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 09:36:04.189  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-30 09:36:04.189  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 09:36:04.189  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 09:36:04.189  3875  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 09:36:04.189  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 09:36:04.189  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 09:36:04.189  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 09:36:04.189  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 09:36:04.189  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 09:36:04.189  3875  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 09:36:04.189  3875  4098 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 09:36:04.189  3875  4101 I bt_vendor: hw_epilog_process
08-30 09:36:04.190  3875  3986 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 09:36:04.190  3875  3986 D bt_userial_mct: userial_close
08-30 09:36:04.190  3875  3986 E bt_userial_mct: pthread_join() FAILED result:3
08-30 09:36:04.190  3875  3986 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 09:36:04.256  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 09:36:04.258  3875  3986 D bt_hci_bdroid: set_power 0
08-30 09:36:04.258  3875  3986 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 09:36:04.258  3875  3986 I bt_vendor: bluetooth satus is on
08-30 09:36:04.258  3875  3986 I bt_vendor: bt-vendor : resetting BT status
08-30 09:36:04.258  3875  3986 I bt_vendor: Starting hciattach daemon
08-30 09:36:04.258  3875  3986 I bt_vendor: try to set false
08-30 09:36:04.259  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 09:36:04.259  3875  3986 I bt_vendor: Starting hciattach daemon
08-30 09:36:04.259  3875  3986 I bt_vendor: try to set false
08-30 09:36:04.260  3875  3986 I bt_vendor: cleanup
08-30 09:36:04.261  3875  4098 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 09:36:04.261  3875  3986 I GKI_LINUX: GKI_exit_task 0 done
08-30 09:36:04.261  3875  3986 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 09:36:04.263  3875  3983 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 09:36:04.267  3875  3875 D HeadsetService: Received stop request...Stopping profile...
08-30 09:36:04.268  3875  3875 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 09:36:04.268  3875  3875 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 09:36:04.268  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@136b0df2
08-30 09:36:04.269  3875  4014 D HeadsetStateMachine: Exit Disconnected: -1
08-30 09:36:04.271  1871  1871 D BluetoothHeadset: Proxy object disconnected
08-30 09:36:04.271  1871  1871 D BluetoothHeadset: Proxy object disconnected
08-30 09:36:04.271  1871  1871 D BluetoothHeadset: Proxy object disconnected
08-30 09:36:04.271  1027  1027 D BluetoothHeadset: Proxy object disconnected
08-30 09:36:04.272  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-30 09:36:04.276  3875  3875 D A2dpService: Received stop request...Stopping profile...
08-30 09:36:04.277  3875  4079 D A2dpStateMachine: Exit Disconnected: -1
08-30 09:36:04.278  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 09:36:04.280  3875  3875 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
,08-30 09:36:04.280  3875  3875 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 09:36:04.280  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@136b0df2
08-30 09:36:04.281  1027  1027 D BluetoothA2dp: Proxy object disconnected
08-30 09:36:04.281  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 09:36:04.282  3875  3875 D HidService: Received stop request...Stopping profile...
08-30 09:36:04.282  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@136b0df2
08-30 09:36:04.283  3875  3983 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 09:36:04.284  3875  3875 D HeadsetStateMachine: Unbinding service...
08-30 09:36:04.284  3875  3875 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 09:36:04.284  3875  3875 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 09:36:04.284  3875  3875 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 09:36:04.284  3875  3875 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 09:36:04.285  3875  3875 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 09:36:04.285  3875  3875 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 09:36:04.285  3875  3875 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-30 09:36:04.288  3875  3875 D HealthService: Received stop request...Stopping profile...
08-30 09:36:04.288  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:04.288  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@136b0df2
08-30 09:36:04.293  6945  6945 D BluetoothInputDevice: Proxy object disconnected
08-30 09:36:04.293  6945  6945 D HidProfile: Bluetooth service disconnected
08-30 09:36:04.298  3875  3875 D PanService: Received stop request...Stopping profile...
,08-30 09:36:04.299  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@136b0df2
08-30 09:36:04.300  3875  3875 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 09:36:04.301  3875  3875 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 09:36:04.301  3875  3875 D BtGatt.GattService: stop()
,08-30 09:36:04.301  3875  3875 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 09:36:04.302  6945  6945 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 09:36:04.302  6945  6945 D PanProfile: Bluetooth service disconnected
08-30 09:36:04.302  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@136b0df2
,08-30 09:36:04.303  3875  3875 I BluetoothA2dpServiceJni: cleanupNative
08-30 09:36:04.303  3875  4080 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 09:36:04.303  3875  3875 I GKI_LINUX: GKI_exit_task 2 done
08-30 09:36:04.303  3875  3875 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 09:36:04.304  3875  3875 D BluetoothMapService: Received stop request...Stopping profile...
08-30 09:36:04.304  3875  3875 D BluetoothMapService: stop()
08-30 09:36:04.305  3875  3875 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 09:36:04.305  3875  3875 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 09:36:04.306  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@136b0df2
08-30 09:36:04.308  6945  6945 D BluetoothMap: Proxy object disconnected
08-30 09:36:04.308  6945  6945 D MapProfile: Bluetooth service disconnected
08-30 09:36:04.308  3875  3875 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 09:36:04.308  3875  3875 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 09:36:04.308  3875  3875 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 09:36:04.308  3875  3875 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 09:36:04.308  3875  3875 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 09:36:04.309  3875  3875 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 09:36:04.309  3875  3875 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 09:36:04.311  3875  3875 V BluetoothMapService: Handler(): got msg=4
08-30 09:36:04.311  3875  3875 D BluetoothMapService: MAP Service closeService in
08-30 09:36:04.311  3875  3875 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 09:36:04.311  3875  3875 V BluetoothMapService: MAP Service closeService out
08-30 09:36:04.311  3875  3875 D BluetoothMapService: cleanup()
08-30 09:36:04.311  3875  3875 D BluetoothMapService: MAP Service closeService in
08-30 09:36:04.311  3875  3875 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 09:36:04.311  3875  3983 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 09:36:04.311  3875  3875 V BluetoothMapService: MAP Service closeService out
08-30 09:36:04.311  3875  3983 D BluetoothAdapterProperties: Setting state to 10
08-30 09:36:04.311  3875  3983 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 09:36:04.312  1027  1089 D BluetoothManagerService: Message: 60
08-30 09:36:04.312  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 09:36:04.312  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 09:36:04.312  6945  6962 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 09:36:04.313  6945  6961 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 09:36:04.313  1871  3507 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:36:04.314  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:36:04.314  1871  1887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:36:04.315  3875  3983 I BluetoothAdapterState: Entering OffState
08-30 09:36:04.315  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 09:36:04.316  6945  6962 D BluetoothMap: onBluetoothStateChange: up=false
08-30 09:36:04.316  1871  3508 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:36:04.317  6945  6961 D BluetoothPan: onBluetoothStateChange on: false
08-30 09:36:04.318  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 09:36:04.319  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 09:36:04.319  7050  7070 W FormManager: Network not available. Please check & try again.
08-30 09:36:04.320  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 09:36:04.320  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 09:36:04.321  1027  1089 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 09:36:04.321  1027  1089 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 09:36:04.321  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 09:36:04.321  1027  1089 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1e416f53 mBinding = false
08-30 09:36:04.321  6945  6945 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 09:36:04.321  1027  1089 D BluetoothManagerService: Sending unbind request.
08-30 09:36:04.321  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 09:36:04.322  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 09:36:04.324  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:04.324  1958  2175 D LGBluetoothAPIService: Message: 2
,08-30 09:36:04.324  1958  2175 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@4716a0d mBinding = false
,08-30 09:36:04.325  1958  2175 D LGBluetoothAPIService: Sending unbind request.
08-30 09:36:04.327  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 09:36:04.331  3875  3986 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 09:36:04.331  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:04.331  3875  3875 I GKI_LINUX: GKI_exit_task 1 done
08-30 09:36:04.331  3875  3875 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 09:36:04.332  3875  3875 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 09:36:04.332  3875  3875 I art     : --- WEIRD: removing null entry 246
08-30 09:36:04.332  3875  3875 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
,08-30 09:36:04.332  3875  3875 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 09:36:04.334  1596  1596 D BluetoothAdapter: 809303916: getState() :  mService = null. Returning STATE_OFF
08-30 09:36:04.334  1596  1596 D BluetoothAdapter: 809303916: getState() :  mService = null. Returning STATE_OFF
08-30 09:36:04.334  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:04.335  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:04.336  3875  3875 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 09:36:04.338  3875  3875 I art     : System.exit called, status: 0
08-30 09:36:04.338  3875  3875 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 09:36:04.342  6945  6945 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 09:36:04.343  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 09:36:04.343  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 09:36:04.343  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 09:36:04.343  6945  6945 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 09:36:04.343  6945  6945 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 09:36:04.346  6945  6945 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 09:36:04.347  6945  6945 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 09:36:04.347  6945  6945 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-30 09:36:04.360  6945  6945 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 09:36:04.364   318  1377 V AudioFlinger: 3875 died, releasing its sessions
08-30 09:36:04.364   318  1377 V AudioFlinger:  pid 1871 @ 0
08-30 09:36:04.364   318  1377 V AudioFlinger:  pid 3399 @ 1
08-30 09:36:04.364   318  1377 V AudioFlinger:  pid 3399 @ 2
08-30 09:36:04.438  1027  2005 I ActivityManager: Process com.android.bluetooth (pid 3875) has died
,08-30 09:36:04.439  1027  2005 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-30 09:36:04.452  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 09:36:04.453  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 09:36:04.458  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:04.459  2251  2251 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 09:36:04.465  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:04.466  6945  6945 D DockEventReceiver: finishStartingService: stopping service
08-30 09:36:04.467  6945  6945 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-30 09:36:04.472  7050  7073 V FormManager: Network unavailable.
08-30 09:36:04.479  4307  7083 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 09:36:04.489  7050  7073 V FormManager: Network unavailable.
08-30 09:36:04.490  4307  7084 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 09:36:04.491  4307  7084 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 09:36:04.496  6963  6963 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 09:36:04.496  6963  6963 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 09:36:04.496  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 09:36:04.507  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 09:36:04.513  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:04.514  6945  6945 D BluetoothPermissionRequest: onReceive
08-30 09:36:04.517  6945  6945 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 09:36:04.518  6945  6945 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-30 09:36:04.521  6945  6945 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 09:36:04.522  7050  7085 W FormManager: Network not available. Please check & try again.
08-30 09:36:04.590  1027  1757 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7087 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 09:36:04.605  7050  7086 V FormManager: Network unavailable.
,08-30 09:36:04.614  7050  7086 V FormManager: Network unavailable.
,08-30 09:36:04.620  7010  7010 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 09:36:04.623  1027  1044 I ActivityManager: Killing 6068:com.android.contacts/u0a19 (adj 15): empty #17
08-30 09:36:04.624  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 09:36:04.624  7010  7010 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 09:36:04.667  7010  7010 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:04.668  7010  7010 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:36:04.675  7010  7010 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 09:36:04.677  7010  7010 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 09:36:04.677  7010  7010 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
,08-30 09:36:04.677  7010  7010 V SoundPool: doLoad: loading sample sampleID=1
08-30 09:36:04.677  7010  7010 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 09:36:04.682  7010  7106 V SoundPool: Start decode
08-30 09:36:04.682  7010  7106 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-30 09:36:04.683   318  1376 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 09:36:04.683   318  1376 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 09:36:04.683   318  1376 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 09:36:04.684   318  1376 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 09:36:04.684   318  1376 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 09:36:04.684   318  1376 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 09:36:04.684   318  1376 V MediaPlayerService: player type = 3
08-30 09:36:04.684   318  1376 V AwesomePlayer: AwesomePlayer create()
08-30 09:36:04.685   318  1376 V AwesomePlayer: reset_l() 
08-30 09:36:04.685   318  1376 V AwesomePlayer: cancelPlayerEvents
,08-30 09:36:04.685   318  1376 V AwesomePlayer: setAudioSink() 
08-30 09:36:04.685   318  1376 V AwesomePlayer: reset_l() 
08-30 09:36:04.685   318  1376 V AudioCache: notify(0xb04095c0, 8, 0, 0)
08-30 09:36:04.685   318  1376 V AudioCache: ignored
08-30 09:36:04.685   318  1376 V AwesomePlayer: cancelPlayerEvents
08-30 09:36:04.685   318  1376 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 09:36:04.685   318  1376 V AwesomePlayer: setDataSource_l dataSource
08-30 09:36:04.685   318  1376 V LGParserOSAL: SniffLGParser start
08-30 09:36:04.685   318  1376 V LGParserOSAL: MainType:5, SubType=0
08-30 09:36:04.686   318  1376 V LGParserOSAL: #### check Mime : application/ogg
08-30 09:36:04.686   318  1376 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 09:36:04.686   318  1376 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 09:36:04.710  1027  1043 W libprocessgroup: failed to open /acct/uid_10019/pid_6068/cgroup.procs: No such file or directory
,08-30 09:36:04.733  6726  6726 D UEI.SmartControl: QS Service created
,08-30 09:36:04.739  7010  7010 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 09:36:04.747   318  1376 V LGParserOSAL: supported mime: application/ogg
08-30 09:36:04.747   318  1376 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 09:36:04.747   318  1376 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 09:36:04.747   318  1376 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 09:36:04.747   318  1376 V AwesomePlayer: AudioTrack Setting
08-30 09:36:04.747   318  1376 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 09:36:04.747   318  1376 V AwesomePlayer: setAudioSource() 
08-30 09:36:04.747   318  1376 V MediaPlayerService: prepare
08-30 09:36:04.747   318  1376 V AwesomePlayer: prepareAsync_l() 
08-30 09:36:04.747   318  1376 V MediaPlayerService: wait for prepare
08-30 09:36:04.748   318  7107 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 09:36:04.748   318  7107 V AwesomePlayer: initAudioDecoder() 
08-30 09:36:04.748   318  7107 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 09:36:04.748   318  7107 V AudioSystem: isOffloadSupported()
08-30 09:36:04.748   318  7107 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 09:36:04.748   318  7107 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 09:36:04.748   318  7107 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 09:36:04.749   318  7107 V AwesomePlayer: getUseOffload() = 0 
08-30 09:36:04.749   318  7107 V OMXCodec: OMXCodec::Create
08-30 09:36:04.749   318  7107 V OMXCodec: findMatchingCodecs()
08-30 09:36:04.749  7010  7010 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 09:36:04.749   318  7107 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 09:36:04.749   318  7107 V OMXCodec: matchingCodecs.size()=1
08-30 09:36:04.749   318  7107 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 09:36:04.749  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 09:36:04.754   318  7107 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 09:36:04.754   318  7107 V LGCodecAdapter: LG Codec Adapter start
08-30 09:36:04.754   318  7107 V OMXCodec: OMXCodec Createtor
08-30 09:36:04.754   318  7107 V OMXCodec: setComponentRole
08-30 09:36:04.754   318  7107 V OMXCodec: configureCodec protected=0
08-30 09:36:04.754   318  7107 V LGCodecAdapter: called getLGCodecSpecificData
08-30 09:36:04.754   318  7107 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 09:36:04.754   318  7107 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 09:36:04.754   318  7107 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 09:36:04.754   318  7107 V LGCodecOSAL: Not support LGCodec
08-30 09:36:04.754   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 09:36:04.754   318  7107 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 09:36:04.754   318  7107 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 09:36:04.754   318  7107 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 09:36:04.754   318  7107 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 09:36:04.754   318  7107 V AudioSystem: isOffloadSupported()
08-30 09:36:04.754   318  7107 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294,967295, duration=1068125 us, has_video=0
08-30 09:36:04.754   318  7107 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 09:36:04.754   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 09:36:04.754   318  7107 V OMXCodec: init()
08-30 09:36:04.754   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 09:36:04.754   318  7107 V OMXCodec: allocateBuffers
08-30 09:36:04.754   318  7107 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 09:36:04.754   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 09:36:04.755   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
08-30 09:36:04.755   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on input port
08-30 09:36:04.755   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b81f0 on input port
08-30 09:36:04.755   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on input port
08-30 09:36:04.755   318  7107 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 09:36:04.755   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 09:36:04.755   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b88d0 on output port
08-30 09:36:04.755   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8970 on output port
08-30 09:36:04.755   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b89c0 on output port
08-30 09:36:04.755   318  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8d80 on output port
08-30 09:36:04.755   318  7107 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 09:36:04.756   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 09:36:04.756   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 09:36:04.756   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 09:36:04.757  7087  7087 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 09:36:04.757  7087  7087 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 09:36:04.758   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 09:36:04.758   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 09:36:04.758   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 09:36:04.758   318  7107 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 09:36:04.758   318  7107 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 09:36:04.758   318  7107 V AudioCache: notify(0xb04095c0, 5, 0, 0)
08-30 09:36:04.758   318  7107 V AudioCache: ignored
,08-30 09:36:04.758   318  7107 V AudioCache: notify(0xb04095c0, 1, 0, 0)
08-30 09:36:04.758   318  7107 V AudioCache: prepared
08-30 09:36:04.758   318  1376 V AudioCache: wait - success
08-30 09:36:04.758   318  1376 V MediaPlayerService: start
08-30 09:36:04.758   318  1376 V AwesomePlayer: play_l() 
08-30 09:36:04.758   318  1376 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 09:36:04.758   318  1376 V AwesomePlayer: createAudioPlayer_l
08-30 09:36:04.758   318  1376 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 09:36:04.758   318  1376 V AwesomePlayer: startAudioPlayer_l() 
08-30 09:36:04.758   318  1376 D AudioPlayer: start of Playback, useOffload 0
08-30 09:36:04.758   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 09:36:04.758   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 09:36:04.759  7087  7087 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 09:36:04.760  7087  7087 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 09:36:04.761   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
,08-30 09:36:04.761   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 09:36:04.761   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 09:36:04.761   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 09:36:04.761   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 09:36:04.761   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 09:36:04.761   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517456
08-30 09:36:04.761   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 09:36:04.761   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517616
08-30 09:36:04.761   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517696
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974518656
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
,08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 09:36:04.762   318  7109 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b89c0 on output port
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8970 on output port
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b88d0 on output port
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8ec0 on output port
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 09:36:04.762   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 09:36:04.764   318  1376 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 09:36:04.768   318  1376 V AudioCache: notify(0xb04095c0, 6, 0, 0)
08-30 09:36:04.768   318  1376 V AudioCache: ignored
08-30 09:36:04.769   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.769   318  7110 V AudioCache: memcpy(0xaf004000, 0xb57fd000, 4096)
,08-30 09:36:04.769   318  1376 V MediaPlayerService: wait for playback complete
08-30 09:36:04.770   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.770   318  7110 V AudioCache: memcpy(0xaf005000, 0xb57fd000, 4096)
08-30 09:36:04.770  6726  6726 I UEI.SmartControl: Service initServices...
08-30 09:36:04.770   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.771   318  7110 V AudioCache: memcpy(0xaf006000, 0xb57fd000, 4096)
08-30 09:36:04.771  6726  6726 D UEI.SmartControl: QS start get config
08-30 09:36:04.772   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.772   318  7110 V AudioCache: memcpy(0xaf007000, 0xb57fd000, 4096)
08-30 09:36:04.776   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.776   318  7110 V AudioCache: memcpy(0xaf008000, 0xb57fd000, 4096)
08-30 09:36:04.780   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.780   318  7110 V AudioCache: memcpy(0xaf009000, 0xb57fd000, 4096)
08-30 09:36:04.781   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.781   318  7110 V AudioCache: memcpy(0xaf00a000, 0xb57fd000, 4096)
08-30 09:36:04.782   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.782   318  7110 V AudioCache: memcpy(0xaf00b000, 0xb57fd000, 4096)
08-30 09:36:04.783   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.783   318  7110 V AudioCache: memcpy(0xaf00c000, 0xb57fd000, 4096)
08-30 09:36:04.784   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.784   318  7110 V AudioCache: memcpy(0xaf00d000, 0xb57fd000, 4096)
08-30 09:36:04.785   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.785   318  7110 V AudioCache: memcpy(0xaf00e000, 0xb57fd000, 4096)
08-30 09:36:04.785  7010  7010 V LGMDMManager: Create singleton instance
08-30 09:36:04.785   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.785   318  7110 V AudioCache: memcpy(0xaf00f000, 0xb57fd000, 4096)
08-30 09:36:04.786   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.786   318  7110 V AudioCache: memcpy(0xaf010000, 0xb57fd000, 4096)
08-30 09:36:04.787   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.787   318  7110 V AudioCache: memcpy(0xaf011000, 0xb57fd000, 4096)
08-30 09:36:04.788   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.788   318  7110 V AudioCache: memcpy(0xaf012000, 0xb57fd000, 4096)
08-30 09:36:04.788   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.788   318  7110 V AudioCache: memcpy(0xaf013000, 0xb57fd000, 4096)
08-30 09:36:04.789   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.789   318  7110 V AudioCache: memcpy(0xaf014000, 0xb57fd000, 4096)
08-30 09:36:04.790   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.790   318  7110 V AudioCache: memcpy(0xaf015000, 0xb57fd000, 4096)
08-30 09:36:04.791   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.791   318  7110 V AudioCache: memcpy(0xaf016000, 0xb57fd000, 4096)
08-30 09:36:04.791  7087  7087 D BluetoothAdapterApp: Loading JNI Library
,08-30 09:36:04.791   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.791   318  7110 V AudioCache: memcpy(0xaf017000, 0xb57fd000, 4096)
08-30 09:36:04.792   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.792   318  7110 V AudioCache: memcpy(0xaf018000, 0xb57fd000, 4096)
08-30 09:36:04.793   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.793   318  7110 V AudioCache: memcpy(0xaf019000, 0xb57fd000, 4096)
08-30 09:36:04.794   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.794   318  7110 V AudioCache: memcpy(0xaf01a000, 0xb57fd000, 4096)
08-30 09:36:04.794   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.794   318  7110 V AudioCache: memcpy(0xaf01b000, 0xb57fd000, 4096)
08-30 09:36:04.795   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.795   318  7110 V AudioCache: memcpy(0xaf01c000, 0xb57fd000, 4096)
08-30 09:36:04.796   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.796   318  7110 V AudioCache: memcpy(0xaf01d000, 0xb57fd000, 4096)
08-30 09:36:04.796   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.796   318  7110 V AudioCache: memcpy(0xaf01e000, 0xb57fd000, 4096)
08-30 09:36:04.797   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.797   318  7110 V AudioCache: memcpy(0xaf01f000, 0xb57fd000, 4096)
08-30 09:36:04.798   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.798   318  7110 V AudioCache: memcpy(0xaf020000, 0xb57fd000, 4096)
08-30 09:36:04.799   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.799   318  7110 V AudioCache: memcpy(0xaf021000, 0xb57fd000, 4096)
08-30 09:36:04.800   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.800   318  7110 V AudioCache: memcpy(0xaf022000, 0xb57fd000, 4096)
08-30 09:36:04.801   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.801   318  7110 V AudioCache: memcpy(0xaf023000, 0xb57fd000, 4096)
08-30 09:36:04.802   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.802   318  7110 V AudioCache: memcpy(0xaf024000, 0xb57fd000, 4096)
08-30 09:36:04.803   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.803   318  7110 V AudioCache: memcpy(0xaf025000, 0xb57fd000, 4096)
08-30 09:36:04.803   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.803   318  7110 V AudioCache: memcpy(0xaf026000, 0xb57fd000, 4096)
08-30 09:36:04.804   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.804   318  7110 V AudioCache: memcpy(0xaf027000, 0xb57fd000, 4096)
08-30 09:36:04.805   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.805   318  7110 V AudioCache: memcpy(0xaf028000, 0xb57fd000, 4096)
08-30 09:36:04.806   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.806   318  7110 V AudioCache: memcpy(0xaf029000, 0xb57fd000, 4096)
08-30 09:36:04.806   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.806   318  7110 V AudioCache: memcpy(0xaf02a000, 0xb57fd000, 4096)
08-30 09:36:04.807   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.807   318  7110 V AudioCache: memcpy(0xaf02b000, 0xb57fd000, 4096)
08-30 09:36:04.808   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.808   318  7110 V AudioCache: memcpy(0xaf02c000, 0xb57fd000, 4096)
08-30 09:36:04.809   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.809   318  7110 V AudioCache: memcpy(0xaf02d000, 0xb57fd000, 4096)
08-30 09:36:04.810   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.810   318  7110 V AudioCache: memcpy(0xaf02e000, 0xb57fd000, 4096)
08-30 09:36:04.810   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.810   318  7110 V AudioCache: memcpy(0xaf02f000, 0xb57fd000, 4096)
08-30 09:36:04.811   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.811   318  7110 V AudioCache: memcpy(0xaf030000, 0xb57fd000, 4096)
08-30 09:36:04.812   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.812   318  7110 V AudioCache: mem,cpy(0xaf031000, 0xb57fd000, 4096)
08-30 09:36:04.813   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.813   318  7110 V AudioCache: memcpy(0xaf032000, 0xb57fd000, 4096)
08-30 09:36:04.813   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.813   318  7110 V AudioCache: memcpy(0xaf033000, 0xb57fd000, 4096)
08-30 09:36:04.814   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.814   318  7110 V AudioCache: memcpy(0xaf034000, 0xb57fd000, 4096)
08-30 09:36:04.815   318  7110 V AudioCache: write(0xb57fd000, 4096)
08-30 09:36:04.815   318  7110 V AudioCache: memcpy(0xaf035000, 0xb57fd000, 4096)
08-30 09:36:04.815   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 09:36:04.815   318  7110 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 09:36:04.815   318  7110 V AwesomePlayer: postAudioEOS() 
08-30 09:36:04.815   318  7110 V AudioCache: write(0xb57fd000, 280)
08-30 09:36:04.815   318  7110 V AudioCache: memcpy(0xaf036000, 0xb57fd000, 280)
08-30 09:36:04.818   318  7107 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 09:36:04.818   318  7107 V AwesomePlayer: onStreamDone
08-30 09:36:04.818   318  7107 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 09:36:04.818   318  7107 V AudioCache: notify(0xb04095c0, 2, 0, 0)
08-30 09:36:04.818   318  7107 V AudioCache: playback complete
08-30 09:36:04.818   318  7107 V AwesomePlayer: pause_l() 
08-30 09:36:04.818   318  7107 V AudioCache: notify(0xb04095c0, 7, 0, 0)
08-30 09:36:04.818   318  7107 V AudioCache: ignored
08-30 09:36:04.818   318  7107 V AwesomePlayer: cancelPlayerEvents
08-30 09:36:04.818   318  1376 V AudioCache: wait - success
08-30 09:36:04.818   318  1376 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 09:36:04.818   318  7107 D AudioPlayer: Pause Playback at 1068125
08-30 09:36:04.818   318  1376 V AwesomePlayer: reset_l() 
08-30 09:36:04.818   318  1376 V AudioCache: notify(0xb04095c0, 8, 0, 0)
08-30 09:36:04.818   318  1376 V AudioCache: ignored
08-30 09:36:04.818   318  1376 V AwesomePlayer: cancelPlayerEvents
08-30 09:36:04.818   318  1376 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 09:36:04.818   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 09:36:04.819   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 09:36:04.819   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 09:36:04.819   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8240 on port 0
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b81f0 on port 0
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 0
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8ec0 on port 1
08-30 09:36:04.820   318  7109 V OMXCodec: [OMX.g,oogle.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 09:36:04.821   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b88d0 on port 1
08-30 09:36:04.821   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 09:36:04.821   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8970 on port 1
08-30 09:36:04.821   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 09:36:04.821   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b89c0 on port 1
08-30 09:36:04.821   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 09:36:04.821   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 09:36:04.821   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 09:36:04.821   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 09:36:04.822   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 09:36:04.822   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 09:36:04.822   318  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 09:36:04.822   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 09:36:04.822   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 09:36:04.822   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 09:36:04.825   318  1376 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 09:36:04.825   318  1376 D AudioPlayer: AudioPlayer releasing audio source
08-30 09:36:04.825   318  1376 D AudioPlayer: AudioPlayer done releasing audio source
08-30 09:36:04.825   318  1376 V AwesomePlayer: reset_l() 
08-30 09:36:04.825   318  1376 V AwesomePlayer: cancelPlayerEvents
08-30 09:36:04.825   318  1376 V AwesomePlayer: ~AwesomePlayer call
08-30 09:36:04.826   318  1376 V AwesomePlayer: reset_l() 
08-30 09:36:04.826   318  1376 V AwesomePlayer: cancelPlayerEvents
08-30 09:36:04.826  7010  7106 V SoundPool: close(31)
08-30 09:36:04.826  7010  7106 V SoundPool: pointer = 0x9fe6d000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 09:36:04.831  7087  7087 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3c655ecb Instance Count = 1
08-30 09:36:04.837  7087  7087 D BluetoothAdapterApp: onCreate
08-30 09:36:04.860  7087  7087 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-30 09:36:04.861  7087  7087 D ProfileConfigQcom: Adding HeadsetService
,08-30 09:36:04.861  7087  7087 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 09:36:04.861  7087  7087 D ProfileConfigQcom: Adding A2dpService
08-30 09:36:04.861  7087  7087 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 09:36:04.861  7087  7087 D ProfileConfigQcom: Adding HidService
08-30 09:36:04.862  7087  7087 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 09:36:04.862  7087  7087 D ProfileConfigQcom: Adding HealthService
08-30 09:36:04.862  7087  7087 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 09:36:04.863  7087  7087 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 09:36:04.863  7087  7087 D ProfileConfigQcom: Adding PanService
08-30 09:36:04.863  7087  7087 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 09:36:04.863  7087  7087 D ProfileConfigQcom: Adding GattService
08-30 09:36:04.864  7087  7087 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 09:36:04.864  7087  7087 D ProfileConfigQcom: Adding BluetoothMapService
08-30 09:36:04.864  7087  7087 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 09:36:04.866  7087  7087 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 09:36:04.866  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 09:36:04.868  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 09:36:04.871  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7794
08-30 09:36:04.874  7087  7087 V LGMDMManagerInternal: Create singleton instance
08-30 09:36:04.878  6945  6945 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-30 09:36:04.956  7087  7087 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 09:36:04.961  7087  7087 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 09:36:04.961  7087  7087 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 09:36:04.961  7087  7087 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 09:36:04.963  7087  7087 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:04.963  7087  7087 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 09:36:04.980  7030  7030 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 09:36:05.236  6726  6726 I UEI.SmartControl: Supports setup maps: true
,08-30 09:36:05.243  6726  6726 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 09:36:05.243  6726  6726 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 09:36:05.243  6726  6726 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 09:36:05.243  6726  6726 I UEI.SmartControl: ### init IR Blaster...
08-30 09:36:05.246  6726  6726 D serial_port: Configuring serial port
08-30 09:36:05.247  6726  6726 E UEI.SmartControl: UEIBLaster setting for 616
08-30 09:36:05.247  6726  6726 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 09:36:05.247  6726  6726 I UEI.SmartControl: configuring settings for MAXQ616
08-30 09:36:05.247  6726  6726 I UEI.SmartControl: Get version...
08-30 09:36:05.265  6726  7119 D UEI.SmartControl: serial port data available: 21
,08-30 09:36:05.292  6726  6726 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 09:36:05.295  6726  6726 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 09:36:05.295  6726  6726 I UEI.SmartControl: QS saving settings...
08-30 09:36:05.298  6726  6726 D UEI.SmartControl: IR Blaster version: 25672567
08-30 09:36:05.315  6726  7119 D UEI.SmartControl: serial port data available: 4
,08-30 09:36:05.347  6726  7122 I UEI.SmartControl: Device manager: loading config....
,08-30 09:36:05.352  6726  7122 D UEI.SmartControl: ----------- loading internal config...
08-30 09:36:05.354  6726  6726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 09:36:05.360  6726  6726 E UEI.SmartControl: Services init done
08-30 09:36:05.360  6726  6726 D UEI.SmartControl: QS Service init finished
08-30 09:36:05.362  6726  6726 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 09:36:05.362  6726  6726 D UEI.SmartControl: QS Service version code: 201091
08-30 09:36:05.362  6726  6726 D UEI.SmartControl: Service requested: Control
08-30 09:36:05.379  6726  7122 E UEI.SmartControl: Loading SETTINGS...
,08-30 09:36:05.383  6726  6726 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 09:36:05.386  7010  7010 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 09:36:05.387  6726  6742 I UEI.SmartControl: ------ IControl API: 11
08-30 09:36:05.387  6726  6742 D UEI.SmartControl: File observer start...
08-30 09:36:05.388  6726  6742 E UEI.SmartControl: IR Port is disabled: false
08-30 09:36:05.389  6726  6742 D UEI.SmartControl: Starting file observer...
08-30 09:36:05.390  6726  6742 I UEI.SmartControl: Registering callback...
08-30 09:36:05.390  6726  6741 I UEI.SmartControl: ------ IControl API: 19
08-30 09:36:05.391  6726  6741 I UEI.SmartControl: Registering Services Ready callback...
08-30 09:36:05.392  6726  6726 D UEI.SmartControl: Internal service binding...
08-30 09:36:05.395  6726  7122 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 09:36:05.407  6726  7121 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 09:36:05.408  7010  7029 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 09:36:05.409  7010  7104 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 09:36:05.409  7010  7104 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 09:36:05.409  7010  7010 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 09:36:05.410  7010  7010 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 09:36:05.410  6726  6742 I UEI.SmartControl: ------ IControl API: 8
08-30 09:36:05.412  6726  7121 D UEI.SmartControl: -----service ready thread exits
,08-30 09:36:05.415  7010  7010 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 09:36:05.415  7010  7010 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 09:36:05.415  7010  7010 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 09:36:05.416  7010  7010 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 09:36:05.417  7010  7010 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 09:36:05.417  7010  7010 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 09:36:05.420  7010  7010 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 09:36:05.422  7010  7010 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 09:36:05.424  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-30 09:36:05.427  7010  7010 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 09:36:05.427  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 09:36:05.428  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 09:36:05.429  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 09:36:05.430  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 09:36:05.431  7010  7010 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472542565431]
08-30 09:36:05.434  7010  7010 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 09:36:05.439  1027  1991 I ActivityManager: Killing 6092:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-30 09:36:05.475  7010  7127 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 09:36:05.480  1027  1991 I ActivityManager: Killing 6567:com.lge.email/u0a23 (adj 15): empty #18
08-30 09:36:05.509  1027  2005 W libprocessgroup: failed to open /acct/uid_10027/pid_6092/cgroup.procs: No such file or directory
,08-30 09:36:05.515  1027  1567 W libprocessgroup: failed to open /acct/uid_10023/pid_6567/cgroup.procs: No such file or directory
08-30 09:36:05.521  7010  7010 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 09:36:05.522  7010  7010 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 09:36:05.522  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 09:36:05.522  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 09:36:05.523  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 09:36:05.523  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 09:36:05.523  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-30 09:36:05.535  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-30 09:36:06.096  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:06.109  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-30 09:36:06.123  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:36:06.126  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:06.129  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:06.132  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:06.134  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-30 09:36:06.143  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:36:06.148  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:06.149  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:06.150  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:06.152  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 09:36:06.155  6477  6944 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 09:36:06.166  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 09:36:06.174  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 09:36:06.192  2251  2251 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:06.260  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:06.262  1027  2009 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7128 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-30 09:36:06.265  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:06.266  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 09:36:06.350  7128  7128 I AppUp4:AppBoxCP: onCreate
08-30 09:36:06.351  7128  7128 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 09:36:06.361  7128  7128 I AppUp4:DB:  setFingerPrint start
08-30 09:36:06.362  7128  7128 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 09:36:06.371  7128  7128 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-30 09:36:06.371  7128  7128 I AppUp4:DB:  SDK version = 21
08-30 09:36:06.371  7128  7128 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 09:36:06.373  7128  7128 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 09:36:06.375  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 09:36:06.375  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:06.377  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 09:36:06.377  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 09:36:06.385  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
08-30 09:36:06.427  7128  7128 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:06.428  7128  7128 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:36:06.437  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3b634cfd
,08-30 09:36:06.438  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 09:36:06.438  7128  7128 D AppUp4:CustFacade: isPhone : true
08-30 09:36:06.438  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
08-30 09:36:06.439  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-30 09:36:06.439  7128  7128 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 09:36:06.440  7128  7163 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 09:36:06.440  7128  7163 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 09:36:06.441  7128  7163 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-30 09:36:06.444  1027  2096 I ActivityManager: Killing 6155:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-30 09:36:06.479  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:06.481  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 09:36:06.481  1027  1727 W libprocessgroup: failed to open /acct/uid_10080/pid_6155/cgroup.procs: No such file or directory
,08-30 09:36:06.487  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:06.491  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:06.500  4307  7165 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 09:36:06.504  4307  7166 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:06.505  4307  7166 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 09:36:06.566  1027  2063 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7170 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 09:36:06.649  7170  7170 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 09:36:06.649  7170  7170 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 09:36:06.651  7170  7170 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 09:36:06.651  7170  7170 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 09:36:06.749  7170  7170 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 09:36:06.770  7170  7170 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 09:36:06.830  7170  7170 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 09:36:06.879  7170  7170 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 09:36:06.879  7170  7170 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:36:07.020  7170  7170 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 09:36:07.054  3399  3399 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 09:36:07.054  3399  3399 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:07.054  3399  3399 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 09:36:07.107  1027  1043 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7201 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 09:36:07.125  7170  7170 I HubEmail: JNI_OnLoad()
08-30 09:36:07.125  7170  7170 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 09:36:07.125  7170  7170 I HubEmail: registerNatives()
08-30 09:36:07.125  7170  7170 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 09:36:07.125  7170  7170 I HubEmail: registerNativeMethods()
08-30 09:36:07.125  7170  7170 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 09:36:07.125  7170  7170 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-30 09:36:07.161  7050  7199 W FormManager: Network not available. Please check & try again.
,08-30 09:36:07.173  7170  7226 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:36:07.176  7050  7200 V FormManager: Network unavailable.
08-30 09:36:07.183  7050  7200 V FormManager: Network unavailable.
08-30 09:36:07.188  1027  1968 I ActivityManager: Killing 6607:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-30 09:36:07.256  7201  7201 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:07.256  7201  7201 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:36:07.259  7201  7201 D PhoneMonitor: Register our PhoneStateListener
08-30 09:36:07.268  1027  1593 W libprocessgroup: failed to open /acct/uid_10061/pid_6607/cgroup.procs: No such file or directory
08-30 09:36:07.285  7201  7201 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 09:36:07.292  7201  7201 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 09:36:07.314  7201  7201 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-30 09:36:07.315  7201  7201 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 09:36:07.316  7201  7201 D TelephonyAutoProfiling: [parse] Load xml
08-30 09:36:07.323  7201  7201 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 09:36:07.323  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 09:36:07.323  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 09:36:07.323  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 09:36:07.323  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 09:36:07.324  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 09:36:07.324  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 09:36:07.324  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 09:36:07.324  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 09:36:07.324  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 09:36:07.324  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 09:36:07.324  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 09:36:07.324  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 09:36:07.324  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 09:36:07.325  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 09:36:07.325  7201  7201 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 09:36:07.325  7201  7201 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 09:36:07.334  7201  7201 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 09:36:07.349  1027  1943 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7237 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 09:36:07.351  1027  1943 I ActivityManager: Killing 6184:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-30 09:36:07.420  1027  1758 W libprocessgroup: failed to open /acct/uid_10097/pid_6184/cgroup.procs: No such file or directory
,08-30 09:36:07.698  1027  2005 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7266 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 09:36:07.704  1027  2005 I ActivityManager: Killing 6671:com.lge.eula/1000 (adj 15): empty #17
,08-30 09:36:07.776  1027  1727 W libprocessgroup: failed to open /acct/uid_1000/pid_6671/cgroup.procs: No such file or directory
08-30 09:36:07.862  1027  1968 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7283 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 09:36:07.866  1027  1968 I ActivityManager: Killing 6697:com.lge.bnr/1000 (adj 15): empty #17
08-30 09:36:07.959  1027  2005 W libprocessgroup: failed to open /acct/uid_1000/pid_6697/cgroup.procs: No such file or directory
,08-30 09:36:07.997  7283  7283 I art     : Almond Protected OAT
,08-30 09:36:08.018  1027  1529 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 09:36:08.018  1027  1529 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 09:36:08.052  7283  7283 D WeatherApplication: removeAccount
,08-30 09:36:08.054  7283  7283 D WeatherApplication: Account.length = 0
,08-30 09:36:08.054  7283  7283 E WeatherApplication: OPERATOR:OPEN
08-30 09:36:08.060  7283  7283 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:8
08-30 09:36:08.063  7283  7283 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-30 09:36:08.063  7283  7283 D Weather.Utils: 2 : All the weather widget is gone.
08-30 09:36:08.065  7283  7283 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 09:36:08.068  7283  7283 D WeatherAncestor: connectivity changed - connection : true
,08-30 09:36:08.069  7283  7283 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-30 09:36:08.083  7283  7283 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 09:36:08.084  7283  7283 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 09:36:08.084  7283  7283 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-30 09:36:08.100  1027  1531 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 09:36:08.101  1027  1531 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-30 09:36:08.113  7283  7283 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 09:36:08.114  7283  7283 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:8
08-30 09:36:08.161  1027  2009 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7307 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 09:36:08.167  1027  2009 I ActivityManager: Killing 2165:com.lge.music/u0a34 (adj 15): empty #17
08-30 09:36:08.184   339   339 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 24.584ms
,08-30 09:36:08.210   339   339 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 414us total 25.119ms
,08-30 09:36:08.230   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 365us total 19.334ms
,08-30 09:36:08.253   318  4036 V AudioFlinger: 2165 died, releasing its sessions
08-30 09:36:08.253   318  4036 V AudioFlinger:  pid 1871 @ 0
08-30 09:36:08.254   318  4036 V AudioFlinger:  pid 3399 @ 1
08-30 09:36:08.254   318  4036 V AudioFlinger:  pid 3399 @ 2
,08-30 09:36:08.289  1027  2005 D WifiServiceImplEx: setWifiEnabled: true pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-30 09:36:08.289  1027  2005 D WifiService: setWifiEnabled: true pid=6817, uid=10118
08-30 09:36:08.289  1027  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 09:36:08.293  1027  1044 W libprocessgroup: failed to open /acct/uid_10034/pid_2165/cgroup.procs: No such file or directory
,08-30 09:36:08.303  1027  1531 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-30 09:36:08.303  1027  1531 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 09:36:08.304  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 09:36:08.305  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 09:36:08.305  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-30 09:36:08.305  1027  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 09:36:08.305  1027  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 09:36:08.305  1027  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 09:36:08.305  1027  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 09:36:08.305  1027  1531 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 09:36:08.305  1027  1531 E WifiHW  : unknown target_country: EU , set to default
08-30 09:36:08.305  1027  1531 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 09:36:08.305  1027  1531 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 09:36:08.305  1027  1531 I WifiUtil: gEnableBmps=1
08-30 09:36:08.390   279   390 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 09:36:08.390   279   390 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 09:36:08.390   279   390 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 09:36:08.392  7307  7332 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 09:36:08.402   279   390 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 09:36:08.402   279   390 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 09:36:08.402   279   390 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 09:36:08.403  7307  7332 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 09:36:08.412   279   390 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 09:36:08.412   279   390 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 09:36:08.412   279   390 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 09:36:08.413  7307  7337 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 09:36:08.415   279   390 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 09:36:08.415   279   390 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 09:36:08.415   279   390 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 09:36:08.415  7307  7337 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-30 09:36:08.622  1027  1418 D PowerManagerServiceEx: acquireWakeLockInternal: lock=665227936, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1027
,08-30 09:36:08.626  1027  1418 V AlarmManager: ELAPSED_WAKEUP set : Alarm{623430a type 2 when 223280 com.google.android.gms} when 223280
08-30 09:36:08.665  7307  7307 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 09:36:08.671  2649  2649 D [Concierge]Service: onStartCommand(). Type : 9
08-30 09:36:08.688  7307  7307 I LibraryLoader: Loading: webviewchromium
,08-30 09:36:08.693  7307  7307 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3359-3364)
08-30 09:36:08.693  7307  7307 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 09:36:08.700  7307  7307 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d16cbee}
08-30 09:36:08.702  7307  7307 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 09:36:08.702  7307  7307 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 09:36:08.715  7307  7307 I BrowserStartupController: Initializing chromium process, renderers=0
,08-30 09:36:08.716  7307  7307 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 09:36:08.728  7307  7307 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-30 09:36:08.729  7307  7307 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 09:36:08.730  7307  7307 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 09:36:08.731   318  1377 V AudioPolicyService: registerClient() client 0xb57edc80, uid 10093
08-30 09:36:08.732  7307  7357 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 09:36:08.744  7307  7307 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 09:36:08.744  7307  7307 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 09:36:08.744  7307  7307 I Adreno-EGL: Build Date: 12/12/14 금
08-30 09:36:08.744  7307  7307 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 09:36:08.744  7307  7307 I Adreno-EGL: Remote Branch: 
08-30 09:36:08.744  7307  7307 I Adreno-EGL: Local Patches: 
08-30 09:36:08.744  7307  7307 I Adreno-EGL: Reconstruct Branch: 
,08-30 09:36:08.830  7307  7307 I NSApplication: Starting up...
,08-30 09:36:08.909  1027  2009 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7376 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 09:36:08.911  1027  2009 I ActivityManager: Killing 6116:com.android.vending/u0a44 (adj 15): empty #17
,08-30 09:36:09.004  1027  2096 W libprocessgroup: failed to open /acct/uid_10044/pid_6116/cgroup.procs: No such file or directory
,08-30 09:36:09.041  1027  1089 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 09:36:09.049  1027  1089 D Tethering: InitialState.processMessage what=4
08-30 09:36:09.050  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 09:36:09.058   313   887 D SoftapController: Softap fwReload - Ok
08-30 09:36:09.059  1027  1531 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (750ms)
08-30 09:36:09.060   313   887 D CommandListener: Setting iface cfg
08-30 09:36:09.060   313   887 D CommandListener: Trying to bring down wlan0
08-30 09:36:09.062   313   887 D CommandListener: Clearing all IP addresses on wlan0
08-30 09:36:09.064  1027  1531 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 09:36:09.066  7376  7376 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 09:36:09.069  1027  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 09:36:09.069  1027  1531 E WifiStateMachine: useWiFiOffloading() : false
08-30 09:36:09.069  1027  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 09:36:09.071  1027  1531 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 09:36:09.071  1027  1531 D WifiMonitor: connecting to supplicant
08-30 09:36:09.073  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:09.075  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 09:36:09.065  7398  7398 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:09.065  7398  7398 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:09.078  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 09:36:09.079  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:09.079  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:09.080  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:09.096  7398  7398 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 09:36:09.131  7398  7398 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 09:36:09.131  7398  7398 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 09:36:09.211  1027  1418 V AlarmManager: ELAPSED_WAKEUP set : Alarm{357a856b type 2 when 223868 android} when 223868
,08-30 09:36:09.223  7398  7398 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 09:36:09.271  7398  7398 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 09:36:09.276  7398  7398 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 09:36:09.277  7398  7398 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 09:36:09.277  1027  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 09:36:09.278  1027  1531 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 09:36:09.278  1027  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 09:36:09.278  1027  1531 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 09:36:09.278  1027  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:09.279  1027  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:09.279  1027  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:09.279  1027  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:09.279  1027  1531 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 09:36:09.279  1027  1531 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 09:36:09.279  1027  7406 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 09:36:09.280  1027  7406 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 09:36:09.280  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 09:36:09.280  1027  1531 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 09:36:09.280  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 09:36:09.280  1027  7406 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 09:36:09.280  1027  1531 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 09:36:09.280  1027  7406 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 09:36:09.280  1027  1531 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 09:36:09.281  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:09.281  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:09.281  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:09.281  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:09.281  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 09:36:09.281  1027  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 09:36:09.281  1027  1531 E WifiStateMachine: useWiFiOffloading() : false
08-30 09:36:09.281  1027  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 09:36:09.284  1958  1958 D WfdService: Waiting for WifiP2p enabling
08-30 09:36:09.284  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 09:36:09.284  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:09.285  1027  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 09:36:09.288  1027  1531 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 09:36:09.289  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:09.289  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:09.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:09.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetoo,th LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:09.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:09.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:09.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:09.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:09.289  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:09.289  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:09.289  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:09.289  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:09.290  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:09.290  1027  1531 D WifiNative-wlan0: SET update_config 1: returned true
08-30 09:36:09.290  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:09.290  1027  1531 D WifiConfigStore: Loading config and enabling all networks 
08-30 09:36:09.290  1027  1531 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 09:36:09.290  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:09.290  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:09.290  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:09.290  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:09.294  1027  1531 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 09:36:09.303  1027  1531 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 09:36:09.306  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 09:36:09.308  6477  6944 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 09:36:09.318  1027  1531 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 09:36:09.319  1027  1531 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 09:36:09.319  2251  2251 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:09.322  1027  1531 D WifiStateMachine: enableVerboseLogging : level 2
08-30 09:36:09.323  1027  1531 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 09:36:09.323  1027  1531 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 09:36:09.323  1027  1531 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 09:36:09.324  1027  1531 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 09:36:09.324  1027  1531 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 09:36:09.324  1027  1531 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 09:36:09.324  1027  1531 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 09:36:09.324  1027  1531 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 09:36:09.324  1027  1531 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 09:36:09.325  1027  1531 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 09:36:09.325  1027  1531 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 09:36:09.325  1027  1531 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 09:36:09.325  1027  1531 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 09:36:09.326  1027  1531 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 09:36:09.327  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 09:36:09.327  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:09.327  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 09:36:09.327  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 09:36:09.328  1027  1531 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 09:36:09.328  1027  1531 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 09:36:09.328  1027  1531 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 09:36:09.328  1027  1531 D WifiNative-HAL: Setting external_sim to 1
08-30 09:36:09.328  1027  1531 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 09:36:09.329  1958  1958 D WfdsService: Supplicant Connection state is changed : true
08-30 09:36:09.329  1958  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 09:36:09.329  1958  2300 D WfdsService: Set the WFDS Monitor: true
08-30 09:36:09.329  1958  2300 D WfdsMonitor: WfdsMonitorThread create
08-30 09:36:09.329  1958  2300 D WfdsMonitor: WFDS Monitor is created and started
08-30 09:36:09.329  1958  2300 D WfdsService: WiFi: Supplicant connection re-established
08-30 09:36:09.329  1027  1531 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 09:36:09.329  1027  1531 I WifiNative-HAL: startHal
08-30 09:36:09.329  1027  1531 D wifi    : setting scan oui 0xaf6ef320
08-30 09:36:09.330  1958  7411 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 09:36:09.330  1958  7411 E CtrlSupplicant: Succeed to open control connection
08-30 09:36:09.330  1027  1531 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 09:36:09.330  1027  1531 I WifiNative-HAL: startHal
08-30 09:36:09.330  1027  1531 D wifi    : setting scan oui 0xaf6ef320
08-30 09:36:09.330  1958  7411 E CtrlSupplicant: Succeed to open monitor connection
08-30 09:36:09.330  1958  7411 D WfdsMonitor: Supplicant connection established
08-30 09:36:09.330  1027  1531 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 09:36:09.330  1027  1531 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 09:36:09.330  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 09:36:09.331  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 09:36:09.331  1027  1531 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 09:36:09.331  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 09:36:09.331  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 09:36:09.331  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 09:36:09.331  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 09:36:09.331  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 09:36:09.332  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 09:36:09.332  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 09:36:09.332  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 09:36:09.332  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 09:36:09.332  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 09:36:09.332  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 09:36:09.332  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 09:36:09.332  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 09:36:09.332  7398  7398 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 09:36:09.332  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
08-30 09:36:09.332  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 09:36:09.332  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 09:36:09.332  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 09:36:09.333  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 09:36:09.333  1027  1531 E WifiNative: : [223,991,846 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 09:36:09.333  1027  1531 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 09:36:09.333  1027  1531 D WifiNative-wlan0: RECONNECT: returned true
08-30 09:36:09.333  1027  1531 D WifiNative-wlan0: doString: [STATUS]
08-30 09:36:09.334  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 09:36:09.334  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 09:36:09.334  1027  1531 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 09:36:09.334  1027  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 09:36:09.334  1027  1531 D WifiNative-wlan0: SET ps 1: returned true
08-30 09:36:09.334  1027  1529 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.335  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 09:36:09.335  1027  1548 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.335  1027  1548 I WifiNative-HAL: startHal
08-30 09:36:09.335  1027  1027 D RttService: SCAN_AVAILABLE : 3
08-30 09:36:09.335  1027  1548 D wifi    : getting scan capabilities on interface[1] = 0xaf6ef320
08-30 09:36:09.335  1027  1548 D wifi    : failed to get capabilities : -3
08-30 09:36:09.335  1027  1548 E WifiScanningService: could not get scan capabilities
08-30 09:36:09.335  1027  1549 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.335  1027  1531 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 09:36:09.335  1027  1531 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 09:36:09.336   313   887 D CommandListener: Setting iface cfg
08-30 09:36:09.336  1958  2300 D WfdsService: Connected to the supplicant for wfds
08-30 09:36:09.336   313   887 D CommandListener: Trying to bring up p2p0
08-30 09:36:09.336  1027  1529 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 09:36:09.336  1027  1529 D LGWifiP2pService: P2pEnablingState
08-30 09:36:09.336  1027  1531 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 09:36:09.336  1027  1529 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.336  1027  1529 D LGWifiP2pService: P2p socket connection successful
08-30 09:36:09.336  1027  1529 D LGWifiP2pService: P2pEnabledState
08-30 09:36:09.336  1027  1531 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 09:36:09.336  1027  1529 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 09:36:09.336  1027  1531 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 09:36:09.336  1027  1529 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 09:36:09.337  1027  1531 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 09:36:09.337  1027  1531 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 09:36:09.337  1027  1531 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 09:36:09.337  7398  7398 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 09:36:09.337  1027  1529 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 09:36:09.337  1027  1529 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 09:36:09.338  1027  1529 D WifiNative-p2p0: SET device_name G3: returned true
08-30 09:36:09.338  1027  1529 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 09:36:09.338  1027  1529 D LGWifiP2pService: before postfix = G3
08-30 09:36:09.338  1027  1529 D WifiServerServiceExt: postfix byte check : 2
08-30 09:36:09.338  1027  1529 D LGWifiP2pService: after postfix = G3
08-30 09:36:09.338  1027  1529 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 09:36:09.338  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 09:36:09.339  1027  1529 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 09:36:09.339  1027  1529 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 09:36:09.339  1027  1529 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 09:36:09.339  1027  1529 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 09:36:09.339  1958  1958 D WfdsService: WifiP2pState is changed : true
08-30 09:36:09.339  1958  2300 D WfdsService: Receive the WFDS_ENABLE Method
08-30 09:36:09.339  1958  2300 D WfdsService: Set the WFDS Monitor: true
08-30 09:36:09.339  1958  2300 D WfdsService: Connected to the supplicant for wfds
08-30 09:36:09.339  1958  2300 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 09:36:09.340  7398  7398 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 09:36:09.340  1958  2300 D WfdsService: selectPreferredScanChannel [36]
08-30 09:36:09.340  1958  2300 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 09:36:09.340  1958  1958 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 09:36:09.340  1027  1529 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 09:36:09.340  1027  1529 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 09:36:09.340  1958  1958 D WfdsService: isConnected: false
08-30 09:36:09.342  1027  1531 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 09:36:09.342  1027  1529 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 09:36:09.342  1027  1529 D WifiNative-HAL: p2pGetDeviceAddress
08-30 09:36:09.343  1027  1529 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 09:36:09.343  1027  1531 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 09:36:09.343  1027  1529 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 09:36:09.343  1027  1529 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 09:36:09.344  1958  1958 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 09:36:09.344  1958  1958 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 09:36:09.344  1958  1958 D WfdsService: Update P2p Interface State: 3
08-30 09:36:09.344  1027  1531 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 09:36:09.344  1027  1531 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 09:36:09.344  7398  7398 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 09:36:09.345  1027  1531 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 09:36:09.345  1027  1531 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 09:36:09.345  1027  1531 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 09:36:09.346  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-30 09:36:09.349  1027  1529 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 09:36:09.349  1027  1529 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 09:36:09.349  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3b634cfd
08-30 09:36:09.349  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 09:36:09.349  7128  7128 D AppUp4:CustFacade: isPhone : true
08-30 09:36:09.349  1027  1529 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 09:36:09.349  1027  1529 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 09:36:09.350  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 09:36:09.350  7398  7398 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:09.350  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 09:36:09.350  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:09.350  1027  7406 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:09.350  1027  7406 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:09.351  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
08-30 09:36:09.351  7398  7398 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 09:36:09.351  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 09:36:09.351  7398  7398 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.351  1027  1531 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 09:36:09.351  1027  1531 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 09:36:09.351  1027  1531 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 09:36:09.351  1958  7411 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:09.351  7398  7398 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.352  1027  1531 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 09:36:09.352  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 09:36:09.352  1027  7406 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:09.352  1027  7406 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.352  1027  7406 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.352  1027  7406 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.352  1027  7406 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:09.352  1027  7406 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.352  1027  7406 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.352  1027  7406 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.352  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 09:36:09.352  7398  7398 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 09:36:09.352  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 09:36:09.352  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 09:36:09.352  1027  7406 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 09:36:09.352  1027  7406 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 09:36:09.353  1958  7411 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:09.353  1027  1531 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 09:36:09.353  1027  1531 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 09:36:09.353  1027  1531 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 09:36:09.353  1027  1531 D WifiNative-wlan0: doBoolean: SCAN
08-30 09:36:09.354  1027  1529 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 09:36:09.354  1027  1529 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 09:36:09.363  1027  1529 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 09:36:09.363  1027  1529 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 09:36:09.363  1027  1529 D LGWifiP2pService: InactiveState
08-30 09:36:09.364  1027  1531 D WifiNative-wlan0: SCAN: returned false
08-30 09:36:09.364  1027  1529 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.364  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.364  1027  1529 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 09:36:09.364  1027  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=224023  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 09:36:09.364  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 09:36:09.364  7398  7398 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:09.365  1027  7406 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 09:36:09.365  1027  7406 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:09.365  1027  7406 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:09.365  1027  7406 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:09.365  7398  7398 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 09:36:09.365  7398  7398 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.365  1958  7411 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 09:36:09.365  1958  7411 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:09.365  1027  1529 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 09:36:09.365  1027  1529 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.366  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.366  7398  7398 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.366  1027  1529 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.366  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.366  1027  1529 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.366  1958  7411 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:09.366  1027  7406 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:09.366  1027  7406 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.366  1027  7406 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.366  1027  7406 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.366  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=224025  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 09:36:09.366  1027  7406 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:09.366  1027  7406 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.366  1027  7406 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.366  1027  7406 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:09.367  1027  1531 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 09:36:09.367  1027  1531 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 09:36:09.367  1027  1531 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 09:36:09.368  1027  1531 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 09:36:09.368  1027  1531 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 09:36:09.369  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:09.369  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:09.369  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:09.369  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:09.369  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 09:36:09.370  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:09.370  1027  1027 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 09:36:09.371  1027  1529 D LGWifiP2pService: InactiveState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.371  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.371  1027  1529 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.371  1027  1027 E WifiServerServiceExt: No p2p device connected
08-30 09:36:09.371  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:09.389  1027  1418 V AlarmManager: ELAPSED_WAKEUP set : Alarm{22ad7974 type 2 when 224048 com.google.android.gms} when 224048
,08-30 09:36:09.490  1027  1968 I art     : Explicit concurrent mark sweep GC freed 54610(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.498ms total 149.490ms
08-30 09:36:09.491  1027  1529 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 09:36:09.491  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.491  1027  1529 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.492  1027  1529 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.492  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.492  1027  1529 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:09.492  1958  2300 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 09:36:09.505  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:09.506  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 09:36:09.510  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:09.516  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:09.527  4307  7415 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 09:36:09.531  7170  7170 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 09:36:09.534  4307  7416 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:09.535  4307  7416 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 09:36:09.558  7170  7417 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:36:09.561  7050  7419 W FormManager: Network not available. Please check & try again.
,08-30 09:36:09.564  3399  3399 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 09:36:09.564  3399  3399 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:09.564  3399  3399 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 09:36:09.567  7201  7201 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 09:36:09.567  7201  7201 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 09:36:09.579  7283  7283 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:9
,08-30 09:36:09.581  7283  7283 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 09:36:09.581  7283  7283 D Weather.Utils: 2 : All the weather widget is gone.
08-30 09:36:09.582  7283  7283 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 09:36:09.582  7050  7420 V FormManager: Network unavailable.
08-30 09:36:09.582  7283  7283 D WeatherAncestor: connectivity changed - connection : true
08-30 09:36:09.582  7283  7283 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1e00dc43
08-30 09:36:09.583  7283  7283 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 09:36:09.583  7283  7283 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 09:36:09.583  7283  7283 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 09:36:09.583  7283  7283 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-30 09:36:09.584  7283  7283 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:9
08-30 09:36:09.590  7050  7420 V FormManager: Network unavailable.
08-30 09:36:09.617  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 09:36:09.617  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 09:36:09.617  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 09:36:09.617  6945  6945 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 09:36:09.617   313  7423 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 09:36:09.619  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 09:36:09.619  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 09:36:09.622  6945  6945 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 09:36:09.622  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 09:36:09.622  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 09:36:09.622  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 09:36:09.622  6945  6945 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 09:36:09.622  6945  6945 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 09:36:09.633  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 09:36:09.637  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 09:36:09.642  7050  7425 W FormManager: Network not available. Please check & try again.
08-30 09:36:09.644  7050  7426 V FormManager: Network unavailable.
08-30 09:36:09.644  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:09.651  7050  7426 V FormManager: Network unavailable.
,08-30 09:36:09.671  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 09:36:09.674  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 09:36:09.679  7050  7428 W FormManager: Network not available. Please check & try again.
08-30 09:36:09.682  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:09.700  7050  7429 V FormManager: Network unavailable.
,08-30 09:36:09.702  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 09:36:09.702  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 09:36:09.704  7050  7429 V FormManager: Network unavailable.
08-30 09:36:09.705  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:09.708  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:09.719  4307  7430 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 09:36:09.724  4307  7431 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 09:36:09.725  4307  7431 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 09:36:09.771  1027  1727 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7432 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-30 09:36:09.776  1027  1418 V AlarmManager: ELAPSED_WAKEUP set : Alarm{357330d1 type 2 when 224416 com.google.android.gms} when 224416
,08-30 09:36:09.908  7432  7432 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 09:36:09.908  7432  7432 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 09:36:09.917  7432  7432 V [BNRBootReceiver]: Boot Receiver Return
08-30 09:36:09.918  7432  7432 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 09:36:09.924  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 09:36:09.939  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:09.941  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 09:36:09.941  7398  7398 E wpa_supplicant: USIM:  scard_init function
08-30 09:36:09.941  1027  7406 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 09:36:09.941  7398  7398 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 09:36:09.941  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 09:36:09.941  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-30 09:36:09.942  1027  7406 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 09:36:09.942  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 09:36:09.942  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 09:36:09.944  1027  1531 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-30 09:36:09.946  1027  1531 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-30 09:36:09.947  1027  1531 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-30 09:36:09.949  1027  1531 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-30 09:36:09.949  1027  1531 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 09:36:09.955  1027  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=224613  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 09:36:09.957  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=224615  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 09:36:09.959  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:09.959  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 09:36:09.962  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:09.963  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:09.964  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:09.964  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:36:09.964  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-30 09:36:09.973  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:36:09.973  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:09.974  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 09:36:09.975  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:09.975  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 09:36:09.986  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:09.986  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:09.988  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 09:36:09.993  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:09.993  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:09.995  7010  7010 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 09:36:09.998  1027  2063 I ActivityManager: Killing 6984:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-30 09:36:10.029  1027  1593 W libprocessgroup: failed to open /acct/uid_10037/pid_6984/cgroup.procs: No such file or directory
,08-30 09:36:10.034  1027  1027 D PowerManagerServiceEx: releaseWakeLockInternal: lock=665227936 [*alarm*], flags=0x0
08-30 09:36:10.037  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 09:36:10.044  6945  6945 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 09:36:10.047  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:10.058  7398  7398 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 09:36:10.061  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 09:36:10.061  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 09:36:10.062  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 09:36:10.062  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 09:36:10.062  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 09:36:10.062  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 09:36:10.063  1027  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=224721  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 09:36:10.063  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 09:36:10.064  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=224722  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 09:36:10.064  1027  1531 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=224723
08-30 09:36:10.065  1027  1531 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=224724
08-30 09:36:10.067  1027  1089 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 09:36:10.067  1027  1531 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=224725
08-30 09:36:10.067  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 09:36:10.067  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 09:36:10.067  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=224726
08-30 09:36:10.067  7398  7398 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 09:36:10.068  7398  7398 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 09:36:10.071  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 09:36:10.071  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 09:36:10.071  1027  7406 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 09:36:10.071  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 09:36:10.072  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 09:36:10.072  1027  7406 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 09:36:10.072  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 09:36:10.072  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-30 09:36:10.073  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:10.074  1027  1531 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=224733
08-30 09:36:10.076  1027  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=224734  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 09:36:10.079  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:10.079  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:10.079  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.079  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.080  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 09:36:10.081  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.085  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:10.086  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 09:36:10.087  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=224746  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 09:36:10.090  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.090  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.090  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 09:36:10.091  7010  7010 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 09:36:10.091  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:10.091  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 09:36:10.092  1027  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=224751  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 09:36:10.094  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=224752  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 09:36:10.094  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:10.095  1027  1531 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:10.096  1027  1531 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:10.097  1027  1531 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:10.097  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-30 09:36:10.098  1027  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:10.099  1027  1531 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=224758
08-30 09:36:10.100  1027  1531 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=224759
08-30 09:36:10.101  1027  1531 D WifiNative-wlan0: doString: [STATUS]
08-30 09:36:10.102  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:10.102  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:10.102  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 09:36:10.102  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 09:36:10.103  1027  1531 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 09:36:10.103  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.105  1027  1531 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 09:36:10.106  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:10.110  1027  1531 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 09:36:10.110  1027  1531 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 09:36:10.115  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.115  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.115  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 09:36:10.115  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:10.118  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.118  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.118  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 09:36:10.124  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:10.124  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:10.125  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 09:36:10.126  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:10.126  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:10.127  7010  7010 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 09:36:10.127  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:10.127  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:10.128  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.130  1027  1531 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 09:36:10.130  1027  1537 D ConnectivityService: Got NetworkAgent Messenger
08-30 09:36:10.130  1027  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 09:36:10.130  1027  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 09:36:10.130  1027  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 09:36:10.130  1027  1537 D ConnectivityService: NetworkAgent connected
08-30 09:36:10.131  1027  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 09:36:10.131  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 09:36:10.131  1027  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 09:36:10.131  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 09:36:10.131  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 09:36:10.131  6945  6945 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 09:36:10.131  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 09:36:10.132  6945  6945 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 09:36:10.132  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 09:36:10.132  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 09:36:10.132  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 09:36:10.132  6945  6945 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 09:36:10.132  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 09:36:10.133  6945  6945 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 09:36:10.135  1027  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 09:36:10.135  1027  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 09:36:10.135  1027  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 09:36:10.135  1027  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 09:36:10.135  1027  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 09:36:10.137  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 09:36:10.141  1027  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 09:36:10.142   313   887 D CommandListener: Setting iface cfg
08-30 09:36:10.145  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 09:36:10.146  1027  1531 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 09:36:10.146  1027  7453 D DhcpStateMachine: StoppedState
08-30 09:36:10.146  1027  7453 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:10.146  1027  7453 D DhcpStateMachine: WaitBeforeStartState
08-30 09:36:10.146  1027  1531 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=224805  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 09:36:10.147  1027  1531 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=224805  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 09:36:10.147  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=224806  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 09:36:10.148  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:10.148  1027  1027 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 09:36:10.149  1027  1531 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=224807  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 09:36:10.149  1027  1531 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=224808  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-30 09:36:10.150  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=224808  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 09:36:10.151  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:10.151  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:178717] from screen [on:0 period:-631212377] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:36:10.152  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-631212376] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:36:10.152  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 09:36:10.156  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:10.156  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:10.157  7010  7010 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 09:36:10.158  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.160  1027  1537 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-30 09:36:10.161  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:10.161  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:10.161  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:10.161  1027  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:10.162  1027  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 09:36:10.162  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:10.163  1027  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:10.164  1027  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 09:36:10.164  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=173,0,0
08-30 09:36:10.164  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=173,0,0
08-30 09:36:10.164  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 09:36:10.165  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 09:36:10.165  1027  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 09:36:10.166  1027  1531 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 09:36:10.166  1027  1531 D WifiNative-wlan0: SET ps 0: returned true
08-30 09:36:10.166  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 09:36:10.166  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 09:36:10.167  1027  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 09:36:10.167  1027  1529 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@13956bb1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:10.167  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@13956bb1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:10.168  1027  1531 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 09:36:10.168  1027  7453 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:10.168  1027  1531 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 09:36:10.168  1027  7453 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 09:36:10.168  1027  1531 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 09:36:10.168  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 09:36:10.169   313   887 D CommandListener: Setting iface cfg
,08-30 09:36:10.169   313   887 D CommandListener: Trying to bring up wlan0
08-30 09:36:10.170  1027  1531 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 09:36:10.171  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:10.171  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 09:36:10.172  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:10.172  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 09:36:10.172  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:10.173  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:10.173  1027  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:10.173  1027  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:10.174  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 09:36:10.175  1027  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 09:36:10.175  1027  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 09:36:10.176  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 09:36:10.176  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 09:36:10.177  1027  1529 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:10.177  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:10.177  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 09:36:10.177  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 09:36:10.178  1027  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 09:36:10.178  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 09:36:10.178  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 09:36:10.178  1027  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 09:36:10.178  1027  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 09:36:10.180  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:10.185  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:10.186  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:10.186  7010  7010 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 09:36:10.188  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 09:36:10.194  1027  1531 D WifiNative-wlan0: SET ps 1: returned true
08-30 09:36:10.195  1027  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 09:36:10.195  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 09:36:10.196  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 09:36:10.196  1027  1531 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 09:36:10.196  1027  1537 D ConnectivityService: ignoring duplicate network state non-change
08-30 09:36:10.198  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:10.203  1027  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 09:36:10.204  1027  1537 D ConnectivityService: Adding iface wlan0 to network 101
08-30 09:36:10.204  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:10.204  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:10.207  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.207  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.207  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.208  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 09:36:10.213  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.213  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.213  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-30 09:36:10.216  1027  1531 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 09:36:10.217  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:10.218  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 09:36:10.222  1958  1958 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 09:36:10.225  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.225  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.225  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 09:36:10.225  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-30 09:36:10.231  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:10.231  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:10.232  1027  1537 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 09:36:10.232  1027  1537 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 09:36:10.233  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.233  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.233  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:10.233  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 09:36:10.233  1027  1537 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 09:36:10.235   313   887 E Netd    : netlink response contains error (File exists)
08-30 09:36:10.236  1027  1537 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 09:36:10.236  1027  1537 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 09:36:10.236  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:10.236  1027  1537 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 09:36:10.236  1027  1537 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 09:36:10.237  1596  1596 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 09:36:10.237  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.240  1027  1537 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 09:36:10.240  1027  1537 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 09:36:10.240  1027  1537 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 09:36:10.240  1027  1537 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 09:36:10.240  1027  1537 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 09:36:10.240  1027  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:10.240  1027  1537 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 09:36:10.240  1027  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 09:36:10.240  1027  1537 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 09:36:10.240  1027  1537 D ConnectivityService: currentScore = 0, newScore = 20
08-30 09:36:10.240  1027  1537 D ConnectivityService:    accepting network in place of null
08-30 09:36:10.241  1027  1537 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:10.241  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:10.241  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 09:36:10.241  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:10.241  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 09:36:10.243  1027  1531 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:10.243  1027  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 09:36:10.243   313  7457 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 09:36:10.245  1027  1537 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 09:36:10.245  1871  1871 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:10.245  1027  1537 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 09:36:10.245  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 09:36:10.245  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 09:36:10.246  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:10.247  1027  1027 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 09:36:10.247  1596  1596 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 09:36:10.247  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 09:36:10.247  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.247  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 09:36:10.247  1027,  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 09:36:10.248  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:10.249  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:10.249  7010  7010 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 09:36:10.251  1027  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:10.251  1027  1537 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 09:36:10.253  1027  1537 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-30 09:36:10.254  1027  1537 D ConnectivityService: validation of new default Network = false
08-30 09:36:10.254  1027  1537 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
,08-30 09:36:10.254  1027  1537 D DSQN    : enableDataServiceNotify 
08-30 09:36:10.254  1027  1537 D DSQN    : start dsqn bin
08-30 09:36:10.255  7458  7458 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:10.255  7458  7458 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:10.259  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:10.261  1027  1537 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 09:36:10.261  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:10.261  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:10.262  1027  1537 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:10.265  1596  1806 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 09:36:10.275  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 09:36:10.276  7458  7458 E DSQN    : DSQN ssw
,08-30 09:36:10.284  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 09:36:10.293  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:10.294  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:10.294  7010  7010 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 09:36:10.300  1027  1528 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 09:36:10.301  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:10.305  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 09:36:10.306  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.306  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.308   313  7457 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 09:36:10.314  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 09:36:10.317  1835  7462 I CheckinService: active receiver: enabled
,08-30 09:36:10.322  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:10.328  1835  7462 I CheckinService: Preparing to send checkin request
08-30 09:36:10.328  1835  7462 I EventLogService: Accumulating logs since 1472542403330
,08-30 09:36:10.334  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:10.334  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:10.338  7010  7010 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 09:36:10.340   313  7457 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 09:36:10.342  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 09:36:10.349  6726  7123 D UEI.SmartControl: Internal timer expired: 2
08-30 09:36:10.349  6726  7123 D UEI.SmartControl: unbind internal service
,08-30 09:36:10.352  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:10.364  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:10.371  1027  7453 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 09:36:10.371  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:10.371  1027  7453 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 09:36:10.372  1027  7453 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 09:36:10.372  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:10.372  7010  7010 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 09:36:10.373  1835  7462 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-30 09:36:10.365  7464  7464 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:10.365  7464  7464 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:10.379  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:10.379   313   886 D LGDataListener: argv[0]=dsqncommand
08-30 09:36:10.379   313   886 D LGDataListener: argv[1]=wlan0
08-30 09:36:10.379   313   886 D LGDataListener: argv[2]=1
08-30 09:36:10.379   313   886 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 09:36:10.379  1027  1087 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 09:36:10.379  1027  1087 D DSQN    : start to monitor internet connection
08-30 09:36:10.385  7464  7464 I dhcpcd  : version 5.5.6 starting
,08-30 09:36:10.387  7464  7464 E dhcpcd  : get_duid: m
08-30 09:36:10.387  7464  7464 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 09:36:10.387  7464  7464 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 09:36:10.388  6726  7120 D serial_port: close(fd = 24)
08-30 09:36:10.389  6963  6963 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 09:36:10.392  6726  7120 I UEI.SmartControl: Serial port is closed.
08-30 09:36:10.397  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 09:36:10.401  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:10.410  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 07:36:10 GMT], X-Android-Received-Millis=[1472542570409], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472542570376]}
,08-30 09:36:10.410  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 09:36:10.410  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 09:36:10.410  1027  1537 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-30 09:36:10.410  1027  1537 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 09:36:10.410  1027  1537 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 09:36:10.410  1027  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:10.410  1027  1537 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 09:36:10.410  1027  1537 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-30 09:36:10.411  1027  1537 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 09:36:10.411  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:10.411  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:10.411  1027  1537 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:10.411  1027  1537 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:10.411  1596  1806 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 09:36:10.412  1027  1531 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:10.412  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 09:36:10.412  1027  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 09:36:10.412  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:10.414  1871  1871 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:10.414  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 09:36:10.423  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:10.423  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:10.424  7010  7010 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 09:36:10.425  7010  7010 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 09:36:10.426  7010  7010 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 09:36:10.433  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:10.438  6963  6963 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 09:36:10.442  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 09:36:10.446  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:10.453  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 09:36:10.454  7464  7464 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 09:36:10.454  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.454  7464  7464 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 09:36:10.454  7464  7464 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 09:36:10.454  7464  7464 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 09:36:10.454  7464  7464 D dhcpcd  : wlan0: sending REQUEST (xid 0xd026ba67), next in 4.47 seconds
08-30 09:36:10.455  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:10.457  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:10.466  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:10.467  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 09:36:10.467  7010  7010 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 09:36:10.468  7010  7010 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 09:36:10.468  7010  7010 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 09:36:10.478  7464  7464 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 09:36:10.498  7464  7464 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 09:36:10.498  7464  7464 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-30 09:36:10.499  7464  7464 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 09:36:10.499  7464  7464 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 09:36:10.499  7464  7464 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 09:36:10.500  7464  7464 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 09:36:10.500  7464  7464 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 09:36:10.500  7464  7464 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 09:36:10.562  1027  1758 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7477 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 09:36:10.591  1027  1418 V AlarmManager: ELAPSED_WAKEUP set : Alarm{927e070 type 2 when 225249 com.google.android.gms} when 225249
,08-30 09:36:10.600  7010  7010 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 09:36:10.601  7010  7010 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7794
08-30 09:36:10.605   313  7499 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 09:36:10.608   313  7499 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-30 09:36:10.631  7477  7477 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 09:36:10.632  7477  7477 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 09:36:10.646   313  7499 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-30 09:36:10.658  7477  7477 I MultiDex: VM with version 2.1.0 has multidex support
08-30 09:36:10.658  7477  7477 I MultiDex: install
08-30 09:36:10.658  7477  7477 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 09:36:10.672  7477  7477 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-30 09:36:10.677  2251  2251 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 09:36:10.694  2251  2251 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 09:36:10.695  2251  2251 D c       : Getting all permits...
08-30 09:36:10.695  2251  2251 D a       : Opening database...
,08-30 09:36:10.697  2251  2251 D a       : Opening database auth.proximity.permit_store...
08-30 09:36:10.699  2251  2251 D a       : Closing database...
,08-30 09:36:10.777  1027  7453 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 09:36:10.778  1027  7453 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 09:36:10.778  1027  7453 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 09:36:10.779  1027  7453 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 09:36:10.779  1027  7453 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 09:36:10.779  1027  7453 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 09:36:10.779  1027  7453 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 09:36:10.779  1027  7453 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 09:36:10.779  1027  7453 D DhcpStateMachine: RunningState
08-30 09:36:10.929  2251  7517 D GCM     : Connected
,08-30 09:36:10.929  7477  7495 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 09:36:10.929  7477  7495 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:36:10.961  2251  7517 D GCM     : Message class com.google.e.a.a.q
,08-30 09:36:11.114  7521  7521 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 09:36:11.198  7521  7521 I dex2oat : dex2oat took 83.550ms (threads: 4)
,08-30 09:36:11.217  7477  7495 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 09:36:11.217  7477  7495 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 09:36:11.217  7477  7495 I Adreno-EGL: Build Date: 12/12/14 금
08-30 09:36:11.217  7477  7495 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 09:36:11.217  7477  7495 I Adreno-EGL: Remote Branch: 
08-30 09:36:11.217  7477  7495 I Adreno-EGL: Local Patches: 
08-30 09:36:11.217  7477  7495 I Adreno-EGL: Reconstruct Branch: 
,08-30 09:36:11.263  1027  1537 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 09:36:11.370  7477  7495 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 09:36:11.370  7477  7495 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 09:36:11.370  7477  7495 I Adreno-EGL: Build Date: 12/12/14 금
08-30 09:36:11.370  7477  7495 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 09:36:11.370  7477  7495 I Adreno-EGL: Remote Branch: 
08-30 09:36:11.370  7477  7495 I Adreno-EGL: Local Patches: 
08-30 09:36:11.370  7477  7495 I Adreno-EGL: Reconstruct Branch: 
,08-30 09:36:11.431  1027  1531 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 09:36:11.433  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 09:36:11.434  1027  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 09:36:11.435  1027  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 09:36:11.437  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:11.439  1027  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 09:36:11.440  1027  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true,
08-30 09:36:11.440  1027  1537 D ConnectivityService: identical MTU - not setting
08-30 09:36:11.440  1027  1537 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 09:36:11.442  1027  1537 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 09:36:11.443  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:11.443  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:11.443  1027  1537 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:11.452  1596  1806 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 09:36:11.522  7477  7495 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 09:36:11.522  7477  7495 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 09:36:11.522  7477  7495 I Adreno-EGL: Build Date: 12/12/14 금
08-30 09:36:11.522  7477  7495 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 09:36:11.522  7477  7495 I Adreno-EGL: Remote Branch: 
08-30 09:36:11.522  7477  7495 I Adreno-EGL: Local Patches: 
08-30 09:36:11.522  7477  7495 I Adreno-EGL: Reconstruct Branch: 
,08-30 09:36:11.709   313  7531 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 09:36:11.711   313  7531 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-30 09:36:11.760   313  7531 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 09:36:11.878  1835  7462 I CheckinTask: Sending checkin request (7859 bytes)
,08-30 09:36:12.170  1835  7462 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-30 09:36:12.210  1835  7462 I CheckinService: active receiver: disabled
,08-30 09:36:12.236  2251  2251 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-30 09:36:12.251  2251  2251 I GCM     : GCM config loaded
,08-30 09:36:12.292  7201  7201 V SetupWizard: Connected to Gservices successfully
,08-30 09:36:13.165  1027  1531 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=86.5, 0.0, 0.0  rx=78.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-631209364] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 09:36:13.177  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=86.5, 0.0, 0.0  rx=78.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-631209361] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:36:13.177  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 09:36:13.211  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 09:36:13.219  1027  1532 V WifiInternetCheck: Single check msg out of sync, ignoring.
08-30 09:36:13.251  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:13.259  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-30 09:36:13.269  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.269  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:13.269  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:13.269  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:13.269  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:13.269  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:13.269  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:36:13.269  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:36:13.269  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:36:13.269  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.269  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:36:13.281  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.281  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:13.281  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:13.281  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:13.281  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:13.281  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:13.281  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:36:13.281  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:36:13.281  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:36:13.281  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.281  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:36:13.283  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.283  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:13.283  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:13.283  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:13.283  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:13.283  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:13.283  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:36:13.283  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:36:13.283  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:36:13.283  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.283  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:36:13.292  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:13.294  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 09:36:13.296  6477  6944 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 09:36:13.313  1027  1043 D WifiServiceImplEx: setWifiEnabled: false pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 09:36:13.313  1027  1043 D WifiService: setWifiEnabled: false pid=6817, uid=10118
08-30 09:36:13.313  1027  1043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 09:36:13.325  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 09:36:13.325  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 09:36:13.325  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-30 09:36:13.326  1027  1531 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 09:36:13.327  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 09:36:13.327  1027  1531 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 09:36:13.327  1027  1531 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 09:36:13.328  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 09:36:13.328  1027  1531 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 09:36:13.328  1027  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 09:36:13.328  1027  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-30 09:36:13.332  1027  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 09:36:13.332  1027  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 09:36:13.338  1027  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 09:36:13.338  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 09:36:13.339  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 09:36:13.339  1027  1529 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.339  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.340  1027  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 09:36:13.340  1027  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 09:36:13.340  1027  1531 D WifiNative-wlan0: SET ps 1: returned true
08-30 09:36:13.340   313   887 D CommandListener: Clearing all IP addresses on wlan0
08-30 09:36:13.348  1027  7453 D DhcpStateMachine: RunningState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 09:36:13.423  1027  1027 D WifiHS20: hidePasspointNotification off =false
,08-30 09:36:13.435  1027  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:13.436  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:13.437  1027  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:13.439  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:13.439  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:13.440  1958  1958 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 09:36:13.443  1027  1529 D LGWifiP2pService: InactiveState{ when=-33ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 09:36:13.443  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-33ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.443  1027  1529 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2fbbe5e3
08-30 09:36:13.446  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:13.451  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:13.451  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:13.451  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 09:36:13.451  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-30 09:36:13.454  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:13.454  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:13.454  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 09:36:13.454  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 09:36:13.454  1027  1027 D RttService: SCAN_AVAILABLE : 1
08-30 09:36:13.455  1027  1548 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.455  1027  1529 D LGWifiP2pService: P2pDisablingState
08-30 09:36:13.455  1027  1549 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.455  1027  1529 D LGWifiP2pService: P2pDisablingState{ when=-12ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.455  1027  1529 D LGWifiP2pService: p2p socket connection lost
08-30 09:36:13.455  1027  1529 D LGWifiP2pService: P2pDisabledState
08-30 09:36:13.456  1027  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 09:36:13.456  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 09:36:13.456  7398  7398 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 09:36:13.456  1027  1529 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.457  1027  1529 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.457  1027  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-30 09:36:13.457  1027  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 09:36:13.458  1027  1531 D WifiNative-wlan0: SET ps 1: returned true
08-30 09:36:13.458   313   887 D CommandListener: Clearing all IP addresses on wlan0
08-30 09:36:13.460  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 09:36:13.460  1958  1958 D WfdsService: WifiP2pState is changed : false
08-30 09:36:13.460  1958  2300 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 09:36:13.460  1958  2300 D WfdsService: Set the WFDS Monitor: false
08-30 09:36:13.460  1027  1531 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 09:36:13.461  1027  1531 D WifiNative-p2p0: TERMINATE: returned true
08-30 09:36:13.461  1027  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 09:36:13.461  1027  1531 E WifiStateMachine: useWiFiOffloading() : false
08-30 09:36:13.461  1027  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 09:36:13.462  1958  2300 D WfdsMonitor: WFDS Monitor is stopped
08-30 09:36:13.462  1958  2300 D WfdsService: STATE : WfdsDisabledState - enter
08-30 09:36:13.462  1958  7411 D CtrlSupplicant: Received on exit socket, terminate
08-30 09:36:13.462  1958  7411 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 09:36:13.462  1958  7411 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 09:36:13.462  1958  7411 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 09:36:13.462  1958  2305 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 09:36:13.463  1958  2300 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 09:36:13.463  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-30 09:36:13.463  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:13.463  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:13.463  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 09:36:13.465  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 09:36:13.468  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 09:36:13.468  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-30 09:36:13.468  1027  1027 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 09:36:13.470  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:13.470  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:13.472  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:13.473  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 09:36:13.473  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:13.474  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:13.476  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:13.504  7307  7334 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 09:36:13.520  7398  7398 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 09:36:13.520  7398  7398 I wpa_supplicant: monitor socket send errors count : 1
08-30 09:36:13.520  7398  7398 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1958-4\x00 that cannot receive messages
08-30 09:36:13.521  1027  7406 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,08-30 09:36:13.521  1027  7406 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 09:36:13.561  7398  7398 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 09:36:13.563  7398  7398 W wpa_supplicant: USIM:  scard_deinit function
08-30 09:36:13.563  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 09:36:13.563  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 09:36:13.563  1027  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 09:36:13.563  1027  7406 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 09:36:13.564  1027  1537 D ConnectivityService: ignoring duplicate network state non-change
08-30 09:36:13.564  1027  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-30 09:36:13.564  1027  7406 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 09:36:13.564  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 09:36:13.564  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 09:36:13.566  1027  1531 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 09:36:13.567  1027  1531 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=228226
08-30 09:36:13.574  1027  1531 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=228233
08-30 09:36:13.575  1027  2005 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-30 09:36:13.576  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.576  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.576  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 09:36:13.577  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.577  1027  1089 D Tethering: InitialState.processMessage what=4
08-30 09:36:13.577  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-30 09:36:13.581  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.581  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:13.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:13.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:13.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:13.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:13.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:13.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:36:13.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:36:13.581  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.582  6817  6817 D io.jxcore.,node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:36:13.584  1027  1531 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=228242  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 09:36:13.586  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 09:36:13.586  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:13.586  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:13.586  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:13.586  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:13.586  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:13.586  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:13.586  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:13.586  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:36:13.587  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.587  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:13.591  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 09:36:13.592  1027  7453 D DhcpStateMachine: StoppedState
08-30 09:36:13.592  1027  7453 D DhcpStateMachine: StoppedState{ when=-134ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.595  1027  1531 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=228253  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 09:36:13.597  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.597  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:13.597  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:13.597  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:13.597  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:13.597  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:13.597  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:13.597  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:13.597  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:36:13.597  1027  1531 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:13.597  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.597  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:36:13.603  1027  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:13.603  1027  1531 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 09:36:13.604  1027  1531 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 09:36:13.604  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-30 09:36:13.606  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:13.618  2251  2251 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:13.619  2251  2251 W GCM     : ACTIVE NETWORK NOT CONNECTED
08-30 09:36:13.623  1027  2009 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-30 09:36:13.629  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 09:36:13.629  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:13.629  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 09:36:13.629  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 09:36:13.634  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 09:36:13.639  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3b634cfd
08-30 09:36:13.639  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 09:36:13.639  7128  7128 D AppUp4:CustFacade: isPhone : true
08-30 09:36:13.639  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
08-30 09:36:13.639  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 09:36:13.643  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:13.644  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 09:36:13.645  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:13.648  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:13.649  7398  7398 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 09:36:13.650  1027  7406 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 09:36:13.650  1027  7406 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
,08-30 09:36:13.650  1027  7406 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 09:36:13.651  1027  1531 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-30 09:36:13.656  4307  7572 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 09:36:13.658  4307  7573 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:13.659  4307  7573 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 09:36:13.665  1027  1085 W ProcessCpuTracker: Skipping unknown process pid 7398
,08-30 09:36:13.672  7170  7170 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 09:36:13.680   313  7575 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 09:36:13.680  1027  1537 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 09:36:13.680  1027  1537 D DSQN    : disableDataServiceNotify
08-30 09:36:13.680  1027  1537 D DSQN    : stop dsqn bin
08-30 09:36:13.681   313  7576 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 09:36:13.683  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,08-30 09:36:13.683  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-60ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.683  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 09:36:13.683  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 09:36:13.689  1027  1537 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 09:36:13.689  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:13.689  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:13.690  1027  1537 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:13.690  1027  1537 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 09:36:13.691  1596  1806 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 09:36:13.691  1027  1537 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 09:36:13.691  1027  1537 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 09:36:13.691  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 09:36:13.692  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.692  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:13.692  1027  7452 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 09:36:13.692  1027  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:13.692  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 09:36:13.693  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 09:36:13.694  1027  1528 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 09:36:13.694  1027  1528 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 09:36:13.695  1027  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:13.695  1027  1537 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:13.695  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 09:36:13.695  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 09:36:13.696  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 09:36:,13.696  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 09:36:13.696  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 09:36:13.696  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 09:36:13.696  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 09:36:13.698  1027  1537 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:13.699  1871  1871 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:13.699  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 09:36:13.699  1027  1537 D NetworkManagementService: Removing idletimer
08-30 09:36:13.699  1027  1537 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:13.707  7170  7577 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:36:13.710  3399  3399 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 09:36:13.710  3399  3399 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:13.711  3399  3399 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 09:36:13.711  3399  3399 D PhoneState: setPdpRejectCasuse : false
08-30 09:36:13.712  7050  7579 W FormManager: Network not available. Please check & try again.
08-30 09:36:13.720  7201  7201 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 09:36:13.720  7201  7201 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 09:36:13.734  7283  7283 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:13
,08-30 09:36:13.735  7050  7580 V FormManager: Network unavailable.
08-30 09:36:13.736  7283  7283 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 09:36:13.736  7283  7283 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 09:36:13.736  7283  7283 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 09:36:13.736  7283  7283 D WeatherAncestor: connectivity changed - connection : true
08-30 09:36:13.737  7283  7283 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1e00dc43
08-30 09:36:13.737  7283  7283 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 09:36:13.737  7283  7283 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 09:36:13.737  7283  7283 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 09:36:13.737  7283  7283 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 09:36:13.738  7283  7283 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:13
08-30 09:36:13.756  1027  1531 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 09:36:13.757  1027  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 09:36:13.757  1027  1531 E WifiStateMachine: useWiFiOffloading() : false
08-30 09:36:13.757  1027  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 09:36:13.757  7050  7580 V FormManager: Network unavailable.
08-30 09:36:13.758  1958  1958 D WfdsService: Supplicant Connection state is changed : false
08-30 09:36:13.759  1958  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 09:36:13.759  1958  2300 D WfdsService: Set the WFDS Monitor: false
08-30 09:36:13.759  1958  2300 D WfdsMonitor: WFDS Monitor is stopped
,08-30 09:36:13.769  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 09:36:13.771  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:36:13.774  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 09:36:13.774  1027  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 09:36:13.774  1027  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 09:36:13.783  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 09:36:13.784  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:13.785  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 09:36:13.793  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:13.793  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:13.793  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:13.794  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:13.794  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:13.794  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:13.794  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:13.794  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:13.794  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:13.794  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:13.794  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:13.794  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:13.796  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 09:36:13.802  6963  6963 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 09:36:13.802  6963  6963 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 09:36:13.802  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 09:36:13.808  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:13.816  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 09:36:13.825  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 09:36:13.825  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:13.828  7010  7010 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 09:36:13.831  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 09:36:13.832  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:13.833  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:13.833  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:13.834  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:13.839  6963  6963 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 09:36:13.840  6963  6963 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 09:36:13.840  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 09:36:13.848  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:13.857  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:13.866  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:13.866  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:13.869  7010  7010 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 09:36:13.873  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 09:36:13.878  6963  6963 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 09:36:13.879  6963  6963 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 09:36:13.879  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 09:36:13.883  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:13.892  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:13.901  7010  7010 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:13.902  7010  7010 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 09:36:13.904  7010  7010 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 09:36:13.917  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 09:36:13.923  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 09:36:13.926  7050  7583 W FormManager: Network not available. Please check & try again.
08-30 09:36:13.933  7050  7584 V FormManager: Network unavailable.
08-30 09:36:13.937  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:13.937  7050  7584 V FormManager: Network unavailable.
08-30 09:36:13.967  1027  1531 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 09:36:13.967  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 09:36:13.967  1027  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 09:36:13.967  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 09:36:13.967  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 09:36:13.968  6945  6945 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 09:36:13.969  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 09:36:13.970  6945  6945 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 09:36:13.970  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 09:36:13.970  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 09:36:13.970  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 09:36:13.970  6945  6945 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 09:36:13.970  6945  6945 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 09:36:13.976  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 09:36:13.977  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 09:36:13.980  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:13.984  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 09:36:13.996  4307  7585 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 09:36:14.004  4307  7586 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-30 09:36:14.004  4307  7586 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 09:36:14.007  6963  6963 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-30 09:36:14.007  6963  6963 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-30 09:36:14.007  6963  6963 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 09:36:14.014  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 09:36:14.021  7050  7588 W FormManager: Network not available. Please check & try again.
08-30 09:36:14.025  7050  7589 V FormManager: Network unavailable.
,08-30 09:36:14.028  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:14.048  7050  7589 V FormManager: Network unavailable.
,08-30 09:36:14.311  1027  1727 I ActivityManager: Killing 7030:com.lge.settings.easy/1000 (adj 15): empty #17
,08-30 09:36:14.427  1027  1757 W libprocessgroup: failed to open /acct/uid_1000/pid_7030/cgroup.procs: No such file or directory
,08-30 09:36:16.222  1027  1531 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-631206306] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 09:36:16.224  1027  1531 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-631206304] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 09:36:16.695  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:16.714  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-30 09:36:16.722  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:36:16.725  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:16.726  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:16.735  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:16.741  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:16.743  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-30 09:36:16.749  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 09:36:16.750  6477  6944 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 09:36:16.759  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:16.760  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:16.761  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:16.774  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 09:36:16.782  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 09:36:16.796  2251  2251 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:16.816  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 09:36:16.816  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:16.816  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 09:36:16.816  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 09:36:16.821  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
08-30 09:36:16.825  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3b634cfd
08-30 09:36:16.825  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 09:36:16.825  7128  7128 D AppUp4:CustFacade: isPhone : true
08-30 09:36:16.826  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
08-30 09:36:16.826  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 09:36:16.831  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:16.831  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 09:36:16.832  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 09:36:16.839  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 09:36:16.846  7170  7170 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 09:36:16.858  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:16.870  4307  7613 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:16.870  4307  7612 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 09:36:16.870  4307  7613 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 09:36:16.873  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:16.873  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 09:36:16.886  7170  7617 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:36:16.889  7050  7619 W FormManager: Network not available. Please check & try again.
08-30 09:36:16.893  3399  3399 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-30 09:36:16.893  3399  3399 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:16.894  3399  3399 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 09:36:16.895  7050  7620 V FormManager: Network unavailable.
08-30 09:36:16.898  7201  7201 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 09:36:16.898  7201  7201 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 09:36:16.903  7050  7620 V FormManager: Network unavailable.
,08-30 09:36:16.908  7283  7283 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:16
08-30 09:36:16.913  7283  7283 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 09:36:16.913  7283  7283 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 09:36:16.913  7283  7283 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 09:36:16.914  7283  7283 D WeatherAncestor: connectivity changed - connection : true
,08-30 09:36:16.914  7283  7283 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1e00dc43
08-30 09:36:16.915  7283  7283 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 09:36:16.915  7283  7283 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 09:36:16.915  7283  7283 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 09:36:16.915  7283  7283 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 09:36:16.915  7283  7283 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:16
08-30 09:36:16.925  1027  2009 I ActivityManager: Killing 7432:com.lge.bnr/1000 (adj 15): empty #17
,08-30 09:36:16.963  1027  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_7432/cgroup.procs: No such file or directory
,08-30 09:36:16.988  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 09:36:16.990  6477  6944 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 09:36:17.019  2251  2251 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:17.037  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-30 09:36:17.038  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:17.038  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-30 09:36:17.038  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 09:36:17.041  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
08-30 09:36:17.045  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3b634cfd
08-30 09:36:17.045  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 09:36:17.045  7128  7128 D AppUp4:CustFacade: isPhone : true
08-30 09:36:17.047  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
08-30 09:36:17.047  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 09:36:17.057  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:17.058  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 09:36:17.062  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:17.068  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:17.080  7170  7170 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 09:36:17.080  4307  7623 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 09:36:17.091  4307  7624 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:17.092  4307  7624 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 09:36:17.116  3399  3399 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 09:36:17.116  3399  3399 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:17.116  3399  3399 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 09:36:17.121  7170  7626 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:17.123  7201  7201 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 09:36:17.123  7201  7201 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 09:36:17.124  7050  7627 W FormManager: Network not available. Please check & try again.
08-30 09:36:17.132  7050  7628 V FormManager: Network unavailable.
,08-30 09:36:17.136  7283  7283 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:17
08-30 09:36:17.138  7050  7628 V FormManager: Network unavailable.
08-30 09:36:17.138  7283  7283 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 09:36:17.138  7283  7283 D Weather.Utils: 2 : All the weather widget is gone.
08-30 09:36:17.139  7283  7283 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 09:36:17.139  7283  7283 D WeatherAncestor: connectivity changed - connection : true
08-30 09:36:17.139  7283  7283 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1e00dc43
08-30 09:36:17.140  7283  7283 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 09:36:17.140  7283  7283 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 09:36:17.140  7283  7283 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 09:36:17.140  7283  7283 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 09:36:17.140  7283  7283 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:17
08-30 09:36:18.329  1027  2063 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:18.329  1027  2063 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 09:36:18.349  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 09:36:18.349  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 09:36:18.349  1027  1027 D Ulp_jni : JNI:system_update. Event-4
,08-30 09:36:18.352  1027  1089 D BluetoothManagerService: Message: 1
08-30 09:36:18.352  1027  1089 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 09:36:18.377  1027  1089 D BluetoothManagerService: Message: 20
08-30 09:36:18.377  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@135c685:true
,08-30 09:36:18.381  7087  7087 D BluetoothAdapterState: make
08-30 09:36:18.386  7087  7087 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 09:36:18.387  7087  7641 I BluetoothAdapterState: Entering OffState
08-30 09:36:18.387  7087  7087 I bluedroid-qcom: init
08-30 09:36:18.388  7087  7087 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 09:36:18.388  7087  7087 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 09:36:18.388  7087  7087 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 09:36:18.388  7087  7087 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 09:36:18.388  7087  7087 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 09:36:18.390  7087  7087 I bluedroid-qcom: get_profile_interface socket
08-30 09:36:18.390  7087  7087 I bluedroid-qcom: get_profile_interface map_client
,08-30 09:36:18.395  7087  7645 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 09:36:18.385  7644  7644 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:18.400  7087  7645 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 09:36:18.395  7644  7644 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:18.410  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-30 09:36:18.413  1027  1089 D BluetoothManagerService: Message: 40
08-30 09:36:18.413  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 09:36:18.414  7087  7103 I bluedroid-qcom: config_hci_snoop_log
08-30 09:36:18.415  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 09:36:18.415  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 09:36:18.417  7644  7644 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 09:36:18.417  7644  7644 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 09:36:18.417  7644  7644 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 09:36:18.420  7644  7644 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 09:36:18.424  7087  7641 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-30 09:36:18.428  7644  7644 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 09:36:18.428  7644  7644 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 09:36:18.431  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 09:36:18.431  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 09:36:18.431  7087  7645 D BluetoothAdapterProperties: Name is: G3
08-30 09:36:18.431  7087  7641 D BluetoothAdapterProperties: Setting state to 11
08-30 09:36:18.432  7087  7641 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 09:36:18.432  1027  1089 D BluetoothManagerService: Message: 60
08-30 09:36:18.432  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 09:36:18.433  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 09:36:18.434  7087  7641 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 09:36:18.441  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 09:36:18.443  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 09:36:18.446  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:18.448  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:18.449  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:18.452  6945  6945 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 09:36:18.458  1027  1529 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:18.458  1027  1529 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 09:36:18.462  7087  7087 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 09:36:18.464  7087  7087 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:18.464  7087  7087 V BluetoothPbapReceiver: ***********state = 11
08-30 09:36:18.465  1027  1531 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-30 09:36:18.466  1027  1531 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-30 09:36:18.474  7087  7641 D BluetoothBondStateMachine: make
,08-30 09:36:18.485  2251  2251 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 09:36:18.496  7087  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:18.496  7087  7641 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 09:36:18.497  7087  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:18.497  7087  7641 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,08-30 09:36:18.497  7087  7646 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 09:36:18.498  7087  7641 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-30 09:36:18.505  7087  7641 E BluetoothAdapterService: File transfer profiles supported!!
08-30 09:36:18.537  1027  1757 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7663 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 09:36:18.543  7087  7087 D HeadsetService: Received start request. Starting profile...
08-30 09:36:18.543  7087  7087 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 09:36:18.544  7087  7087 D LGBluetoothHfpAdapter: Version 1.6
,08-30 09:36:18.545  7087  7641 E BluetoothAdapterService: File transfer profiles supported!!
08-30 09:36:18.547  7087  7087 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 09:36:18.548  7087  7087 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 09:36:18.549  7087  7087 D HeadsetStateMachine: make
,08-30 09:36:18.558  7087  7641 E BluetoothAdapterService: File transfer profiles supported!!
08-30 09:36:18.565  7087  7641 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 09:36:18.573  7087  7641 E BluetoothAdapterService: File transfer profiles supported!!
08-30 09:36:18.579  7087  7641 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 09:36:18.589  7087  7641 E BluetoothAdapterService: File transfer profiles supported!!
08-30 09:36:18.594  7087  7087 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:18.594  7087  7087 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 09:36:18.600  7087  7087 D HeadsetStateMachine: max_hf_connections = 1
08-30 09:36:18.600  7087  7087 I bluedroid-qcom: get_profile_interface handsfree
08-30 09:36:18.602  7087  7087 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-30 09:36:18.603   318  4036 V AudioPolicyService: registerClient() client 0xb57edb20, uid 1002
08-30 09:36:18.603   318   318 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 09:36:18.603   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 09:36:18.603   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 09:36:18.603  7087  7087 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 09:36:18.604   318  1377 V AudioFlinger: registerClient() client 0xb55814f0, pid 7087
08-30 09:36:18.604   318  1371 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:18.604   318  1371 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 09:36:18.605  1027  1567 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:18.605  1027  1567 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 09:36:18.605  1871  3508 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:18.605  1871  3508 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 09:36:18.605  7087  7102 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:18.605  7087  7102 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 09:36:18.605  3399  3414 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:18.605  3399  3414 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 09:36:18.605  1596  1615 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:18.605  1596  1615 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 09:36:18.605  7087  7087 V ToneGenerator: Create Track: 0xb4928a80
08-30 09:36:18.605   318  1372 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:18.605   318  1372 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 09:36:18.605  7087  7087 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 09:36:18.605  7087  7087 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 09:36:18.606  1596  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:18.606  1596  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 09:36:18.606  1871  2550 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:18.606  1871  2550 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 09:36:18.606   318  1377 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 09:36:18.606   318  1377 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 09:36:18.606   318  1377 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 09:36:18.606   318  1377 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 09:36:18.606  7087  7103 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:18.606  7087  7103 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 09:36:18.606  1027  1043 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:18.606  1027  1043 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 09:36:18.606   318   318 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 09:36:18.606  3399  3418 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:18.606  3399  3418 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 09:36:18.606   318  1377 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 09:36:18.606   318  1377 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 09:36:18.606   31,8  1377 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 09:36:18.606   318  1377 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 09:36:18.607  7087  7087 V AudioSystem: getLatency() output 2, latency 50
08-30 09:36:18.607  7087  7087 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 09:36:18.607  7087  7087 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 09:36:18.607   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 09:36:18.607   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 09:36:18.607   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 09:36:18.607   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 09:36:18.607   318   318 V AudioFlinger: createTrack() lSessionId: 22
08-30 09:36:18.608  7087  7087 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 09:36:18.608   318  4036 V AudioFlinger: acquiring 22 from 7087, for 7087
08-30 09:36:18.608   318  4036 V AudioFlinger:  added new entry for 22
08-30 09:36:18.608  7087  7087 V ToneGenerator: ToneGenerator INIT OK, time: 233280
08-30 09:36:18.608  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:18.609  7087  7674 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 09:36:18.609  7087  7674 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 09:36:18.609  7087  7674 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 09:36:18.610  7087  7674 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 09:36:18.610  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:18.611   318  1377 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7087
08-30 09:36:18.611   318  1377 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 09:36:18.611   318  1377 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 09:36:18.611   318  1377 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 09:36:18.611   318  1377 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 09:36:18.611   318  1377 V voice   : voice_set_parameters: exit with code(0)
08-30 09:36:18.611   318  1377 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 09:36:18.611   318  1377 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 09:36:18.611   318  1377 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 09:36:18.611   318  1377 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 09:36:18.611   318  1377 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 09:36:18.611   318  1377 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 09:36:18.612  7087  7674 V ToneGenerator: ToneGenerator destructor
08-30 09:36:18.612  7087  7674 V ToneGenerator: stopTone
08-30 09:36:18.612  7087  7674 V ToneGenerator: Delete Track: 0xb4928a80
08-30 09:36:18.612  7087  7087 D A2dpService: Received start request. Starting profile...
08-30 09:36:18.613  7087  7087 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 09:36:18.613  7087  7674 V AudioTrack: ~AudioTrack, releasing session id from 7087 on behalf of 7087
08-30 09:36:18.613   318  1376 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 09:36:18.613   318  1377 V AudioFlinger: releasing 22 from 7087 for 7087
08-30 09:36:18.613   318  1377 V AudioFlinger:  decremented refcount to 0
08-30 09:36:18.613   318  1376 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 09:36:18.613   318  1377 V AudioFl,inger: purging stale effects
08-30 09:36:18.613   318  1252 V AudioPolicyService: AudioCommandThread() waking up
08-30 09:36:18.613   318  1252 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 09:36:18.613   318  1252 V AudioPolicyManager: releaseOutput() 2
08-30 09:36:18.613   318  1252 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 09:36:18.613   318  1376 V AudioFlinger: PlaybackThread::Track destructor
08-30 09:36:18.613   318  1376 V AudioFlinger: removeClient_l() pid 7087, calling pid 318
08-30 09:36:18.614  7087  7087 V Avrcp   : make
08-30 09:36:18.614  7087  7087 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 09:36:18.614  7087  7087 I bluedroid-qcom: get_profile_interface avrcp
08-30 09:36:18.614  7087  7641 V LGMDMManager: Create singleton instance
08-30 09:36:18.615  1027  1567 W Process : Unable to open /proc/7682/status
08-30 09:36:18.619  7087  7641 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 09:36:18.625  7087  7087 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 09:36:18.627  7087  7087 E AudioManager: No RCC entry present to update
08-30 09:36:18.627  7087  7087 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 09:36:18.631  7087  7087 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 09:36:18.632  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 09:36:18.632  7087  7087 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 09:36:18.638  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 09:36:18.690  7663  7663 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 09:36:18.690  7663  7663 W LG Account v2.2: No ProfileInfo entries
08-30 09:36:18.690  7663  7663 I LG Account v2.2: isEnabled: false
08-30 09:36:18.690  7663  7663 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 09:36:18.690  7663  7663 I Feature : [Lifetracker]Country: EU
08-30 09:36:18.691  7663  7663 I Feature : [Lifetracker]Operator: OPEN
08-30 09:36:18.691  7663  7663 I Feature : [Lifetracker]Ranking support: false
08-30 09:36:18.691  7663  7663 I Feature : [Lifetracker]Comfort support: false
08-30 09:36:18.691  7663  7663 I Feature : [Lifetracker]Accessory: true
08-30 09:36:18.691  7663  7663 I Feature : [Lifetracker]Health device: true,
08-30 09:36:18.691  7663  7663 I Feature : [Lifetracker]Extra Pedometer: false
08-30 09:36:18.691  7663  7663 I Feature : [Lifetracker]Blood glucose device: false
08-30 09:36:18.691  7663  7663 I Feature : [Lifetracker]Device Number: 3
,08-30 09:36:18.703  6945  6945 D BluetoothPermissionRequest: onReceive
08-30 09:36:18.706  6945  6945 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 09:36:18.767  1027  1758 V SIM_STK : Menu title from STK is T-Mobile
08-30 09:36:18.767  1027  1758 V SIM_STK : Menu title from STK is T-Mobile
,08-30 09:36:18.840  1027  1044 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 09:36:18.850  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 09:36:18.854  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-30 09:36:18.854  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 09:36:18.855  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 09:36:18.855  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 09:36:18.855  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 09:36:18.855  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 09:36:18.855  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,08-30 09:36:18.855  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 09:36:18.855  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 09:36:18.855  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 09:36:18.856  7087  7087 I BluetoothA2dpServiceJni: classInitNative
08-30 09:36:18.856  7087  7087 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 09:36:18.856  7087  7087 D A2dpStateMachine: make
08-30 09:36:18.859  7087  7087 I bluedroid-qcom: get_profile_interface a2dp
08-30 09:36:18.860  7087  7689 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 09:36:18.864  7087  7087 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 09:36:18.865  7087  7087 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 09:36:18.867  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:18.868  7087  7688 D A2dpStateMachine: Enter Disconnected: -2
08-30 09:36:18.870  7087  7087 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 09:36:18.875  7087  7087 D HidService: Received start request. Starting profile...
08-30 09:36:18.875  7087  7087 I bluedroid-qcom: get_profile_interface hidhost
08-30 09:36:18.875  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:18.877  7087  7087 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 09:36:18.880  7087  7087 D HealthService: Received start request. Starting profile...
08-30 09:36:18.883  7087  7087 I bluedroid-qcom: get_profile_interface health
,08-30 09:36:18.883  7087  7087 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 09:36:18.884  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:18.884  7087  7087 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 09:36:18.886  7087  7087 D PanService: Received start request. Starting profile...
08-30 09:36:18.886  7087  7087 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 09:36:18.886  7087  7087 I bluedroid-qcom: get_profile_interface pan
08-30 09:36:18.895  7087  7087 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 09:36:18.895  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:18.896  7087  7087 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-30 09:36:18.902  7087  7087 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 09:36:18.902  7087  7087 D BtGatt.GattService: Received start request. Starting profile...
08-30 09:36:18.902  7087  7087 D BtGatt.GattService: start()
08-30 09:36:18.902  7087  7087 I bluedroid-qcom: get_profile_interface gatt
08-30 09:36:18.903  7087  7087 D BtGatt.AdvertiseManager: advertise manager created
08-30 09:36:18.916  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
,08-30 09:36:18.921  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:18.922  7087  7087 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 09:36:18.925  7087  7087 V BluetoothMapService: BluetoothMapBinder()
08-30 09:36:18.926  7087  7087 D BluetoothMapService: Received start request. Starting profile...
08-30 09:36:18.926  7087  7087 D BluetoothMapService: start()
08-30 09:36:18.936  7087  7087 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-30 09:36:18.936  7087  7087 D BluetoothMapEmailAppObserver: createReceiver()
08-30 09:36:18.940  7087  7087 D BluetoothMapEmailAppObserver: initObservers()
08-30 09:36:18.940  7087  7087 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 09:36:18.958  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
,08-30 09:36:18.959  7087  7087 D HeadsetStateMachine: Proxy object connected
08-30 09:36:18.960  7087  7087 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 09:36:18.960  7087  7087 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 09:36:18.965  7087  7087 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 09:36:18.965  7087  7674 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 09:36:18.966  7087  7674 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 09:36:18.966  7087  7674 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 09:36:18.970  7087  7087 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 09:36:18.975  7087  7087 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 09:36:18.978  7087  7087 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 09:36:18.981  7087  7087 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 09:36:18.982  7087  7087 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 09:36:18.985  7087  7087 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-30 09:36:18.985  7087  7087 V BluetoothMapService: Handler(): got msg=1
08-30 09:36:18.987  7087  7641 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 09:36:18.987  7087  7641 I bluedroid-qcom: enable
08-30 09:36:18.987  7087  7699 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 09:36:18.987  7087  7699 I bt-btu  : btu_task pending for preload complete event
08-30 09:36:18.987  7087  7641 I bt_hci_bdroid: init
08-30 09:36:18.989  7087  7641 I bt_vendor: bt-vendor : init
08-30 09:36:18.989  7087  7641 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 09:36:18.989  7087  7641 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 09:36:18.989  7087  7641 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 09:36:18.989  7087  7641 D bt_userial_mct: userial_init
08-30 09:36:18.990  7087  7641 D bt_hci_bdroid: set_power 1
08-30 09:36:18.990  7087  7641 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 09:36:18.990  7087  7641 I bt_vendor: Starting hciattach daemon
08-30 09:36:18.990  7087  7641 I bt_vendor: try to set true
08-30 09:36:18.985  7702  7702 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:18.995  7087  7087 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:18.985  7702  7702 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:18.998  7087  7087 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 09:36:18.999  7087  7087 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-30 09:36:18.999  7087  7087 V BluetoothSapReceiver: SapReceiver onReceive 
,08-30 09:36:18.999  7087  7087 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:18.999  7087  7087 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 09:36:19.016  7703  7703 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 09:36:19.043  1027  1043 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7706 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 09:36:19.090  7726  7726 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 09:36:19.101  7727  7727 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 09:36:19.105  7706  7706 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 09:36:19.122  7729  7729 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 09:36:19.131  1027  1968 I ActivityManager: Killing 6726:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 09:36:19.133  7730  7730 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-30 09:36:19.145  7731  7731 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 09:36:19.151  7010  7010 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 09:36:19.151  7010  7010 W System.err: android.os.DeadObjectException
08-30 09:36:19.151  7010  7010 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 09:36:19.151  7010  7010 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 09:36:19.151  7010  7010 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 09:36:19.152  7010  7010 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 09:36:19.152  7010  7010 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 09:36:19.152  7010  7010 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 09:36:19.152  7010  7010 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 09:36:19.152  7010  7010 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 09:36:19.152  7010  7010 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 09:36:19.152  7010  7010 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 09:36:19.152  7010  7010 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:36:19.152  7010  7010 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 09:36:19.152  7010  7010 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 09:36:19.152  7010  7010 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 09:36:19.152  7010  7010 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 09:36:19.152  7010  7010 W System.err: android.os.DeadObjectException
08-30 09:36:19.153  7010  7010 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 09:36:19.153  7010  7010 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 09:36:19.153  7010  7010 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 09:36:19.154  7010  7010 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 09:36:19.154  7010  7010 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 09:36:19.154  7010  7010 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 09:36:19.154  7010  7010 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 09:36:19.154  7010  7010 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 09:36:19.154  7010  7010 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 09:36:19.154  7010  7010 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 09:36:19.154  7010  7010 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:36:19.154  7010  7010 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 09:36:19.154  7010  7010 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 09:36:19.154  7010  7010 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 09:36:19.154  7010  7010 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 09:36:19.155  7010  7010 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 09:36:19.162  7732  7732 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 09:36:19.189  7734  7734 I libmdmdetect: ESOC framework not supported
08-30 09:36:19.190  7734  7734 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 09:36:19.198  7734  7734 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 09:36:19.198  7734  7734 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 09:36:19.199  7734  7734 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 09:36:19.199  7734  7734 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 09:36:19.199  7734  7734 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 09:36:19.199  7734  7734 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 09:36:19.199  7734  7734 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 09:36:19.238  7734  7735 E QC-QMI  : qmi_client [7734] 14: failed to locate client data
,08-30 09:36:19.239   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 09:36:19.240   467   467 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-30 09:36:19.251  1027  2096 W libprocessgroup: failed to open /acct/uid_1000/pid_6726/cgroup.procs: No such file or directory
08-30 09:36:19.251  1027  2096 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 09:36:19.262  7010  7010 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 09:36:19.263  7010  7010 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-30 09:36:19.271  7736  7736 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 09:36:19.283  7737  7737 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 09:36:19.318  1027  1567 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7739 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 09:36:19.320  7010  7010 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 09:36:19.341  7087  7641 I bt_vendor: bluetooth satus is on
,08-30 09:36:19.342  7087  7641 D bt_hci_bdroid: preload
08-30 09:36:19.342  7087  7701 D bt_userial_mct: userial_open(port:0)
08-30 09:36:19.342  7087  7701 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 09:36:19.345  7087  7701 I bt_vendor: Done intiailizing UART
08-30 09:36:19.346  7087  7701 I bt_vendor: Done intiailizing UART
08-30 09:36:19.346  7087  7701 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 09:36:19.346  7087  7701 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 09:36:19.346  7087  7699 I bt-btu  : btu_task received preload complete event
08-30 09:36:19.346  7087  7756 D bt_userial_mct: Entering userial_read_thread()
08-30 09:36:19.347  7087  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 09:36:19.347  7087  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 09:36:19.349  7087  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 09:36:19.352  7087  7699 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 09:36:19.400  7739  7739 D UEI.SmartControl: Quickset Services start...
,08-30 09:36:19.402  7739  7739 I UEI.SmartControl: Manufacture = LGE
08-30 09:36:19.402  7739  7739 D UEI.SmartControl: Id = LGNevo
08-30 09:36:19.403  7739  7739 D UEI.SmartControl: File observer start...
08-30 09:36:19.404  7739  7739 E UEI.SmartControl: IR Port is disabled: false
08-30 09:36:19.404  7739  7739 D UEI.SmartControl: Starting file observer...
08-30 09:36:19.404  7739  7739 D UEI.SmartControl: Extracting JNI libs...
08-30 09:36:19.405  7739  7739 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 09:36:19.410  7087  7699 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 09:36:19.410  7087  7699 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0183061 
08-30 09:36:19.410  7087  7699 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0183061 
08-30 09:36:19.436  7087  7645 E bt-btif : Calling BTA_HhEnable
08-30 09:36:19.436  7087  7645 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 09:36:19.436  7087  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-30 09:36:19.436  7087  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-30 09:36:19.436  7087  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-30 09:36:19.436  7087  7645 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 09:36:19.436  7087  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-30 09:36:19.436  7087  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 09:36:19.438  7087  7645 D BluetoothAdapterProperties: Name is: G3
08-30 09:36:19.439  7087  7645 D BluetoothAdapterProperties: Scan Mode:20
08-30 09:36:19.439  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 09:36:19.439  7087  7645 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 09:36:19.439  7087  7645 D bt_hci_bdroid: postload
08-30 09:36:19.439  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 09:36:19.440  7087  7645 D bte_conf: Device ID record 1 : primary
08-30 09:36:19.440  7087  7645 D bte_conf:   vendorId            = 00c4
08-30 09:36:19.440  7087  7645 D bte_conf:   vendorIdSource      = 0001
08-30 09:36:19.440  7087  7645 D bte_conf:   product             = 13a1
08-30 09:36:19.440  7087  7645 D bte_conf:   version             = 1000
08-30 09:36:19.440  7087  7645 D bte_conf:   clientExecutableURL = 
08-30 09:36:19.440  7087  7645 D bte_conf:   serviceDescription  = 
08-30 09:36:19.440  7087  7645 D bte_conf:   documentationURL    = 
08-30 09:36:19.440  7087  7645 D bte_conf: bte_load_did_conf no section named DID2.
08-30 09:36:19.441  7087  7701 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 09:36:19.443  7087  7699 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 09:36:19.443  7087  7645 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 09:36:19.445  7087  7701 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 09:36:19.445  7087  7641 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 09:36:19.445  7087  7641 D BluetoothAdapterProperties: ScanMode =  20
08-30 09:36:19.446  7087  7641 D BluetoothAdapterProperties: State =  11
08-30 09:36:19.446  7087  7641 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 09:36:19.446  7087  7641 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 09:36:19.447  7087  7641 D BluetoothAdapterProperties: Setting state to 12
08-30 09:36:19.447  7087  7641 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 09:36:19.447  7087  7645 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 09:36:19.448  1027  1089 D BluetoothManagerService: Message: 60
08-30 09:36:19.448  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 09:36:19.448  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 09:36:19.449  7087  7701 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 09:36:19.445  7759  7759 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:19.451  7087  7701 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 09:36:19.445  7759  7759 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:19.452  7087  7641 I BluetoothAdapterState: Entering On State
,08-30 09:36:19.461  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:19.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:19.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:19.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:19.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:19.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:19.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:19.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:19.463  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:19.464  7087  7756 E bt_mct  : hci lib postload completed
08-30 09:36:19.465  7087  7645 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 09:36:19.466  7087  7645 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 09:36:19.467  6945  7080 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 09:36:19.468  7087  7641 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 09:36:19.468  7087  7641 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 09:36:19.468  7087  7641 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 09:36:19.470  7087  7641 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-30 09:36:19.472  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:19.472  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:19.472  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:19.472  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:19.472  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:19.472  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:19.472  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:19.472  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:19.473  6945  6962 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 09:36:19.474  7087  7699 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 09:36:19.475  7087  7699 W bt-smp  : Plain text(LSB ~ MSB) = 34 13 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 09:36:19.475  7087  7699 W bt-smp  : Encrypted text(LSB ~ MSB) = f2 c3 a0 85 71 34 88 02 e3 13 0e b9 63 64 f5 43 
,08-30 09:36:19.475  7087  7699 W bt-btm  : Stopping oneshot timer
08-30 09:36:19.476  6945  6945 D BluetoothInputDevice: Proxy object connected
08-30 09:36:19.476  6945  6945 D HidProfile: Bluetooth service connected
08-30 09:36:19.478  1871  3507 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:36:19.479  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:19.484  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:19.484  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:19.484  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:19.484  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:19.484  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:19.484  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:19.484  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:19.484  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:36:19.488  1871  1871 D BluetoothHeadset: Proxy object connected
08-30 09:36:19.489  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:36:19.489  1027  1027 D BluetoothHeadset: Proxy object connected
08-30 09:36:19.490  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:19.491  1871  3508 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:36:19.493  1871  1871 D BluetoothHeadset: Proxy object connected
08-30 09:36:19.493  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 09:36:19.494  6945  6961 D BluetoothMap: onBluetoothStateChange: up=true
08-30 09:36:19.495  1027  1027 D BluetoothA2dp: Proxy object connected
08-30 09:36:19.500  6945  6945 D BluetoothMap: Proxy object connected
08-30 09:36:19.500  1871  1887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:36:19.500  6945  6945 D MapProfile: Bluetooth service connected
08-30 09:36:19.500  6945  6945 D BluetoothMap: getConnectedDevices()
,08-30 09:36:19.503  7087  7641 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 09:36:19.504  7087  7699 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 09:36:19.504  7087  7699 W bt-smp  : Plain text(LSB ~ MSB) = b9 51 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 09:36:19.504  7087  7699 W bt-smp  : Encrypted text(LSB ~ MSB) = a4 5d e9 7f ab 46 60 54 3f 0c f3 0e c2 1f bd 8e 
08-30 09:36:19.504  7087  7699 W bt-btm  : Stopping oneshot timer
08-30 09:36:19.506  1871  1871 D BluetoothHeadset: Proxy object connected
08-30 09:36:19.507  6945  6962 D BluetoothPan: onBluetoothStateChange on: true
08-30 09:36:19.507  6945  6962 D BluetoothPan: onBluetoothStateChange call bindService
08-30 09:36:19.512  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-30 09:36:19.514  1027  1089 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 09:36:19.514  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 09:36:19.518  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:19.518  1958  2175 D LGBluetoothAPIService: Message: 1
08-30 09:36:19.518  1958  2175 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 09:36:19.519  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 09:36:19.524  7087  7761 V BluetoothMapService: getConnectedDevices()
,08-30 09:36:19.525  6817  6817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 09:36:19.527  1027  1089 D BluetoothManagerService: Message: 40
08-30 09:36:19.527  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 09:36:19.528  7765  7765 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 09:36:19.528  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:19.529  1958  2175 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 09:36:19.530  7087  7699 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-30 09:36:19.530  7087  7699 W bt-smp  : Plain text(LSB ~ MSB) = be ff 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 09:36:19.530  7087  7699 W bt-smp  : Encrypted text(LSB ~ MSB) = f8 7d 9a fd 01 f2 aa 11 f2 28 3f 56 72 7e aa 3f 
08-30 09:36:19.530  7087  7699 W bt-btm  : Stopping oneshot timer
08-30 09:36:19.532  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:19.533  7087  7087 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:19.533  7087  7087 D BluetoothMapService: STATE_ON
08-30 09:36:19.534  6945  6945 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 09:36:19.534  6945  6945 D PanProfile: Bluetooth service connected
08-30 09:36:19.535  7087  7087 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 09:36:19.537  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:19.537  7087  7087 D LGBluetoothAPIServer: [BTUI] onBind()
,08-30 09:36:19.539  1958  1958 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 09:36:19.539  1958  2175 D LGBluetoothAPIService: Message: 100
08-30 09:36:19.539  1958  2175 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 09:36:19.543  7087  7699 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 09:36:19.543  7087  7699 W bt-smp  : Plain text(LSB ~ MSB) = 83 06 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 09:36:19.543  7087  7699 W bt-smp  : Encrypted text(LSB ~ MSB) = f0 20 be 52 a1 f3 8c 94 64 5b e2 39 8c 1a a2 93 
08-30 09:36:19.543  7087  7699 W bt-btm  : Stopping oneshot timer
08-30 09:36:19.544  6945  6945 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 09:36:19.547  1027  1089 D BluetoothManagerService: Message: 30
08-30 09:36:19.550  6945  6945 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 09:36:19.552  7087  7699 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 09:36:19.552  7087  7699 W bt-smp  : Plain text(LSB ~ MSB) = bb 42 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 09:36:19.552  7087  7699 W bt-smp  : Encrypted text(LSB ~ MSB) = 02 6b a2 68 12 b0 f6 b8 c5 39 d2 99 ec c7 a9 74 
08-30 09:36:19.553  7087  7699 W bt-btm  : Stopping oneshot timer
08-30 09:36:19.554  1027  1089 D BluetoothManagerService: Message: 30
08-30 09:36:19.556  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:19.556  7087  7087 V BluetoothPbapService: Pbap Service onCreate
08-30 09:36:19.556  7087  7087 V BluetoothPbapService: Starting PBAP service
08-30 09:36:19.557  7087  7087 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 09:36:19.558  7087  7087 V BluetoothPbapService: Pbap Service onBind
,08-30 09:36:19.561  7087  7087 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 09:36:19.561  7087  7087 V BluetoothPbapService: state: 12
08-30 09:36:19.561  7087  7087 V BluetoothMapService: Handler(): got msg=1
08-30 09:36:19.562  7087  7087 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 09:36:19.563  7087  7087 V BluetoothPbapService: Handler(): got msg=1
08-30 09:36:19.563  7087  7087 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 09:36:19.564  7087  7772 D BluetoothMapMasInstance: MAS initSocket()
08-30 09:36:19.564  7087  7772 D BluetoothMapMasInstance:   masId = 00
08-30 09:36:19.564  7087  7772 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 09:36:19.564  7087  7772 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 09:36:19.564  7087  7772 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 09:36:19.565  7087  7773 V BluetoothPbapService: Pbap Service initSocket
08-30 09:36:19.568  1027  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:19.569  1027  2063 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:19.570  7087  7773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 09:36:19.571  7087  7772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 09:36:19.572  7087  7773 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 09:36:19.572  7087  7772 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
08-30 09:36:19.572  7087  7772 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 09:36:19.572  7087  7773 V BluetoothPbapService: Succeed to create listening socket 
08-30 09:36:19.572  7087  7772 D BluetoothMapMasInstance: Accepting socket connection...
08-30 09:36:19.572  7087  7773 V BluetoothPbapService: Accepting socket connection...
08-30 09:36:19.573  7087  7645 D BluetoothAdapterProperties: Scan Mode:21
08-30 09:36:19.573  7087  7645 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 09:36:19.575  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:19.576  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:19.578  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:19.581  6945  6945 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 09:36:19.582  6945  6945 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 09:36:19.588  7739  7739 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-30 09:36:19.588  7739  7739 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-30 09:36:19.588  7739  7739 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-30 09:36:19.589  6945  6945 D BluetoothA2dp: Proxy object connected
08-30 09:36:19.589  7087  7087 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 09:36:19.589  7087  7087 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:19.589  7087  7087 V BluetoothPbapReceiver: ***********state = 12
08-30 09:36:19.589  6945  6945 D A2dpProfile: Bluetooth service connected
08-30 09:36:19.591  6945  6945 D BluetoothPbap: Proxy object connected
08-30 09:36:19.591  6945  6945 D PbapServerProfile: Bluetooth service connected
08-30 09:36:19.591  6945  6945 D BluetoothHeadset: Proxy object connected
08-30 09:36:19.592  6945  6945 D HeadsetProfile: Bluetooth service connected
08-30 09:36:19.592  2251  2251 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 09:36:19.593  2251  2251 D c       : Getting all permits...
08-30 09:36:19.594  2251  2251 D a       : Opening database...
08-30 09:36:19.597  2251  2251 D a       : Opening database auth.proximity.permit_store...
08-30 09:36:19.598  2251  2251 D a       : Closing database...
08-30 09:36:19.605  6945  6945 D DockEventReceiver: finishStartingService: stopping service
08-30 09:36:19.610  6945  6945 D BluetoothPermissionRequest: onReceive
,08-30 09:36:19.612  6945  6945 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 09:36:19.614  6945  6945 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 09:36:19.617  7087  7087 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 09:36:19.619  7087  7087 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 09:36:19.623  7739  7739 I UEI.SmartControl: --- Selecting new region: 6
,08-30 09:36:19.625  7739  7739 I UEI.SmartControl: Model = LG-D855
08-30 09:36:19.626  7087  7087 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 09:36:19.627  7739  7739 D UEI.SmartControl: QS Service created
08-30 09:36:19.641  7739  7739 I UEI.SmartControl: Service initServices...
,08-30 09:36:19.645  7739  7739 D UEI.SmartControl: QS start get config
08-30 09:36:19.647  7087  7087 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 09:36:19.648  7087  7087 V BtOppService: onCreate
08-30 09:36:19.652  7087  7087 V BluetoothOppNotification: send message
08-30 09:36:19.656  7087  7087 V BtOppService: Starting RfcommListener
,08-30 09:36:19.668  7087  7087 D BluetoothOppPreference: Dumping Names:  
08-30 09:36:19.668  7087  7087 D BluetoothOppPreference: {}
,08-30 09:36:19.668  7087  7087 D BluetoothOppPreference: Dumping Channels:  
08-30 09:36:19.668  7087  7087 D BluetoothOppPreference: {}
08-30 09:36:19.671  7087  7087 V BtOppService: onStartCommand
08-30 09:36:19.671  7087  7780 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 09:36:19.674  7087  7777 V BtOppService: Deleted complete outbound shares, number =  0
08-30 09:36:19.675  7087  7777 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 09:36:19.675  7087  7777 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 09:36:19.678  7087  7087 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:19.679  7087  7087 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 09:36:19.679  7087  7777 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a34237c on behalf of 
08-30 09:36:19.681  7087  7780 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-30 09:36:19.688  7087  7087 V BluetoothOppNotification: new notify threadi!
08-30 09:36:19.690  7087  7087 V BluetoothOppNotification: send delay message
08-30 09:36:19.690  7087  7087 V BtOppService: start RfcommListener
08-30 09:36:19.691  7087  7780 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28eb1405 on behalf of 
08-30 09:36:19.691  7087  7780 V BluetoothOppNotification: update too frequent, put in queue
08-30 09:36:19.693  7087  7780 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 09:36:19.693  7087  7780 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 09:36:19.695  7087  7087 V BtOppService: RfcommListener started
08-30 09:36:19.696  7087  7087 V BtOppService: ContentObserver received notification
08-30 09:36:19.696  7087  7087 V BtOppService: ContentObserver received notification
08-30 09:36:19.696  7087  7781 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 09:36:19.698  7087  7782 V BtOppRfcommListener: Starting RFCOMM listener....
,08-30 09:36:19.699  1027  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:19.701  7087  7782 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:36:19.703  7087  7782 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-30 09:36:19.704  7087  7782 V BtOppRfcommListener: Started RFCOMM listener....
08-30 09:36:19.704  7087  7782 I BtOppRfcommListener: Accept thread started.
08-30 09:36:19.704  7087  7782 V BtOppRfcommListener: Accepting connection...
08-30 09:36:19.710  7739  7739 D UEI.SmartControl: Loading JNI Libs...
,08-30 09:36:19.712  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:19.712  7087  7087 V BluetoothFtpService: Ftp Service onCreate
08-30 09:36:19.712  7087  7087 I BluetoothFtpService: Ftp Service onCreate
08-30 09:36:19.712  7087  7087 V BluetoothFtpService: Ftp Service onStartCommand
08-30 09:36:19.713  7087  7087 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:19.713  7087  7087 V BluetoothFtpService: Starting Listening on sockets
08-30 09:36:19.713  7087  7087 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 09:36:19.713  7087  7087 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 09:36:19.713  7087  7087 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 09:36:19.713  7087  7087 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:19.713  7087  7087 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 09:36:19.713  7087  7087 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 09:36:19.715  7087  7087 V BluetoothFtpService: Handler(): got msg=1
08-30 09:36:19.717  7087  7087 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 09:36:19.717  7087  7087 V BluetoothFtpService: Ftp Service initSocket
08-30 09:36:19.720  1027  2096 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 09:36:19.721  7087  7087 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:36:19.722  7087  7087 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
,08-30 09:36:19.723  7087  7087 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 09:36:19.724  7087  7783 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 09:36:19.737  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
,08-30 09:36:19.737  7087  7087 V BluetoothSapService: Sap Service onCreate
,08-30 09:36:19.739  7087  7087 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:19.739  7087  7087 V BluetoothSapService: state: 12
08-30 09:36:19.739  7087  7087 V BluetoothSapService: Starting SAP server process
08-30 09:36:19.735  7784  7784 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:19.735  7784  7784 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:19.743  7087  7087 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 09:36:19.745  7087  7785 V BluetoothSapService: Sap Service initRfcommSocket
08-30 09:36:19.745  1027  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:19.746  7087  7785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:36:19.747  7087  7785 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 09:36:19.747  7087  7785 V BluetoothSapService: Succeed to create listening socket 
08-30 09:36:19.747  7784  7784 V BT_SAP  : Event pipe created
08-30 09:36:19.747  7784  7784 V BT_SAP  : create_server_socket qcom.sap.server
08-30 09:36:19.747  7784  7784 V BT_SAP  : created socket fd 6
08-30 09:36:19.747  7087  7785 V BluetoothSapService: Accepting socket connection...
08-30 09:36:19.777  1027  1567 I art     : Explicit concurrent mark sweep GC freed 128012(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.400ms total 82.550ms
08-30 09:36:19.777  7087  7780 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1974c426 on behalf of 
08-30 09:36:19.777  7087  7781 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5df4867 on behalf of 
,08-30 09:36:19.778  7087  7780 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-30 09:36:19.779  7087  7780 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 09:36:19.779  7087  7781 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 09:36:19.779  7087  7781 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 09:36:19.780  7087  7780 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ecb6614 on behalf of 
08-30 09:36:19.780  7087  7780 V BluetoothOppNotification: update too frequent, put in queue
08-30 09:36:19.781  7087  7781 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d2cbebd on behalf of 
08-30 09:36:19.781  7087  7781 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 09:36:19.782  7087  7780 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 09:36:19.782  7087  7781 V BluetoothOppNotification: outbound notification was removed.
,08-30 09:36:19.782  7087  7781 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 09:36:19.783  7087  7781 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2158fcb2 on behalf of 
08-30 09:36:19.783  7087  7781 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 09:36:19.784  7087  7781 V BluetoothOppNotification: inbound notification was removed.
,08-30 09:36:19.784  7087  7781 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 09:36:19.785  7087  7781 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@338e0403 on behalf of 
08-30 09:36:19.981  7739  7739 I UEI.SmartControl: Supports setup maps: true
08-30 09:36:19.985  7739  7739 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 09:36:19.985  7739  7739 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 09:36:19.985  7739  7739 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 09:36:19.985  7739  7739 I UEI.SmartControl: ### init IR Blaster...
,08-30 09:36:19.990  7739  7739 D serial_port: Configuring serial port
08-30 09:36:19.994  7739  7739 E UEI.SmartControl: UEIBLaster setting for 616
08-30 09:36:19.994  7739  7739 I UEI.SmartControl: Setting serial record hearder size = 2
,08-30 09:36:19.995  7739  7739 I UEI.SmartControl: configuring settings for MAXQ616
08-30 09:36:19.995  7739  7739 I UEI.SmartControl: Get version...
08-30 09:36:20.012  7739  7786 D UEI.SmartControl: serial port data available: 21
,08-30 09:36:20.041  7739  7739 D UEI.SmartControl: MAXQ616 A2-X4 software.,
08-30 09:36:20.041  7739  7739 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 09:36:20.042  7739  7739 I UEI.SmartControl: QS saving settings...
,08-30 09:36:20.044  7739  7739 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 09:36:20.064  7739  7786 D UEI.SmartControl: serial port data available: 4
,08-30 09:36:20.103  7739  7792 I UEI.SmartControl: Device manager: loading config....
08-30 09:36:20.104  7739  7792 D UEI.SmartControl: ----------- loading internal config...
,08-30 09:36:20.109  7739  7739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 09:36:20.122  7739  7739 E UEI.SmartControl: Services init done
08-30 09:36:20.122  7739  7739 D UEI.SmartControl: QS Service init finished
08-30 09:36:20.123  7739  7739 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 09:36:20.124  7739  7739 D UEI.SmartControl: QS Service version code: 201091
,08-30 09:36:20.125  7739  7739 D UEI.SmartControl: Service requested: Control
08-30 09:36:20.128  7739  7792 E UEI.SmartControl: Loading SETTINGS...
08-30 09:36:20.130  7739  7739 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 09:36:20.133  7010  7010 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 09:36:20.134  7739  7754 I UEI.SmartControl: ------ IControl API: 11
08-30 09:36:20.134  1027  1043 I ActivityManager: Killing 7010:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 09:36:20.135  7739  7754 I UEI.SmartControl: Registering callback...
08-30 09:36:20.141  7739  7792 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 09:36:20.164  7739  7791 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 09:36:20.164  7739  7791 D UEI.SmartControl: -----service ready thread exits
,08-30 09:36:20.179  1027  1757 W libprocessgroup: failed to open /acct/uid_10112/pid_7010/cgroup.procs: No such file or directory
08-30 09:36:20.180  7739  7739 D UEI.SmartControl: Internal service binding...
,08-30 09:36:20.414  1596  1596 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 09:36:20.488  1027  1471 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 09:36:20.517  1027  1085 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7800 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 09:36:20.523  1596  1596 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 09:36:20.524  1596  1596 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 09:36:20.556  1027  1027 D administrator: Handling package changes for user 0
,08-30 09:36:20.590  2085  2085 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 09:36:20.615  2085  2085 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 09:36:20.629  7800  7800 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 09:36:20.691  7087  7087 V BluetoothOppNotification: new notify threadi!
08-30 09:36:20.691  7087  7087 V BluetoothOppNotification: send delay message
,08-30 09:36:20.692  7087  7834 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 09:36:20.694  7087  7834 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1602cf80 on behalf of 
08-30 09:36:20.694  7087  7834 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 09:36:20.695  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 09:36:20.695  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 09:36:20.696  7087  7834 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 09:36:20.698  7087  7834 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@376b89b9 on behalf of 
08-30 09:36:20.698  7087  7834 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 09:36:20.708  7087  7834 V BluetoothOppNotification: outbound notification was removed.
08-30 09:36:20.708  7087  7834 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-30 09:36:20.709  7087  7834 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ad631fe on behalf of 
08-30 09:36:20.709  7087  7834 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 09:36:20.710  7800  7800 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:20.710  7800  7800 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 09:36:20.711  7087  7834 V BluetoothOppNotification: inbound notification was removed.
08-30 09:36:20.711  7087  7834 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 09:36:20.712  7087  7834 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18e2dd5f on behalf of 
08-30 09:36:20.749  1027  1084 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 09:36:20.755  1027  1084 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 09:36:20.772  2085  2085 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 09:36:20.776  2478  2478 V GmsNetworkLocationProvi: DISABLE
08-30 09:36:20.806  1027  1084 D LocationProviderProxy: applying state to connected service
,08-30 09:36:20.809  2478  2478 E GCoreFlp: Bound FusedProviderService with LocationManager
08-30 09:36:20.819  7800  7847 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 09:36:20.819  7800  7847 I Babel   : MmsConfig.loadMmsSettings
,08-30 09:36:20.822  7800  7847 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 09:36:20.822  7800  7847 I Babel   : MmsConfig.loadFromDatabase
,08-30 09:36:20.836  7800  7847 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 09:36:20.836  7800  7847 I Babel   : MmsConfig.loadFromResources
08-30 09:36:20.837  7800  7847 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 09:36:20.837  7800  7845 W AudioCapabilities: Unsupported mime audio/evrc
08-30 09:36:20.838  7800  7847 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 09:36:20.839  7800  7845 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 09:36:20.840  7800  7800 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:20.840  7800  7845 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 09:36:20.848  7800  7845 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-30 09:36:20.849  7800  7845 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 09:36:20.851  7800  7845 W AudioCapabilities: Unsupported mime audio/evrc
08-30 09:36:20.859  7800  7845 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 09:36:20.861  7800  7845 W VideoCapabilities: Unsupported mime video/divx
,08-30 09:36:20.864  7800  7845 W VideoCapabilities: Unsupported mime video/divx311
08-30 09:36:20.865  7800  7845 W VideoCapabilities: Unsupported mime video/divx4
08-30 09:36:20.865  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
08-30 09:36:20.866  1835  7848 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 09:36:20.866  1835  7848 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-30 09:36:20.868  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3b634cfd
08-30 09:36:20.868  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 09:36:20.868  7128  7128 D AppUp4:CustFacade: isPhone : true
08-30 09:36:20.869  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
08-30 09:36:20.869  7128  7128 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 09:36:20.872  7800  7845 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-30 09:36:20.884  7800  7845 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 09:36:20.887  7800  7845 W AudioCapabilities: Unsupported mime audio/eac3
08-30 09:36:20.888  7800  7845 W AudioCapabilities: Unsupported mime audio/ac3
08-30 09:36:20.889  7800  7845 W AudioCapabilities: Unsupported mime audio/g726
08-30 09:36:20.889  7800  7845 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 09:36:20.890  7800  7845 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 09:36:20.891  7800  7845 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 09:36:20.892  7800  7845 W VideoCapabilities: Unsupported mime video/theora
08-30 09:36:20.893  7800  7845 W VideoCapabilities: Unsupported mime video/mjpg
08-30 09:36:20.905  1027  2009 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7852 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-30 09:36:20.914  1835  4744 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-30 09:36:20.941  1027  1727 I ActivityManager: Killing 6963:com.lge.sync/1000 (adj 15): empty #17
08-30 09:36:20.951  7852  7852 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 09:36:20.951  7852  7852 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 09:36:20.952  7852  7852 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 09:36:20.953  7852  7852 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 09:36:20.953  7852  7852 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 09:36:21.012  1027  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_6963/cgroup.procs: No such file or directory
,08-30 09:36:21.047  7852  7852 I SystemConfig: BUILD Country: EU
08-30 09:36:21.047  7852  7852 I SystemConfig: BUILD Operator: OPEN
,08-30 09:36:21.091  1027  1968 I ActivityManager: Killing 7477:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-30 09:36:21.195  1027  1943 W libprocessgroup: failed to open /acct/uid_10005/pid_7477/cgroup.procs: No such file or directory
,08-30 09:36:21.246  1027  1968 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7876 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 09:36:21.252  7852  7870 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 09:36:21.252  7852  7870 I SystemConfig: existFile = false
08-30 09:36:21.252  7852  7870 I SystemConfig: canReadFile = false
08-30 09:36:21.252  7852  7870 I SystemConfig: systemFeature RCS result false
08-30 09:36:21.254  7852  7870 D SystemConfig: refreshRcsSupport() :false
,08-30 09:36:21.301  7876  7876 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 09:36:21.301  7876  7876 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 09:36:21.301  7876  7876 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 09:36:21.302  7876  7876 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 09:36:21.420  7876  7876 I AppConfig: Total System Memory = 2995761152
,08-30 09:36:21.431  7876  7876 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 09:36:21.548  1027  1991 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7898 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 09:36:21.552  1027  1991 I ActivityManager: Killing 7170:com.lge.email/u0a23 (adj 15): empty #17
08-30 09:36:21.619  1027  1758 W libprocessgroup: failed to open /acct/uid_10023/pid_7170/cgroup.procs: No such file or directory
,08-30 09:36:21.821  7898  7898 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 09:36:21.930  7898  7898 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:21.930  7898  7898 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:36:21.995  7898  7898 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 09:36:22.015  7898  7898 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 09:36:22.017  7898  7898 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 09:36:22.033  7898  7898 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 09:36:22.034  7898  7898 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 09:36:22.054  1027  1593 I ActivityManager: Killing 7050:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 09:36:22.089  1027  1968 W libprocessgroup: failed to open /acct/uid_10026/pid_7050/cgroup.procs: No such file or directory
,08-30 09:36:22.096  3485  3500 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 09:36:22.098  4571  7935 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-30 09:36:22.105  3485  3500 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1fcedc11 on behalf of 7898
,08-30 09:36:22.162  1027  1943 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7936 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 09:36:22.187   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 470us total 27.636ms
,08-30 09:36:22.210   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 21.702ms
,08-30 09:36:22.234   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 879us total 22.281ms
,08-30 09:36:22.255  7898  7898 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 09:36:22.274  7936  7936 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 09:36:22.275  7898  7898 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-30 09:36:22.289  7936  7936 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-30 09:36:22.289  7936  7936 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 09:36:22.289  7936  7936 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 09:36:22.289  7936  7936 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 09:36:22.289  7936  7936 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 09:36:22.289  7936  7936 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 09:36:22.306  1027  2005 I ActivityManager: Killing 6477:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 09:36:22.335  1027  1593 W libprocessgroup: failed to open /acct/uid_1000/pid_6477/cgroup.procs: No such file or directory
,08-30 09:36:22.565  1027  2005 V SIM_STK : Menu title from STK is T-Mobile
,08-30 09:36:22.595  4571  7935 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 497 ms] updated apps [took 497 ms] 
,08-30 09:36:23.372  1027  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 09:36:23.373  1027  2009 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1328da6c mBinding = false
,08-30 09:36:23.401  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 09:36:23.402  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 09:36:23.402  1027  1027 D Ulp_jni : JNI:system_update. Event-4
,08-30 09:36:23.405  1027  1089 D BluetoothManagerService: Message: 2
08-30 09:36:23.406  1027  1089 D BluetoothManagerService: Sending off request.
08-30 09:36:23.406  7087  7103 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 09:36:23.407  7087  7641 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 09:36:23.407  7087  7641 D BluetoothAdapterProperties: Setting state to 13
08-30 09:36:23.407  7087  7641 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 09:36:23.408  7087  7641 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 09:36:23.408  7087  7641 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 09:36:23.410  7087  7645 D BluetoothAdapterProperties: Scan Mode:20
08-30 09:36:23.412  7087  7641 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 09:36:23.413  7087  7773 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 09:36:23.414  7087  7772 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 09:36:23.414  7087  7772 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 09:36:23.414  7087  7772 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 09:36:23.414  7087  7772 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 09:36:23.414  7087  7772 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 09:36:23.414  7087  7772 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 09:36:23.414  7087  7772 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 09:36:23.414  7087  7772 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-30 09:36:23.418  7087  7782 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 09:36:23.419  7087  7783 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 09:36:23.419  7087  7785 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 09:36:23.420  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 09:36:23.420  7087  7699 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 09:36:23.421  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 09:36:23.421  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 09:36:23.421  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 09:36:23.421  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 09:36:23.421  7087  7699 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 09:36:23.421  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 09:36:23.422  7087  7699 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 09:36:23.422  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 09:36:23.422  7087  7699 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 09:36:23.422  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 09:36:23.422  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 09:36:23.422  7087  7699 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 09:36:23.423  7087  7641 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 09:36:23.430  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 09:36:23.440  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:23.440  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:23.440  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:23.440  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:23.440  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:23.440  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:23.440  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:23.440  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:23.443  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:23.444  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:36:23.449  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:23.449  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:23.449  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:23.449  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:23.449  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:23.449  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:23.449  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:23.449  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:23.449  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:23.449  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:23.449  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:23.452  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:23.452  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:23.452  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:23.452  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:23.452  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:23.452  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:36:23.452  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:23.452  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:23.452  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:23.455  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:36:23.455  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:23.456  1027  1089 D BluetoothManagerService: Message: 60
08-30 09:36:23.457  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 09:36:23.457  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-30 09:36:23.461  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 09:36:23.466  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:23.473  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:36:23.476  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:23.477  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:23.478  7087  7087 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:23.479  7087  7087 D BluetoothMapService: STATE_TURNING_OFF
08-30 09:36:23.480  7087  7087 V BluetoothMapService: Handler(): got msg=4
08-30 09:36:23.480  7087  7087 D BluetoothMapService: MAP Service closeService in
08-30 09:36:23.480  7087  7087 D BluetoothMapMasInstance: MAP Service shutdown
08-30 09:36:23.480  7087  7087 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 09:36:23.480  7087  7087 V BluetoothMapService: MAP Service closeService out
08-30 09:36:23.486  7087  7087 V BtOppService: Receiver DISABLED_ACTION 
08-30 09:36:23.486  7087  7087 I BtOppRfcommListener: stopping Accept Thread
,08-30 09:36:23.486  7087  7087 V BtOppRfcommListener: close mBtServerSocket
08-30 09:36:23.489  7087  7782 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 09:36:23.489  7087  7087 V BtOppRfcommListener: waiting for thread to terminate
08-30 09:36:23.490  7087  7087 V BtOppRfcommListener: done waiting for thread to terminate
,08-30 09:36:23.501  6945  6945 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-30 09:36:23.504  6945  6945 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 09:36:23.508  7087  7087 V BtOppService: onDestroy
08-30 09:36:23.509  7087  7087 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 09:36:23.513  7087  7087 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 09:36:23.513  7087  7087 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:23.513  7087  7087 V BluetoothPbapReceiver: ***********state = 13
,08-30 09:36:23.516  7087  7087 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 09:36:23.519  7087  7087 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:23.519  7087  7087 V BluetoothPbapService: state: 13
08-30 09:36:23.519  7087  7087 V BluetoothPbapService: Pbap Service closeService in
08-30 09:36:23.521  7087  7087 V BluetoothPbapService: successfully stopped pbap service
08-30 09:36:23.521  7087  7087 V BluetoothPbapService: Pbap Service closeService out
08-30 09:36:23.523  7087  7087 V BluetoothPbapService: Pbap Service onDestroy
08-30 09:36:23.523  7087  7087 V BluetoothPbapService: Pbap Service closeService in
08-30 09:36:23.523  7087  7087 V BluetoothPbapService: Pbap Service closeService out
08-30 09:36:23.523  7087  7087 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 09:36:23.542  2251  2251 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 09:36:23.547  6945  6945 D DockEventReceiver: finishStartingService: stopping service
08-30 09:36:23.549  6945  6945 D BluetoothPbap: Proxy object disconnected
08-30 09:36:23.549  6945  6945 D PbapServerProfile: Bluetooth service disconnected
08-30 09:36:23.559  6945  6945 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 09:36:23.565  6945  6945 D BluetoothPermissionRequest: onReceive
08-30 09:36:23.565  6945  6945 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 09:36:23.571  6945  6945 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 09:36:23.574  7087  7087 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 09:36:23.574  7087  7087 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-30 09:36:23.575  7087  7087 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 09:36:23.580  7087  7087 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:23.580  7087  7087 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 09:36:23.581  7087  7087 V BluetoothFtpService: Ftp Service onStartCommand
08-30 09:36:23.581  7087  7087 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:23.581  7087  7087 V BluetoothFtpService: Ftp Service closeService
08-30 09:36:23.582  7087  7087 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 09:36:23.583  7087  7087 V BluetoothFtpService: successfully stopped ftp service
08-30 09:36:23.584  7087  7087 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 09:36:23.584  7087  7087 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 09:36:23.584  7087  7087 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 09:36:23.584  7087  7087 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:23.584  7087  7087 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 09:36:23.584  7087  7087 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 09:36:23.585  7087  7087 V BluetoothFtpService: Ftp Service onDestroy
08-30 09:36:23.585  7087  7087 V BluetoothFtpService: Ftp Service closeService
08-30 09:36:23.591  7087  7087 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:23.591  7087  7087 V BluetoothSapService: state: 13
08-30 09:36:23.591  7087  7087 V BluetoothSapService: Stopping SAP server process
08-30 09:36:23.592  7087  7087 V BluetoothSapService: Sap Service closeSapService in
08-30 09:36:23.592  7087  7087 V BluetoothSapService: Close listen Socket : 
08-30 09:36:23.592  7087  7087 V BluetoothSapService: Close rfcomm Socket : 
08-30 09:36:23.593  7087  7087 V BluetoothSapService: Close sapd  Socket : 
,08-30 09:36:23.594  7087  7087 V BluetoothSapService: Sap Service closeSapService out
08-30 09:36:23.594  7087  7087 V BluetoothSapService: Sap Service onDestroy
08-30 09:36:23.594  7087  7087 V BluetoothSapService: Sap Service closeSapService in
08-30 09:36:23.594  7087  7087 V BluetoothSapService: Close listen Socket : 
08-30 09:36:23.594  7087  7087 V BluetoothSapService: Close rfcomm Socket : 
08-30 09:36:23.595  7087  7087 V BluetoothSapService: Close sapd  Socket : 
08-30 09:36:23.595  7087  7087 V BluetoothSapService: Sap Service closeSapService out
08-30 09:36:23.710  1027  1537 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-30 09:36:24.362  7087  7645 D bt_hci_bdroid: cleanup
,08-30 09:36:24.370  7087  7701 I bt_lpm  : LPM is already off!!!
08-30 09:36:24.370  7087  7756 I bt_userial_mct: exiting userial_read_thread
08-30 09:36:24.370  7087  7756 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 09:36:24.371  7087  7699 W bt-btif : ag scb idx 1 not allocated
08-30 09:36:24.371  7087  7699 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 09:36:24.371  7087  7699 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 09:36:24.371  7087  7699 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 09:36:24.372  7087  7645 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 09:36:24.372  7087  7701 I bt_vendor: hw_epilog_process
08-30 09:36:24.373  7087  7645 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 09:36:24.373  7087  7645 D bt_userial_mct: userial_close
08-30 09:36:24.373  7087  7645 E bt_userial_mct: pthread_join() FAILED result:3
08-30 09:36:24.373  7087  7645 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 09:36:24.435  7087  7645 D bt_hci_bdroid: set_power 0
08-30 09:36:24.435  7087  7645 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 09:36:24.435  7087  7645 I bt_vendor: bluetooth satus is on
08-30 09:36:24.435  7087  7645 I bt_vendor: bt-vendor : resetting BT status
08-30 09:36:24.435  7087  7645 I bt_vendor: Starting hciattach daemon
08-30 09:36:24.435  7087  7645 I bt_vendor: try to set false
,08-30 09:36:24.442  7087  7645 I bt_vendor: Starting hciattach daemon
08-30 09:36:24.442  7087  7645 I bt_vendor: try to set false
08-30 09:36:24.443  7087  7645 I bt_vendor: cleanup
08-30 09:36:24.443  7087  7699 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 09:36:24.444  7087  7645 I GKI_LINUX: GKI_exit_task 0 done
08-30 09:36:24.444  7087  7645 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 09:36:24.445  7087  7641 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 09:36:24.453  7087  7641 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-30 09:36:24.456  7087  7087 D HeadsetService: Received stop request...Stopping profile...
08-30 09:36:24.457  7087  7087 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 09:36:24.457  7087  7087 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 09:36:24.457  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:24.461  7087  7674 D HeadsetStateMachine: Exit Disconnected: -1
08-30 09:36:24.463  1871  1871 D BluetoothHeadset: Proxy object disconnected
08-30 09:36:24.463  1871  1871 D BluetoothHeadset: Proxy object disconnected
08-30 09:36:24.463  1871  1871 D BluetoothHeadset: Proxy object disconnected
08-30 09:36:24.463  1027  1027 D BluetoothHeadset: Proxy object disconnected
08-30 09:36:24.463  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 09:36:24.466  7087  7087 D A2dpService: Received stop request...Stopping profile...
,08-30 09:36:24.469  7087  7688 D A2dpStateMachine: Exit Disconnected: -1
08-30 09:36:24.471  7087  7087 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 09:36:24.472  7087  7087 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 09:36:24.472  7087  7087 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 09:36:24.472  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:24.474  7087  7087 D HidService: Received stop request...Stopping profile...
08-30 09:36:24.474  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:24.474  1027  1027 D BluetoothA2dp: Proxy object disconnected
08-30 09:36:24.475  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 09:36:24.477  7087  7087 D HealthService: Received stop request...Stopping profile...
08-30 09:36:24.477  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:24.479  7087  7087 D PanService: Received stop request...Stopping profile...
,08-30 09:36:24.482  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:24.483  7087  7087 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 09:36:24.484  7087  7087 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 09:36:24.484  7087  7087 D BtGatt.GattService: stop()
08-30 09:36:24.484  7087  7087 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 09:36:24.485  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:24.487  7087  7087 D BluetoothMapService: Received stop request...Stopping profile...
08-30 09:36:24.487  7087  7087 D BluetoothMapService: stop()
08-30 09:36:24.487  7087  7087 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 09:36:24.487  7087  7087 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 09:36:24.488  7087  7087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:24.489  7087  7087 D HeadsetStateMachine: Unbinding service...
08-30 09:36:24.491  7087  7087 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 09:36:24.491  7087  7087 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 09:36:24.491  7087  7087 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 09:36:24.491  7087  7087 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 09:36:24.491  7087  7087 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 09:36:24.491  7087  7087 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 09:36:24.491  7087  7087 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 09:36:24.491  7087  7087 I BluetoothA2dpServiceJni: cleanupNative
,08-30 09:36:24.494  7087  7689 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 09:36:24.495  7087  7087 I GKI_LINUX: GKI_exit_task 2 done
08-30 09:36:24.495  7087  7087 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 09:36:24.496  7087  7087 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 09:36:24.496  7087  7087 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 09:36:24.496  7087  7087 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 09:36:24.496  7087  7087 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 09:36:24.496  7087  7087 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 09:36:24.497  7087  7087 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 09:36:24.497  7087  7087 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 09:36:24.499  7087  7087 V BluetoothMapService: Handler(): got msg=4
08-30 09:36:24.499  7087  7087 D BluetoothMapService: MAP Service closeService in
08-30 09:36:24.499  7087  7087 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 09:36:24.499  7087  7087 V BluetoothMapService: MAP Service closeService out
08-30 09:36:24.500  7087  7641 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 09:36:24.500  7087  7641 D BluetoothAdapterProperties: Setting state to 10
08-30 09:36:24.500  7087  7641 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 09:36:24.500  7087  7087 D BluetoothMapService: cleanup()
08-30 09:36:24.500  7087  7087 D BluetoothMapService: MAP Service closeService in
08-30 09:36:24.500  7087  7087 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 09:36:24.500  7087  7087 V BluetoothMapService: MAP Service closeService out
08-30 09:36:24.502  1027  1089 D BluetoothManagerService: Message: 60
08-30 09:36:24.502  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 09:36:24.502  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 09:36:24.502  7087  7641 I BluetoothAdapterState: Entering OffState
08-30 09:36:24.502  6945  6961 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 09:36:24.503  6945  6961 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 09:36:24.505  6945  6961 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 09:36:24.513  6945  6945 D BluetoothHeadset: Proxy object disconnected
08-30 09:36:24.513  6945  6945 D HeadsetProfile: Bluetooth service disconnected
08-30 09:36:24.513  1871  1887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:36:24.513  6945  6945 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 09:36:24.513  6945  6945 D PanProfile: Bluetooth service disconnected
08-30 09:36:24.514  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:36:24.514  6945  6961 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:36:24.515  6945  6945 D BluetoothMap: Proxy object disconnected
08-30 09:36:24.515  6945  6945 D MapProfile: Bluetooth service disconnected
08-30 09:36:24.516  1871  1886 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 09:36:24.517  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 09:36:24.518  6945  7080 D BluetoothMap: onBluetoothStateChange: up=false
08-30 09:36:24.519  1871  3508 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:36:24.519  6945  6962 D BluetoothPan: onBluetoothStateChange on: false
08-30 09:36:24.520  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 09:36:24.520  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 09:36:24.522  1027  1089 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 09:36:24.522  1027  1089 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 09:36:24.522  1027  1089 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1328da6c mBinding = false
08-30 09:36:24.522  1027  1089 D BluetoothManagerService: Sending unbind request.
08-30 09:36:24.528  7087  7645 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 09:36:24.529  7087  7087 I GKI_LINUX: GKI_exit_task 1 done
08-30 09:36:24.529  7087  7087 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 09:36:24.529  7087  7087 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 09:36:24.529  7087  7087 I art     : --- WEIRD: removing null entry 248
08-30 09:36:24.530  7087  7087 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 09:36:24.530  7087  7087 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-30 09:36:24.531  7087  7087 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 09:36:24.532  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 09:36:24.534  7087  7087 I art     : System.exit called, status: 0
08-30 09:36:24.534  7087  7087 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 09:36:24.546  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:24.546  1958  2175 D LGBluetoothAPIService: Message: 2
08-30 09:36:24.546  1958  2175 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1d6eaf10 mBinding = false
08-30 09:36:24.546  1958  2175 D LGBluetoothAPIService: Sending unbind request.
,08-30 09:36:24.547  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 09:36:24.554  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:24.555  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:24.556  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:24.560  6945  6945 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 09:36:24.560  6945  6945 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-30 09:36:24.566  6945  6945 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 09:36:24.567  1596  1596 D BluetoothAdapter: 809303916: getState() :  mService = null. Returning STATE_OFF
08-30 09:36:24.567  1596  1596 D BluetoothAdapter: 809303916: getState() :  mService = null. Returning STATE_OFF
08-30 09:36:24.567   318  4036 V AudioFlinger: 7087 died, releasing its sessions
08-30 09:36:24.567   318  4036 V AudioFlinger:  pid 1871 @ 0
08-30 09:36:24.567   318  4036 V AudioFlinger:  pid 3399 @ 1
08-30 09:36:24.567   318  4036 V AudioFlinger:  pid 3399 @ 2
08-30 09:36:24.570  6945  6945 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 09:36:24.571  1027  2063 W ActivityManager: Exception when unbinding service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer
08-30 09:36:24.571  1027  2063 W ActivityManager: android.os.DeadObjectException
08-30 09:36:24.571  1027  2063 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 09:36:24.571  1027  2063 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 09:36:24.571  1027  2063 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-30 09:36:24.571  1027  2063 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-30 09:36:24.571  1027  2063 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-30 09:36:24.571  1027  2063 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-30 09:36:24.571  1027  2063 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-30 09:36:24.571  1027  2063 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-30 09:36:24.571  1027  2063 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-30 09:36:24.571  1027  2063 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 09:36:24.618  1027  1043 I ActivityManager: Process com.android.bluetooth (pid 7087) has died
,08-30 09:36:24.618  1027  1043 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms,
08-30 09:36:24.675  1027  1044 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=8025 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 09:36:24.679  6945  6945 D DockEventReceiver: finishStartingService: stopping service
,08-30 09:36:24.755  8025  8025 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 09:36:24.756  8025  8025 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 09:36:24.757  8025  8025 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 09:36:24.759  8025  8025 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 09:36:24.779  8025  8025 D BluetoothAdapterApp: Loading JNI Library
,08-30 09:36:24.816  8025  8025 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3c655ecb Instance Count = 1
,08-30 09:36:24.824  8025  8025 D BluetoothAdapterApp: onCreate
,08-30 09:36:24.850  8025  8025 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 09:36:24.850  8025  8025 D ProfileConfigQcom: Adding HeadsetService
08-30 09:36:24.850  8025  8025 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-30 09:36:24.850  8025  8025 D ProfileConfigQcom: Adding A2dpService
08-30 09:36:24.851  8025  8025 D ProfileConfigQcom: [BTUI] HidService is supported
,08-30 09:36:24.851  8025  8025 D ProfileConfigQcom: Adding HidService
08-30 09:36:24.851  8025  8025 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 09:36:24.852  8025  8025 D ProfileConfigQcom: Adding HealthService
08-30 09:36:24.852  8025  8025 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 09:36:24.854  8025  8025 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 09:36:24.854  8025  8025 D ProfileConfigQcom: Adding PanService
08-30 09:36:24.854  8025  8025 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 09:36:24.854  8025  8025 D ProfileConfigQcom: Adding GattService
08-30 09:36:24.855  8025  8025 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 09:36:24.855  8025  8025 D ProfileConfigQcom: Adding BluetoothMapService
,08-30 09:36:24.855  8025  8025 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-30 09:36:24.856  8025  8025 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-30 09:36:24.857  8025  8025 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-30 09:36:24.858  8025  8025 V BluetoothPbapReceiver: ***********state = 10
,08-30 09:36:24.860  8025  8025 V LGMDMManagerInternal: Create singleton instance
,08-30 09:36:24.952  6945  6945 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-30 09:36:24.953  2251  2251 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 09:36:24.956  1027  1727 I ActivityManager: Killing 7201:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-30 09:36:25.038  1027  1043 W libprocessgroup: failed to open /acct/uid_10046/pid_7201/cgroup.procs: No such file or directory
,08-30 09:36:25.068  6945  6945 D BluetoothPermissionRequest: onReceive
,08-30 09:36:25.072  6945  6945 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 09:36:25.072  6945  6945 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 09:36:25.075  6945  6945 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 09:36:25.082  8025  8025 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-30 09:36:25.087  8025  8025 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:25.091  8025  8025 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 09:36:25.091  8025  8025 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 09:36:25.091  8025  8025 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 09:36:25.093  8025  8025 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:25.093  8025  8025 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 09:36:25.103  7706  7706 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 09:36:25.103  7739  7793 D UEI.SmartControl: Internal timer expired: 1
08-30 09:36:25.104  7739  7793 D UEI.SmartControl: unbind internal service
,08-30 09:36:25.110  7739  7739 D UEI.SmartControl: Service.onUnbind: IControl
08-30 09:36:25.110  7739  7739 D UEI.SmartControl: Service.onDestroy
08-30 09:36:25.110  7739  7739 D UEI.SmartControl: Lock is in USE false
08-30 09:36:25.110  7739  7739 D UEI.SmartControl: unbind internal service
08-30 09:36:25.110  7739  7739 D serial_port: close(fd = 25)
08-30 09:36:25.114  7739  7739 I UEI.SmartControl: Serial port is closed.
08-30 09:36:25.115  7739  7739 I UEI.SmartControl: Serial port is closed.
08-30 09:36:25.115  7739  7739 D UEI.SmartControl: Blaster closed
08-30 09:36:25.116  7739  7739 D UEI.SmartControl: Shut down QS...
08-30 09:36:25.116  7739  7739 D UEI.SmartControl: Stopping QS lib
08-30 09:36:25.116  7739  7739 D UEI.SmartControl: QS lib stop result = true
,08-30 09:36:25.116  7739  7739 D UEI.SmartControl: Stopped QS lib
08-30 09:36:25.118  7739  7739 D UEI.SmartControl: Stopped file observer...
08-30 09:36:25.118  7739  7739 D UEI.SmartControl: QS shutdown complete
,08-30 09:36:28.461  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:36:28.461  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:36:28.473  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:36:28.473  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1aa8e152 removed from the list
08-30 09:36:28.473  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:36:28.474  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:36:28.474  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:36:28.476  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:36:28.477  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@148fd520 added. We now have 4 listener(s)
08-30 09:36:28.477  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:36:28.483  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:36:28.483  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@148fd520 removed from the list
08-30 09:36:28.483  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:36:28.483  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:36:28.483  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:36:28.484  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:36:28.484  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aedaed9 added. We now have 4 listener(s)
08-30 09:36:28.484  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:36:28.485  1027  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:28.485  1027  2005 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 09:36:28.486  1027  1089 D BluetoothManagerService: Message: 2
08-30 09:36:33.495  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:36:33.507  1027  1567 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:33.508  1027  1567 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-30 09:36:33.523  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 09:36:33.523  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 09:36:33.523  1027  1027 D Ulp_jni : JNI:system_update. Event-4
,08-30 09:36:33.526  1027  1089 D BluetoothManagerService: Message: 1
08-30 09:36:33.527  1027  1089 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 09:36:33.556  1027  1089 D BluetoothManagerService: Message: 20
08-30 09:36:33.556  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39a6ab17:true
,08-30 09:36:33.560  8025  8025 D BluetoothAdapterState: make
08-30 09:36:33.564  8025  8025 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 09:36:33.565  8025  8025 I bluedroid-qcom: init
08-30 09:36:33.566  8025  8059 I BluetoothAdapterState: Entering OffState
08-30 09:36:33.566  8025  8025 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 09:36:33.566  8025  8025 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 09:36:33.567  8025  8025 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 09:36:33.567  8025  8025 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 09:36:33.567  8025  8025 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 09:36:33.569  8025  8025 I bluedroid-qcom: get_profile_interface socket
08-30 09:36:33.569  8025  8025 I bluedroid-qcom: get_profile_interface map_client
,08-30 09:36:33.574  8025  8063 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 09:36:33.576  8025  8063 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 09:36:33.565  8062  8062 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:33.575  8062  8062 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:33.587  8062  8062 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 09:36:33.587  8062  8062 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 09:36:33.587  8062  8062 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 09:36:33.592  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 09:36:33.593  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 09:36:33.595  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 09:36:33.595  1027  1089 D BluetoothManagerService: Message: 40
08-30 09:36:33.595  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 09:36:33.596  8025  8042 I bluedroid-qcom: config_hci_snoop_log
08-30 09:36:33.597  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 09:36:33.597  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 09:36:33.598  8062  8062 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 09:36:33.600  8025  8063 D BluetoothAdapterProperties: Name is: G3
08-30 09:36:33.605  8062  8062 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 09:36:33.605  8062  8062 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-30 09:36:33.611  8025  8059 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 09:36:33.611  8025  8059 D BluetoothAdapterProperties: Setting state to 11
08-30 09:36:33.611  8025  8059 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 09:36:33.613  8025  8059 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 09:36:33.617  1027  1089 D BluetoothManagerService: Message: 60
08-30 09:36:33.617  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 09:36:33.617  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-30 09:36:33.623  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:33.624  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 09:36:33.627  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:33.630  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:36:33.636  6945  6945 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 09:36:33.646  8025  8059 D BluetoothBondStateMachine: make
,08-30 09:36:33.646  8025  8025 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-30 09:36:33.646  8025  8025 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:33.646  8025  8025 V BluetoothPbapReceiver: ***********state = 11
08-30 09:36:33.650  8025  8059 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:33.650  8025  8059 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 09:36:33.650  8025  8059 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:33.651  8025  8059 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 09:36:33.651  8025  8059 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 09:36:33.651  2251  2251 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 09:36:33.652  8025  8076 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 09:36:33.655  8025  8059 E BluetoothAdapterService: File transfer profiles supported!!
08-30 09:36:33.665  8025  8059 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 09:36:33.666  8025  8025 D HeadsetService: Received start request. Starting profile...
08-30 09:36:33.667  8025  8025 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 09:36:33.667  8025  8025 D LGBluetoothHfpAdapter: Version 1.6
08-30 09:36:33.670  6945  6945 D BluetoothPermissionRequest: onReceive
08-30 09:36:33.671  8025  8025 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 09:36:33.672  8025  8025 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 09:36:33.672  8025  8025 D HeadsetStateMachine: make
08-30 09:36:33.675  6945  6945 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 09:36:33.679  8025  8059 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 09:36:33.686  8025  8059 E BluetoothAdapterService: File transfer profiles supported!!
08-30 09:36:33.692  8025  8059 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 09:36:33.698  8025  8059 E BluetoothAdapterService: File transfer profiles supported!!
08-30 09:36:33.703  8025  8059 E BluetoothAdapterService: File transfer profiles supported!!
08-30 09:36:33.712  8025  8025 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 09:36:33.713  8025  8025 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 09:36:33.718  8025  8025 D HeadsetStateMachine: max_hf_connections = 1
08-30 09:36:33.718  8025  8025 I bluedroid-qcom: get_profile_interface handsfree
08-30 09:36:33.719  8025  8059 V LGMDMManager: Create singleton instance
08-30 09:36:33.720  8025  8025 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 09:36:33.721   318  1377 V AudioPolicyService: registerClient() client 0xb558a920, uid 1002
08-30 09:36:33.721  8025  8059 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 09:36:33.721   318   318 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 09:36:33.721   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 09:36:33.721   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 09:36:33.722  8025  8025 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 09:36:33.722   318  4036 V AudioFlinger: registerClient() client 0xb55819e8, pid 8025
08-30 09:36:33.723   318  1371 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:33.723   318  1371 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 09:36:33.723  3399  3414 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:33.723  3399  3414 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 09:36:33.724  1027  1758 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:33.724  1027  1758 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 09:36:33.724  1596  3130 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:33.724  1596  3130 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 09:36:33.726  1871  3508 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:33.726  1871  3508 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-30 09:36:33.728   318  1372 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:33.728   318  1372 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 09:36:33.728  1596  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:33.728  1596  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 09:36:33.728  1871  3507 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:33.728  1871  3507 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 09:36:33.728  3399  3418 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:33.728  3399  3418 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 09:36:33.729  1027  1043 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:33.729  1027  1043 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 09:36:33.729  8025  8041 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 09:36:33.729  8025  8041 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 09:36:33.729  8025  8041 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 09:36:33.729  8025  8041 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 09:36:33.729  8025  8025 V ToneGenerator: Create Track: 0xb4928a80
08-30 09:36:33.729  8025  8025 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 09:36:33.729  8025  8025 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 09:36:33.729   318  1376 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 09:36:33.729   318  1376 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 09:36:33.729   318  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 09:36:33.729   318  1376 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 09:36:33.729   318  4036 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 09:36:33.730   318  1377 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 09:36:33.730   318  1377 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
,08-30 09:36:33.730   318  1377 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 09:36:33.730   318  1377 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 09:36:33.730  8025  8025 V AudioSystem: getLatency() output 2, latency 50
08-30 09:36:33.730  8025  8025 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 09:36:33.730  8025  8025 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 09:36:33.730   318  1376 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 09:36:33.730   318  1376 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 09:36:33.730   318  1376 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 09:36:33.730   318  1376 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 09:36:33.730   318  1376 V AudioFlinger: createTrack() lSessionId: 23
08-30 09:36:33.731  8025  8025 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 09:36:33.731   318   318 V AudioFlinger: acquiring 23 from 8025, for 8025
08-30 09:36:33.731   318   318 V AudioFlinger:  added new entry for 23
08-30 09:36:33.732  8025  8025 V ToneGenerator: ToneGenerator INIT OK, time: 248403
08-30 09:36:33.732  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:33.732  8025  8081 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 09:36:33.732  8025  8081 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 09:36:33.732  8025  8081 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 09:36:33.733  8025  8081 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 09:36:33.733  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:33.733   318  1377 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 8025
08-30 09:36:33.734   318  1377 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 09:36:33.734   318  1377 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 09:36:33.734   318  1377 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 09:36:33.734   318  1377 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 09:36:33.734   318  1377 V voice   : voice_set_parameters: exit with code(0)
08-30 09:36:33.734   318  1377 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 09:36:33.734   318  1377 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 09:36:33.734   318  1377 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 09:36:33.734   318  1377 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 09:36:33.734   318  1377 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 09:36:33.734   318  1377 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 09:36:33.735  8025  8081 V ToneGenerator: ToneGenerator destructor
08-30 09:36:33.735  8025  8081 V ToneGenerator: stopTone
08-30 09:36:33.735  8025  8081 V ToneGenerator: Delete Track: 0xb4928a80
08-30 09:36:33.735   318  1376 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 09:36:33.735   318  1376 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 09:36:33.735   318  1376 V AudioFlinger: PlaybackThread::Track destructor
08-30 09:36:33.735   318  1252 V AudioPolicyService: AudioCommandThread() waking up
08-30 09:36:33.735   318  1376 V AudioFlinger: removeClient_l() pid 8025, calling pid 318
08-30 09:36:33.735   318  1252 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 09:36:33.735   318  1252 V AudioPolicyManager: releaseOutput() 2
08-30 09:36:33.735   318 , 1252 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 09:36:33.735  8025  8081 V AudioTrack: ~AudioTrack, releasing session id from 8025 on behalf of 8025
08-30 09:36:33.736  8025  8025 D A2dpService: Received start request. Starting profile...
08-30 09:36:33.736   318  1377 V AudioFlinger: releasing 23 from 8025 for 8025
08-30 09:36:33.736   318  1377 V AudioFlinger:  decremented refcount to 0
08-30 09:36:33.736   318  1377 V AudioFlinger: purging stale effects
08-30 09:36:33.736  8025  8025 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 09:36:33.737  8025  8025 V Avrcp   : make
08-30 09:36:33.738  8025  8025 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 09:36:33.738  8025  8025 I bluedroid-qcom: get_profile_interface avrcp
08-30 09:36:33.749  8025  8025 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 09:36:33.751  8025  8025 E AudioManager: No RCC entry present to update
08-30 09:36:33.751  8025  8025 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 09:36:33.754  8025  8025 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 09:36:33.755  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 09:36:33.755  8025  8025 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 09:36:33.761  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 09:36:33.916  1027  1567 V SIM_STK : Menu title from STK is T-Mobile
08-30 09:36:33.916  1027  1567 V SIM_STK : Menu title from STK is T-Mobile
,08-30 09:36:34.050  1027  1943 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 09:36:34.060  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 09:36:34.064  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 09:36:34.065  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 09:36:34.065  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 09:36:34.065  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 09:36:34.065  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 09:36:34.065  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 09:36:34.065  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 09:36:34.065  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 09:36:34.065  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 09:36:34.065  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 09:36:34.066  8025  8025 I BluetoothA2dpServiceJni: classInitNative
08-30 09:36:34.066  8025  8025 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 09:36:34.066  8025  8025 D A2dpStateMachine: make
,08-30 09:36:34.069  8025  8025 I bluedroid-qcom: get_profile_interface a2dp
08-30 09:36:34.070  8025  8091 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 09:36:34.076  8025  8025 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 09:36:34.076  8025  8025 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 09:36:34.079  8025  8090 D A2dpStateMachine: Enter Disconnected: -2
08-30 09:36:34.079  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
,08-30 09:36:34.086  8025  8025 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 09:36:34.089  8025  8025 D HidService: Received start request. Starting profile...
08-30 09:36:34.089  8025  8025 I bluedroid-qcom: get_profile_interface hidhost
08-30 09:36:34.089  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:34.090  8025  8025 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 09:36:34.091  8025  8025 D HealthService: Received start request. Starting profile...
,08-30 09:36:34.093  8025  8025 I bluedroid-qcom: get_profile_interface health
08-30 09:36:34.093  8025  8025 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 09:36:34.093  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:34.094  8025  8025 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 09:36:34.096  8025  8025 D PanService: Received start request. Starting profile...
08-30 09:36:34.096  8025  8025 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 09:36:34.096  8025  8025 I bluedroid-qcom: get_profile_interface pan
08-30 09:36:34.104  8025  8025 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 09:36:34.104  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:34.106  8025  8025 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-30 09:36:34.111  8025  8025 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 09:36:34.112  8025  8025 D BtGatt.GattService: Received start request. Starting profile...
08-30 09:36:34.112  8025  8025 D BtGatt.GattService: start()
08-30 09:36:34.112  8025  8025 I bluedroid-qcom: get_profile_interface gatt
08-30 09:36:34.112  8025  8025 D BtGatt.AdvertiseManager: advertise manager created
08-30 09:36:34.120  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
,08-30 09:36:34.121  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:34.122  8025  8025 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 09:36:34.123  8025  8025 V BluetoothMapService: BluetoothMapBinder()
08-30 09:36:34.124  8025  8025 D BluetoothMapService: Received start request. Starting profile...
08-30 09:36:34.124  8025  8025 D BluetoothMapService: start()
08-30 09:36:34.128  8025  8025 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 09:36:34.128  8025  8025 D BluetoothMapEmailAppObserver: createReceiver()
08-30 09:36:34.130  8025  8025 D BluetoothMapEmailAppObserver: initObservers()
08-30 09:36:34.130  8025  8025 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 09:36:34.140  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:34.140  8025  8025 D HeadsetStateMachine: Proxy object connected
08-30 09:36:34.141  8025  8025 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 09:36:34.141  8025  8025 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-30 09:36:34.152  8025  8025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 09:36:34.152  8025  8081 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 09:36:34.153  8025  8081 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 09:36:34.154  8025  8081 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-30 09:36:34.159  8025  8025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 09:36:34.163  8025  8025 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:34.170  8025  8025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 09:36:34.178  8025  8025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 09:36:34.179  8025  8025 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 09:36:34.186  8025  8025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 09:36:34.193  8025  8025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 09:36:34.193  8025  8025 V BluetoothMapService: Handler(): got msg=1
08-30 09:36:34.195  8025  8025 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 09:36:34.195  8025  8059 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 09:36:34.195  8025  8025 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 09:36:34.195  8025  8025 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 09:36:34.195  8025  8059 I bluedroid-qcom: enable
08-30 09:36:34.195  8025  8025 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:34.196  8025  8025 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 09:36:34.197  8025  8099 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 09:36:34.198  8025  8059 I bt_hci_bdroid: init
08-30 09:36:34.198  8025  8099 I bt-btu  : btu_task pending for preload complete event
08-30 09:36:34.200  8025  8059 I bt_vendor: bt-vendor : init
08-30 09:36:34.200  8025  8059 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 09:36:34.200  8025  8059 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 09:36:34.200  8025  8059 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 09:36:34.200  8025  8059 D bt_userial_mct: userial_init
,08-30 09:36:34.204  8025  8059 D bt_hci_bdroid: set_power 1
,08-30 09:36:34.204  8025  8059 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-30 09:36:34.204  8025  8059 I bt_vendor: Starting hciattach daemon
08-30 09:36:34.204  8025  8059 I bt_vendor: try to set true
08-30 09:36:34.205  8102  8102 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:34.205  8102  8102 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:34.257  8103  8103 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 09:36:34.372  8109  8109 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 09:36:34.385  8110  8110 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 09:36:34.420  8112  8112 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 09:36:34.440  8113  8113 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 09:36:34.456  8115  8115 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 09:36:34.480  8119  8119 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 09:36:34.504  8121  8121 I libmdmdetect: ESOC framework not supported
,08-30 09:36:34.507  8121  8121 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 09:36:34.518  8121  8121 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 09:36:34.519  8121  8121 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 09:36:34.519  8121  8121 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 09:36:34.519  8121  8121 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 09:36:34.519  8121  8121 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 09:36:34.519  8121  8121 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 09:36:34.519  8121  8121 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-30 09:36:34.573  8121  8122 E QC-QMI  : qmi_client [8121] 15: failed to locate client data
,08-30 09:36:34.581   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 09:36:34.581   467   467 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-30 09:36:34.604  8126  8126 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 09:36:34.621  8127  8127 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 09:36:34.658  8025  8059 I bt_vendor: bluetooth satus is on
08-30 09:36:34.658  8025  8059 D bt_hci_bdroid: preload
08-30 09:36:34.658  8025  8101 D bt_userial_mct: userial_open(port:0)
08-30 09:36:34.658  8025  8101 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 09:36:34.663  8025  8101 I bt_vendor: Done intiailizing UART
08-30 09:36:34.667  8025  8101 I bt_vendor: Done intiailizing UART
08-30 09:36:34.667  8025  8101 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 09:36:34.667  8025  8101 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 09:36:34.668  8025  8099 I bt-btu  : btu_task received preload complete event
08-30 09:36:34.668  8025  8099 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 09:36:34.668  8025  8099 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 09:36:34.671  8025  8099 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 09:36:34.674  8025  8129 D bt_userial_mct: Entering userial_read_thread()
,08-30 09:36:34.682  8025  8099 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 09:36:34.682  8025  8099 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 09:36:34.682  8025  8099 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 09:36:34.682  8025  8099 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 09:36:34.682  8025  8099 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 09:36:34.682  8025  8099 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 09:36:34.682  8025  8099 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 09:36:34.682  8025  8099 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 09:36:34.683  8025  8099 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 09:36:34.683  8025  8099 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 09:36:34.683  8025  8099 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 09:36:34.683  8025  8099 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 09:36:34.683  8025  8099 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 09:36:34.683  8025  8099 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 09:36:34.683  8025  8099 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 09:36:34.683  8025  8099 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 09:36:34.754  8025  8099 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 09:36:34.754  8025  8099 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0183061 
08-30 09:36:34.754  8025  8099 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0183061 
,08-30 09:36:34.806  8025  8063 E bt-btif : Calling BTA_HhEnable
08-30 09:36:34.806  8025  8063 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 09:36:34.807  8025  8063 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 09:36:34.814  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 09:36:34.814  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 09:36:34.815  8025  8063 D BluetoothAdapterProperties: Name is: G3
08-30 09:36:34.817  8025  8063 D BluetoothAdapterProperties: Scan Mode:20
08-30 09:36:34.818  8025  8063 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 09:36:34.818  8025  8063 D bt_hci_bdroid: postload
08-30 09:36:34.820  8025  8063 D bte_conf: Device ID record 1 : primary
08-30 09:36:34.820  8025  8063 D bte_conf:   vendorId            = 00c4
08-30 09:36:34.820  8025  8063 D bte_conf:   vendorIdSource      = 0001
08-30 09:36:34.820  8025  8063 D bte_conf:   product             = 13a1
08-30 09:36:34.820  8025  8063 D bte_conf:   version             = 1000
08-30 09:36:34.820  8025  8063 D bte_conf:   clientExecutableURL = 
08-30 09:36:34.820  8025  8063 D bte_conf:   serviceDescription  = 
08-30 09:36:34.820  8025  8063 D bte_conf:   documentationURL    = 
08-30 09:36:34.824  8025  8101 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 09:36:34.829  8025  8063 D bte_conf: bte_load_did_conf no section named DID2.
08-30 09:36:34.830  8025  8101 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 09:36:34.835  8025  8059 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 09:36:34.835  8025  8059 D BluetoothAdapterProperties: ScanMode =  20
08-30 09:36:34.835  8025  8059 D BluetoothAdapterProperties: State =  11
08-30 09:36:34.835  8025  8059 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 09:36:34.835  8025  8059 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 09:36:34.836  8025  8059 D BluetoothAdapterProperties: Setting state to 12
08-30 09:36:34.836  8025  8059 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 09:36:34.838  8025  8063 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 09:36:34.835  8131  8131 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:34.835  8131  8131 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:34.848  1027  1089 D BluetoothManagerService: Message: 60
08-30 09:36:34.848  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 09:36:34.849  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-30 09:36:34.850  8025  8129 E bt_mct  : hci lib postload completed
,08-30 09:36:34.864  8025  8059 I BluetoothAdapterState: Entering On State
,08-30 09:36:34.878  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:34.878  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:34.878  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:34.878  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:34.878  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:34.878  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:34.878  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:34.878  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:36:34.883  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:34.885  8025  8063 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 09:36:34.885  8025  8063 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 09:36:34.889  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:34.889  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:34.889  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:34.889  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:34.889  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:34.889  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:34.889  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:34.889  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:34.895  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:36:34.909  8025  8059 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 09:36:34.909  8025  8059 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 09:36:34.909  8025  8059 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-30 09:36:34.912  8025  8059 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 09:36:34.913  8025  8099 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 09:36:34.913  8025  8099 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 09:36:34.913  8025  8099 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 09:36:34.913  8025  8099 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 09:36:34.913  8025  8099 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 09:36:34.913  8025  8099 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 09:36:34.913  8025  8063 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 09:36:34.914  6945  6962 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 09:36:34.914  8025  8059 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 09:36:34.929  6945  6962 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 09:36:34.932  8025  8099 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 09:36:34.932  8025  8099 W bt-smp  : Plain text(LSB ~ MSB) = 86 2d 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 09:36:34.932  8025  8099 W bt-smp  : Encrypted text(LSB ~ MSB) = 71 6f d1 b3 49 0b 22 d5 da 94 d9 19 4b 68 09 8d 
08-30 09:36:34.932  8025  8099 W bt-btm  : Stopping oneshot timer
08-30 09:36:34.940  6945  7080 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 09:36:34.965  8136  8136 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-30 09:36:34.971  1871  1887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:36:34.977  1871  1871 D BluetoothHeadset: Proxy object connected
08-30 09:36:34.980  8025  8099 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 09:36:34.980  8025  8099 W bt-smp  : Plain text(LSB ~ MSB) = 4a 44 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 09:36:34.981  8025  8099 W bt-smp  : Encrypted text(LSB ~ MSB) = eb 55 6a d3 59 72 72 32 89 99 5b 22 50 4b d4 59 
08-30 09:36:34.981  8025  8099 W bt-btm  : Stopping oneshot timer
,08-30 09:36:34.988  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:36:34.989  6945  6945 D BluetoothInputDevice: Proxy object connected
08-30 09:36:34.990  6945  6945 D HidProfile: Bluetooth service connected
08-30 09:36:34.991  1027  1027 D BluetoothHeadset: Proxy object connected
08-30 09:36:34.991  6945  6961 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 09:36:34.994  1871  3508 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:36:34.996  1871  1871 D BluetoothHeadset: Proxy object connected
08-30 09:36:34.996  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 09:36:34.997  1027  1027 D BluetoothA2dp: Proxy object connected
08-30 09:36:34.998  6945  6945 D BluetoothA2dp: Proxy object connected
08-30 09:36:34.998  6945  7080 D BluetoothMap: onBluetoothStateChange: up=true
08-30 09:36:34.998  6945  6945 D A2dpProfile: Bluetooth service connected
,08-30 09:36:35.002  6945  6945 D BluetoothHeadset: Proxy object connected
08-30 09:36:35.002  6945  6945 D HeadsetProfile: Bluetooth service connected
08-30 09:36:35.003  1871  2550 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:36:35.004  8025  8099 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 09:36:35.004  8025  8099 W bt-smp  : Plain text(LSB ~ MSB) = 98 d0 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 09:36:35.004  8025  8099 W bt-smp  : Encrypted text(LSB ~ MSB) = d7 a0 88 a9 9a 3c 10 37 20 44 dc ec 16 7f c1 ef 
08-30 09:36:35.004  8025  8099 W bt-btm  : Stopping oneshot timer
08-30 09:36:35.005  1871  1871 D BluetoothHeadset: Proxy object connected
08-30 09:36:35.005  6945  7080 D BluetoothPan: onBluetoothStateChange on: true
08-30 09:36:35.005  6945  7080 D BluetoothPan: onBluetoothStateChange call bindService
08-30 09:36:35.006  6945  6945 D BluetoothMap: Proxy object connected
08-30 09:36:35.006  6945  6945 D MapProfile: Bluetooth service connected
08-30 09:36:35.006  6945  6945 D BluetoothMap: getConnectedDevices()
08-30 09:36:35.009  1027  1089 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 09:36:35.009  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 09:36:35.010  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:35.010  1958  2175 D LGBluetoothAPIService: Message: 1
08-30 09:36:35.010  1958  2175 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-30 09:36:35.013  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 09:36:35.017  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:35.020  8025  8150 V BluetoothMapService: getConnectedDevices()
08-30 09:36:35.020  8025  8099 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 09:36:35.020  8025  8099 W bt-smp  : Plain text(LSB ~ MSB) = b8 6a 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 09:36:35.020  8025  8099 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 2f f3 34 8c 2a 89 4b 62 bc f7 37 23 a2 97 c3 
08-30 09:36:35.021  8025  8099 W bt-btm  : Stopping oneshot timer
08-30 09:36:35.022  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 09:36:35.023  1027  1089 D BluetoothManagerService: Message: 40
08-30 09:36:35.023  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 09:36:35.023  1958  2175 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-30 09:36:35.026  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:35.029  6945  6945 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 09:36:35.030  8025  8025 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:35.030  8025  8025 D BluetoothMapService: STATE_ON
08-30 09:36:35.031  6945  6945 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 09:36:35.032  8025  8025 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 09:36:35.033  8025  8025 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 09:36:35.034  1958  1958 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 09:36:35.034  1958  2175 D LGBluetoothAPIService: Message: 100
08-30 09:36:35.034  1958  2175 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 09:36:35.034  6945  6945 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 09:36:35.034  6945  6945 D PanProfile: Bluetooth service connected
08-30 09:36:35.036  8025  8099 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 09:36:35.036  8025  8099 W bt-smp  : Plain text(LSB ~ MSB) = e6 7f 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 09:36:35.036  8025  8099 W bt-smp  : Encrypted text(LSB ~ MSB) = 22 dc cf 7b 86 38 c7 48 30 21 ca 66 42 e5 06 ba 
08-30 09:36:35.036  8025  8099 W bt-btm  : Stopping oneshot timer
08-30 09:36:35.041  6945  6945 D DockEventReceiver: finishStartingService: stopping service
,08-30 09:36:35.051  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
08-30 09:36:35.052  8025  8025 V BluetoothPbapService: Pbap Service onCreate
08-30 09:36:35.052  8025  8025 V BluetoothPbapService: Starting PBAP service
08-30 09:36:35.053  8025  8025 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 09:36:35.053  8025  8025 V BluetoothMapService: Handler(): got msg=1
,08-30 09:36:35.054  8025  8025 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 09:36:35.055  8025  8025 V BluetoothPbapService: Pbap Service onBind
08-30 09:36:35.056  8025  8157 D BluetoothMapMasInstance: MAS initSocket()
08-30 09:36:35.056  8025  8025 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:35.056  8025  8025 V BluetoothPbapService: state: 12
08-30 09:36:35.056  8025  8157 D BluetoothMapMasInstance:   masId = 00
08-30 09:36:35.056  8025  8157 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 09:36:35.056  8025  8157 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 09:36:35.056  8025  8157 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 09:36:35.056  8025  8025 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 09:36:35.057  8025  8025 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:35.057  8025  8025 V BluetoothPbapReceiver: ***********state = 12
08-30 09:36:35.058  1027  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:35.058  6945  6945 D BluetoothPbap: Proxy object connected
08-30 09:36:35.058  6945  6945 D PbapServerProfile: Bluetooth service connected
08-30 09:36:35.059  8025  8025 V BluetoothPbapService: Handler(): got msg=1
08-30 09:36:35.059  8025  8025 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 09:36:35.059  8025  8157 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:36:35.061  8025  8157 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=74 mFd=0
08-30 09:36:35.061  8025  8157 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 09:36:35.061  8025  8157 D BluetoothMapMasInstance: Accepting socket connection...
08-30 09:36:35.062  8025  8063 D BluetoothAdapterProperties: Scan Mode:21
08-30 09:36:35.062  8025  8063 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 09:36:35.063  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:35.063  8025  8158 V BluetoothPbapService: Pbap Service initSocket
08-30 09:36:35.064  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:36:35.067  2251  2251 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 09:36:35.068  2251  2251 D c       : Getting all permits...
08-30 09:36:35.068  2251  2251 D a       : Opening database...
08-30 09:36:35.073  2251  2251 D a       : Opening database auth.proximity.permit_store...
08-30 09:36:35.074  1027  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:35.074  2251  2251 D a       : Closing database...
08-30 09:36:35.075  8025  8158 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:36:35.079  8025  8158 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=74
08-30 09:36:35.079  8025  8158 V BluetoothPbapService: Succeed to create listening socket 
08-30 09:36:35.079  8025  8158 V BluetoothPbapService: Accepting socket connection...
,08-30 09:36:35.085  6945  6945 D BluetoothPermissionRequest: onReceive
08-30 09:36:35.087  6945  6945 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 09:36:35.089  6945  6945 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 09:36:35.093  8025  8025 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-30 09:36:35.095  8025  8025 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 09:36:35.102  8025  8025 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 09:36:35.127  8025  8025 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 09:36:35.127  8025  8025 V BtOppService: onCreate
08-30 09:36:35.236  1027  1943 I art     : Explicit concurrent mark sweep GC freed 28365(1407KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.365ms total 105.139ms
,08-30 09:36:35.239  8025  8025 V BluetoothOppNotification: send message
08-30 09:36:35.241  8025  8025 V BtOppService: Starting RfcommListener
08-30 09:36:35.252  8025  8025 D BluetoothOppPreference: Dumping Names:  
08-30 09:36:35.252  8025  8025 D BluetoothOppPreference: {}
08-30 09:36:35.252  8025  8025 D BluetoothOppPreference: Dumping Channels:  
08-30 09:36:35.252  8025  8025 D BluetoothOppPreference: {}
08-30 09:36:35.252  8025  8025 V BtOppService: onStartCommand
,08-30 09:36:35.256  8025  8162 V BtOppService: Deleted complete outbound shares, number =  0
08-30 09:36:35.257  8025  8165 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 09:36:35.257  8025  8165 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 09:36:35.257  8025  8025 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:35.257  8025  8025 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 09:36:35.258  8025  8162 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 09:36:35.258  8025  8162 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 09:36:35.261  8025  8162 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a34237c on behalf of 
08-30 09:36:35.263  8025  8025 V BluetoothOppNotification: new notify threadi!
08-30 09:36:35.264  8025  8165 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28eb1405 on behalf of 
08-30 09:36:35.265  8025  8025 V BluetoothOppNotification: send delay message
08-30 09:36:35.267  8025  8165 V BluetoothOppNotification: update too frequent, put in queue
08-30 09:36:35.267  8025  8025 V BtOppService: start RfcommListener
,08-30 09:36:35.269  8025  8165 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 09:36:35.270  8025  8166 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 09:36:35.271  8025  8166 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d0f3c5a on behalf of 
08-30 09:36:35.272  8025  8166 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 09:36:35.273  8025  8166 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 09:36:35.274  8025  8166 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b7c4e8b on behalf of 
08-30 09:36:35.275  8025  8166 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 09:36:35.276  8025  8025 V BtOppService: RfcommListener started
08-30 09:36:35.276  8025  8025 V BtOppService: ContentObserver received notification
08-30 09:36:35.276  8025  8166 V BluetoothOppNotification: outbound notification was removed.
08-30 09:36:35.277  8025  8166 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 09:36:35.277  8025  8025 V BtOppService: ContentObserver received notification
08-30 09:36:35.279  8025  8166 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e5dfb68 on behalf of 
,08-30 09:36:35.281  8025  8167 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 09:36:35.283  1027  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:35.283  8025  8166 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 09:36:35.283  8025  8168 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 09:36:35.283  8025  8168 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 09:36:35.284  8025  8168 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b0deb81 on behalf of 
08-30 09:36:35.286  8025  8167 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:36:35.286  8025  8168 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 09:36:35.288  8025  8167 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-30 09:36:35.288  8025  8167 V BtOppRfcommListener: Started RFCOMM listener....
08-30 09:36:35.289  8025  8167 I BtOppRfcommListener: Accept thread started.
08-30 09:36:35.289  8025  8167 V BtOppRfcommListener: Accepting connection...
08-30 09:36:35.289  8025  8166 V BluetoothOppNotification: inbound notification was removed.
08-30 09:36:35.289  8025  8166 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 09:36:35.290  8025  8166 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1974c426 on behalf of 
,08-30 09:36:35.294  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
,08-30 09:36:35.294  8025  8025 V BluetoothFtpService: Ftp Service onCreate
08-30 09:36:35.294  8025  8025 I BluetoothFtpService: Ftp Service onCreate
08-30 09:36:35.294  8025  8025 V BluetoothFtpService: Ftp Service onStartCommand
08-30 09:36:35.294  8025  8025 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:35.294  8025  8025 V BluetoothFtpService: Starting Listening on sockets
08-30 09:36:35.295  8025  8025 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 09:36:35.295  8025  8025 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 09:36:35.295  8025  8025 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 09:36:35.295  8025  8025 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:35.295  8025  8025 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 09:36:35.296  8025  8025 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 09:36:35.297  8025  8025 V BluetoothFtpService: Handler(): got msg=1
08-30 09:36:35.298  8025  8025 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 09:36:35.298  8025  8025 V BluetoothFtpService: Ftp Service initSocket
08-30 09:36:35.303  1027  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:35.304  8025  8025 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 09:36:35.305  8025  8025 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-30 09:36:35.305  8025  8025 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 09:36:35.307  8025  8169 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 09:36:35.321  8025  8025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e00dc43
,08-30 09:36:35.321  8025  8025 V BluetoothSapService: Sap Service onCreate
08-30 09:36:35.323  8025  8025 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:36:35.323  8025  8025 V BluetoothSapService: state: 12
08-30 09:36:35.323  8025  8025 V BluetoothSapService: Starting SAP server process
08-30 09:36:35.326  8025  8025 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 09:36:35.315  8170  8170 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:35.315  8170  8170 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:35.327  8025  8171 V BluetoothSapService: Sap Service initRfcommSocket
08-30 09:36:35.328  1027  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:36:35.329  8025  8171 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:36:35.330  8025  8171 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 09:36:35.330  8025  8171 V BluetoothSapService: Succeed to create listening socket 
08-30 09:36:35.330  8025  8171 V BluetoothSapService: Accepting socket connection...
08-30 09:36:35.338  8170  8170 V BT_SAP  : Event pipe created
08-30 09:36:35.338  8170  8170 V BT_SAP  : create_server_socket qcom.sap.server
08-30 09:36:35.338  8170  8170 V BT_SAP  : created socket fd 6
,08-30 09:36:36.267  8025  8025 V BluetoothOppNotification: new notify threadi!
,08-30 09:36:36.275  8025  8025 V BluetoothOppNotification: send delay message
08-30 09:36:36.281  8025  8181 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 09:36:36.284  8025  8181 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@338e0403 on behalf of 
,08-30 09:36:36.291  8025  8181 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-30 09:36:36.292  8025  8181 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 09:36:36.293  8025  8181 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1602cf80 on behalf of 
,08-30 09:36:36.294  8025  8181 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 09:36:36.295  8025  8181 V BluetoothOppNotification: outbound notification was removed.
08-30 09:36:36.295  8025  8181 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-30 09:36:36.296  8025  8181 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@376b89b9 on behalf of 
08-30 09:36:36.297  8025  8181 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 09:36:36.298  8025  8181 V BluetoothOppNotification: inbound notification was removed.
08-30 09:36:36.298  8025  8181 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 09:36:36.299  8025  8181 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ad631fe on behalf of 
08-30 09:36:38.551  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:38.551  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:38.551  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:38.551  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:36:38.551  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:38.551  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:38.551  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:38.551  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:36:38.564  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:36:38.565  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:36:38.565  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aedaed9 removed from the list
08-30 09:36:38.565  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:36:38.565  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:36:38.565  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:36:38.566  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:36:38.566  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@274fc09e added. We now have 4 listener(s)
08-30 09:36:38.566  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:36:38.568  1027  1991 D WifiServiceImplEx: setWifiEnabled: false pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 09:36:38.569  1027  1991 D WifiService: setWifiEnabled: false pid=6817, uid=10118
08-30 09:36:38.569  1027  1991 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 09:36:43.580  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:36:43.591  1027  2005 D WifiServiceImplEx: setWifiEnabled: true pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 09:36:43.592  1027  2005 D WifiService: setWifiEnabled: true pid=6817, uid=10118
08-30 09:36:43.592  1027  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 09:36:43.613  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 09:36:43.613  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 09:36:43.613  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-30 09:36:43.614  1027  1531 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 09:36:43.614  1027  1531 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 09:36:43.617  1027  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 09:36:43.617  1027  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 09:36:43.617  1027  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 09:36:43.617  1027  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 09:36:43.617  1027  1531 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 09:36:43.617  1027  1531 E WifiHW  : unknown target_country: EU , set to default
08-30 09:36:43.617  1027  1531 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 09:36:43.617  1027  1531 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 09:36:43.618  1027  1531 I WifiUtil: gEnableBmps=1
08-30 09:36:44.201   313   887 D SoftapController: Softap fwReload - Ok
,08-30 09:36:44.207  1027  1531 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (585ms)
08-30 09:36:44.213   313   887 D CommandListener: Setting iface cfg
08-30 09:36:44.213   313   887 D CommandListener: Trying to bring down wlan0
08-30 09:36:44.217  1027  1089 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 09:36:44.233   313   887 D CommandListener: Clearing all IP addresses on wlan0
,08-30 09:36:44.249  1027  1531 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-30 09:36:44.245  8192  8192 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:44.255  8192  8192 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 09:36:44.269  1027  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 09:36:44.269  1027  1531 E WifiStateMachine: useWiFiOffloading() : false
08-30 09:36:44.269  1027  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 09:36:44.288  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-30 09:36:44.293  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:44.294  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 09:36:44.299  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:44.300  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:44.318  1027  1531 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 09:36:44.318  1027  1531 D WifiMonitor: connecting to supplicant
,08-30 09:36:44.322  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-30 09:36:44.322  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 09:36:44.322  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 09:36:44.322  6945  6945 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 09:36:44.327  8192  8192 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 09:36:44.347  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 09:36:44.351  6945  6945 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 09:36:44.351  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 09:36:44.351  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 09:36:44.351  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 09:36:44.351  6945  6945 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 09:36:44.351  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 09:36:44.352  6945  6945 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 09:36:44.387  8192  8192 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 09:36:44.388  8192  8192 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-30 09:36:44.391  1027  1089 D Tethering: InitialState.processMessage what=4
,08-30 09:36:44.410  1027  2005 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8210 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-30 09:36:44.413  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 09:36:44.469  8192  8192 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 09:36:44.512  1027  2009 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8232 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 09:36:44.515  8210  8230 W FormManager: Network not available. Please check & try again.
,08-30 09:36:44.526  8210  8231 V FormManager: Network unavailable.
,08-30 09:36:44.528  8210  8231 V FormManager: Network unavailable.
,08-30 09:36:44.540  8192  8192 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 09:36:44.543  8192  8192 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 09:36:44.544  1027  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 09:36:44.545  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 09:36:44.545  1027  1531 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 09:36:44.545  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 09:36:44.545  1027  8250 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 09:36:44.545  1027  8250 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-30 09:36:44.545  1027  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 09:36:44.545  1027  1531 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 09:36:44.546  1027  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:44.546  1027  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:44.546  1027  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:44.547  1027  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:44.547  1027  1531 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 09:36:44.547  1027  1531 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 09:36:44.548  1027  1531 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 09:36:44.548  1027  1531 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
,08-30 09:36:44.548  1027  1531 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 09:36:44.548  1027  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 09:36:44.548  1027  1531 E WifiStateMachine: useWiFiOffloading() : false
08-30 09:36:44.548  1027  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 09:36:44.549  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:44.549  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:44.549  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:44.549  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:44.549  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 09:36:44.549  1958  1958 D WfdService: Waiting for WifiP2p enabling
08-30 09:36:44.549  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:44.550  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 09:36:44.550  1027  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 09:36:44.551  1027  1531 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 09:36:44.551  1027  1531 D WifiNative-wlan0: SET update_config 1: returned true
08-30 09:36:44.551  1027  1531 D WifiConfigStore: Loading config and enabling all networks 
08-30 09:36:44.551  1027  1531 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 09:36:44.551  1027  1531 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 09:36:44.553  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:44.553  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:44.553  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:44.553  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:44.553  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:44.553  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:44.553  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:44.553  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:36:44.554  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:44.555  1027  1531 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 09:36:44.556  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:44.556  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:44.556  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:44.556  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:44.556  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:44.556  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:36:44.556  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:36:44.556  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:36:44.557  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:36:44.561  1027  1531 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 09:36:44.561  1027  1531 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 09:36:44.562  1027  1531 D WifiStateMachine: enableVerboseLogging : level 2
08-30 09:36:44.562  1027  1531 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 09:36:44.562  1027  1531 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 09:36:44.562  1027  1531 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 09:36:44.563  1027  1531 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 09:36:44.563  1027  1531 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 09:36:44.563  1027  1531 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 09:36:44.563  1027  1531 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 09:36:44.563  1027  1531 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 09:36:44.563  1027  1531 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 09:36:44.563  1027  1531 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 09:36:44.563  1027  1531 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 09:36:44.564  1027  1531 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 09:36:44.564  1027  1531 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 09:36:44.564  1027  1531 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-30 09:36:44.564  1027  1531 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 09:36:44.565  1027  1531 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 09:36:44.565  1027  1531 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 09:36:44.565  1027  1531 D WifiNative-HAL: Setting external_sim to 1
08-30 09:36:44.565  1027  1531 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 09:36:44.565  1027  1531 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 09:36:44.565  1027  1531 I WifiNative-HAL: startHal
08-30 09:36:44.565  1027  1531 D wifi    : setting scan oui 0xaf6ef320
08-30 09:36:44.565  1027  1531 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 09:36:44.565  1027  1531 I WifiNative-HAL: startHal
08-30 09:36:44.565  1027  1531 D wifi    : setting scan oui 0xaf6ef320
08-30 09:36:44.566  1027  1531 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 09:36:44.566  1027  1531 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 09:36:44.566  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 09:36:44.566  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 09:36:44.566  1027  1531 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 09:36:44.566  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 09:36:44.566  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 09:36:44.567  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 09:36:44.567  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 09:36:44.567  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 09:36:44.567  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 09:36:44.567  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 09:36:44.567  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 09:36:44.567  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 09:36:44.567  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 09:36:44.567  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 09:36:44.568  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 09:36:44.568  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 09:36:44.568  8192  8192 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 09:36:44.568  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 09:36:44.568  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 09:36:44.568  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 09:36:44.568  1027  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 09:36:44.569  1027  1531 E WifiNative: : [259,227,404 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 09:36:44.569  1027  1531 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 09:36:44.569  1027  1531 D WifiNative-wlan0: RECONNECT: returned true
08-30 09:36:44.569  1027  1531 D WifiNative-wlan0: doString: [STATUS]
08-30 09:36:44.569  1958  1958 D WfdsService: Supplicant Connection state is changed : true
08-30 09:36:44.570  1958  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 09:36:44.570  1958  2300 D WfdsService: Set the WFDS Monitor: true
08-30 09:36:44.570  1958  2300 D WfdsMonitor: WfdsMonitorThread create
08-30 09:36:44.570  1958  2300 D WfdsMonitor: WFDS Monitor is created and started
08-30 09:36:44.570  1958  2300 D WfdsService: WiFi: Supplicant connection re-established
08-30 09:36:44.570  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 09:36:44.570  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 09:36,:44.570  7800  7800 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:44.570  1027  1531 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 09:36:44.570  1027  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 09:36:44.571  1027  1531 D WifiNative-wlan0: SET ps 1: returned true
08-30 09:36:44.571  1958  8251 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 09:36:44.571  1027  1529 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.571  1958  8251 E CtrlSupplicant: Succeed to open control connection
08-30 09:36:44.571  1958  8251 E CtrlSupplicant: Succeed to open monitor connection
08-30 09:36:44.571  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 09:36:44.571  1958  8251 D WfdsMonitor: Supplicant connection established
08-30 09:36:44.571  1027  1027 D RttService: SCAN_AVAILABLE : 3
08-30 09:36:44.571  1027  1531 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 09:36:44.571  1958  2300 D WfdsService: Connected to the supplicant for wfds
08-30 09:36:44.571  1027  1548 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.571  1027  1548 I WifiNative-HAL: startHal
08-30 09:36:44.571  1027  1548 D wifi    : getting scan capabilities on interface[1] = 0xaf6ef320
08-30 09:36:44.571  1027  1548 D wifi    : failed to get capabilities : -3
08-30 09:36:44.571  1027  1548 E WifiScanningService: could not get scan capabilities
08-30 09:36:44.572  1027  1531 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 09:36:44.572  1027  1549 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.572  1027  1531 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 09:36:44.572   313   887 D CommandListener: Setting iface cfg
08-30 09:36:44.572   313   887 D CommandListener: Trying to bring up p2p0
08-30 09:36:44.572  1027  1531 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 09:36:44.572  1027  1529 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 09:36:44.572  1027  1529 D LGWifiP2pService: P2pEnablingState
08-30 09:36:44.572  1027  1529 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.572  1027  1529 D LGWifiP2pService: P2p socket connection successful
08-30 09:36:44.572  1027  1529 D LGWifiP2pService: P2pEnabledState
08-30 09:36:44.572  1027  1531 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 09:36:44.572  1027  1529 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 09:36:44.573  1027  1531 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 09:36:44.573  1027  1529 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 09:36:44.573  1027  1531 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 09:36:44.573  1027  1531 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 09:36:44.573  8192  8192 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 09:36:44.573  1027  1529 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 09:36:44.573  1027  1529 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 09:36:44.573  1027  1531 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 09:36:44.573  1027  1529 D WifiNative-p2p0: SET device_name G3: returned true
08-30 09:36:44.573  1027  1529 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 09:36:44.573  1027  1529 D LGWifiP2pService: before postfix = G3
08-30 09:36:44.573  1027  1529 D WifiServerServiceExt: postfix byte check : 2
08-30 09:36:44.573  1027  1529 D LGWifiP2pService: after postfix = G3
08-30 09:36:44.574  1027  1529 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 09:36:44.574  1027  1531 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 09:36:44.574  1027  1529 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 09:36:44.574  1027  1529 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 09:36:44.574  1027  1531 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 09:36:44.574  1027  1531 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 09:36:44.574  1027  1529 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 09:36:44.574  1027  1529 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 09:36:44.574  8192  8192 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 09:36:44.574  1027  1529 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 09:36:44.574  1027  1529 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 09:36:44.575  1027  1529 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 09:36:44.575  1027  1529 D WifiNative-HAL: p2pGetDeviceAddress
08-30 09:36:44.575  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 09:36:44.575  1958  1958 D WfdsService: WifiP2pState is changed : true
08-30 09:36:44.575  1027  1529 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 09:36:44.575  1027  1531 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 09:36:44.575  1027  1529 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 09:36:44.575  1027  1529 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 09:36:44.575  1027  1529 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 09:36:44.575  1027  1529 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 09:36:44.576  1027  1529 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 09:36:44.576  1027  1529 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 09:36:44.576  1027  1529 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 09:36:44.576  1027  1529 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 09:36:44.577  1027  1531 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 09:36:44.577  1027  1531 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 09:36:44.577  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 09:36:44.577  1958  2300 D WfdsService: Receive the WFDS_ENABLE Method
08-30 09:36:44.577  1958  2300 D WfdsService: Set the WFDS Monitor: true
08-30 09:36:44.577  1958  2300 D WfdsService: Connected to the supplicant for wfds
08-30 09:36:44.577  1958  2300 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 09:36:44.577  1958  1958 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 09:36:44.578  1958  1958 D WfdsService: isConnected: false
08-30 09:36:44.578  1958  1958 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 09:36:44.578  1958  1958 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 09:36:44.578  1958  1958 D WfdsService: Update P2p Interface State: 3
08-30 09:36:44.583  8192  8192 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 09:36:44.584  1027  1529 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 09:36:44.584  1027  1529 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 09:36:44.584  1027  1529 D LGWifiP2pService: InactiveState
08-30 09:36:44.584  1027  1529 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.584  1958  2300 D WfdsService: selectPreferredScanChannel [36]
08-30 09:36:44.584  1958  2300 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 09:36:44.584  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.584  1027  1529 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 09:36:44.585  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 09:36:44.585  8192  8192 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:44.585  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 09:36:44.585  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:44.585  1027  8250 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:44.585  8192  8192 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 09:36:44.585  1027  8250 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:44.586  8192  8192 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.586  1027  1531 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 09:36:44.586  8192  8192 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.586  1027  1531 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 09:36:44.586  1958  8251 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:44.586  1958  8251 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:44.586  1027  1531 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 09:36:44.586  1027  8250 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:44.587  1027  8250 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.587  1027  8250 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.587  1027  8250 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.587  1027  1531 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 09:36:44.587  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 09:36:44.587  1027  8250 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:44.587  1027  8250 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.587  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 09:36:44.587  1027  8250 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.587  1027  8250 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.587  8192  8192 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:44.587  8192  8192 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 09:36:44.587  8192  8192 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.588  8192  8192 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.588  1958  8251 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 09:36:44.588  1958  8251 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:44.588  1958  8251 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:44.588  1027  1529 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  8250 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 09:36:44.589  1027  8250 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  1027 E WifiServerServiceExt: No p2p device connected
08-30 09:36:44.589  1027  8250 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  8250 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  8250 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:44.589  1027  8250 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.589  1027  8250 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  8250 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  8250 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 09:36:44.589  1027  1529 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:44.589  1027  8250 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.589  1027  8250 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.589  1027  8250 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 09:36:44.590  1958  2300 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 09:36:44.590  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 09:36:44.590  8192  8192 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 09:36:44.590  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 09:36:44.590  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 09:36:44.590  1027  8250 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 09:36:44.590  1027  8250 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 09:36:44.591  1027  1531 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 09:36:44.591  1027  1531 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 09:36:44.591  1027  1531 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 09:36:44.591  1027  1531 D WifiNative-wlan0: doBoolean: SCAN
08-30 09:36:44.591  1027  1531 D WifiNative-wlan0: SCAN: returned false
08-30 09:36:44.591  1027  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=259250  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 09:36:44.592  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=259251  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 09:36:44.593  1027  1531 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 09:36:44.593  1027  1531 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 09:36:44.593  1027  1531 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 09:36:44.593  1027  1531 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 09:36:44.594  1027  1531 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 09:36:44.594  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:44.594  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:44.594  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 09:36:44.594  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:44.594  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:44.595  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:44.595  1027  1027 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 09:36:44.595  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:44.609  8232  8232 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 09:36:44.612  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 09:36:44.616  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:44.617  1027  2005 I ActivityManager: Killing 7237:com.android.chrome/u0a57 (adj 15): empty #17
08-30 09:36:44.672  1027  1943 W libprocessgroup: failed to open /acct/uid_10057/pid_7237/cgroup.procs: No such file or directory
,08-30 09:36:44.700  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 09:36:44.700  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-30 09:36:44.700  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 09:36:44.700  6945  6945 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 09:36:44.703  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 09:36:44.705  6945  6945 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 09:36:44.706  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 09:36:44.706  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 09:36:44.706  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 09:36:44.706  6945  6945 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 09:36:44.706  6945  6945 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 09:36:44.719  8232  8232 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 09:36:44.724  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 09:36:44.731  8210  8255 W FormManager: Network not available. Please check & try again.
,08-30 09:36:44.735  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:44.746  8210  8256 V FormManager: Network unavailable.
,08-30 09:36:44.756  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 09:36:44.756  8210  8256 V FormManager: Network unavailable.
08-30 09:36:44.757  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 09:36:44.760  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 09:36:44.765  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:44.777  4307  8257 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 09:36:44.778  4307  8258 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 09:36:44.779  4307  8258 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 09:36:44.825  1027  1044 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8259 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 09:36:44.968  8259  8259 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 09:36:44.968  8259  8259 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 09:36:44.978  8259  8259 V [BNRBootReceiver]: Boot Receiver Return
,08-30 09:36:44.980  8259  8259 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 09:36:45.036  1027  1758 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8277 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 09:36:45.037  1027  1758 I ActivityManager: Killing 7266:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-30 09:36:45.109  1027  1043 W libprocessgroup: failed to open /acct/uid_10062/pid_7266/cgroup.procs: No such file or directory
,08-30 09:36:45.132  8277  8277 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 09:36:45.156  8277  8277 D PluginManager: init()
,08-30 09:36:45.267  8192  8192 E wpa_supplicant: USIM:  scard_init function
08-30 09:36:45.268  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 09:36:45.268  1027  8250 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 09:36:45.268  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 09:36:45.268  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-30 09:36:45.268  1027  8250 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-30 09:36:45.269  1027  1531 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 09:36:45.269  8192  8192 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 09:36:45.269  1027  1531 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 09:36:45.270  1027  1531 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 09:36:45.270  1027  1531 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 09:36:45.270  1027  1531 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 09:36:45.274  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 09:36:45.274  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-30 09:36:45.293  1027  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=259951  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 09:36:45.297  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:45.297  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 09:36:45.299  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.299  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.299  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 09:36:45.301  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.302  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=259960  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 09:36:45.303  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:36:45.303  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.303  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 09:36:45.304  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:45.304  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 09:36:45.321  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:45.321  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:45.323  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 09:36:45.389  8192  8192 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 09:36:45.392  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 09:36:45.392  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 09:36:45.393  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 09:36:45.393  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 09:36:45.393  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 09:36:45.393  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 09:36:45.400  1027  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=260058  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 09:36:45.400  1027  1089 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 09:36:45.404  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=260062  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 09:36:45.405  1027  1531 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=260063
08-30 09:36:45.406  1027  1531 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=260064
08-30 09:36:45.406  1027  1531 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=260065
08-30 09:36:45.407  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=260065
08-30 09:36:45.407  1027  1531 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=260066
08-30 09:36:45.408  1027  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=260066  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 09:36:45.410  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:45.410  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:45.411  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.411  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.411  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.411  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 09:36:45.412  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 09:36:45.413  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 09:36:45.413  8192  8192 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 09:36:45.413  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 09:36:45.413  8192  8192 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 09:36:45.413  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 09:36:45.413  1027  8250 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 09:36:45.413  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 09:36:45.413  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 09:36:45.413  1027  8250 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 09:36:45.414  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=260072  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 09:36:45.414  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 09:36:45.414  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 09:36:45.417  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from ,android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:36:45.417  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.417  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 09:36:45.418  1027  1531 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:45.418  1027  1531 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:45.419  1027  1531 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:45.419  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:45.420  1027  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 09:36:45.421  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:45.421  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 09:36:45.422  1027  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=260080  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 09:36:45.423  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=260081  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 09:36:45.423  1027  1531 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=260082
08-30 09:36:45.424  1027  1531 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=260082
08-30 09:36:45.424  1027  1531 D WifiNative-wlan0: doString: [STATUS]
08-30 09:36:45.424  1027  8250 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 09:36:45.424  1027  8250 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 09:36:45.428  1027  1531 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 09:36:45.429  1027  1531 I WifiServiceExtension: setVHTCapabilityType  : false
,08-30 09:36:45.433  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:45.433  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:45.434  1027  1531 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 09:36:45.434  1027  1531 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 09:36:45.435  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.437  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.437  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.437  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 09:36:45.439  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.439  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.440  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 09:36:45.443  1027  1531 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-30 09:36:45.443  1027  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 09:36:45.443  1027  1537 D ConnectivityService: Got NetworkAgent Messenger
08-30 09:36:45.443  1027  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 09:36:45.443  1027  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 09:36:45.443  1027  1537 D ConnectivityService: NetworkAgent connected
08-30 09:36:45.444  1027  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 09:36:45.444  1027  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 09:36:45.448  1027  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 09:36:45.448  1027  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 09:36:45.448  1027  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 09:36:45.448  1027  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 09:36:45.448  1027  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 09:36:45.453  1027  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 09:36:45.454   313   887 D CommandListener: Setting iface cfg
08-30 09:36:45.455  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:45.456  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:45.456  1027  1531 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 09:36:45.456  1027  8298 D DhcpStateMachine: StoppedState
08-30 09:36:45.456  1027  8298 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:45.456  1027  8298 D DhcpStateMachine: WaitBeforeStartState
08-30 09:36:45.456  1027  1531 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=260115  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 09:36:45.456  1027  1531 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=260115  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 09:36:45.457  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=260115  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 09:36:45.457  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.457  1027  1531 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=260116  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 09:36:45.458  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:45.458  1027  1027 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 09:36:45.458  1027  1531 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=260116  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 09:36:45.458  1027  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=260117  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 09:36:45.459  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:29234] from screen [on:0 period:-631177069] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:36:45.459  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:45.459  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:45.460  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_PO,LL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-631177068] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:36:45.460  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 09:36:45.460  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.464  1027  1537 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-30 09:36:45.465  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:45.465  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:45.465  1027  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:45.466  1027  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:45.466  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:45.466  1027  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 09:36:45.467  1027  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 09:36:45.467  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=205,0,0
08-30 09:36:45.467  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=205,0,0
08-30 09:36:45.467  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 09:36:45.468  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 09:36:45.468  1027  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
,08-30 09:36:45.468  1027  1531 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 09:36:45.469  1027  1531 D WifiNative-wlan0: SET ps 0: returned true
08-30 09:36:45.469  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 09:36:45.469  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 09:36:45.469  1027  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 09:36:45.470  1027  1529 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@61765bb target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:45.470  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@61765bb target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:45.470  1027  8298 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:45.470  1027  8298 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 09:36:45.470  1027  1531 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,08-30 09:36:45.470  1027  1531 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 09:36:45.470  1027  1531 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 09:36:45.471   313   887 D CommandListener: Setting iface cfg
08-30 09:36:45.472   313   887 D CommandListener: Trying to bring up wlan0
08-30 09:36:45.472  1027  1531 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 09:36:45.473  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-30 09:36:45.473  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-30 09:36:45.473  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 09:36:45.473  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 09:36:45.474  1027  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 09:36:45.474  1027  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 09:36:45.474  8192  8192 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 09:36:45.474  1027  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 09:36:45.474  1027  1531 D WifiNative-wlan0: doBoolean: SET ps 1
,08-30 09:36:45.477  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 09:36:45.477  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 09:36:45.477  1027  1529 D LGWifiP2pService: InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:45.477  1027  1529 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:45.479  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.495  1027  1531 D WifiNative-wlan0: SET ps 1: returned true
08-30 09:36:45.495  1027  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-30 09:36:45.495  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:45.496  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:45.496  1027  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:45.496  1027  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:45.496  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:45.497  1027  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:45.497  1027  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 09:36:45.497  1027  1531 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 09:36:45.497  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 09:36:45.498  1027  1531 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 09:36:45.498  1027  1537 D ConnectivityService: ignoring duplicate network state non-change
08-30 09:36:45.500  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:45.500  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:45.501  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.502  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.502  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.503  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 09:36:45.503  1027  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 09:36:45.504  1027  1537 D ConnectivityService: Adding iface wlan0 to network 102
08-30 09:36:45.506  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.506  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.506  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 09:36:45.507  1027  1531 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 09:36:45.511  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-30 09:36:45.515  1958  1958 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 09:36:45.518  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.518  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.518  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 09:36:45.519  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 09:36:45.525  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.525  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:36:45.525  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 09:36:45.539  1027  1537 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 09:36:45.539  1027  1537 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 09:36:45.540  1027  1537 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 09:36:45.540   313   887 E Netd    : netlink response contains error (File exists)
08-30 09:36:45.540  1027  1537 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 09:36:45.541  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:45.541  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 09:36:45.541  1027  1537 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 09:36:45.541  1027  1537 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 09:36:45.541  1027  1537 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-30 09:36:45.542  1027  1537 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 09:36:45.542  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.542  1027  1537 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 09:36:45.542  1027  1537 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 09:36:45.542  1027  1537 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 09:36:45.542  1027  1537 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 09:36:45.542  1027  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:45.542  1027  1537 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 09:36:45.542  1027  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:45.542  1027  1537 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 09:36:45.542  1027  1537 D ConnectivityService: currentScore = 0, newScore = 20
08-30 09:36:45.542  1027  1537 D ConnectivityService:    accepting network in place of null
08-30 09:36:45.542  1027  1537 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:45.543  1027  1531 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:45.543  1027  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 09:36:45.543  1027  1537 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 09:36:45.543  1027  1537 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgen,tInfo [WIFI () - 102] isDefaultNetwork=true
08-30 09:36:45.543  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 09:36:45.544  1027  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:45.544  1027  1537 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 09:36:45.544  1027  8297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:45.544  1027  8297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 09:36:45.544  1027  8297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 09:36:45.545  1027  8297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 09:36:45.545  1027  1537 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 09:36:45.546  1871  1871 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:45.546  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 09:36:45.547  1027  1537 D ConnectivityService: validation of new default Network = false
08-30 09:36:45.547  1027  1027 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 09:36:45.547  1027  1537 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 09:36:45.547  1027  1537 D DSQN    : enableDataServiceNotify 
08-30 09:36:45.547  1027  1537 D DSQN    : start dsqn bin
08-30 09:36:45.548  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 09:36:45.548  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 09:36:45.548  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 09:36:45.549  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:45.550  1596  1596 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 09:36:45.550  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.551   313  8308 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 09:36:45.551   313  8308 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-30 09:36:45.554  1027  1537 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 09:36:45.554  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:45.554  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:45.554  1027  1537 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:45.555  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:45.555  1596  1596 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 09:36:45.555  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.556  1596  1806 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 09:36:45.557  1027  1528 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 09:36:45.555  8309  8309 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:45.555  8309  8309 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:45.573  8309  8309 E DSQN    : DSQN ssw
,08-30 09:36:45.578  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 09:36:45.579  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.579  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.600   313  8308 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 09:36:45.626   313   886 D LGDataListener: argv[0]=dsqncommand
,08-30 09:36:45.627   313   886 D LGDataListener: argv[1]=wlan0
,08-30 09:36:45.627   313   886 D LGDataListener: argv[2]=1
08-30 09:36:45.627   313   886 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 09:36:45.627  1027  1087 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 09:36:45.627  1027  1087 D DSQN    : start to monitor internet connection
08-30 09:36:45.648  8277  8277 W ExternalStrings: load override strings
08-30 09:36:45.648  8277  8277 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 09:36:45.648  8277  8277 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 09:36:45.650  8277  8277 D StatusProvider: onCreate
08-30 09:36:45.653  1027  8297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 07:36:45 GMT], X-Android-Received-Millis=[1472542605652], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472542605625]}
08-30 09:36:45.654  1027  8297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 09:36:45.654  1027  8297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 09:36:45.654  1027  1537 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 09:36:45.655  1027  1537 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 09:36:45.655  1027  1537 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 09:36:45.655  1027  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:45.655  1027  1537 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-30 09:36:45.655  1027  1537 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 09:36:45.655  1027  1537 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 09:36:45.656  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:45.656  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:45.657  1027  1537 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:45.657  1596  1806 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 09:36:45.659  1027  1537 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:45.660  1027  1531 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:45.660  1027  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 09:36:45.660  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 09:36:45.660  1871  1871 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:45.661  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 09:36:45.674  1027  8298 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 09:36:45.677  1027  8298 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 09:36:45.678  1027  8298 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-30 09:36:45.675  8315  8315 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:45.675  8315  8315 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 09:36:45.689  8315  8315 I dhcpcd  : version 5.5.6 starting
08-30 09:36:45.690  8315  8315 E dhcpcd  : get_duid: m
08-30 09:36:45.690  8315  8315 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 09:36:45.690  8315  8315 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-30 09:36:45.694  8277  8277 V Signer  : override build config not found
08-30 09:36:45.694  8277  8277 D Signer  : value of property debug is false
08-30 09:36:45.696  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 09:36:45.699  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.700  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 09:36:45.737  8315  8315 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-30 09:36:45.737  8315  8315 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 09:36:45.737  8315  8315 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 09:36:45.737  8315  8315 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 09:36:45.737  8315  8315 D dhcpcd  : wlan0: sending REQUEST (xid 0x1a0dd478), next in 4.67 seconds
08-30 09:36:45.751  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-30 09:36:45.751  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-30 09:36:45.751  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-30 09:36:45.752  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 09:36:45.752  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 09:36:45.752  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-30 09:36:45.753  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 09:36:45.753  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
,08-30 09:36:45.753  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 09:36:45.753  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 09:36:45.754  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 09:36:45.754  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 09:36:45.754  8277  8277 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-30 09:36:45.766  8277  8277 V LGMDMManager: Create singleton instance
,08-30 09:36:45.813  8315  8315 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 09:36:45.819  8277  8277 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-30 09:36:45.888  8315  8315 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 09:36:45.889  8315  8315 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 09:36:45.889  8315  8315 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 09:36:45.890  8315  8315 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-30 09:36:45.890  8315  8315 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 09:36:45.891  8315  8315 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 09:36:45.892  8315  8315 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 09:36:45.892  8315  8315 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 09:36:45.921  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 09:36:45.926  8277  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 09:36:45.934  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:45.943  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:45.994  1027  2009 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8334 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 09:36:45.995  1027  2009 I ActivityManager: Killing 7283:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-30 09:36:46.089  1027  2096 W libprocessgroup: failed to open /acct/uid_10085/pid_7283/cgroup.procs: No such file or directory
,08-30 09:36:46.105  8277  8324 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 09:36:46.108  8334  8334 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 09:36:46.125  8334  8334 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-30 09:36:46.161  8334  8334 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-30 09:36:46.161  8334  8334 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 09:36:46.161  8334  8334 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 09:36:46.162  8334  8334 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 09:36:46.162  8334  8334 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 09:36:46.164  8334  8334 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-30 09:36:46.168  8334  8334 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-30 09:36:46.172  8334  8334 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:46.174  8334  8334 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:46.184  8334  8334 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 09:36:46.185  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 09:36:46.187  8334  8334 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 09:36:46.188  6945  6945 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 09:36:46.190  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.191  8277  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 09:36:46.192  8334  8334 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 09:36:46.197  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:46.202  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:46.206  8334  8334 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:46.206  8334  8334 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:46.207  8334  8334 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 09:36:46.209  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 09:36:46.209  8277  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 09:36:46.215  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 09:36:46.219  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:46.223  8334  8334 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 09:36:46.223  8334  8334 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:46.224  8334  8334 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 09:36:46.226  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 09:36:46.226  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 09:36:46.226  6945  6945 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 09:36:46.226  6945  6945 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 09:36:46.226  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 09:36:46.227  6945  6945 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 09:36:46.227  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 09:36:46.227  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 09:36:46.227  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 09:36:46.227  6945  6945 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 09:36:46.227  6945  6945 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 09:36:46.227  6945  6945 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 09:36:46.231  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.231  8277  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 09:36:46.242  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:46.247  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:46.252  8334  8334 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:46.252  8334  8334 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:46.252  8334  8334 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 09:36:46.254  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.254  8277  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 09:36:46.260  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 09:36:46.264  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:46.269  8334  8334 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 09:36:46.269  8334  8334 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:46.269  8334  8334 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 09:36:46.272  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.272  8277  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 09:36:46.277  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:46.282  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:46.284  1027  8298 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 09:36:46.285  1027  8298 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 09:36:46.285  1027  8298 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 09:36:46.285  1027  8298 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 09:36:46.285  1027  8298 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 09:36:46.285  1027  8298 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 09:36:46.285  1027  8298 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 09:36:46.285  1027  8298 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 09:36:46.286  1027  8298 D DhcpStateMachine: RunningState
08-30 09:36:46.286  8277  8324 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:46.286  8277  8324 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 09:36:46.290  8334  8334 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:46.290  8334  8334 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:46.290  8334  8334 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 09:36:46.292  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 09:36:46.292  8277  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 09:36:46.300  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 09:36:46.303  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:46.308  8334  8334 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 09:36:46.310  8334  8334 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:46.310  8334  8334 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 09:36:46.318  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.318  8277  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 09:36:46.329  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:46.333  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 09:36:46.339  8334  8334 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:46.339  8334  8334 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:46.343  8334  8334 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 09:36:46.348  8277  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 09:36:46.350  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.356  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:46.363  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:46.370  8334  8334 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:46.371  8334  8334 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:46.371  8334  8334 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 09:36:46.374  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.375  8277  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 09:36:46.379  8232  8232 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 09:36:46.383  8232  8232 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 09:36:46.386  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:46.392  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:46.400  8334  8334 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:46.401  8334  8334 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:46.402  8334  8334 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 09:36:46.403  8334  8334 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 09:36:46.403  8334  8334 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 09:36:46.409  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.409  8277  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 09:36:46.413  8232  8232 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 09:36:46.413  8232  8232 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 09:36:46.414  8277  8324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-30 09:36:46.416  6945  6945 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 09:36:46.422  6945  6945 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 09:36:46.429  8334  8334 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 09:36:46.429  8334  8334 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 09:36:46.430  8334  8334 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 09:36:46.431  8334  8334 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 09:36:46.431  8334  8334 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 09:36:46.434  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 09:36:46.441  8334  8334 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-30 09:36:46.442  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-30 09:36:46.442  8334  8334 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 09:36:46.445  8277  8324 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-30 09:36:46.457  8277  8324 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-30 09:36:46.459  8277  8324 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-30 09:36:46.468  8277  8324 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 09:36:46.469  8277  8324 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 09:36:46.470  8277  8324 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-30 09:36:46.474  8277  8324 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-30 09:36:46.478  8277  8324 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-30 09:36:46.480  8334  8334 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:46.481  8334  8334 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 09:36:46.488  8334  8334 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 09:36:46.489  8334  8334 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 09:36:46.489  8334  8334 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 09:36:46.489  8334  8334 V SoundPool: doLoad: loading sample sampleID=1
08-30 09:36:46.489  8334  8334 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-30 09:36:46.492  8334  8379 V SoundPool: Start decode
08-30 09:36:46.492  8334  8379 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 09:36:46.493  7739  7739 D UEI.SmartControl: QS Service created
08-30 09:36:46.493  8334  8334 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 09:36:46.495   318  4036 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 09:36:46.495   318  4036 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 09:36:46.495   318  4036 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 09:36:46.496   318  4036 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 09:36:46.496   318  4036 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 09:36:46.496   318  4036 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 09:36:46.496   318  4036 V MediaPlayerService: player type = 3
08-30 09:36:46.496   318  4036 V AwesomePlayer: AwesomePlayer create()
08-30 09:36:46.496   318  4036 V AwesomePlayer: reset_l() 
08-30 09:36:46.497   318  4036 V AwesomePlayer: cancelPlayerEvents
08-30 09:36:46.497   318  4036 V AwesomePlayer: setAudioSink() 
,08-30 09:36:46.497   318  4036 V AwesomePlayer: reset_l() 
08-30 09:36:46.497   318  4036 V AudioCache: notify(0xb5474780, 8, 0, 0)
08-30 09:36:46.497   318  4036 V AudioCache: ignored
08-30 09:36:46.497   318  4036 V AwesomePlayer: cancelPlayerEvents
08-30 09:36:46.497   318  4036 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 09:36:46.497   318  4036 V AwesomePlayer: setDataSource_l dataSource
08-30 09:36:46.497   318  4036 V LGParserOSAL: SniffLGParser start
08-30 09:36:46.498   318  4036 V LGParserOSAL: MainType:5, SubType=0
08-30 09:36:46.498   318  4036 V LGParserOSAL: #### check Mime : application/ogg
08-30 09:36:46.498   318  4036 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 09:36:46.498   318  4036 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 09:36:46.499  8334  8334 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 09:36:46.500  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 09:36:46.513  7739  7739 I UEI.SmartControl: Service initServices...
08-30 09:36:46.513  7739  7739 D UEI.SmartControl: QS start get config
08-30 09:36:46.519  8334  8334 V LGMDMManager: Create singleton instance
,08-30 09:36:46.545   318  4036 V LGParserOSAL: supported mime: application/ogg
08-30 09:36:46.545   318  4036 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 09:36:46.545   318  4036 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 09:36:46.545   318  4036 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 09:36:46.545   318  4036 V AwesomePlayer: AudioTrack Setting
08-30 09:36:46.545   318  4036 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 09:36:46.545   318  4036 V AwesomePlayer: setAudioSource() 
08-30 09:36:46.545   318  4036 V MediaPlayerService: prepare
08-30 09:36:46.545   318  4036 V AwesomePlayer: prepareAsync_l() 
08-30 09:36:46.545   318  4036 V MediaPlayerService: wait for prepare
08-30 09:36:46.545   318  8380 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 09:36:46.545   318  8380 V AwesomePlayer: initAudioDecoder() 
08-30 09:36:46.545   318  8380 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 09:36:46.545   318  8380 V AudioSystem: isOffloadSupported()
08-30 09:36:46.545   318  8380 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 09:36:46.545   318  8380 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 09:36:46.545   318  8380 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 09:36:46.545   318  8380 V AwesomePlayer: getUseOffload() = 0 
08-30 09:36:46.545   318  8380 V OMXCodec: OMXCodec::Create
08-30 09:36:46.545   318  8380 V OMXCodec: findMatchingCodecs()
08-30 09:36:46.545   318  8380 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 09:36:46.545   318  8380 V OMXCodec: matchingCodecs.size()=1
08-30 09:36:46.545   318  8380 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 09:36:46.547   318  8380 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 09:36:46.547   318  8380 V LGCodecAdapter: LG Codec Adapter start
08-30 09:36:46.547   318  8380 V OMXCodec: OMXCodec Createtor
08-30 09:36:46.547   318  8380 V OMXCodec: setComponentRole
08-30 09:36:46.547   318  8380 V OMXCodec: configureCodec protected=0
08-30 09:36:46.547   318  8380 V LGCodecAdapter: called getLGCodecSpecificData
08-30 09:36:46.547   318  8380 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 09:36:46.547   318  8380 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 09:36:46.547   318  8380 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 09:36:46.547   318  8380 V LGCodecOSAL: Not support LGCodec
08-30 09:36:46.547   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 09:36:46.547   318  8380 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 09:36:46.547   318  8380 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 09:36:46.547   318  8380 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 09:36:46.547   318  8380 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 09:36:46.547   318  8380 V AudioSystem: isOffloadSupported()
08-30 09:36:46.547   318  8380 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 09:36:46.547   318  8380 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 09:36:46.547   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 09:36:46.547   318  8380 V OMXCodec: init()
08-30 09:36:46.547   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-30 09:36:46.547   318  8380 V OMXCodec: allocateBuffers
08-30 09:36:46.547   318  8380 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 09:36:46.547   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 09:36:46.548   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
08-30 09:36:46.548   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on input port
08-30 09:36:46.548   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on input port
08-30 09:36:46.548   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
08-30 09:36:46.548   318  8380 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 09:36:46.548   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 09:36:46.548   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b81f0 on output port
08-30 09:36:46.548   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b88d0 on output port
08-30 09:36:46.548   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8920 on output port
08-30 09:36:46.548   318  8380 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8970 on output port
08-30 09:36:46.548   318  8380 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 09:36:46.548   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 09:36:46.548   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 09:36:46.548   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
,08-30 09:36:46.549   318  8380 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 09:36:46.549   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 09:36:46.549   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 09:36:46.549   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 09:36:46.549   318  8380 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 09:36:46.549   318  8380 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 09:36:46.549   318  8380 V AudioCache: notify(0xb5474780, 5, 0, 0)
08-30 09:36:46.549   318  8380 V AudioCache: ignored
08-30 09:36:46.549   318  8380 V AudioCache: notify(0xb5474780, 1, 0, 0)
08-30 09:36:46.549   318  8380 V AudioCache: prepared
08-30 09:36:46.549   318  4036 V AudioCache: wait - success
08-30 09:36:46.549   318  4036 V MediaPlayerService: start
08-30 09:36:46.549   318  4036 V AwesomePlayer: play_l() 
08-30 09:36:46.549   318  4036 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 09:36:46.549   318  4036 V AwesomePlayer: createAudioPlayer_l
08-30 09:36:46.549   318  4036 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 09:36:46.549   318  4036 V AwesomePlayer: startAudioPlayer_l() 
08-30 09:36:46.549   318  4036 D AudioPlayer: start of Playback, useOffload 0
08-30 09:36:46.549   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 09:36:46.549   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 09:36:46.552   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 09:36:46.552   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 09:36:46.552   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 09:36:46.552   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 09:36:46.552   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 09:36:46.552   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974515696
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517456
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517536
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517616
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 09:36:46.553   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 09:36:46.554   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 09:36:46.554   318  8382 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 09:36:46.554   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 09:36:46.554   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8920 on output port
08-30 09:36:46.554   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b88d0 on output port
08-30 09:36:46.554   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] allocated b,uffer 0xb14b81f0 on output port
08-30 09:36:46.554   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-30 09:36:46.555   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 09:36:46.555   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 09:36:46.555   318  4036 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 09:36:46.556   318  4036 V AudioCache: notify(0xb5474780, 6, 0, 0)
08-30 09:36:46.556   318  4036 V AudioCache: ignored
08-30 09:36:46.556   318  4036 V MediaPlayerService: wait for playback complete
08-30 09:36:46.557   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.557   318  8383 V AudioCache: memcpy(0xac004000, 0xb57d6000, 4096)
08-30 09:36:46.559   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.559   318  8383 V AudioCache: memcpy(0xac005000, 0xb57d6000, 4096)
,08-30 09:36:46.560   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.560   318  8383 V AudioCache: memcpy(0xac006000, 0xb57d6000, 4096)
08-30 09:36:46.560   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.560   318  8383 V AudioCache: memcpy(0xac007000, 0xb57d6000, 4096)
08-30 09:36:46.560   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.560   318  8383 V AudioCache: memcpy(0xac008000, 0xb57d6000, 4096)
08-30 09:36:46.561   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.561   318  8383 V AudioCache: memcpy(0xac009000, 0xb57d6000, 4096)
08-30 09:36:46.562   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.562   318  8383 V AudioCache: memcpy(0xac00a000, 0xb57d6000, 4096)
08-30 09:36:46.562   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.562   318  8383 V AudioCache: memcpy(0xac00b000, 0xb57d6000, 4096)
08-30 09:36:46.562   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.562   318  8383 V AudioCache: memcpy(0xac00c000, 0xb57d6000, 4096)
08-30 09:36:46.562   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.562   318  8383 V AudioCache: memcpy(0xac00d000, 0xb57d6000, 4096)
08-30 09:36:46.563   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.563   318  8383 V AudioCache: memcpy(0xac00e000, 0xb57d6000, 4096)
,08-30 09:36:46.564   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.564   318  8383 V AudioCache: memcpy(0xac00f000, 0xb57d6000, 4096)
08-30 09:36:46.564   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.564   318  8383 V AudioCache: memcpy(0xac010000, 0xb57d6000, 4096)
08-30 09:36:46.565   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.565   318  8383 V AudioCache: memcpy(0xac011000, 0xb57d6000, 4096)
08-30 09:36:46.565   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.565   318  8383 V AudioCache: memcpy(0xac012000, 0xb57d6000, 4096)
08-30 09:36:46.566   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.566   318  8383 V AudioCache: memcpy(0xac013000, 0xb57d6000, 4096)
08-30 09:36:46.566   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.566   318  8383 V AudioCache: memcpy(0xac014000, 0xb57d6000, 4096)
08-30 09:36:46.567   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.567   318  8383 V AudioCache: memcpy(0xac015000, 0xb57d6000, 4096)
08-30 09:36:46.567   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.567   318  8383 V AudioCache: memcpy(0xac016000, 0xb57d6000, 4096)
08-30 09:36:46.568   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.568   318  8383 V AudioCache: memcpy(0xac017000, 0xb57d6000, 4096)
08-30 09:36:46.568   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.569   318  8383 V AudioCache: memcpy(0xac018000, 0xb57d6000, 4096)
08-30 09:36:46.569   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.569   318  8383 V AudioCache: memcpy(0xac019000, 0xb57d6000, 4096)
08-30 09:36:46.569   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.569   318  8383 V AudioCache: memcpy(0xac01a000, 0xb57d6000, 4096)
08-30 09:36:46.570   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.570   318  8383 V AudioCache: memcpy(0xac01b000, 0xb57d6000, 4096)
08-30 09:36:46.570   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.570   318  8383 V AudioCache: memcpy(0xac01c000, 0xb57d6000, 4096)
08-30 09:36:46.571   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.571   318  8383 V AudioCache: memcpy(0xac01d000, 0xb57d6000, 4096)
08-30 09:36:46.571   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.571   318  8383 V AudioCache: memcpy(0xac01e000, 0xb57d6000, 4096)
08-30 09:36:46.572   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.572   318  8383 V AudioCache: memcpy(0xac01f000, 0xb57d6000, 4096)
08-30 09:36:46.572   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.572   318  8383 V AudioCache: memcpy(0xac020000, 0xb57d6000, 4096)
08-30 09:36:46.573   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.573   318  8383 V AudioCache: memcpy(0xac021000, 0xb57d6000, 4096)
08-30 09:36:46.573   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.573   318  8383 V AudioCache: memcpy(0xac022000, 0xb57d6000, 4096)
08-30 09:36:46.574   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.574   318  8383 V AudioCache: memcpy(0xac023000, 0xb57d6000, 4096)
08-30 09:36:46.574   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.574   318  8383 V AudioCache: memcpy(0xac024000, 0xb57d6000, 4096)
08-30 09:36:46.575   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.575   318  8383 V AudioCache: memcpy(0xac025000, 0xb57d6000, 4096)
08-30 09:36:46.576   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.576   318  8383 V AudioCache: memcpy(0xac026000, 0xb57d6000, 4096)
08-30 09:36:46.576   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.576   318  8383 V AudioCache: memcpy(0xac027000, 0xb57d6000, 4096)
08-30 09:36:46.577   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.577   318  8383 V AudioCache: memcpy(0xac028000, 0xb57d6000, 4096)
08-30 09:36:46.577   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.577   318  8383 V AudioCache: mem,cpy(0xac029000, 0xb57d6000, 4096)
,08-30 09:36:46.578   318  8383 V AudioCache: write(0xb57d6000, 4096)
,08-30 09:36:46.578   318  8383 V AudioCache: memcpy(0xac02a000, 0xb57d6000, 4096)
08-30 09:36:46.578   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.578   318  8383 V AudioCache: memcpy(0xac02b000, 0xb57d6000, 4096)
08-30 09:36:46.579   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.579   318  8383 V AudioCache: memcpy(0xac02c000, 0xb57d6000, 4096)
08-30 09:36:46.579   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.580   318  8383 V AudioCache: memcpy(0xac02d000, 0xb57d6000, 4096)
08-30 09:36:46.580   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.580   318  8383 V AudioCache: memcpy(0xac02e000, 0xb57d6000, 4096)
08-30 09:36:46.581   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.581   318  8383 V AudioCache: memcpy(0xac02f000, 0xb57d6000, 4096)
08-30 09:36:46.581   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.581   318  8383 V AudioCache: memcpy(0xac030000, 0xb57d6000, 4096)
08-30 09:36:46.582   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.582   318  8383 V AudioCache: memcpy(0xac031000, 0xb57d6000, 4096)
08-30 09:36:46.582   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.582   318  8383 V AudioCache: memcpy(0xac032000, 0xb57d6000, 4096)
08-30 09:36:46.583   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.583   318  8383 V AudioCache: memcpy(0xac033000, 0xb57d6000, 4096)
08-30 09:36:46.583   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.583   318  8383 V AudioCache: memcpy(0xac034000, 0xb57d6000, 4096)
08-30 09:36:46.584   318  8383 V AudioCache: write(0xb57d6000, 4096)
08-30 09:36:46.584   318  8383 V AudioCache: memcpy(0xac035000, 0xb57d6000, 4096)
08-30 09:36:46.584   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 09:36:46.584   318  8383 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 09:36:46.584   318  8383 V AwesomePlayer: postAudioEOS() 
08-30 09:36:46.584   318  8383 V AudioCache: write(0xb57d6000, 280)
08-30 09:36:46.584   318  8383 V AudioCache: memcpy(0xac036000, 0xb57d6000, 280)
08-30 09:36:46.586   318  8380 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 09:36:46.586   318  8380 V AwesomePlayer: onStreamDone
08-30 09:36:46.586   318  8380 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 09:36:46.586   318  8380 V AudioCache: notify(0xb5474780, 2, 0, 0)
08-30 09:36:46.586   318  8380 V AudioCache: playback complete
08-30 09:36:46.586   318  8380 V AwesomePlayer: pause_l() 
08-30 09:36:46.586   318  8380 V AudioCache: notify(0xb5474780, 7, 0, 0)
08-30 09:36:46.586   318  8380 V AudioCache: ignored
08-30 09:36:46.586   318  8380 V AwesomePlayer: cancelPlayerEvents
08-30 09:36:46.586   318  8380 D AudioPlayer: Pause Playback at 1068125
08-30 09:36:46.586   318  4036 V AudioCache: wait - success
08-30 09:36:46.586   318  4036 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 09:36:46.588   318  4036 V AwesomePlayer: reset_l() 
08-30 09:36:46.588   318  4036 V AudioCache: notify(0xb5474780, 8, 0, 0)
08-30 09:36:46.588   318  4036 V AudioCache: ignored
08-30 09:36:46.588   318  4036 V AwesomePlayer: cancelPlayerEvents
08-30 09:36:46.588   318  4036 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 09:36:46.588   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 09:36:46.588   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 09:36:46.588   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 09:36:46.588   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 09:36:46.588   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 09:36:46.588   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 09:36:46.588   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex,=0
08-30 09:36:46.588   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
08-30 09:36:46.588   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 09:36:46.588   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 0
08-30 09:36:46.588   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 09:36:46.588   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 0
08-30 09:36:46.588   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 09:36:46.588   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
08-30 09:36:46.588   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b81f0 on port 1
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b88d0 on port 1
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8920 on port 1
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 09:36:46.589   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 09:36:46.589   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 09:36:46.589   318  8382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 09:36:46.589   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 09:36:46.589   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 09:36:46.589   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 09:36:46.590   318  4036 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 09:36:46.590   318  4036 D AudioPlayer: AudioPlayer releasing audio source
08-30 09:36:46.590   318  4036 D AudioPlayer: AudioPlayer done releasing audio source
08-30 09:36:46.590   318  4036 V AwesomePlayer: reset_l() 
08-30 09:36:46.590   318  4036 V AwesomePlayer: cancelPlayerEvents
08-30 09:36:46.590   318  4036 V AwesomePlayer: ~AwesomePlayer call
08-30 09:36:46.590   318  4036 V AwesomePlayer: reset_l() 
08-30 09:36:46.590   318  4036 V AwesomePlayer: cancelPlayerEvents
08-30 09:36:46.590  8334  8379 V SoundPool: close(31)
08-30 09:36:46.590  8334  8379 V SoundPool: pointer = 0x9fe77000, size = 205080, sampleRate = 48000, numChannels = 2
,08-30 09:36:46.617  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-30 09:36:46.618  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 09:36:46.620  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1378
08-30 09:36:46.622  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.638  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 09:36:46.640  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.641  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.642  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.643  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.645  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.646  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.648  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 09:36:46.650  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 09:36:46.961  7739  7739 I UEI.SmartControl: Supports setup maps: true
,08-30 09:36:46.967  7739  7739 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 09:36:46.967  7739  7739 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 09:36:46.967  7739  7739 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-30 09:36:46.967  7739  7739 I UEI.SmartControl: ### init IR Blaster...
08-30 09:36:46.972  7739  7739 D serial_port: Configuring serial port
08-30 09:36:46.972  7739  7739 E UEI.SmartControl: UEIBLaster setting for 616
08-30 09:36:46.973  7739  7739 I UEI.SmartControl: Setting serial record hearder size = 2
,08-30 09:36:46.973  7739  7739 I UEI.SmartControl: configuring settings for MAXQ616
08-30 09:36:46.973  7739  7739 I UEI.SmartControl: Get version...
,08-30 09:36:46.989  7739  8394 D UEI.SmartControl: serial port data available: 21
,08-30 09:36:47.015  7739  7739 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 09:36:47.015  7739  7739 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 09:36:47.015  7739  7739 I UEI.SmartControl: QS saving settings...
,08-30 09:36:47.018  7739  7739 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 09:36:47.025  1027  1531 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 09:36:47.051  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:47.051  1027  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:47.052  1027  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:47.052  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:47.053  1027  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 09:36:47.055  1027  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 09:36:47.055  1027  1537 D ConnectivityService: identical MTU - not setting
08-30 09:36:47.055  1027  1537 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 09:36:47.055  1027  1537 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 09:36:47.056  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 09:36:47.056  1027  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:47.056  1027  1537 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 09:36:47.057  1596  1806 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 09:36:47.078  7739  8394 D UEI.SmartControl: serial port data available: 4
,08-30 09:36:47.111  7739  7739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 09:36:47.125  7739  8400 I UEI.SmartControl: Device manager: loading config....
08-30 09:36:47.126  7739  8400 D UEI.SmartControl: ----------- loading internal config...
08-30 09:36:47.131  7739  7739 E UEI.SmartControl: Services init done
08-30 09:36:47.131  7739  7739 D UEI.SmartControl: QS Service init finished
,08-30 09:36:47.135  7739  7739 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 09:36:47.135  7739  7739 D UEI.SmartControl: QS Service version code: 201091
08-30 09:36:47.135  7739  7739 D UEI.SmartControl: Service requested: Control
08-30 09:36:47.139  7739  8400 E UEI.SmartControl: Loading SETTINGS...
08-30 09:36:47.141  7739  7739 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 09:36:47.144  8334  8334 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-30 09:36:47.148  7739  7754 I UEI.SmartControl: ------ IControl API: 11
08-30 09:36:47.148  7739  7754 D UEI.SmartControl: File observer start...
08-30 09:36:47.149  7739  7754 E UEI.SmartControl: IR Port is disabled: false
08-30 09:36:47.149  7739  7754 D UEI.SmartControl: Starting file observer...
08-30 09:36:47.149  7739  7754 I UEI.SmartControl: Registering callback...
08-30 09:36:47.150  7739  7739 D UEI.SmartControl: Internal service binding...
08-30 09:36:47.150  7739  7755 I UEI.SmartControl: ------ IControl API: 19
08-30 09:36:47.151  7739  7755 I UEI.SmartControl: Registering Services Ready callback...
08-30 09:36:47.155  7739  8400 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 09:36:47.172  7739  8399 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-30 09:36:47.176  8334  8352 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 09:36:47.177  8334  8377 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 09:36:47.177  8334  8377 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-30 09:36:47.177  8334  8334 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 09:36:47.178  7739  8399 D UEI.SmartControl: -----service ready thread exits
08-30 09:36:47.178  8334  8334 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 09:36:47.179  7739  7754 I UEI.SmartControl: ------ IControl API: 8
08-30 09:36:47.180  8334  8334 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 09:36:47.181  8334  8334 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 09:36:47.181  8334  8334 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 09:36:47.182  8334  8334 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 09:36:47.183  8334  8334 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 09:36:47.183  8334  8334 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 09:36:47.187  8334  8334 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-30 09:36:47.193  8334  8334 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 09:36:47.194  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 09:36:47.195  8334  8334 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 09:36:47.195  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 09:36:47.196  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 09:36:47.197  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 09:36:47.197  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 09:36:47.199  8334  8334 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472542607198]
08-30 09:36:47.204  8334  8334 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-30 09:36:47.209  1027  1043 I ActivityManager: Killing 7307:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-30 09:36:47.252  8334  8402 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 09:36:47.259  1027  1758 W libprocessgroup: failed to open /acct/uid_10093/pid_7307/cgroup.procs: No such file or directory
08-30 09:36:47.269  8334  8334 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-30 09:36:47.272  8334  8334 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 09:36:47.272  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 09:36:47.272  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 09:36:47.273  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 09:36:47.273  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 09:36:47.273  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 09:36:47.282  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 09:36:48.468  1027  1531 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=102.5, 0.0, 0.0  rx=91.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-631174061] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 09:36:48.471  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=102.5, 0.0, 0.0  rx=91.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-631174057] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:36:48.471  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 09:36:48.492  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 09:36:48.514  1027  1532 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-30 09:36:48.546  1027  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:48.566  1027  1089 D Tethering: MasterInitialState.processMessage what=3
,08-30 09:36:48.575  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:48.575  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:48.575  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:48.575  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:48.575  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:48.575  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:36:48.575  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:36:48.575  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:36:48.577  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:36:48.581  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:48.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:48.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:48.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:48.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:48.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:36:48.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:36:48.581  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:36:48.589  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:36:48.603  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-30 09:36:48.611  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 09:36:48.616  8277  8372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 09:36:48.629  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:36:48.629  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:48.629  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:36:48.629  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:48.629  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:48.629  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:36:48.629  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:36:48.629  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:36:48.630  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:36:48.633  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:36:48.633  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@274fc09e removed from the list
08-30 09:36:48.633  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:36:48.633  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:36:48.633  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:36:48.639  6817  8403 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-30 09:36:48.639  6817  8403 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 09:36:48.649  2251  2251 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:36:48.665  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 09:36:48.665  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:48.665  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 09:36:48.665  7128  7128 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 09:36:48.670  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
08-30 09:36:48.673  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3b634cfd
08-30 09:36:48.673  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 09:36:48.673  7128  7128 D AppUp4:CustFacade: isPhone : true
08-30 09:36:48.674  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
08-30 09:36:48.674  7128  7128 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 09:36:48.679  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:48.679  4307  4307 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 09:36:48.680  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 09:36:48.687  4307  4307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 09:36:48.692  3485  3485 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:48.715  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:48.715   313  8418 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 09:36:48.715   313  8418 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-30 09:36:48.710  3485  3485 V DownloadManager: DownloadService onCreate
,08-30 09:36:48.722  3485  8422 I DownloadManager: in removeSpuriousFiles
08-30 09:36:48.723  3485  8422 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-30 09:36:48.725  3485  8422 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@18471176 on behalf of 3485
08-30 09:36:48.726  3485  8422 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-30 09:36:48.726  3485  8422 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-30 09:36:48.726  3485  8422 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-30 09:36:48.726  3485  8422 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-30 09:36:48.726  3485  8422 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-30 09:36:48.726  3485  8422 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-30 09:36:48.726  3485  8422 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-30 09:36:48.727  3485  8422 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-30 09:36:48.727  3485  8422 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-30 09:36:48.727  3485  8422 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-30 09:36:48.727  3485  8422 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-30 09:36:48.728  3485  8422 I DownloadManager: in trimDatabase
08-30 09:36:48.729  3485  8422 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-30 09:36:48.730  4307  8421 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 09:36:48.734  4307  8421 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-30 09:36:48.736  3485  8422 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34d89377 on behalf of 3485
08-30 09:36:48.737  4307  8424 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:48.737  4307  8424 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 09:36:48.748  1027  1593 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8427 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 09:36:48.750  3485  3485 V DownloadManager: DownloadService onStartCommand
08-30 09:36:48.754  4307  8421 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-30 09:36:48.756  3485  8423 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-30 09:36:48.758   313  8418 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-30 09:36:48.761  3485  8423 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@118acf02 on behalf of 3485
,08-30 09:36:48.761  4307  4307 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-30 09:36:48.762  4307  4307 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-30 09:36:48.763  4307  4307 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-30 09:36:48.765  4307  4307 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-30 09:36:48.768  4307  4307 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-30 09:36:48.770  3485  8423 V DownloadManager: processing inserted download 1
08-30 09:36:48.772  3485  8423 V DownloadManager: processing inserted download 4
08-30 09:36:48.773  3485  8423 V DownloadManager: processing inserted download 7
08-30 09:36:48.774  3485  8423 V DownloadManager: processing inserted download 8
08-30 09:36:48.775  3485  8423 V DownloadManager: processing inserted download 9
08-30 09:36:48.776  3485  8423 V DownloadManager: processing inserted download 10
08-30 09:36:48.777  3485  8423 V DownloadManager: processing inserted download 11
,08-30 09:36:48.778  3485  8423 V DownloadManager: processing inserted download 12
08-30 09:36:48.779  3485  8423 V DownloadManager: processing inserted download 13
08-30 09:36:48.781  3485  8423 V DownloadManager: processing inserted download 14
08-30 09:36:48.782  3485  8423 V DownloadManager: processing inserted download 16
08-30 09:36:48.791  3485  3485 V DownloadManager: DownloadService onDestroy
,08-30 09:36:48.804  8427  8427 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 09:36:48.805  8427  8427 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 09:36:48.806  8427  8427 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 09:36:48.806  8427  8427 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 09:36:48.815  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 09:36:48.863  8427  8427 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 09:36:48.873  8427  8427 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 09:36:48.927  8427  8427 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 09:36:48.964  8427  8427 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 09:36:48.964  8427  8427 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:36:49.007  2251  8448 D GCM     : Connected
,08-30 09:36:49.038  2251  8448 D GCM     : Message class com.google.e.a.a.q
08-30 09:36:49.078  8427  8427 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 09:36:49.116  8427  8427 I HubEmail: JNI_OnLoad()
,08-30 09:36:49.116  8427  8427 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 09:36:49.116  8427  8427 I HubEmail: registerNatives()
08-30 09:36:49.116  8427  8427 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 09:36:49.116  8427  8427 I HubEmail: registerNativeMethods()
08-30 09:36:49.116  8427  8427 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 09:36:49.116  8427  8427 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 09:36:49.130  8427  8454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:36:49.151  3399  3399 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 09:36:49.151  3399  3399 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 09:36:49.151  3399  3399 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 09:36:49.151  3399  3399 D PhoneState: setPdpRejectCasuse : false
,08-30 09:36:49.155   313  8458 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 09:36:49.156   313  8458 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-30 09:36:49.213   313  8458 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-30 09:36:49.230  1027  1567 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8459 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 09:36:49.260  8210  8455 V FormManager: There are no updated forms. The schedule will be deleted.
08-30 09:36:49.262  8210  8455 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,08-30 09:36:49.289  1027  2005 I ActivityManager: Killing 7800:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 09:36:49.363  8459  8459 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:49.363  8459  8459 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:36:49.367  8459  8459 D PhoneMonitor: Register our PhoneStateListener
08-30 09:36:49.370  1027  2096 W libprocessgroup: failed to open /acct/uid_10072/pid_7800/cgroup.procs: No such file or directory
08-30 09:36:49.393  8459  8459 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 09:36:49.395  8459  8459 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 09:36:49.419  8459  8459 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-30 09:36:49.419  8459  8459 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 09:36:49.420  8459  8459 D TelephonyAutoProfiling: [parse] Load xml
08-30 09:36:49.422  8459  8459 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 09:36:49.422  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 09:36:49.422  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
,08-30 09:36:49.422  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 09:36:49.423  8459  8459 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 09:36:49.423  8459  8459 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 09:36:49.432  8459  8459 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 09:36:49.464  1027  1043 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8479 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 09:36:49.465  1027  1043 I ActivityManager: Killing 7852:com.android.contacts/u0a19 (adj 15): empty #17
,08-30 09:36:49.532  1027  1758 W libprocessgroup: failed to open /acct/uid_10019/pid_7852/cgroup.procs: No such file or directory
,08-30 09:36:49.566  1835  8496 I CheckinService: active receiver: enabled
,08-30 09:36:49.586  1835  8496 I CheckinService: Preparing to send checkin request
08-30 09:36:49.586  1835  8496 I EventLogService: Accumulating logs since 1472542570329
08-30 09:36:49.625  1835  8496 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 09:36:49.727   313  8499 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 09:36:49.727   313  8499 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-30 09:36:49.759   313  8499 D libc-netbsd: res_queryN name = www.google.com succeed
,08-30 09:36:49.763   313  8505 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 09:36:49.764   313  8505 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 09:36:49.764   313  8505 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 09:36:49.765  1027  1943 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8503 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 09:36:49.772  1027  1943 I ActivityManager: Killing 7876:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 09:36:49.830  1027  1533 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-30 09:36:49.889  1027  1043 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8522 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 09:36:49.891  1027  1593 W libprocessgroup: failed to open /acct/uid_10027/pid_7876/cgroup.procs: No such file or directory
08-30 09:36:49.916   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 28.610ms
,08-30 09:36:49.939   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 22.788ms
,08-30 09:36:49.957  8522  8522 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 09:36:49.957  8522  8522 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 09:36:49.967   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.400ms total 26.612ms
08-30 09:36:49.995  8522  8522 I MultiDex: VM with version 2.1.0 has multidex support
08-30 09:36:49.995  8522  8522 I MultiDex: install
,08-30 09:36:49.995  8522  8522 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 09:36:50.019  1027  1593 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8545 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 09:36:50.021  1027  1593 I ActivityManager: Killing 7936:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 09:36:50.070  1027  2096 W libprocessgroup: failed to open /acct/uid_10080/pid_7936/cgroup.procs: No such file or directory
,08-30 09:36:50.080  8522  8522 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-30 09:36:50.112  8545  8545 I art     : Almond Protected OAT
,08-30 09:36:50.149  1027  1531 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 09:36:50.151  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 09:36:50.152  1027  1531 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 09:36:50.153  1027  1531 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 09:36:50.154  1027  1531 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 09:36:50.156  1027  1531 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-30 09:36:50.187  8545  8545 D WeatherApplication: removeAccount
,08-30 09:36:50.188  8545  8545 D WeatherApplication: Account.length = 0
08-30 09:36:50.189  8545  8545 E WeatherApplication: OPERATOR:OPEN
08-30 09:36:50.194  8545  8545 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:50
08-30 09:36:50.196  8545  8545 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 09:36:50.197  8545  8545 D Weather.Utils: 2 : All the weather widget is gone.
08-30 09:36:50.198  8545  8545 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 09:36:50.200  8545  8545 D WeatherAncestor: connectivity changed - connection : true
08-30 09:36:50.201  8545  8545 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-30 09:36:50.210  8545  8545 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 09:36:50.210  8545  8545 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 09:36:50.211  8545  8545 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-30 09:36:50.232  8545  8545 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-30 09:36:50.232  8545  8545 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:36:50
,08-30 09:36:50.277  1027  2009 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8564 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 09:36:50.279  1027  2009 I ActivityManager: Killing 7898:com.android.vending/u0a44 (adj 15): empty #17
,08-30 09:36:50.376  1027  1968 W libprocessgroup: failed to open /acct/uid_10044/pid_7898/cgroup.procs: No such file or directory
08-30 09:36:50.378  8522  8538 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:50.379  8522  8538 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 09:36:50.462   279   390 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 09:36:50.462   279   390 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 09:36:50.462   279   390 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 09:36:50.463  8564  8582 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 09:36:50.465   279   390 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 09:36:50.465   279   390 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 09:36:50.465   279   390 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 09:36:50.466  8564  8582 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 09:36:50.476   279   390 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 09:36:50.476   279   390 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 09:36:50.476   279   390 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 09:36:50.476  8564  8584 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 09:36:50.480   279   390 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 09:36:50.480   279   390 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 09:36:50.480   279   390 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 09:36:50.481  8564  8584 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-30 09:36:50.536  8588  8588 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 09:36:50.581  8588  8588 I dex2oat : dex2oat took 45.538ms (threads: 4)
08-30 09:36:50.600  8522  8538 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 09:36:50.600  8522  8538 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 09:36:50.600  8522  8538 I Adreno-EGL: Build Date: 12/12/14 금
08-30 09:36:50.600  8522  8538 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 09:36:50.600  8522  8538 I Adreno-EGL: Remote Branch: 
08-30 09:36:50.600  8522  8538 I Adreno-EGL: Local Patches: 
08-30 09:36:50.600  8522  8538 I Adreno-EGL: Reconstruct Branch: 
,08-30 09:36:50.618  2251  2268 I art     : Explicit concurrent mark sweep GC freed 8878(590KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 1.731ms total 35.318ms
,08-30 09:36:50.703  8522  8538 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 09:36:50.703  8522  8538 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 09:36:50.703  8522  8538 I Adreno-EGL: Build Date: 12/12/14 금
08-30 09:36:50.703  8522  8538 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 09:36:50.703  8522  8538 I Adreno-EGL: Remote Branch: 
08-30 09:36:50.703  8522  8538 I Adreno-EGL: Local Patches: 
08-30 09:36:50.703  8522  8538 I Adreno-EGL: Reconstruct Branch: 
,08-30 09:36:50.781  1027  2009 I art     : Explicit concurrent mark sweep GC freed 80623(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 3.330ms total 115.931ms
,08-30 09:36:50.832  8564  8564 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 09:36:50.838  8564  8564 I LibraryLoader: Loading: webviewchromium
08-30 09:36:50.840  8564  8564 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5509-5511)
08-30 09:36:50.840  8564  8564 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 09:36:50.844  8564  8564 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {17ee71c}
08-30 09:36:50.844  8564  8564 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 09:36:50.845  8564  8564 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 09:36:50.851  8564  8564 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 09:36:50.852  8564  8564 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 09:36:50.860  8564  8564 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 09:36:50.860  8564  8564 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-30 09:36:50.862  8564  8564 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 09:36:50.867   318  1377 V AudioPolicyService: registerClient() client 0xb14b7580, uid 10093
08-30 09:36:50.869  8564  8616 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 09:36:50.876  8564  8564 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 09:36:50.876  8564  8564 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 09:36:50.876  8564  8564 I Adreno-EGL: Build Date: 12/12/14 금
08-30 09:36:50.876  8564  8564 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 09:36:50.876  8564  8564 I Adreno-EGL: Remote Branch: 
08-30 09:36:50.876  8564  8564 I Adreno-EGL: Local Patches: 
08-30 09:36:50.876  8564  8564 I Adreno-EGL: Reconstruct Branch: 
,08-30 09:36:50.915  8522  8538 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 09:36:50.915  8522  8538 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 09:36:50.915  8522  8538 I Adreno-EGL: Build Date: 12/12/14 금
08-30 09:36:50.915  8522  8538 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 09:36:50.915  8522  8538 I Adreno-EGL: Remote Branch: 
08-30 09:36:50.915  8522  8538 I Adreno-EGL: Local Patches: 
08-30 09:36:50.915  8522  8538 I Adreno-EGL: Reconstruct Branch: 
,08-30 09:36:50.933  8564  8564 I NSApplication: Starting up...
,08-30 09:36:50.957  1027  1943 I ActivityManager: Killing 7663:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-30 09:36:51.046  1027  1727 W libprocessgroup: failed to open /acct/uid_10037/pid_7663/cgroup.procs: No such file or directory
,08-30 09:36:51.077  2251  2251 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-30 09:36:51.089  2251  2251 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-30 09:36:51.089  2251  2251 D c       : Getting all permits...
08-30 09:36:51.089  2251  2251 D a       : Opening database...
08-30 09:36:51.092  2251  2251 D a       : Opening database auth.proximity.permit_store...
,08-30 09:36:51.093  2251  2251 D a       : Closing database...
08-30 09:36:51.111   313  8633 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 09:36:51.111   313  8633 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-30 09:36:51.145   313  8633 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 09:36:51.297  1835  8496 I CheckinTask: Sending checkin request (7863 bytes)
,08-30 09:36:51.498  1027  1531 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=55.8, 0.0, 0.0  rx=48.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-631171030] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:36:51.499  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=55.8, 0.0, 0.0  rx=48.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-631171029] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:36:51.499  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 09:36:51.535  1835  8496 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-30 09:36:51.555  1835  8496 I CheckinService: active receiver: disabled
,08-30 09:36:51.577  2251  2251 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 09:36:51.596  2251  2251 I GCM     : GCM config loaded
,08-30 09:36:51.622  8459  8459 V SetupWizard: Connected to Gservices successfully
,08-30 09:36:51.637  8334  8334 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 09:36:51.637  8334  8334 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1378
,08-30 09:36:51.647  6817  8403 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-30 09:36:51.647  6817  8403 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-30 09:36:51.647  6817  8403 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 09:36:51.648  6817  8403 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 09:36:51.651  6817  8403 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 09:36:51.659  6817  8642 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-30 09:36:51.659  6817  8642 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-30 09:36:51.659  6817  8642 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 09:36:51.660  6817  8642 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 09:36:51.663  6817  8642 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 09:36:51.664  6817  8644 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 872, name: OutgoingSocketThread/Sender)
08-30 09:36:51.664  6817  8660 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: IncomingSocketThread/Receiver)
,08-30 09:36:51.665  6817  8660 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 875, thread name: IncomingSocketThread/Receiver)
08-30 09:36:51.665  6817  8660 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 09:36:51.665  6817  8660 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 875, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 09:36:51.666  6817  8650 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 873, name: OutgoingSocketThread/Receiver)
08-30 09:36:51.667  6817  8650 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 873, thread name: OutgoingSocketThread/Receiver)
08-30 09:36:51.667  6817  8650 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 09:36:51.667  6817  8650 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 873, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 09:36:51.668  6817  8659 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 874, name: IncomingSocketThread/Sender)
08-30 09:36:52.107  7739  8401 D UEI.SmartControl: Internal timer expired: 2
08-30 09:36:52.107  7739  8401 D UEI.SmartControl: unbind internal service
,08-30 09:36:52.176  7739  8395 D serial_port: close(fd = 24)
,08-30 09:36:52.187  7739  8395 I UEI.SmartControl: Serial port is closed.
08-30 09:36:54.512  1027  1531 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=45.4, 0.0, 0.0  rx=38.1 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-631168017] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:36:54.515  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=45.4, 0.0, 0.0  rx=38.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-631168013] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:36:54.515  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 09:36:54.652  6817  6896 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 09:36:54.656  6817  6896 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 09:36:54.658  6817  6896 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a7c7d97 Bundle[{}]
08-30 09:36:54.659  6817  6896 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 09:36:54.660  6817  6896 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 09:36:54.660  6817  6896 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 09:36:54.661  6817  6896 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 09:36:54.662  6817  6896 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 09:36:54.662  6817  6896 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 09:36:54.669  6817  6896 I System.out: Running OutgoingSocketThread
,08-30 09:36:54.675  6817  8673 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-30 09:36:54.675  6817  8673 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 09:36:55.494  8564  8585 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 09:36:56.107  1027  2005 I ActivityManager: Killing 7706:com.lge.settings.easy/1000 (adj 15): empty #17
,08-30 09:36:56.141  1027  1943 W libprocessgroup: failed to open /acct/uid_1000/pid_7706/cgroup.procs: No such file or directory
,08-30 09:36:57.537  1027  1531 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=22.7, 0.0, 0.0  rx=19.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-631164992] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 09:36:57.547  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=22.7, 0.0, 0.0  rx=19.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-631164981] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:36:57.547  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 09:36:57.687  6817  8673 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-30 09:36:57.687  6817  8673 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 09:36:57.687  6817  8673 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 09:36:57.693  6817  8673 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 09:36:57.693  6817  8673 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 09:36:57.695  6817  8676 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-30 09:36:57.695  6817  8676 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 09:36:57.695  6817  8676 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 09:36:57.695  6817  8676 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 09:36:57.695  6817  8676 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 09:36:57.698  6817  8679 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 885, name: OutgoingSocketThread/Receiver)
08-30 09:36:57.698  6817  8679 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 885, thread name: OutgoingSocketThread/Receiver)
08-30 09:36:57.698  6817  8679 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 09:36:57.698  6817  8679 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 885, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 09:36:57.701  6817  8680 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 886, name: IncomingSocketThread/Sender)
08-30 09:36:57.702  6817  8681 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 887, name: IncomingSocketThread/Receiver)
08-30 09:36:57.702  6817  8681 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 887, thread name: IncomingSocketThread/Receiver)
08-30 09:36:57.702  6817  8681 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 09:36:57.702  6817  8681 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 887, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 09:36:57.708  6817  8678 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 884, name: OutgoingSocketThread/Sender)
08-30 09:36:59.658  1596  1596 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 09:36:59.693  1027  1471 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 09:36:59.764  1027  1085 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8682 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 09:36:59.777  1596  1596 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 09:36:59.780  1596  1596 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 09:36:59.799  2085  2085 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 09:36:59.808  2085  2085 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 09:36:59.809  1027  1027 D administrator: Handling package changes for user 0
,08-30 09:36:59.858  8682  8682 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 09:36:59.928  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 09:36:59.928  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 09:36:59.972  8682  8682 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:36:59.972  8682  8682 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:36:59.997  1027  1084 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 09:37:00.003  1027  1084 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 09:37:00.012  2085  2085 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 09:37:00.018  2478  2478 V GmsNetworkLocationProvi: DISABLE
08-30 09:37:00.049  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-30 09:37:00.052  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-30 09:37:00.052  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 09:37:00.052  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
08-30 09:37:00.053  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 09:37:00.053  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-30 09:37:00.053  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
08-30 09:37:00.054  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 09:37:00.059  1027  1084 D LocationProviderProxy: applying state to connected service
08-30 09:37:00.061  2478  2478 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-30 09:37:00.115  8682  8726 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-30 09:37:00.117  8682  8726 I Babel   : MmsConfig.loadMmsSettings
,08-30 09:37:00.127  8682  8726 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 09:37:00.127  8682  8726 I Babel   : MmsConfig.loadFromDatabase
,08-30 09:37:00.152  8682  8726 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 09:37:00.153  8682  8726 I Babel   : MmsConfig.loadFromResources
08-30 09:37:00.157  8682  8726 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 09:37:00.158  8682  8726 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 09:37:00.173  8682  8682 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:37:00.201  8682  8724 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 09:37:00.203  8682  8724 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 09:37:00.205  8682  8724 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 09:37:00.219  8682  8724 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-30 09:37:00.221  8682  8724 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 09:37:00.223  8682  8724 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 09:37:00.234  7128  7128 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 09:37:00.237  1835  8728 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 09:37:00.237  1835  8728 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-30 09:37:00.240  7128  7128 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3b634cfd
08-30 09:37:00.240  7128  7128 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 09:37:00.240  7128  7128 D AppUp4:CustFacade: isPhone : true
08-30 09:37:00.240  7128  7128 D AppUp4:CustModeStarterReceiver: begin check event
08-30 09:37:00.241  7128  7128 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 09:37:00.248  8682  8724 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 09:37:00.250  8682  8724 W VideoCapabilities: Unsupported mime video/divx
,08-30 09:37:00.255  8682  8724 W VideoCapabilities: Unsupported mime video/divx311
08-30 09:37:00.258  8682  8724 W VideoCapabilities: Unsupported mime video/divx4
08-30 09:37:00.266  8682  8724 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 09:37:00.281  8682  8724 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 09:37:00.286  1027  2005 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8732 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 09:37:00.287  8682  8724 W AudioCapabilities: Unsupported mime audio/eac3
08-30 09:37:00.290  8682  8724 W AudioCapabilities: Unsupported mime audio/ac3
08-30 09:37:00.292  8682  8724 W AudioCapabilities: Unsupported mime audio/g726
08-30 09:37:00.292  1027  1593 I ActivityManager: Killing 8259:com.lge.bnr/1000 (adj 15): empty #17
,08-30 09:37:00.298  8682  8724 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 09:37:00.309  1835  4744 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-30 09:37:00.310  8682  8724 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 09:37:00.311  8682  8724 W AudioCapabilities: Unsupported mime audio/adpcm
,08-30 09:37:00.314  8682  8724 W VideoCapabilities: Unsupported mime video/theora
08-30 09:37:00.315  8682  8724 W VideoCapabilities: Unsupported mime video/mjpg
08-30 09:37:00.421  1027  2096 W libprocessgroup: failed to open /acct/uid_1000/pid_8259/cgroup.procs: No such file or directory
,08-30 09:37:00.441  8732  8732 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 09:37:00.441  8732  8732 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 09:37:00.441  8732  8732 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 09:37:00.442  8732  8732 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 09:37:00.442  8732  8732 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 09:37:00.497  8732  8732 I SystemConfig: BUILD Country: EU
08-30 09:37:00.497  8732  8732 I SystemConfig: BUILD Operator: OPEN
,08-30 09:37:00.569  1027  1531 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=12.8, 0.0, 0.0  rx=10.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-631161959] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 09:37:00.571  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=12.8, 0.0, 0.0  rx=10.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-631161957] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:37:00.571  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 09:37:00.577  1027  2096 I ActivityManager: Killing 8232:com.lge.sync/1000 (adj 15): empty #17
08-30 09:37:00.685  6817  6896 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 896)
08-30 09:37:00.687  6817  6896 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 09:37:00.687  6817  6896 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 897)
,08-30 09:37:00.698  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 09:37:00.699  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d9577f added. We now have 3 listener(s)
08-30 09:37:00.700  1027  2063 W libprocessgroup: failed to open /acct/uid_1000/pid_8232/cgroup.procs: No such file or directory
,08-30 09:37:00.709  1027  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:37:00.713  8732  8751 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 09:37:00.713  8732  8751 I SystemConfig: existFile = false
08-30 09:37:00.713  8732  8751 I SystemConfig: canReadFile = false
08-30 09:37:00.713  8732  8751 I SystemConfig: systemFeature RCS result false
08-30 09:37:00.713  8732  8751 D SystemConfig: refreshRcsSupport() :false
08-30 09:37:00.713  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 09:37:00.713  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:37:00.713  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:37:00.713  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:37:00.714  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6d234c added. We now have 4 listener(s)
08-30 09:37:00.714  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:37:00.714  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 09:37:00.789  1027  1943 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8753 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-30 09:37:00.792  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:37:00.801  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:37:00.801  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:37:00.801  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:37:00.801  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:37:00.801  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:37:00.801  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:37:00.801  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:37:00.801  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:37:00.804  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:37:00.805  6817  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:37:00.805  6817  6896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 09:37:00.805  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 09:37:00.805  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 09:37:00.806  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:37:00.806  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:00.806  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:37:00.806  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 09:37:00.806  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d9577f removed from the list
08-30 09:37:00.806  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:00.808  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6d234c removed from the list
08-30 09:37:00.810  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:37:00.810  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:37:00.810  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:00.811  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:00.811  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:00.813  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:37:00.813  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:37:00.813  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:00.813  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6d234c not in the list
08-30 09:37:00.813  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:00.813  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:00.814  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:37:00.814  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:37:00.814  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:37:00.814  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:00.815  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6d234c not in the list
08-30 09:37:00.815  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:37:00.815  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:00.815  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:00.815  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d9577f not in the list
08-30 09:37:00.815  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 09,:37:00.816  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2af348aa added. We now have 3 listener(s)
08-30 09:37:00.816  1027  1593 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:37:00.820  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 09:37:00.820  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:37:00.820  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:37:00.820  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:37:00.821  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@735ec9b added. We now have 4 listener(s)
08-30 09:37:00.821  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:37:00.821  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 09:37:00.824  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:37:00.829  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:37:00.829  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:37:00.829  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:37:00.829  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:37:00.829  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:37:00.829  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:37:00.829  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:37:00.829  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:37:00.831  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:37:00.831  6817  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:37:00.832  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 09:37:00.832  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 09:37:00.832  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 09:37:00.832  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:37:00.832  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 09:37:00.836  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:37:00.837  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 09:37:00.837  1027  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:37:00.839  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:37:00.842  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 09:37:00.843  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 09:37:00.845  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 09:37:00.845  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 09:37:00.849  6817  6896 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 09:37:00.849  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 09:37:00.849  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 09:37:00.887  8753  8753 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 09:37:00.887  8753  8753 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 09:37:00.888  8753  8753 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 09:37:00.888  8753  8753 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 09:37:00.991  8753  8753 I AppConfig: Total System Memory = 2995761152
,08-30 09:37:01.002  8753  8753 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 09:37:01.132  1027  1758 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8775 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 09:37:01.133  1027  1758 I ActivityManager: Killing 6945:com.android.settings/1000 (adj 15): empty #17
,08-30 09:37:01.206  1027  2096 W libprocessgroup: failed to open /acct/uid_1000/pid_6945/cgroup.procs: No such file or directory
08-30 09:37:01.401  8775  8775 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 09:37:01.503  8775  8775 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 09:37:01.503  8775  8775 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:37:01.555  8775  8775 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 09:37:01.578  8775  8775 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 09:37:01.579  8775  8775 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 09:37:01.599  8775  8775 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 09:37:01.599  8775  8775 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 09:37:01.619  1027  1727 I ActivityManager: Killing 8427:com.lge.email/u0a23 (adj 15): empty #17
,08-30 09:37:01.682  1027  1044 W libprocessgroup: failed to open /acct/uid_10023/pid_8427/cgroup.procs: No such file or directory
,08-30 09:37:01.705  4571  8815 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 09:37:01.714  3485  7324 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 09:37:01.716  3485  7324 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@9963250 on behalf of 8775
08-30 09:37:01.774  1027  1757 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8816 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 09:37:01.833  8775  8775 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 09:37:01.860  8775  8775 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 09:37:01.892  8816  8816 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 09:37:01.927  8816  8816 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 09:37:01.927  8816  8816 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 09:37:01.927  8816  8816 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 09:37:01.927  8816  8816 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 09:37:01.927  8816  8816 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 09:37:01.927  8816  8816 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 09:37:01.949  1027  1968 I ActivityManager: Killing 8210:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 09:37:01.979  1027  2009 W libprocessgroup: failed to open /acct/uid_10026/pid_8210/cgroup.procs: No such file or directory
,08-30 09:37:02.171  1027  1567 V SIM_STK : Menu title from STK is T-Mobile
,08-30 09:37:02.200  4571  8815 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 494 ms] updated apps [took 494 ms] 
,08-30 09:37:03.591  1027  1531 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=6.9, 0.0, 0.0  rx=5.8 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-631158937] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:37:03.594  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=6.9, 0.0, 0.0  rx=5.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-631158934] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 09:37:03.594  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 09:37:03.851  6817  6896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 09:37:03.851  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 09:37:03.851  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 09:37:03.861  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:37:03.861  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:03.862  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:37:03.862  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 09:37:03.863  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2af348aa removed from the list
08-30 09:37:03.863  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:03.863  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@735ec9b removed from the list
08-30 09:37:03.863  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:37:03.863  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:03.866  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:03.866  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:03.870  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:37:03.870  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:37:03.874  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:37:03.874  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:37:03.874  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:03.874  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@735ec9b not in the list
08-30 09:37:03.874  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:03.874  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:03.876  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:37:03.876  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:37:03.876  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:37:03.876  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:37:03.876  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:03.877  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@735ec9b not in the list
08-30 09:37:03.877  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:37:03.877  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:03.877  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:03.877  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2af348aa not in the list
08-30 09:37:03.878  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 09:37:03.878  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36fcb777 added. We now have 3 listener(s)
08-30 09:37:03.879  1027  2063 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:37:03.881  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 09:37:03.882  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:37:03.882  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:37:03.882  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:37:03.882  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68a8fe4 added. We now have 4 listener(s)
08-30 09:37:03.882  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:37:03.885  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 09:37:03.892  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:37:03.896  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:37:03.896  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:37:03.896  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:37:03.896  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:37:03.896  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:37:03.896  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:37:03.896  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:37:03.896  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:37:03.899  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:37:03.899  6817  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 09:37:03.903  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:37:03.905  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:37:03.906  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 09:37:03.907  6817  6896 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 09:37:03.907  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-30 09:37:03.910  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 09:37:03.910  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 09:37:03.911  6817  6896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 09:37:03.911  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:37:03.916  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 09:37:03.916  6817  6896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 09:37:03.917  6817  6896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 09:37:03.917  6817  6817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 09:37:03.919  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 09:37:03.919  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 09:37:03.919  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:37:03.919  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 09:37:03.925  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 09:37:03.928  1027  2063 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:37:03.933  1027  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:37:03.934  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 09:37:03.935  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 09:37:03.937  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 09:37:03.940  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 09:37:03.942  6817  8858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:37:03.942  6817  6896 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 09:37:03.943  8025  8042 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-30 09:37:03.944  6817  8858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 09:37:06.620  1027  1531 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-631155908] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 09:37:06.623  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-631155905] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 09:37:06.624  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 09:37:06.947  6817  6896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 09:37:06.956  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 09:37:06.957  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 09:37:06.957  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 09:37:06.957  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 09:37:06.957  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 09:37:06.960  6817  8858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 09:37:06.960  6817  8858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 09:37:06.960  6817  8858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 09:37:06.961  6817  6817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 09:37:06.962  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:37:06.962  6817  6896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 09:37:06.962  6817  6817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 09:37:06.962  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 09:37:06.962  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:06.962  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:37:06.966  6817  6817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 09:37:06.966  6817  6817 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 09:37:06.969  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:37:06.969  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:06.969  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:37:06.969  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 09:37:06.969  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36fcb777 removed from the list
08-30 09:37:06.969  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:06.969  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68a8fe4 removed from the list
08-30 09:37:06.969  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:37:06.969  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:06.972  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:06.972  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:06.973  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:37:06.973  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:37:06.974  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:37:06.974  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:37:06.974  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:06.974  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68a8fe4 not in the list
08-30 09:37:06.974  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:06.974  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:06.975  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:37:06.977  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:37:06.977  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:37:06.977  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:37:06.977  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:06.977  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68a8fe4 not in the list
08-30 09:37:06.977  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:37:06.977  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:06.977  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:06.977  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36fcb777 not in the list
08-30 09:37:06.978  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 09:37:06.978  6817  ,6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a52c650 added. We now have 3 listener(s)
08-30 09:37:06.979  1027  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 09:37:06.986  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 09:37:06.986  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:37:06.986  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:37:06.986  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:37:06.986  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8b0049 added. We now have 4 listener(s)
08-30 09:37:06.986  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:37:06.987  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 09:37:06.991  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:37:06.997  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:37:06.997  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:37:06.997  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:37:06.997  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:37:06.997  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:37:06.997  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:37:06.997  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:37:06.997  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:37:06.999  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:37:06.999  6817  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:37:07.002  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:37:07.004  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:37:07.006  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 09:37:07.006  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 09:37:07.006  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 09:37:07.006  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:37:07.006  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 09:37:07.010  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 09:37:07.010  1027  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 09:37:07.016  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 09:37:07.019  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 09:37:07.020  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 09:37:07.021  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:37:07.022  6817  6896 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 09:37:09.650  1027  1531 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-631152878] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 09:37:09.653  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-631152875] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 09:37:09.653  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 09:37:10.030  6817  6896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 09:37:10.031  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 09:37:10.031  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 09:37:10.039  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:37:10.039  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:10.040  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:37:10.040  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 09:37:10.040  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a52c650 removed from the list
08-30 09:37:10.040  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:10.040  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8b0049 removed from the list
08-30 09:37:10.040  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:37:10.040  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:10.042  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:10.042  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:10.043  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:37:10.043  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:37:10.044  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:37:10.044  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:37:10.044  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:10.044  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8b0049 not in the list
08-30 09:37:10.044  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:10.044  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:10.045  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:37:10.047  6817  6896 D BluetoothLeScanner: could not find callback wrapper
08-30 09:37:10.047  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:37:10.047  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:37:10.047  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:10.047  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8b0049 not in the list
08-30 09:37:10.047  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:37:10.047  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:10.047  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:10.047  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a52c650 not in the list
08-30 09:37:10.048  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 09:37:10.048  681,7  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37a5805 added. We now have 3 listener(s)
08-30 09:37:10.049  1027  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 09:37:10.056  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 09:37:10.056  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:37:10.056  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:37:10.056  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:37:10.056  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ac7305a added. We now have 4 listener(s)
08-30 09:37:10.056  6817  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:37:10.057  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 09:37:10.062  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:37:10.068  6817  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:37:10.068  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:37:10.068  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 09:37:10.068  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:37:10.068  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:37:10.068  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:37:10.068  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:37:10.068  6817  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:37:10.070  6817  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:37:10.070  6817  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:37:10.073  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:37:10.075  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:37:10.078  6817  6896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 09:37:10.079  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 09:37:10.079  6817  6896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 09:37:10.079  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:37:10.079  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:10.079  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:37:10.079  6817  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 09:37:10.079  6817  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37a5805 removed from the list
08-30 09:37:10.079  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:10.079  6817  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ac7305a removed from the list
08-30 09:37:10.079  6817  6896 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:37:10.079  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:10.080  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:10.080  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:10.081  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:37:10.081  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:37:10.081  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:10.081  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ac7305a not in the list
08-30 09:37:10.081  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:10.082  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:10.083  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:37:10.083  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:37:10.083  6817  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:37:10.083  6817  6896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ac7305a not in the list
08-30 09:37:10.083  6817  6896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:37:10.083  6817  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:37:10.083  6817  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:37:10.083  6817  6896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37a5805 not in the list
08-30 09:37:10.08,4  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 09:37:10.084  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 09:37:10.084  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 09:37:10.084  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 09:37:10.085  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 09:37:10.085  6817  6896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 09:37:12.110  6817  8859 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 906, name: My test thread name)
,08-30 09:37:12.679  1027  1531 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-631149849] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 09:37:12.682  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-631149846] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 09:37:12.682  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 09:37:14.105  6817  6896 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 906
,08-30 09:37:14.105  6817  6896 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 906, name: My test thread name)
,08-30 09:37:14.121  6817  8860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 907, name: My test thread name)
08-30 09:37:14.121  6817  8860 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 907, thread name: My test thread name)
08-30 09:37:14.121  6817  8860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 907, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-30 09:37:14.124  6817  6896 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 09:37:14.128  6817  8861 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 911, name: My test thread name)
08-30 09:37:14.128  6817  8861 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 911, thread name: My test thread name): Test exception.
08-30 09:37:14.128  6817  8861 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 911, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 09:37:14.134  6817  6896 I jxcore-log: Total number of executed tests:  82
08-30 09:37:14.134  6817  6896 I jxcore-log: 
08-30 09:37:14.134  6817  6896 I jxcore-log: Number of passed tests:  82
08-30 09:37:14.134  6817  6896 I jxcore-log: 
08-30 09:37:14.135  6817  6896 I jxcore-log: Number of failed tests:  0
08-30 09:37:14.135  6817  6896 I jxcore-log: 
08-30 09:37:14.135  6817  6896 I jxcore-log: Number of ignored tests:  0
08-30 09:37:14.135  6817  6896 I jxcore-log: 
08-30 09:37:14.135  6817  6896 I jxcore-log: Total duration:  111868
08-30 09:37:14.135  6817  6896 I jxcore-log: 
08-30 09:37:14.137  6817  6896 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 09:37:14.137  6817  6896 I jxcore-log: 
08-30 09:37:14.141  6817  6896 I jxcore-log: My device name is: LGE-LG-D855
08-30 09:37:14.141  6817  6896 I jxcore-log: 
08-30 09:37:14.144  6817  6896 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 09:37:14.144  6817  6896 I jxcore-log: 
,08-30 09:37:14.159  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.159  6817  6896 I jxcore-log: 
08-30 09:37:14.160  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.160  6817  6896 I jxcore-log: 
08-30 09:37:14.161  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.161  6817  6896 I jxcore-log: 
08-30 09:37:14.162  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.162  6817  6896 I jxcore-log: 
08-30 09:37:14.165  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.165  6817  6896 I jxcore-log: 
08-30 09:37:14.167  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 09:37:14.167  6817  6896 I jxcore-log: 
,08-30 09:37:14.177  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:37:14.177  6817  6896 I jxcore-log: 
08-30 09:37:14.179  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:37:14.179  6817  6896 I jxcore-log: 
08-30 09:37:14.179  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.179  6817  6896 I jxcore-log: 
08-30 09:37:14.180  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.180  6817  6896 I jxcore-log: 
08-30 09:37:14.181  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.181  6817  6896 I jxcore-log: 
08-30 09:37:14.183  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:37:14.183  6817  6896 I jxcore-log: 
08-30 09:37:14.184  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:37:14.184  6817  6896 I jxcore-log: 
08-30 09:37:14.185  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:37:14.185  6817  6896 I jxcore-log: 
08-30 09:37:14.185  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.185  6817  6896 I jxcore-log: 
08-30 09:37:14.186  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.186  6817  6896 I jxcore-log: 
08-30 09:37:14.187  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.187  6817  6896 I jxcore-log: 
08-30 09:37:14.189  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.189  6817  6896 I jxcore-log: 
08-30 09:37:14.189  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.189  6817  6896 I jxcore-log: 
08-30 09:37:14.190  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.190  6817  6896 I jxcore-log: 
08-30 09:37:14.191  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.191  6817  6896 I jxcore-log: 
,08-30 09:37:14.192  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.192  6817  6896 I jxcore-log: 
08-30 09:37:14.199  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.199  6817  6896 I jxcore-log: 
08-30 09:37:14.200  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.200  6817  6896 I jxcore-log: 
08-30 09:37:14.201  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.201  6817  6896 I jxcore-log: 
08-30 09:37:14.201  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.201  6817  6896 I jxcore-log: 
08-30 09:37:14.202  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.202  6817  6896 I jxcore-log: 
08-30 09:37:14.203  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.203  6817  6896 I jxcore-log: 
08-30 09:37:14.204  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:37:14.204  6817  6896 I jxcore-log: 
08-30 09:37:14.204  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 09:37:14.204  6817  6896 I jxcore-log: 
08-30 09:37:14.205  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 09:37:14.205  6817  6896 I jxcore-log: 
08-30 09:37:14.206  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.206  6817  6896 I jxcore-log: 
08-30 09:37:14.207  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.207  6817  6896 I jxcore-log: 
08-30 09:37:14.207  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.207  6817  6896 I jxcore-log: 
08-30 09:37:14.209  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.209  6817  6896 I jxcore-log: 
08-30 09:37:14.210  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.210  6817  6896 I jxcore-log: 
08-30 09:37:14.211  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.211  6817  6896 I jxcore-log: 
08-30 09:37:14.211  6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.211  6817  6896 I jxcore-log: 
08-30 09:37:14.212 , 6817  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:37:14.212  6817  6896 I jxcore-log: 
,08-30 09:37:14.220  6817  8859 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 906, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
08-30 09:37:14.499  8862  8862 D AndroidRuntime: 
08-30 09:37:14.499  8862  8862 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 09:37:14.503  8862  8862 D AndroidRuntime: CheckJNI is OFF
,08-30 09:37:14.706  8862  8862 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 09:37:14.721  1027  1085 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-30 09:37:14.724  1027  1085 I ActivityManager: Killing 6817:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-30 09:37:14.782  1027  1968 I WindowState: WIN DEATH: Window{2f37e056 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 09:37:14.782  1027  1536 D WifiService: Client connection lost with reason: 4
08-30 09:37:14.790  1027  1968 D InputDispatcher: Window went away: Window{2f37e056 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 09:37:14.953  1027  1085 I ActivityManager:   Force finishing activity ActivityRecord{12007793 u0 com.test.thalitest/.MainActivity t6}
,08-30 09:37:15.008   335   358 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 09:37:15.016  1027  1943 W ActivityManager: Spurious death for ProcessRecord{1e1f5ebc 6817:com.test.thalitest/u0a118}, curProc for 6817: null
,08-30 09:37:15.017  1027  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 09:37:15.022  1027  1101 I ActivityManager:   Force finishing activity ActivityRecord{12007793 u0 com.test.thalitest/.MainActivity t6 f}
08-30 09:37:15.022  1027  1101 W ActivityManager: Duplicate finish request for ActivityRecord{12007793 u0 com.test.thalitest/.MainActivity t6 f}
,08-30 09:37:15.060  2085  2085 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 09:37:15.061  1958  1980 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 09:37:15.061  1958  1980 D SplitWindowPolicy: topRunningActivity=ActivityInfo{39a5ae2f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 09:37:15.062  1958  3977 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 09:37:15.062  1958  3977 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2df7ac3c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 09:37:15.063  2085  2085 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-30 09:37:15.069  2085  2085 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-30 09:37:15.072  1027  1084 W InputMethodInfo: Duplicated subtype definition found: , voice
08-30 09:37:15.072  2085  2186 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-30 09:37:15.073  4571  4571 I art     : Explicit concurrent mark sweep GC freed 15427(884KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 685us total 42.654ms
08-30 09:37:15.076  1596  1596 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 09:37:15.082  1027  1471 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 09:37:15.083  2031  2031 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 09:37:15.083  3829  3829 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 09:37:15.085  2478  2610 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 09:37:15.094  1923  1923 D ActionManagerService: notifyUserLog: 1000003
08-30 09:37:15.095  2085  2085 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 09:37:15.099  8025  8025 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 09:37:15.099  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-30 09:37:15.102  3829  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 09:37:15.109  1596  1645 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 09:37:15.109  1596  1645 D KeyguardModel: createShortcutInfo...
08-30 09:37:15.114  2085  2085 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-30 09:37:15.148  8277  8277 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-30 09:37:15.160  4452  4452 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 09:37:15.160  4452  4452 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 09:37:15.160  4452  4452 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 09:37:15.160  4452  4452 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 09:37:15.160  4452  4452 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 09:37:15.160  4452  4452 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 09:37:15.160  4452  4452 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 09:37:15.160  4452  4452 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 09:37:15.160  4452  4452 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:37:15.160  4452  4452 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 09:37:15.160  4452  4452 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 09:37:15.160  4452  4452 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 09:37:15.172  2085  2085 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-30 09:37:15.172  1596  1596 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 09:37:15.174  2085  2085 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 09:37:15.178  1835  1835 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-30 09:37:15.178  2085  2085 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-30 09:37:15.179  1923  1923 D ActionManagerService: notifyUserLog: 1000004
08-30 09:37:15.180  3829  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 09:37:15.181  3829  3844 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 09:37:15.181  1596  1645 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 09:37:15.181  1596  1645 D KeyguardModel: createShortcutInfo...
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , expire_time: 0
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , display: false
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , animation: false }
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , expire_time: 0
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , display: false
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , animation: false }
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , expire_time: 0
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , display: false
08-30 09:37:15.183  2085  2085 I GBoardWebViewUtils: , animation: false }
08-30 09:37:15.186  1027  2005 V SIM_STK : Menu title from STK is T-Mobile
08-30 09:37:15.200  2085  8894 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-30 09:37:15.203  1596  1645 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 09:37:15.203  1596  1645 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 09:37:15.203  1596  1645 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 09:37:15.204  1596  1645 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 09:37:15.211  1596  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 09:37:15.211  1596  1645 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 09:37:15.215  1596  1645 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 09:37:15.215  1596  1645 D KeyguardModel: createShortcutInfo...
08-30 09:37:15.215  1027  1027 I art     : Explicit concurrent mark sweep GC freed 43551(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 3.203ms total 167.021ms
08-30 09:37:15.217  1027  1101 I art     : WaitForGcToComplete blocked for 105.541ms for cause Explicit
,08-30 09:37:15.219  1596  1596 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 09:37:15.219  1596  1596 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 09:37:15.219  2085  2085 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 09:37:15.220  2085  2085 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 09:37:15.232  1888  1888 D SplitUIManager: split_name #11 / not available #0
08-30 09:37:15.232  1888  1888 D SplitUIService: removed split : 
08-30 09:37:15.237  1596  1645 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 09:37:15.237  1596  1645 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 09:37:15.241  1835  1835 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 09:37:15.245  2251  2251 I ConfigService: onCreate
08-30 09:37:15.245  2251  2251 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 09:37:15.246  1596  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 09:37:15.246  1596  1645 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 09:37:15.248  1596  1645 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 09:37:15.248  1596  1645 D KeyguardModel: createShortcutInfo...
08-30 09:37:15.251  2251  2251 I ConfigService: onBind returning update interface
,08-30 09:37:15.252  2251  2251 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 09:37:15.252  2251  2251 I ConfigService: onBind returning config service
08-30 09:37:15.257  2251  2251 I ConfigService: onDestroy
08-30 09:37:15.267  1888  1888 D SplitUIManager: split_name #11 / not available #0
08-30 09:37:15.267  1888  1888 I SplitUIService: split app #11
,08-30 09:37:15.273  1596  1645 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 09:37:15.273  1596  1645 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 09:37:15.273  1596  1645 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 09:37:15.273  1596  1645 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 09:37:15.274  1596  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 09:37:15.274  1596  1645 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 09:37:15.275  1596  1645 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 09:37:15.275  1596  1645 D KeyguardModel: createShortcutInfo...
08-30 09:37:15.281  1596  1596 D KeyguardModel: handleShortcutListChanged...
08-30 09:37:15.281  1596  1596 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-30 09:37:15.285  1596  1645 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 09:37:15.286  1596  1645 D KeyguardModel: createShortcutInfo...
08-30 09:37:15.287  1596  1645 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 09:37:15.287  1596  1645 D KeyguardModel: createShortcutInfo...
08-30 09:37:15.291  1835  8898 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 09:37:15.291  1596  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 09:37:15.291  1596  1645 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 09:37:15.293  1596  1645 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 09:37:15.293  1596  1645 D KeyguardModel: createShortcutInfo...
08-30 09:37:15.293  1027  1593 V SIM_STK : Menu title from STK is T-Mobile
08-30 09:37:15.293  1027  1593 V SIM_STK : Menu title from STK is T-Mobile
08-30 09:37:15.298  2085  2085 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-30 09:37:15.323  1596  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 09:37:15.324  1596  1645 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-30 09:37:15.325  1596  1645 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 09:37:15.325  1596  1645 D KeyguardModel: createShortcutInfo...
08-30 09:37:15.326  1596  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 09:37:15.326  1596  1645 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 09:37:15.328  1596  1645 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 09:37:15.328  1596  1645 D KeyguardModel: createShortcutInfo...
08-30 09:37:15.334  1027  2063 V SIM_STK : Menu title from STK is T-Mobile
08-30 09:37:15.339  1596  1596 D KeyguardModel: handleShortcutListChanged...
08-30 09:37:15.339  1596  1596 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-30 09:37:15.353  5973  8904 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-30 09:37:15.363  1027  1043 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 09:37:15.364  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 09:37:15.364  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 09:37:15.364  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 09:37:15.365  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 09:37:15.365  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 09:37:15.365  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 09:37:15.365  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 09:37:15.365  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 09:37:15.365  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 09:37:15.365  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 09:37:15.365  8025  8025 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 09:37:15.367  1027  1027 D administrator: Handling package changes for user 0
,08-30 09:37:15.384  2085  2085 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-30 09:37:15.391  2085  2085 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 09:37:15.393  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 09:37:15.394  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 09:37:15.395  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 09:37:15.396  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-30 09:37:15.408  1835  8906 I PeopleContactsSync: CP2 sync disabled
,08-30 09:37:15.412  1027  1090 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8e194a0 u0 com.lge.launcher2/.Launcher t5} time:290084
08-30 09:37:15.414   329   426 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 09:37:15.416  3195  8908 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 09:37:15.419  2085  2085 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 09:37:15.419  2085  2085 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 09:37:15.426  1835  8903 W GmsApplication: Using Auth Proxy for data requests.
,08-30 09:37:15.433  2085  2307 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 09:37:15.433  2085  2307 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 09:37:15.444  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 09:37:15.445  2085  2085 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-30 09:37:15.446  2085  2085 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 09:37:15.451  1835  8903 W GmsApplication: Using Auth Proxy for data requests.
08-30 09:37:15.455  2085  2085 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-30 09:37:15.457  2649  2649 D [Concierge]Service: onStartCommand(). Type : 8
08-30 09:37:15.457  2649  2649 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 09:37:15.457  2649  2649 D [Concierge]Service: Update widget ID : 11
08-30 09:37:15.460  2085  2085 D [Concierge]WidgetView: change position of spinner
,08-30 09:37:15.462  2085  2085 I [Concierge]WidgetView: initWebView(). Time : 1472542635462
08-30 09:37:15.462  2649  2649 D [Concierge]Service: onStartCommand(). Type : 0
08-30 09:37:15.472  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 09:37:15.472  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 09:37:15.472  1027  1027 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 09:37:15.472  7128  7128 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-30 09:37:15.474  1027  1571 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 09:37:15.481  1835  1835 I art     : Explicit concurrent mark sweep GC freed 39427(2MB) AllocSpace objects, 27(432KB) LOS objects, 51% free, 30MB/62MB, paused 1.780ms total 107.822ms
08-30 09:37:15.486  1835  4744 I Icing   : doRemovePackageData com.test.thalitest
,08-30 09:37:15.489  2085  2085 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 677394856
08-30 09:37:15.489  2085  2085 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 09:37:15.490  2085  2085 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 09:37:15.492  2085  2085 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@366334c5
08-30 09:37:15.492  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 09:37:15.493  2085  2085 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 09:37:15.493  2085  2085 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 09:37:15.498  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 09:37:15.499  2085  2085 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 09:37:15.502  2188  8912 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 09:37:15.515  1027  1101 I art     : Explicit concurrent mark sweep GC freed 10723(566KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.664ms total 296.573ms
,08-30 09:37:15.528  1027  1044 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8913 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 09:37:15.530  2085  2085 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472542373762, New one : 1472542635462
08-30 09:37:15.530  2085  2085 D [Concierge]WidgetView: Unregister all receivers
08-30 09:37:15.531  2085  2085 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 09:37:15.532  2085  2085 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 09:37:15.532  2085  2085 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 09:37:15.534  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 09:37:15.535  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 09:37:15.536  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 09:37:15.537  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 09:37:15.538  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 09:37:15.538  2085  2085 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 09:37:15.539  2085  2085 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 09:37:15.571  2085  2085 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 09:37:15.585  8913  8913 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 09:37:15.585  8913  8913 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 09:37:15.586  8913  8913 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 09:37:15.586  8913  8913 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 09:37:15.589  2085  2085 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 09:37:15.590  2085  2085 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 09:37:15.591  2085  2085 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 09:37:15.611  2085  2085 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@26efd12d time:290283
,08-30 09:37:15.646  1027  1084 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 09:37:15.650  8913  8913 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-30 09:37:15.651  1027  1084 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 09:37:15.654  8862  8862 D AndroidRuntime: Shutting down VM
08-30 09:37:15.656  2085  2085 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 09:37:15.658  8913  8913 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-30 09:37:15.677  8913  8913 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 09:37:15.696  8913  8913 D LgDataFeature: LgDataFeature() Constructor: none
08-30 09:37:15.697  8913  8913 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 09:37:15.704  1027  1531 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-631146824] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 09:37:15.705  1027  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-631146823] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 09:37:15.705  1027  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 09:37:15.736  2085  2085 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-30 09:37:15.742  8913  8913 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-30 09:37:15.754  1027  1567 I ActivityManager: Killing 8479:com.android.chrome/u0a57 (adj 15): empty #17
,08-30 09:37:15.771  2085  2908 I GBoardtInterface: onReloaded()
,08-30 09:37:15.773  2085  2085 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 09:37:15.816  2031  2031 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 09:37:15.816  2031  2031 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-30 09:37:15.817  1027  2096 W libprocessgroup: failed to open /acct/uid_10057/pid_8479/cgroup.procs: No such file or directory
08-30 09:37:15.817  2031  2031 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-30 09:37:15.817  3829  3844 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 09:37:15.822  8277  8277 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 09:37:15.823  3829  3845 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 09:37:15.860  1027  1043 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8936 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 09:37:15.866  1923  1923 D ActionManagerService: notifyUserLog: 1000001
08-30 09:37:15.868  3829  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 09:37:15.868  3829  4481 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-30 09:37:15.898  1027  1101 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8953 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 09:37:15.898  1923  1923 D ActionManagerService: notifyUserLog: 1000001
08-30 09:37:15.900  3829  3845 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 09:37:15.901  3829  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 09:37:15.901  3829  4481 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 09:37:15.901  3829  4481 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 09:37:15.901  3829  4481 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 09:37:15.902  2085  2085 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 09:37:15.902  2085  2085 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 09:37:15.904  2085  2085 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 09:37:15.904  2085  2085 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 09:37:15.906  2085  2085 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 09:37:15.906  2085  2085 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-30 09:37:15.950  8936  8936 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 09:37:15.950  8936  8936 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: Unable to open database for writing.
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 09:37:15.951  8936  8936 E Lifetra,ckerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 09:37:15.951  8936  8936 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)

```
