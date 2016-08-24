#### Test 80912877ffdb7be_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-24 10:05:00.089  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:05:00.093  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:05:00.093  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:05:00.094  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
08-24 10:05:00.100  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:05:00.101  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:05:00.103  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:05:00.105  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:05:10.990  6756  6756 D AndroidRuntime: 
08-24 10:05:10.990  6756  6756 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 10:05:10.994  6756  6756 D AndroidRuntime: CheckJNI is OFF
08-24 10:05:11.199  6756  6756 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 10:05:11.209  1032  1960 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 10:05:11.225  1943  2726 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-24 10:05:11.230  1032  1960 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-24 10:05:11.232  1032  1960 D ActivityManager: setTaskToReturnTo : TaskRecord{26eec143 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 10:05:11.232  1032  1960 D ActivityManager: setTaskToReturnTo : TaskRecord{26eec143 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 10:05:11.234  1032  1960 D WindowStateEx: AppWindowTokenEx init.. 
08-24 10:05:11.235   342   359 E GBMv2   : DFP En is all cleared set to be enabled
08-24 10:05:11.263  1032  1960 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6771 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 10:05:11.265  6756  6756 D AndroidRuntime: Shutting down VM
08-24 10:05:11.320  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-24 10:05:11.321  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{25a96830 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 10:05:11.321  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-24 10:05:11.322  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2c002ca9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 10:05:11.366  6771  6771 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-24 10:05:11.439  6771  6771 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-24 10:05:11.445  6771  6771 I LibraryLoader: Loading: webviewchromium
08-24 10:05:11.447  6771  6771 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1695-1697)
08-24 10:05:11.447  6771  6771 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 10:05:11.458  6771  6771 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fccd5e}
,08-24 10:05:11.459  6771  6771 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 10:05:11.460  6771  6771 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 10:05:11.466  6771  6771 I BrowserStartupController: Initializing chromium process, renderers=0
08-24 10:05:11.467  6771  6771 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 10:05:11.478  6771  6771 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-24 10:05:11.479  6771  6771 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-24 10:05:11.479  6771  6771 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-24 10:05:11.484   325  2184 V AudioPolicyService: registerClient() client 0xb1022d20, uid 10118
08-24 10:05:11.489  1032  1097 D BluetoothManagerService: Message: 20
08-24 10:05:11.489  1032  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@129adbb5:true
,08-24 10:05:11.504  6771  6771 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 10:05:11.504  6771  6771 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 10:05:11.504  6771  6771 I Adreno-EGL: Build Date: 12/12/14 금
08-24 10:05:11.504  6771  6771 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 10:05:11.504  6771  6771 I Adreno-EGL: Remote Branch: 
08-24 10:05:11.504  6771  6771 I Adreno-EGL: Local Patches: 
08-24 10:05:11.504  6771  6771 I Adreno-EGL: Reconstruct Branch: 
,08-24 10:05:11.594  6771  6817 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-24 10:05:11.597  6771  6771 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-24 10:05:11.619  6771  6771 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 10:05:11.626  6771  6771 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 10:05:11.629  6771  6771 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-24 10:05:11.633  6771  6771 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-24 10:05:11.633  6771  6771 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-24 10:05:11.653  6771  6771 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-24 10:05:11.661  6771  6771 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 10:05:11.661  6771  6771 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 10:05:11.686  6771  6833 D OpenGLRenderer: Render dirty regions requested: true
08-24 10:05:11.686  6771  6833 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 10:05:11.696  6771  6833 D OpenGLRenderer: Enabling debug mode 0
,08-24 10:05:11.706  6771  6771 D Atlas   : Validating map...
08-24 10:05:11.714  1032  1048 D SplitWindow: check instance of lgWin Window{25ba0f87 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 10:05:11.773  6771  6831 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 10:05:11.773  6771  6831 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 10:05:11.843  1032  1098 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +525ms (total +608ms)
08-24 10:05:11.843  6771  6771 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3a99cbc5 time:162093
,08-24 10:05:11.847  1032  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f5ce3c0 u0 com.test.thalitest/.MainActivity t6} time:162097
08-24 10:05:11.972  6771  6771 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-24 10:05:11.972  6771  6771 I chromium: 
,08-24 10:05:12.027  6771  6771 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 10:05:12.093  6771  6831 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-24 10:05:12.093  6771  6831 I chromium: 
,08-24 10:05:12.235  6771  6847 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
,08-24 10:05:12.253  6771  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 10:05:12.253  6771  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 10:05:12.253  6771  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 10:05:12.253  6771  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 10:05:12.253  6771  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 10:05:12.253  6771  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3790b579 added. We now have 1 listener(s)
08-24 10:05:12.260  1032  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 10:05:12.262  6771  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-24 10:05:12.267  6771  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-24 10:05:12.269  6771  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 10:05:12.270  6771  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 10:05:12.280  6771  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11ae526c added. We now have 1 listener(s)
08-24 10:05:12.281  6771  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 10:05:12.287  1032  1405 D WifiService: New client listening to asynchronous messages
,08-24 10:05:12.291  6771  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 10:05:12.291  6771  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 10:05:12.293  6771  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 10:05:12.293  6771  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 10:05:12.293  6771  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 10:05:12.301  6771  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 10:05:12.302  1032  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 10:05:12.303  6771  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-24 10:05:12.318  6771  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-24 10:05:12.321  6771  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 10:05:12.321  6771  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 10:05:12.321  6771  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 10:05:12.321  6771  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 10:05:12.321  6771  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 10:05:12.321  6771  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 10:05:12.321  6771  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 10:05:12.321  6771  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 10:05:12.322  6771  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 10:05:12.322  6771  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 10:05:12.325  6771  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 10:05:12.327  6771  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 10:05:12.328  6771  6847 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 10:05:12.364  6771  6771 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 10:05:12.710   342   367 E GBMv2   : DFP En is all cleared set to be enabled
08-24 10:05:12.711   342   367 E GBMv2   : Set value is all cleared set the max
08-24 10:05:12.711   342   367 I GBMv2   : DFP Enabled. Ignore VFP set
,08-24 10:05:13.537  6771  6850 W jxcore-log: Initializing JXcore engine
08-24 10:05:13.537  6771  6850 W jxcore-log: JXcore engine is ready
,08-24 10:05:13.617  6850  6850 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7434]" dev="sockfs" ino=7434 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-24 10:05:13.617  6850  6850 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-24 10:05:13.617  6850  6850 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7524]" dev="sockfs" ino=7524 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 10:05:13.617  6850  6850 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-24 10:05:13.617  6850  6850 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[29956]" dev="sockfs" ino=29956 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-24 10:05:13.655  6771  6850 W jxcore-log: Starting JXcore engine
,08-24 10:05:13.817  6771  6850 W jxcore-log: Platform android
08-24 10:05:13.817  6771  6850 W jxcore-log: 
08-24 10:05:13.818  6771  6850 W jxcore-log: Process ARCH arm
08-24 10:05:13.818  6771  6850 W jxcore-log: 
,08-24 10:05:14.218  6771  6850 I jxcore-log: JXcore Cordova bridge is ready!
08-24 10:05:14.218  6771  6850 I jxcore-log: 
08-24 10:05:14.219  6771  6850 W jxcore-log: JXcore engine is started
,08-24 10:05:14.229  6771  6847 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-24 10:05:14.236  6771  6771 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 10:05:23.771  6771  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 10:05:23.771  6771  6850 I jxcore-log: 
,08-24 10:05:23.774  6771  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 10:05:23.774  6771  6850 I jxcore-log: 
08-24 10:05:23.780  6771  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 10:05:23.780  6771  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 10:05:23.780  6771  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 10:05:23.780  6771  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 10:05:23.780  6771  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 10:05:23.780  6771  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 10:05:23.780  6771  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 10:05:23.780  6771  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 10:05:23.783  6771  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 10:05:23.785  6771  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 10:05:23.785  6771  6850 I jxcore-log: 
,08-24 10:05:23.786  6771  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 10:05:23.786  6771  6850 I jxcore-log: 
08-24 10:05:24.291  6771  6850 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-24 10:05:24.291  6771  6850 I jxcore-log: Failed to execute UT.
08-24 10:05:24.291  6771  6850 I jxcore-log: 
08-24 10:05:24.292  6771  6850 I jxcore-log: Unit Test app is loaded
08-24 10:05:24.292  6771  6850 I jxcore-log: 
,08-24 10:05:24.301  6771  6771 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 10:05:24.310  6771  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 10:05:24.310  6771  6850 I jxcore-log: 
,08-24 10:05:24.325  6771  6850 I jxcore-log: My device name is: LGE-LG-D855
08-24 10:05:24.325  6771  6850 I jxcore-log: 
,08-24 10:05:32.023  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 10:05:32.023  6771  6850 I jxcore-log: 
,08-24 10:05:32.947  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 10:05:32.947  6771  6850 I jxcore-log: 
,08-24 10:05:32.973  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 10:05:32.973  6771  6850 I jxcore-log: 
,08-24 10:05:32.978  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 10:05:32.978  6771  6850 I jxcore-log: 
,08-24 10:05:32.994  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 10:05:32.994  6771  6850 I jxcore-log: 
,08-24 10:05:32.998  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 10:05:32.998  6771  6850 I jxcore-log: 
08-24 10:05:36.122  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 10:05:36.122  6771  6850 I jxcore-log: 
,08-24 10:05:36.136  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 10:05:36.136  6771  6850 I jxcore-log: 
,08-24 10:05:36.146  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-24 10:05:36.146  6771  6850 I jxcore-log: 
,08-24 10:05:36.301  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 10:05:36.301  6771  6850 I jxcore-log: 
,08-24 10:05:37.101  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 10:05:37.101  6771  6850 I jxcore-log: 
,08-24 10:05:37.347  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 10:05:37.347  6771  6850 I jxcore-log: 
,08-24 10:05:37.353  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 10:05:37.353  6771  6850 I jxcore-log: 
,08-24 10:05:37.542  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 10:05:37.542  6771  6850 I jxcore-log: 
,08-24 10:05:37.563  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 10:05:37.563  6771  6850 I jxcore-log: 
,08-24 10:05:37.567  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 10:05:37.567  6771  6850 I jxcore-log: 
,08-24 10:05:37.573  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 10:05:37.573  6771  6850 I jxcore-log: 
,08-24 10:05:37.587  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 10:05:37.587  6771  6850 I jxcore-log: 
,08-24 10:05:37.605  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 10:05:37.605  6771  6850 I jxcore-log: 
,08-24 10:05:37.685  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-24 10:05:37.685  6771  6850 I jxcore-log: 
,08-24 10:05:37.693  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-24 10:05:37.693  6771  6850 I jxcore-log: 
,08-24 10:05:37.718  6771  6850 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-24 10:05:37.718  6771  6850 I jxcore-log: 
,08-24 10:05:37.728  6771  6850 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-24 10:05:37.730  6771  6850 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-24 10:05:37.730  6771  6850 I jxcore-log: 
08-24 10:05:47.230   309   309 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
08-24 10:05:47.230   309   309 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-24 10:05:47.230   309   309 I rmt_storage: wakelock acquired: 1, error no: 42
08-24 10:05:47.231   309   906 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,08-24 10:05:47.340   309   906 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
08-24 10:05:47.340   309   906 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-24 10:05:47.340   309   906 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
08-24 10:05:47.340   309   906 I rmt_storage: 
,08-24 10:05:47.343   309   309 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
08-24 10:05:47.344   905   917 E Diag_Lib: [IMS_FATAL]| 3347 | 917 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-24 10:06:00.070  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:06:00.071  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:06:00.071  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:06:00.072  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:06:00.083  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:06:00.083  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:06:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:06:00.087  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:06:35.103  1032  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=534321851, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,08-24 10:06:35.114  1032  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1ee45895 type 2 when 220479 android} when 220479
08-24 10:06:35.157  2618  2618 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 10:06:35.192  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=534321851 [*alarm*], flags=0x0
,08-24 10:06:38.433  1605  1605 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 10:06:38.434  1605  1605 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 10:06:38.448  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 10:06:38.448  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 10:06:38.451  1032  1405 D WifiController: battery changed pluggedType: 2
08-24 10:06:38.452  3915  4050 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 10:06:38.454  1943  2074 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 10:06:38.454  1943  2074 D LEDHandler: Battery Level Remaining: 100%
08-24 10:06:38.455  1943  2074 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-24 10:06:38.456  1605  1605 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-24 10:06:38.456  1605  1605 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 10:06:38.457  1605  1605 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 10:06:38.463  6645  6645 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 10:07:00.071  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:07:00.071  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:07:00.071  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:07:00.072  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:07:00.083  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:07:00.083  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:07:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:07:00.087  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:08:00.072  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:08:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:08:00.072  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:08:00.073  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:08:00.085  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:08:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:08:00.087  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:08:00.089  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:08:06.163  1032  3524 I LocationManagerService: remove 1699d25b
,08-24 10:08:06.169  1032  3524 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-24 10:08:06.171  1032  3524 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 10:08:06.172  1032  3524 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-24 10:08:06.175  1032  3524 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-24 10:08:06.176  1032  3524 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-24 10:09:00.072  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:09:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:09:00.072  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:09:00.073  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:09:00.085  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:09:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:09:00.087  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:09:00.089  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:10:00.004  1032  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=534321851, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,08-24 10:10:00.037  1032  1377 V AlarmManager: RTC_WAKEUP set : Alarm{15180d9b type 0 when 1472026185387 com.google.android.gms} when 1472026185387
,08-24 10:10:00.058  1819  6864 I EventLogService: Aggregate from 1472025809602 (log), 1472024385286 (data)
,08-24 10:10:00.065  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:10:00.065  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:10:00.065  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:10:00.065  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
08-24 10:10:00.068  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:10:00.068  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:10:00.068  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:10:00.086  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:10:00.089  2618  2618 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 10:10:00.122  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=534321851 [*alarm*], flags=0x0
,08-24 10:10:00.650  1032  1048 I art     : Explicit concurrent mark sweep GC freed 35091(1647KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 3.511ms total 227.838ms
,08-24 10:11:00.084  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:11:00.084  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:11:00.084  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:11:00.085  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:11:00.095  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:11:00.095  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:11:00.098  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:11:00.102  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:12:00.072  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:12:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:12:00.072  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:12:00.073  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:12:00.084  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:12:00.084  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:12:00.087  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:12:00.089  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:13:00.072  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:13:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:13:00.072  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:13:00.073  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:13:00.085  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:13:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:13:00.088  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:13:00.091  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:13:02.224  1605  1605 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 10:13:02.224  1605  1605 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 10:13:02.240  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 10:13:02.240  1032  1405 D WifiController: battery changed pluggedType: 2
,08-24 10:13:02.242  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 10:13:02.245  1943  2074 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 10:13:02.245  1943  2074 D LEDHandler: Battery Level Remaining: 100%
08-24 10:13:02.245  1943  2074 D LEDHandler: Battery Temp: 279, mChargingStatus=5, mChargingStop=false
08-24 10:13:02.247  1605  1605 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
08-24 10:13:02.247  1605  1605 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 10:13:02.248  1605  1605 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 10:13:02.250  3915  4050 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 10:13:02.256  6645  6645 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 10:13:17.924  1032  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=534321851, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,08-24 10:13:17.974  2618  2618 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 10:13:18.004  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=534321851 [*alarm*], flags=0x0
,08-24 10:14:00.071  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:14:00.071  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:14:00.071  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:14:00.072  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:14:00.082  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:14:00.083  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:14:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:14:00.087  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:14:15.602  1032  1710 I ActivityManager: Killing 6322:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-24 10:14:15.634  1032  1048 W libprocessgroup: failed to open /acct/uid_10014/pid_6322/cgroup.procs: No such file or directory
,08-24 10:15:00.072  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:15:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:15:00.072  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:15:00.073  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:15:00.084  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:15:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:15:00.087  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:15:00.089  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:15:01.769  1032  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=534321851, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,08-24 10:15:01.858  1032  1093 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6897 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-24 10:15:01.901  2618  2618 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 10:15:02.023  6897  6897 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR,
,08-24 10:15:02.028  6897  6897 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@16a4ade3
08-24 10:15:02.028  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=534321851 [*alarm*], flags=0x0
08-24 10:15:02.030  1032  1925 I ActivityManager: Killing 6304:com.android.defcontainer/u0a4 (adj 15): empty #17
08-24 10:15:02.072  1032  1616 W libprocessgroup: failed to open /acct/uid_10004/pid_6304/cgroup.procs: No such file or directory
,08-24 10:15:34.253  1605  1605 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 10:15:34.253  1605  1605 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 10:16:00.071  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:16:00.071  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:16:00.071  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:16:00.072  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:16:00.083  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:16:00.083  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:16:00.086  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:16:00.088  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:17:00.072  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:17:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:17:00.072  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:17:00.073  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:17:00.085  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:17:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:17:00.087  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:17:00.089  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:18:00.071  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:18:00.071  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:18:00.071  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:18:00.072  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:18:00.083  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:18:00.083  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:18:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:18:00.087  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:18:02.667  1032  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=534321851, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,08-24 10:18:02.672  1032  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{30453538 type 2 when 930021 com.google.android.gms} when 930021
,08-24 10:18:02.710  2618  2618 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 10:18:02.731  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=534321851 [*alarm*], flags=0x0
,08-24 10:18:02.820  2156  3025 D GCM     : Message class com.google.e.a.a.h
08-24 10:18:14.032  1032  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{4fee911 type 2 when 944253 com.android.bluetooth} when 944253
,08-24 10:18:14.051  3915  4132 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 10:18:14.051  3915  4132 W bt-smp  : Plain text(LSB ~ MSB) = 71 29 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 10:18:14.051  3915  4132 W bt-smp  : Encrypted text(LSB ~ MSB) = 06 8f 1f dd 2f 83 4f 4c 2c 37 24 02 6b 81 fb 0e 
08-24 10:18:14.051  3915  4132 W bt-btm  : Stopping oneshot timer
,08-24 10:19:00.072  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:19:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:19:00.072  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:19:00.073  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:19:00.084  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:19:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:19:00.087  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:19:00.089  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:20:00.072  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:20:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:20:00.072  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:20:00.073  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:20:00.084  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:20:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:20:00.087  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:20:00.089  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 10:20:40.672  1605  1605 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 10:20:40.673  1605  1605 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 10:20:40.688  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 10:20:40.688  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 10:20:40.689  1032  1405 D WifiController: battery changed pluggedType: 2
08-24 10:20:40.694  1605  1605 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
08-24 10:20:40.694  1605  1605 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 10:20:40.695  1943  2074 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 10:20:40.696  1943  2074 D LEDHandler: Battery Level Remaining: 100%
08-24 10:20:40.696  1943  2074 D LEDHandler: Battery Temp: 277, mChargingStatus=5, mChargingStop=false
08-24 10:20:40.696  3915  4050 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 10:20:40.697  1605  1605 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 10:20:40.703  6645  6645 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 10:21:00.051  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:21:00.051  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:21:00.051  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:21:00.052  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:21:00.063  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:21:00.063  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:21:00.065  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:21:00.067  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:22:00.071  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:22:00.071  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:22:00.071  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:22:00.072  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:22:00.084  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:22:00.084  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:22:00.086  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:22:00.088  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:22:50.071  1032  1092 I UsageStatsService: User[0] Flushing usage stats to disk
,08-24 10:23:00.071  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:23:00.071  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:23:00.071  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:23:00.072  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:23:00.083  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:23:00.083  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:23:00.086  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:23:00.088  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:24:00.071  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:24:00.071  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:24:00.071  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:24:00.072  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:24:00.084  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:24:00.084  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:24:00.086  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:24:00.088  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:25:00.072  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:25:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:25:00.072  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:25:00.073  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:25:00.085  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:25:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:25:00.088  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:25:00.089  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:26:00.072  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:26:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:26:00.072  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:26:00.073  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:26:00.085  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:26:00.085  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:26:00.087  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:26:00.089  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:27:00.071  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:27:00.071  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:27:00.071  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:27:00.072  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:27:00.084  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:27:00.084  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:27:00.087  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:27:00.089  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 10:28:00.072  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 10:28:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 10:28:00.072  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 10:28:00.073  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-24 10:28:00.085  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 10:28:00.086  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:28:00.088  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-24 10:28:00.091  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,TIME-OUT KILL (timeout was 1400000ms)
```
