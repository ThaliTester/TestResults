#### Test 829140730a15ac0_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-07 13:17:00.101  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 13:17:00.101  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 13:17:00.102  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 13:17:00.102  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,09-07 13:17:00.115  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 13:17:00.115  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 13:17:00.116  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 13:17:00.116  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 13:17:00.499  6645  6645 D AndroidRuntime: 
09-07 13:17:00.499  6645  6645 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 13:17:00.506  6645  6645 D AndroidRuntime: CheckJNI is OFF
09-07 13:17:00.707  6645  6645 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 13:17:00.717  1034  1944 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 13:17:00.733  1927  2856 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-07 13:17:00.739  1034  1944 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-07 13:17:00.740  1034  1944 D ActivityManager: setTaskToReturnTo : TaskRecord{247b26bc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 13:17:00.740  1034  1944 D ActivityManager: setTaskToReturnTo : TaskRecord{247b26bc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 13:17:00.742  1034  1944 D WindowStateEx: AppWindowTokenEx init.. 
09-07 13:17:00.743   331   345 E GBMv2   : DFP En is all cleared set to be enabled
09-07 13:17:00.771  1034  1944 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6660 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 13:17:00.774  6645  6645 D AndroidRuntime: Shutting down VM
09-07 13:17:00.833  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-07 13:17:00.834  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2d974860 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 13:17:00.835  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-07 13:17:00.835  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1bb74119 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 13:17:00.889  6660  6660 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-07 13:17:00.979  6660  6660 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-07 13:17:00.988  6660  6660 I LibraryLoader: Loading: webviewchromium
09-07 13:17:00.990  6660  6660 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7144-7147)
09-07 13:17:00.991  6660  6660 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 13:17:01.007  6660  6660 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f908d0e}
,09-07 13:17:01.008  6660  6660 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 13:17:01.008  6660  6660 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 13:17:01.017  6660  6660 I BrowserStartupController: Initializing chromium process, renderers=0
09-07 13:17:01.018  6660  6660 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 13:17:01.036  6660  6660 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-07 13:17:01.036  6660  6660 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,09-07 13:17:01.037  6660  6660 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-07 13:17:01.052   312  1365 V AudioPolicyService: registerClient() client 0xb1427bc0, uid 10118
,09-07 13:17:01.064  6660  6660 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 13:17:01.064  6660  6660 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 13:17:01.064  6660  6660 I Adreno-EGL: Build Date: 12/12/14 금
09-07 13:17:01.064  6660  6660 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 13:17:01.064  6660  6660 I Adreno-EGL: Remote Branch: 
09-07 13:17:01.064  6660  6660 I Adreno-EGL: Local Patches: 
09-07 13:17:01.064  6660  6660 I Adreno-EGL: Reconstruct Branch: 
,09-07 13:17:01.093  1034  1117 D BluetoothManagerService: Message: 20
,09-07 13:17:01.094  1034  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15a1ad66:true
09-07 13:17:01.193  6660  6707 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-07 13:17:01.196  6660  6660 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-07 13:17:01.216  6660  6660 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 13:17:01.222  6660  6660 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-07 13:17:01.225  6660  6660 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-07 13:17:01.229  6660  6660 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-07 13:17:01.229  6660  6660 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-07 13:17:01.246  6660  6660 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-07 13:17:01.255  6660  6660 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 13:17:01.255  6660  6660 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 13:17:01.292  6660  6722 D OpenGLRenderer: Render dirty regions requested: true
09-07 13:17:01.292  6660  6722 I OpenGLRenderer: Initialized EGL, version 1.4
09-07 13:17:01.298  6660  6722 D OpenGLRenderer: Enabling debug mode 0
09-07 13:17:01.304  6660  6660 D Atlas   : Validating map...
,09-07 13:17:01.308  1034  1945 D SplitWindow: check instance of lgWin Window{9e307f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 13:17:01.383  6660  6720 D LgDataFeature: LgDataFeature() Constructor: none
09-07 13:17:01.383  6660  6720 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 13:17:01.422  1034  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +590ms (total +678ms)
09-07 13:17:01.422  1034  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3fa4f645 u0 com.test.thalitest/.MainActivity t6} time:167579
,09-07 13:17:01.424  6660  6660 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@17be4f35 time:167581
09-07 13:17:01.615  6660  6660 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 13:17:01.689  6660  6720 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-07 13:17:01.689  6660  6720 I chromium: 
,09-07 13:17:01.820  6660  6736 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435108352
,09-07 13:17:01.835  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 13:17:01.835  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 13:17:01.835  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 13:17:01.835  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 13:17:01.835  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-07 13:17:01.835  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1382dde9 added. We now have 1 listener(s)
09-07 13:17:01.841  1034  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 13:17:01.844  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-07 13:17:01.848  6660  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 13:17:01.851  6660  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:01.851  6660  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:17:01.853  6660  6660 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-07 13:17:01.853  6660  6660 I chromium: 
,09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 13:17:01.861  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2847299c added. We now have 1 listener(s)
09-07 13:17:01.862  6660  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:01.866  1034  1528 D WifiService: New client listening to asynchronous messages
,09-07 13:17:01.871  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 13:17:01.871  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 13:17:01.873  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 13:17:01.873  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 13:17:01.873  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 13:17:01.877  6660  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:01.878  1034  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 13:17:01.880  6660  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-07 13:17:01.896  6660  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-07 13:17:01.896  6660  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:01.896  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:01.896  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:01.896  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:01.896  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:01.896  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:01.896  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:01.896  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:01.896  6660  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 13:17:01.897  6660  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:17:01.900  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:01.902  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:01.902  6660  6736 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 13:17:01.940  6660  6660 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 13:17:02.692   331   347 E GBMv2   : DFP En is all cleared set to be enabled
09-07 13:17:02.692   331   347 E GBMv2   : Set value is all cleared set the max
,09-07 13:17:02.692   331   347 I GBMv2   : DFP Enabled. Ignore VFP set
09-07 13:17:03.109  6660  6739 W jxcore-log: Initializing JXcore engine
09-07 13:17:03.109  6660  6739 W jxcore-log: JXcore engine is ready
,09-07 13:17:03.174  6739  6739 W Thread-762: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8268]" dev="sockfs" ino=8268 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-07 13:17:03.174  6739  6739 W Thread-762: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-07 13:17:03.174  6739  6739 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7718]" dev="sockfs" ino=7718 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-07 13:17:03.174  6739  6739 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,09-07 13:17:03.174  6739  6739 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30916]" dev="sockfs" ino=30916 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-07 13:17:03.226  6660  6739 W jxcore-log: Starting JXcore engine
,09-07 13:17:03.401  6660  6739 W jxcore-log: Platform android
09-07 13:17:03.401  6660  6739 W jxcore-log: 
09-07 13:17:03.401  6660  6739 W jxcore-log: Process ARCH arm
09-07 13:17:03.401  6660  6739 W jxcore-log: 
,09-07 13:17:03.812  6660  6739 I jxcore-log: JXcore Cordova bridge is ready!
09-07 13:17:03.812  6660  6739 I jxcore-log: 
,09-07 13:17:03.814  6660  6739 W jxcore-log: JXcore engine is started
09-07 13:17:03.821  6660  6736 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-07 13:17:03.826  6660  6660 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 13:17:21.183  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 13:17:21.183  6660  6739 I jxcore-log: 
,09-07 13:17:21.186  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 13:17:21.186  6660  6739 I jxcore-log: 
09-07 13:17:21.190  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:21.190  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:21.190  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:21.190  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:21.190  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:21.190  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:21.190  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:21.190  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:21.193  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:21.196  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 13:17:21.196  6660  6739 I jxcore-log: 
09-07 13:17:21.197  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 13:17:21.197  6660  6739 I jxcore-log: 
,09-07 13:17:21.701  6660  6739 D executeNativeTests: Running unit tests
,09-07 13:17:21.782  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:17:21.782  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 added. We now have 2 listener(s)
,09-07 13:17:21.783  1034  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:21.784  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 13:17:21.785  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:21.785  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:17:21.785  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:21.785  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be added. We now have 2 listener(s)
09-07 13:17:21.785  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:21.785  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 13:17:21.786  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:21.789  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:21.789  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:21.789  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:21.789  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:21.789  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:21.789  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:21.789  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:21.789  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:21.791  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:21.791  6660  6739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:17:21.792  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:21.793  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:21.801  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 13:17:21.803  6660  6739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 13:17:21.803  6660  6739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 13:17:21.807  6660  6739 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 13:17:21.808  6660  6739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 13:17:21.808  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 13:17:21.808  6660  6739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 13:17:21.808  6660  6739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 13:17:21.809  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.809  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.810  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.810  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.810  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.810  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:21.810  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:17:21.810  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 removed from the list
09-07 13:17:21.810  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.810  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be removed from the list
09-07 13:17:21.810  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.810  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:17:21.811  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.811  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:17:21.812  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 13:17:21.812  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.812  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:17:21.812  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.814  6660  6739 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 13:17:21.814  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.814  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.814  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 13:17:21.814  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.814  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:17:21.814  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.814  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.814  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.814  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.814  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.814  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.814  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.814  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.814  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.816  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 13:17:21.816  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-07 13:17:21.816  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.816  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.821  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 13:17:21.821  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 13:17:21.821  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 13:17:21.821  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 13:17:21.821  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-07 13:17:21.821  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 13:17:21.821  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 13:17:21.821  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 13:17:21.821  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-07 13:17:21.821  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210],
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 13:17:21.822  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 13:17:21.822  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.822  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.822  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.823  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.823  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.823  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.823  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.823  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.823  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.823  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.823  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.823  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.823  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.823  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.824  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.824  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.824  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.824  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.825  6660  6739 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 13:17:21.826  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:21.828  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:21.828  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:21.828  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:21.828  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:21.828  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:21.828  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:21.828  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:21.828  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:21.829  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:21.829  6660  6739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:17:21.830  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:21.831  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:21.832  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:17:21.832  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:17:21.834  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:17:21.834  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:21.834  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 13:17:21.837  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 13:17:21.837  1034  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:21.841  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 13:17:21.845  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 13:17:21.846  6660  6739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 13:17:21.847  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 13:17:21.848  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:21.849  6660  6739 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 13:17:21.849  6660  6739 I io.jxcore.node.ConnectionHelper: start: OK
09-07 13:17:21.851  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.851  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.851  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.851  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.851  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.851  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:21.851  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.851  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.851  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.851  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.851  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.851  6660  6739 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 13:17:21.853  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:21.855  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:21.855  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:21.855  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:21.855  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:21.855  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:21.855  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:21.855  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:21.855  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:17:21.856  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:21.856  6660  6739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:17:21.857  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:21.858  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:21.858  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:17:21.858  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:17:21.858  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:17:21.858  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:21.858  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 13:17:21.861  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 13:17:21.861  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:21.862  6660  6739 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 13:17:21.862  6660  6739 I io.jxcore.node.ConnectionHelper: start: OK
09-07 13:17:21.863  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.863  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.863  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.863  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.863  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.864  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:21.864  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.864  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.864  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.864  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.864  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.864  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.864  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.865  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.865  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.866  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.866  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.866  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.866  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.866  6660  6739 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 13:17:21.868  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:21.869  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:21.869  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:21.869  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:21.869  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:21.869  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:21.869  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:21.869  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:21.869  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:21.870  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:21.870  6660  6739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:17:21.871  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:17:21.871  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:17:21.871  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:17:21.871  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:21.871  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 13:17:21.872  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:21.874  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:21.874  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 13:17:21.875  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:21.875  6660  6739 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 13:17:21.875  6660  6739 I io.jxcore.node.ConnectionHelper: start: OK
09-07 13:17:21.875  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.876  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.876  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.876  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.876  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.876  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.876  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.876  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.876  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:21.876  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.876  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.876  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.876  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.876  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.877  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.877  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.877  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.877  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.878  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.878  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.878  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.878  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.878  6660  6739 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 13:17:21.878  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.878  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.878  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.878  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.879  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.879  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.879  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.879  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.879  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.879  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.879  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.879  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.879  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.879  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.879  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.879  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.880  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.880  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.880  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.880  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.881  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 13:17:21.881  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.881  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.881  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.881  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.881  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.881  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.881  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.881  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.881  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.881  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.881  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.881  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.881  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.881  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.882  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.882  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.882  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.882  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.882  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.883  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.883  6660  6739 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 13:17:21.883  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.883  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.883  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.883  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.883  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.883  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.883  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.883  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.883  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.884  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.884  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.884  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.884  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.884  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.884  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.884  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.885  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.885  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.885  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.885  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
,09-07 13:17:21.885  6660  6739 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 13:17:21.885  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.885  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.885  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.886  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.886  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.886  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.886  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.886  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.886  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.886  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.886  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.886  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.886  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.886  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.887  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.887  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.887  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.887  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.887  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.887  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.887  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 13:17:21.888  6660  6739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 13:17:21.888  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 13:17:21.888  6660  6739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 13:17:21.889  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 13:17:21.889  6660  6739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 13:17:21.889  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.889  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.889  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.889  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.889  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.889  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.889  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.889  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.889  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.889  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.889  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.889  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.889  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.889  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.890  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.890  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.892  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.892  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.892  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.892  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.892  6660  6739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:17:21.893  6660  6739 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 13:17:21.893  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 13:17:21.896  6660  6739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:17:21.896  6660  6739 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 13:17:21.896  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 13:17:21.896  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 13:17:21.896  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 13:17:21.897  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 13:17:21.897  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 13:17:21.897  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 13:17:21.897  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 13:17:21.897  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 13:17:21.897  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 13:17:21.897  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 13:17:21.897  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 13:17:21.897  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 13:17:21.897  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 13:17:21.897  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 13:17:21.898  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 13:17:21.898  6660  6739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 13:17:21.898  6660  6739 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 13:17:21.898  6660  6739 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 13:17:21.898  6660  6739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:17:21.898  6660  6739 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 13:17:21.898  6660  6739 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 13:17:21.899  6660  6739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:17:21.899  6660  6739 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 13:17:21.899  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 13:17:21.901  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 13:17:21.901  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 13:17:21.901  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 13:17:21.902  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 13:17:21.902  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 13:17:21.902  6660  6739 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 13:17:21.902  6660  6739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:17:21.902  6660  6739 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 13:17:21.902  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.902  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.902  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.903  6660  6765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
09-07 13:17:21.913  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.913  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.913  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.914  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 13:17:21.918  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.918  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.918  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.918  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.918  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.918  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.919  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.919  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.919  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.919  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.920  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.920  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.920  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.920  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.920  6660  6739 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 13:17:21.920  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.921  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.921  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.921  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.921  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.921  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.921  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.921  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.921  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.921  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.921  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.921  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.921  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.921  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.921  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.921  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.922  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.922  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.922  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.922  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.922  6660  6739 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 13:17:21.923  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.923  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.923  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.923  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.923  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.923  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.923  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.923  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.923  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.923  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.923  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.923  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.923  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.923  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.924  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.924  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.924  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.924  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.924  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.924  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.925  6660  6739 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 13:17:21.925  6660  6739 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 13:17:21.925  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 13:17:21.925  6660  6739 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 13:17:21.925  6660  6739 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 13:17:21.925  6660  6739 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 13:17:21.925  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 13:17:21.925  6660  6739 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 13:17:21.925  6660  6739 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 13:17:21.925  6660  6739 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 13:17:21.925  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 13:17:21.925  6660  6739 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 13:17:21.925  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.925  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.925  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.927  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.927  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.927  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.927  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.927  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.927  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.927  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.927  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.927  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.927  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.927  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.929  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.929  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.930  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.930  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.930  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.930  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.931  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.931  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.931  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.931  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.931  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.931  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.931  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.931  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.931  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.932  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.932  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.932  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.932  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.932  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.932  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.932  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.932  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.932  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.932  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.932  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.932  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.932  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.932  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.932  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.932  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.932  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.932  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.932  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.932  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.933  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.933  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.934  6660  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
09-07 13:17:21.934  6660  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
09-07 13:17:21.934  6660  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
09-07 13:17:21.934  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.934  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.934  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.934  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.935  6660  6739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 13:17:21.935  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:21.936  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 13:17:21.936  6660  6739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 13:17:21.936  6660  6739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 13:17:21.937  6660  6660 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 13:17:21.937  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 13:17:21.937  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 13:17:21.938  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.938  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 13:17:21.938  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 13:17:21.938  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 13:17:21.938  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.938  6660  6739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 13:17:21.938  6660  6660 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 13:17:21.938  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.938  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.938  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 13:17:21.938  1034  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:21.938  6660  6739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 13:17:21.938  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 13:17:21.939  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 13:17:21.939  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:21.939  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:21.939  6660  6776 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:17:21.939  6660  6739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 13:17:21.940  3865  3990 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-07 13:17:21.939  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.940  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.940  6660  6739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:17:21.941  6660  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 13:17:21.941  6660  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 13:17:21.941  6660  6660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:17:21.941  6660  6660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:17:21.941  6660  6660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:17:21.941  6660  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 13:17:21.941  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.941  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.941  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.941  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.941  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.941  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.941  6660  6660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 13:17:21.941  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.941  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.941  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.941  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.941  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.941  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.941  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.941  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.941  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.942  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.942  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.942  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.942  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.943  6660  6739 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 13:17:21.946  6660  6739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 13:17:21.946  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 13:17:21.947  6660  6739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 13:17:21.947  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.947  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.947  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.947  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.948  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.948  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.948  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.948  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.948  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.948  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.948  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.948  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.948  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.948  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.950  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.950  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.950  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.950  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.951  1034  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:21.951  1034  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:21.952  1034  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:21.952  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.952  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.952  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.952  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.952  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.952  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.952  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.953  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.953  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.953  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.953  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.953  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.953  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.953  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.953  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.953  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.953  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.953  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.954  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:21.954  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:21.954  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:21.954  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:21.954  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.954  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.954  6660  6739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ce879 not in the list
09-07 13:17:21.954  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.954  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.954  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:21.954  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.954  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.954  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:21.954  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:21.955  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:21.955  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:21.955  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:21.955  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa09be not in the list
09-07 13:17:21.956  6660  6739 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 13:17:21.956  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 13:17:21.957  6660  6739 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 13:17:21.957  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 13:17:21.957  6660  6739 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 13:17:21.957  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 13:17:21.958  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 13:17:21.958  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 13:17:21.958  6660  6739 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 13:17:21.959  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 13:17:21.959  6660  6739 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 13:17:21.959  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 13:17:21.959  6660  6739 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 13:17:21.959  6660  6739 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 13:17:21.959  6660  6739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 13:17:21.959  6660  6739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 13:17:21.960  6660  6739 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 13:17:21.960  6660  6739 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 13:17:21.960  6660  6739 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 13:17:21.960  6660  6739 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 13:17:21.960  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:21.961  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e2b4e17 added. We now have 2 listener(s)
09-07 13:17:21.961  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:17:21.963  6660  6739 D BluetoothAdapter: enable(): BT is already enabled..!
09-07 13:17:21.964  1034  1836 D WifiServiceImplEx: setWifiEnabled: true pid=6660, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 13:17:21.964  1034  1836 D WifiService: setWifiEnabled: true pid=6660, uid=10118
09-07 13:17:21.964  1034  1836 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 13:17:21.966  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:21.966  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27057204 added. We now have 3 listener(s)
09-07 13:17:21.966  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:21.968  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:21.968  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3926f3ed added. We now have 4 listener(s)
09-07 13:17:21.968  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:21.969  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:21.969  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a364222 added. We now have 5 listener(s)
09-07 13:17:21.969  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:21.971  1034  1836 D WifiServiceImplEx: setWifiEnabled: false pid=6660, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 13:17:21.971  1034  1836 D WifiService: setWifiEnabled: false pid=6660, uid=10118
09-07 13:17:21.971  1034  1836 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 13:17:21.982  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 13:17:21.982  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 13:17:21.982  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-07 13:17:21.983  1034  1633 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:21.983  1034  1633 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3588ac13 mBinding = false
09-07 13:17:21.983  1034  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 13:17:21.983  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 13:17:21.984  1034  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-07 13:17:21.984  1034  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-07 13:17:21.984  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-07 13:17:21.985  1034  1522 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 13:17:21.985  1034  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 13:17:21.985  1034  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 13:17:21.985  1034  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 13:17:21.985  1034  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 13:17:21.990  1034  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 13:17:21.991  1034  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:21.991  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:21.991  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 13:17:21.991  2760  2760 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 13:17:21.992  1034  1117 D BluetoothManagerService: Message: 2
09-07 13:17:21.992  1034  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 13:17:21.992  1034  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 13:17:21.992  1034  1117 D BluetoothManagerService: Sending off request.
09-07 13:17:21.993  1034  1522 D WifiNative-wlan0: SET ps 1: returned true
09-07 13:17:21.993  3865  3883 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-07 13:17:21.993  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 13:17:21.993  3865  3948 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-07 13:17:21.993  3865  3948 D BluetoothAdapterProperties: Setting state to 13
09-07 13:17:21.993  3865  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 13:17:21.993  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 13:17:21.993  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-07 13:17:21.993  3865  3948 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 13:17:21.994  3865  3948 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-07 13:17:21.994   308   892 D CommandListener: Clearing all IP addresses on wlan0
09-07 13:17:21.994  1034  1117 D BluetoothManagerService: Message: 60
09-07 13:17:21.994  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-07 13:17:21.994  1034  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-07 13:17:21.994  1034  2861 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:22.004  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:17:22.009  3865  3865 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:22.009  3865  3865 D BluetoothMapService: STATE_TURNING_OFF
09-07 13:17:22.009  3865  3865 V BluetoothMapService: Handler(): got msg=4
09-07 13:17:22.009  3865  3865 D BluetoothMapService: MAP Service closeService in
09-07 13:17:22.009  3865  3865 D BluetoothMapMasInstance: MAP Service shutdown
09-07 13:17:22.010  3865  4186 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-07 13:17:22.010  3865  4186 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 13:17:22.010  3865  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-07 13:17:22.010  3865  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-07 13:17:22.010  3865  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-07 13:17:22.010  3865  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-07 13:17:22.010  3865  4186 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-07 13:17:22.010  3865  4186 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-07 13:17:22.010  3865  3865 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 13:17:22.010  3865  3865 V BluetoothMapService: MAP Service closeService out
09-07 13:17:22.010  3865  3865 V BtOppService: Receiver DISABLED_ACTION 
09-07 13:17:22.011  3865  3865 I BtOppRfcommListener: stopping Accept Thread
09-07 13:17:22.011  3865  3865 V BtOppRfcommListener: close mBtServerSocket
09-07 13:17:22.011  3865  3865 V BtOppRfcommListener: waiting for thread to terminate
09-07 13:17:22.012  3865  4246 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 13:17:22.013  3865  4246 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 13:17:22.013  3865  3865 V BtOppRfcommListener: done waiting for thread to terminate
09-07 13:17:22.013  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 13:17:22.019  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.019  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:22.019  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:22.019  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:22.019  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:22.019  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:22.019  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:22.019  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:22.019  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:17:22.020  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 13:17:22.020  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-07 13:17:22.043  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.043  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 13:17:22.045  6660  6765 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-07 13:17:22.046  6660  6765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
09-07 13:17:22.055  1034  1098 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6782 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-07 13:17:22.056  3865  3952 D BluetoothAdapterProperties: Scan Mode:20
09-07 13:17:22.056  3865  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 13:17:22.056  3865  4187 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 13:17:22.057  3865  3948 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 13:17:22.057  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-07 13:17:22.057  3865  4057 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-07 13:17:22.058  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 13:17:22.058  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 13:17:22.058  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 13:17:22.058  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 13:17:22.058  3865  4057 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:17:22.058  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 13:17:22.058  3865  4057 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:17:22.058  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 13:17:22.058  3865  4057 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:17:22.058  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-07 13:17:22.058  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-07 13:17:22.058  3865  4057 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 13:17:22.058  3865  4247 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 13:17:22.059  3865  4250 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 13:17:22.061  1034  1521 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:22.061  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:22.061  1034  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@cf9605c
09-07 13:17:22.061  1034  1521 D LGWifiP2pService: P2pDisablingState
09-07 13:17:22.061  1034  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 1 0 cz
09-07 13:17:22.061  1034  1521 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:22.061  1034  1521 D LGWifiP2pService: p2p socket connection lost
09-07 13:17:22.061  1034  1521 D LGWifiP2pService: P2pDisabledState
09-07 13:17:22.062  1034  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:22.062  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:22.062  1034  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:22.064  3865  3865 V BtOppService: onDestroy
09-07 13:17:22.065  3865  3865 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-07 13:17:22.070  1034  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:22.070  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:22.071  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:22.071  1034  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:22.072  1034  1522 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 13:17:22.074  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.074  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:22.074  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:22.074  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:22.074  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:22.074  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:22.074  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:22.074  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:22.074  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:17:22.077  1034  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:22.077  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-07 13:17:22.078  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:22.078  1034  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:22.078  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:22.078  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:22.079  1034  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-07 13:17:22.079  1034  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:22.079  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 13:17:22.079  1034  1521 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:22.079  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 13:17:22.079  2760  2760 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 13:17:22.079  1034  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 13:17:22.079  1034  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 13:17:22.080  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.080  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:22.080  6660  6739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:17:22.081  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-07 13:17:22.081  1034  1522 D WifiNative-wlan0: SET ps 1: returned true
09-07 13:17:22.081  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-07 13:17:22.082  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:22.083   308   892 D CommandListener: Clearing all IP addresses on wlan0
09-07 13:17:22.083  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:22.083  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:22.083  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 13:17:22.084  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 13:17:22.084  1034  1034 D RttService: SCAN_AVAILABLE : 1
09-07 13:17:22.084  1034  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:22.086  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:22.086  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:22.086  1034  1540 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:22.087  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:22.087  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 13:17:22.087  1927  1927 D WfdsService: WifiP2pState is changed : false
09-,07 13:17:22.087  1927  2285 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-07 13:17:22.087  1927  2285 D WfdsService: Set the WFDS Monitor: false
09-07 13:17:22.088  1927  2285 D WfdsMonitor: WFDS Monitor is stopped
09-07 13:17:22.088  1927  2285 D WfdsService: STATE : WfdsDisabledState - enter
09-07 13:17:22.088  1927  2853 D CtrlSupplicant: Received on exit socket, terminate
09-07 13:17:22.088  1927  2853 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-07 13:17:22.088  1927  2853 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-07 13:17:22.088  1927  2853 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-07 13:17:22.088  1927  2287 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-07 13:17:22.088  1927  2285 W WfdsService: DefaultState - msg [9445378] is not handled
09-07 13:17:22.090  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.090  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:22.090  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:22.090  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:22.090  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:22.090  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:22.090  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:22.090  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:22.090  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:22.091  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.091  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:17:22.092  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:17:22.094  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:22.096  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:22.096  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:22.099  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:22.099  1034  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-07 13:17:22.099  1034  1529 D DSQN    : disableDataServiceNotify
09-07 13:17:22.100  1034  1529 D DSQN    : stop dsqn bin
09-07 13:17:22.106  1034  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-07 13:17:22.106  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:22.106  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:22.107  1034  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:22.107  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-07 13:17:22.108  1034  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-07 13:17:22.108  1034  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-07 13:17:22.108  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 13:17:22.109  1034  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:22.109  1034  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:22.109  1034  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-07 13:17:22.110  1587  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 13:17:22.119  1034  1098 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6803 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-07 13:17:22.120  1034  1522 D WifiNative-p2p0: doBoolean: TERMINATE
09-07 13:17:22.121  1034  1522 D WifiNative-p2p0: TERMINATE: returned true
09-07 13:17:22.121  1034  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 13:17:22.121  1034  1522 E WifiStateMachine: useWiFiOffloading() : false
09-07 13:17:22.121  1034  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 13:17:22.124  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:22.125  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 13:17:22.128  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 13:17:22.128  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:22.130  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 13:17:22.132  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-07 13:17:22.133  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:22.133  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:22.133  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 13:17:22.133  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 13:17:22.134  1034  1522 E WifiStateMachine:  SupplicantStoppingState CMD_SET_COUNTRY_CODE 1 0 cz
09-07 13:17:22.134  1034  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 13:17:22.134  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:22.134  1034  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:22.134  1034  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:22.134  1034  1529 D NetworkManagementService: Removing idletimer
09-07 13:17:22.134  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-07 13:17:22.135  1034  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:22.135  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:22.135  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 13:17:22.138  1034  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 13:17:22.138  1034  1522 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:22.138  1034  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:17:22.141  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.141  6782  6782 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:17:22.141  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:22.141  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:22.141  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:22.141  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:22.141  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:22.141  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:22.141  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:22.141  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:22.141  6782  6782 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-07 13:17:22.141  6660  6660 W org.thaliproject.p2p.btconnect,orlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.141  6782  6782 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 13:17:22.141  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:22.141  6782  6782 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-07 13:17:22.143  6782  6782 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-07 13:17:22.143  1034  2015 I art     : Explicit concurrent mark sweep GC freed 36613(1716KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.481ms total 126.673ms
09-07 13:17:22.144  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-07 13:17:22.145  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 13:17:22.145  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:22.145  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-07 13:17:22.145  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 13:17:22.145  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 13:17:22.145  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 13:17:22.145  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 13:17:22.145  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 13:17:22.145  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 13:17:22.149  1034  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-07 13:17:22.150  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.150  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:22.150  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:22.150  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:22.150  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:22.150  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:22.150  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:22.150  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:22.150  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:22.150  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.150  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:22.151  6782  6782 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 13:17:22.181  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 13:17:22.182  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 13:17:22.183  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:22.183  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 13:17:22.194  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 13:17:22.194  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:22.194  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:22.200  1034  2861 D DhcpStateMachine: StoppedState
09-07 13:17:22.200  1034  2861 D DhcpStateMachine: StoppedState{ when=-118ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:22.201  1034  1522 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-07 13:17:22.201  1034  1522 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-07 13:17:22.208  6803  6803 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-07 13:17:22.208  6803  6803 W LG Account v2.2: No ProfileInfo entries
09-07 13:17:22.208  6803  6803 I LG Account v2.2: isEnabled: false
09-07 13:17:22.209  6803  6803 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-07 13:17:22.209  6803  6803 I Feature : [Lifetracker]Country: EU
09-07 13:17:22.209  6803  6803 I Feature : [Lifetracker]Operator: OPEN
09-07 13:17:22.209  6803  6803 I Feature : [Lifetracker]Ranking support: false
09-07 13:17:22.209  6803  6803 I Feature : [Lifetracker]Comfort support: false
09-07 13:17:22.209  6803  6803 I Feature : [Lifetracker]Accessory: true
09-07 13:17:22.209  6803  6803 I Feature : [Lifetracker]Health device: true
09-07 13:17:22.209  6803  6803 I Feature : [Lifetracker]Extra Pedometer: false
09-07 13:17:22.209  6803  6803 I Feature : [Lifetracker]Blood glucose device: false
09-07 13:17:22.209  6803  6803 I Feature : [Lifetracker]Device Number: 3
09-07 13:17:22.217  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:22.244  2760  2760 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-07 13:17:22.244  2760  2760 I wpa_supplicant: monitor socket send errors count : 1
09-07 13:17:22.244  2760  2760 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-2\x00 that cannot receive messages
09-07 13:17:22.245  1034  2852 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-07 13:17:22.245  1034  2852 D WifiMonitor: Dropping event because (p2p0) is stopped
09-07 13:17:22.246  1034  1998 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6823 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-07 13:17:22.247  1034  1998 I ActivityManager: Killing 5886:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-07 13:17:22.282  2760  2760 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 13:17:22.282  1034  2852 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,09-07 13:17:22.282  1034  2852 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 13:17:22.282  1034  2852 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 13:17:22.282  1034  2852 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-07 13:17:22.282  1034  1522 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=188428
09-07 13:17:22.283  1034  2852 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 13:17:22.283  1034  2852 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 13:17:22.284  2760  2760 W wpa_supplicant: USIM:  scard_deinit function
09-07 13:17:22.285  1034  1522 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=188430
09-07 13:17:22.286  1034  1522 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=188431  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 13:17:22.286  1034  1980 W libprocessgroup: failed to open /acct/uid_10014/pid_5886/cgroup.procs: No such file or directory
09-07 13:17:22.287  1034  1522 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=188433  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 13:17:22.288  1034  1117 D Tethering: InitialState.processMessage what=4
09-07 13:17:22.298  1034  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 13:17:22.301  1034  1522 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:22.302  1034  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-07 13:17:22.354  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-07 13:17:22.364  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 13:17:22.365  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 13:17:22.369  1034  1890 I ActivityManager: Killing 6237:com.android.defcontainer/u0a4 (adj 15): empty #17
09-07 13:17:22.378  6782  6782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-07 13:17:22.395  2760  2760 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-07 13:17:22.396  1034  2852 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-07 13:17:22.396  1034  2852 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-TERMINATING 
09-07 13:17:22.396  1034  2852 D WifiMonitor: Disconnecting from the supplicant, no more events
09-07 13:17:22.396  1034  1522 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 19 0
,09-07 13:17:22.442  6660  6660 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 13:17:22.468  1034  1836 W libprocessgroup: failed to open /acct/uid_10004/pid_6237/cgroup.procs: No such file or directory
,09-07 13:17:22.479  3865  3865 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 13:17:22.480  3865  3865 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:22.480  3865  3865 V BluetoothPbapReceiver: ***********state = 13
,09-07 13:17:22.484  3865  3865 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-07 13:17:22.488  3865  3865 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:22.488  3865  3865 V BluetoothPbapService: state: 13
09-07 13:17:22.488  3865  3865 V BluetoothPbapService: Pbap Service closeService in
09-07 13:17:22.493  3865  3865 V BluetoothPbapService: successfully stopped pbap service
09-07 13:17:22.494  3865  3865 V BluetoothPbapService: Pbap Service closeService out
09-07 13:17:22.494  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 13:17:22.495  3865  3865 V BluetoothPbapService: Pbap Service onDestroy
09-07 13:17:22.495  3865  3865 V BluetoothPbapService: Pbap Service closeService in
09-07 13:17:22.495  3865  3865 V BluetoothPbapService: Pbap Service closeService out
09-07 13:17:22.496  3865  3865 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-07 13:17:22.505  1034  1522 D WifiOffDelayIfNotUsed: stopMonitoring
09-07 13:17:22.505  1034  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 13:17:22.505  1034  1522 E WifiStateMachine: useWiFiOffloading() : false
09-07 13:17:22.505  1034  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 13:17:22.507  1927  1927 D WfdsService: Supplicant Connection state is changed : false
09-07 13:17:22.507  1927  2285 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-07 13:17:22.508  1927  2285 D WfdsService: Set the WFDS Monitor: false
09-07 13:17:22.508  1927  2285 D WfdsMonitor: WFDS Monitor is stopped
,09-07 13:17:22.510  2484  2484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:22.511  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:22.512  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 13:17:22.513  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 13:17:22.522  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-07 13:17:22.523  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-07 13:17:22.523  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-07 13:17:22.525  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.525  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:22.525  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:22.525  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:22.525  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:22.525  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:22.525  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:22.525  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:22.525  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:17:22.529  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:22.529  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:22.529  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:22.529  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:22.529  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:22.529  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:22.529  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:22.529  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:22.529  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:17:22.564  6782  6782 D LgDataFeature: LgDataFeature() Constructor: none
,09-07 13:17:22.564  6782  6782 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 13:17:22.574  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:22.584  1034  1117 D BluetoothManagerService: Message: 20
09-07 13:17:22.584  1034  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fdcf005:true
,09-07 13:17:22.596  1034  1117 D BluetoothManagerService: Message: 30
09-07 13:17:22.606  1034  1117 D BluetoothManagerService: Message: 30
,09-07 13:17:22.610  6782  6782 D LocalBluetoothProfileManager: Adding local MAP profile
09-07 13:17:22.612  6782  6782 D BluetoothMap: Create BluetoothMap proxy object
09-07 13:17:22.612  1034  1117 D BluetoothManagerService: Message: 30
09-07 13:17:22.620  1034  1117 D BluetoothManagerService: Message: 30
,09-07 13:17:22.624  6782  6782 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-07 13:17:22.627  6782  6782 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-07 13:17:22.648  6782  6782 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-07 13:17:22.653  6782  6782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-07 13:17:22.672  6782  6782 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:17:22.702  6782  6782 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-07 13:17:22.707  1034  1522 E WifiStateMachine:  InitialState CMD_SET_COUNTRY_CODE 1 0 cz
,09-07 13:17:22.708  1034  1522 E WifiStateMachine:  DefaultState CMD_SET_COUNTRY_CODE 1 0 cz
09-07 13:17:22.712  6782  6782 D BluetoothInputDevice: Proxy object connected
09-07 13:17:22.714  6782  6782 D HidProfile: Bluetooth service connected
09-07 13:17:22.716  6782  6782 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 13:17:22.718  6782  6782 D PanProfile: Bluetooth service connected
09-07 13:17:22.719  6782  6782 D BluetoothMap: Proxy object connected
09-07 13:17:22.721  6782  6782 D MapProfile: Bluetooth service connected
09-07 13:17:22.721  6782  6782 D BluetoothMap: getConnectedDevices()
09-07 13:17:22.723  6782  6782 D BluetoothMap: Bluetooth is Not enabled
09-07 13:17:22.723  6782  6782 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-07 13:17:22.727  6782  6782 D BluetoothPermissionRequest: onReceive
09-07 13:17:22.731  6782  6782 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-07 13:17:22.744  1034  1908 I ActivityManager: Killing 6409:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-07 13:17:22.751  6782  6782 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 13:17:22.865  3865  3865 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-07 13:17:22.865  3865  3865 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-07 13:17:22.867  1034  1890 W libprocessgroup: failed to open /acct/uid_10008/pid_6409/cgroup.procs: No such file or directory
09-07 13:17:22.868  3865  3865 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-07 13:17:22.931  1034  1908 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6857 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-07 13:17:22.938  3865  3865 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:22.938  3865  3865 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 13:17:22.939  3865  3865 V BluetoothFtpService: Ftp Service onStartCommand
09-07 13:17:22.939  3865  3865 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:22.940  3865  3865 V BluetoothFtpService: Ftp Service closeService
09-07 13:17:22.940  3865  3865 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-07 13:17:22.947  3865  3865 V BluetoothFtpService: successfully stopped ftp service
09-07 13:17:22.948  3865  3865 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 13:17:22.948  3865  3865 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 13:17:22.948  3865  3865 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 13:17:22.948  3865  3865 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:22.948  3865  3865 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-07 13:17:22.948  3865  3865 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-07 13:17:22.951  3865  3865 V BluetoothFtpService: Ftp Service onDestroy
09-07 13:17:22.951  3865  3865 V BluetoothFtpService: Ftp Service closeService
09-07 13:17:23.010  1034  1980 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6878 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 13:17:23.021  3865  3865 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:23.021  3865  3865 V BluetoothSapService: state: 13
09-07 13:17:23.021  3865  3865 V BluetoothSapService: Stopping SAP server process
09-07 13:17:23.022  3865  3865 V BluetoothSapService: Sap Service closeSapService in
09-07 13:17:23.022  3865  3865 V BluetoothSapService: Close listen Socket : 
09-07 13:17:23.023  3865  3865 V BluetoothSapService: Close rfcomm Socket : 
09-07 13:17:23.023  3865  3865 V BluetoothSapService: Close sapd  Socket : 
09-07 13:17:23.024  3865  3865 V BluetoothSapService: Sap Service closeSapService out
,09-07 13:17:23.024  3865  3865 V BluetoothSapService: Sap Service onDestroy
09-07 13:17:23.024  3865  3865 V BluetoothSapService: Sap Service closeSapService in
09-07 13:17:23.024  3865  3865 V BluetoothSapService: Close listen Socket : 
09-07 13:17:23.024  3865  3865 V BluetoothSapService: Close rfcomm Socket : 
09-07 13:17:23.024  3865  3865 V BluetoothSapService: Close sapd  Socket : 
09-07 13:17:23.026  3865  3865 V BluetoothSapService: Sap Service closeSapService out
,09-07 13:17:23.054  6857  6857 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 13:17:23.060  3865  3952 D bt_hci_bdroid: cleanup
09-07 13:17:23.061  3865  4059 I bt_lpm  : LPM is already off!!!
09-07 13:17:23.061  3865  4057 W bt-btif : ag scb idx 1 not allocated
09-07 13:17:23.061  3865  4057 E bt-btif : BTA AG is already disabled, ignoring ...
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 13:17:23.061  3865  4176 I bt_userial_mct: exiting userial_read_thread
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:17:23.061  3865  4176 D bt_userial_mct: Leaving userial_evt_read_thread()
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 13:17:23.061  3865  4057 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:17:23.061  3865  4057 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 13:17:23.061  3865  3952 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 13:17:23.061  3865  4059 I bt_vendor: hw_epilog_process
09-07 13:17:23.062  3865  3952 D bt_hci_bdroid: cleanup Finalizing cleanup
09-07 13:17:23.062  3865  3952 D bt_userial_mct: userial_close
09-07 13:17:23.062  3865  3952 E bt_userial_mct: pthread_join() FAILED result:3
09-07 13:17:23.062  3865  3952 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-07 13:17:23.079  6878  6878 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 13:17:23.091  6857  6857 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-07 13:17:23.094  1034  1559 I ActivityManager: Killing 5992:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-07 13:17:23.123  3865  3952 D bt_hci_bdroid: set_power 0
,09-07 13:17:23.123  3865  3952 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 13:17:23.123  3865  3952 I bt_vendor: bluetooth satus is on
09-07 13:17:23.123  3865  3952 I bt_vendor: bt-vendor : resetting BT status
09-07 13:17:23.123  3865  3952 I bt_vendor: Starting hciattach daemon
09-07 13:17:23.123  3865  3952 I bt_vendor: try to set false
09-07 13:17:23.124  3865  3952 I bt_vendor: Starting hciattach daemon
09-07 13:17:23.124  3865  3952 I bt_vendor: try to set false
09-07 13:17:23.125  3865  3952 I bt_vendor: cleanup
09-07 13:17:23.125  3865  4057 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-07 13:17:23.126  3865  3952 I GKI_LINUX: GKI_exit_task 0 done
09-07 13:17:23.126  3865  3952 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-07 13:17:23.127  1034  1909 W libprocessgroup: failed to open /acct/uid_10011/pid_5992/cgroup.procs: No such file or directory
09-07 13:17:23.128  3865  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-07 13:17:23.130  3865  3865 D HeadsetService: Received stop request...Stopping profile...
09-07 13:17:23.131  3865  3865 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 13:17:23.131  3865  3865 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 13:17:23.131  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125a832f
09-07 13:17:23.131  3865  3983 D HeadsetStateMachine: Exit Disconnected: -1
09-07 13:17:23.132  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-07 13:17:23.133  1034  1034 D BluetoothHeadset: Proxy object disconnected
09-07 13:17:23.133  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-07 13:17:23.133  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-07 13:17:23.133  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-07 13:17:23.134  3865  3865 D A2dpService: Received stop request...Stopping profile...
09-07 13:17:23.134  3865  4022 D A2dpStateMachine: Exit Disconnected: -1
09-07 13:17:23.135  3865  3865 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-07 13:17:23.137  3865  3865 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-07 13:17:23.137  3865  3865 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 13:17:23.137  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125a832f
,09-07 13:17:23.138  3865  3865 D HeadsetStateMachine: Unbinding service...
,09-07 13:17:23.138  1034  1034 D BluetoothA2dp: Proxy object disconnected
09-07 13:17:23.138  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-07 13:17:23.139  3865  3865 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 13:17:23.139  3865  3865 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 13:17:23.139  3865  3865 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 13:17:23.139  3865  3865 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 13:17:23.139  3865  3865 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 13:17:23.139  3865  3865 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 13:17:23.139  3865  3865 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 13:17:23.140  3865  3865 D HidService: Received stop request...Stopping profile...
09-07 13:17:23.140  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125a832f
09-07 13:17:23.140  3865  3948 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 13:17:23.142  3865  3865 D HealthService: Received stop request...Stopping profile...
09-07 13:17:23.143  6782  6782 D BluetoothInputDevice: Proxy object disconnected
09-07 13:17:23.143  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125a832f
09-07 13:17:23.143  6782  6782 D HidProfile: Bluetooth service disconnected
09-07 13:17:23.144  3865  3865 D PanService: Received stop request...Stopping profile...
09-07 13:17:23.144  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125a832f
09-07 13:17:23.146  6782  6782 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 13:17:23.146  3865  3865 I BluetoothA2dpServiceJni: cleanupNative
09-07 13:17:23.146  6782  6782 D PanProfile: Bluetooth service disconnected
09-07 13:17:23.146  3865  4023 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-07 13:17:23.146  3865  3865 I GKI_LINUX: GKI_exit_task 2 done
09-07 13:17:23.146  3865  3865 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 13:17:23.146  3865  3865 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 13:17:23.147  3865  3865 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 13:17:23.147  3865  3865 D BtGatt.GattService: stop()
09-07 13:17:23.147  3865  3865 D BtGatt.AdvertiseManager: advertise clients cleared
09-07 13:17:23.148  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125a832f
09-07 13:17:23.149  3865  3865 D BluetoothMapService: Received stop request...Stopping profile...
09-07 13:17:23.149  3865  3865 D BluetoothMapService: stop()
09-07 13:17:23.149  3865  3865 D BluetoothMapEmailAppObserver: deinitObservers()
09-07 13:17:23.149  3865  3865 D BluetoothMapEmailAppObserver: removeReceiver()
09-07 13:17:23.150  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125a832f
,09-07 13:17:23.151  3865  3865 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-07 13:17:23.151  3865  3865 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 13:17:23.151  3865  3865 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 13:17:23.151  3865  3865 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 13:17:23.151  3865  3865 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 13:17:23.152  3865  3865 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 13:17:23.152  3865  3865 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 13:17:23.153  3865  3865 V BluetoothMapService: Handler(): got msg=4
09-07 13:17:23.153  3865  3865 D BluetoothMapService: MAP Service closeService in
09-07 13:17:23.153  3865  3865 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 13:17:23.153  3865  3865 V BluetoothMapService: MAP Service closeService out
09-07 13:17:23.154  3865  3865 D BluetoothMapService: cleanup()
09-07 13:17:23.154  3865  3865 D BluetoothMapService: MAP Service closeService in
09-07 13:17:23.154  3865  3865 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 13:17:23.154  3865  3865 V BluetoothMapService: MAP Service closeService out
09-07 13:17:23.155  3865  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-07 13:17:23.155  3865  3948 D BluetoothAdapterProperties: Setting state to 10
09-07 13:17:23.155  3865  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 13:17:23.155  3865  3948 I BluetoothAdapterState: Entering OffState
09-07 13:17:23.155  1034  1117 D BluetoothManagerService: Message: 60
09-07 13:17:23.155  6782  6782 D BluetoothMap: Proxy object disconnected
09-07 13:17:23.155  6782  6782 D MapProfile: Bluetooth service disconnected
09-07 13:17:23.155  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-07 13:17:23.156  1034  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-07 13:17:23.156  6782  6802 D BluetoothMap: onBluetoothStateChange: up=false
09-07 13:17:23.157  6782  6801 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 13:17:23.157  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:17:23.158  6782  6802 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 13:17:23.159  6782  6801 D BluetoothPan: onBluetoothStateChange on: false
09-07 13:17:23.159  1837  2691 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:17:23.161  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:17:23.161  1034  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 13:17:23.161  1034  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:17:23.162  1034  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-07 13:17:23.162  1034  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-07 13:17:23.165  1034  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-07 13:17:23.165  1034  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-07 13:17:23.165  1034  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3588ac13 mBinding = false
09-07 13:17:23.166  1034  1117 D BluetoothManagerService: Sending unbind request.
09-07 13:17:23.168  1034  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-07 13:17:23.170  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:23.170  1927  2089 D LGBluetoothAPIService: Message: 2
09-07 13:17:23.171  1927  2089 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@153285de mBinding = false
09-07 13:17:23.171  1927  2089 D LGBluetoothAPIService: Sending unbind request.
09-07 13:17:23.173  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 13:17:23.174  6782  6782 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 13:17:23.176  3865  3952 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-07 13:17:23.176  3865  3865 I GKI_LINUX: GKI_exit_task 1 done
09-07 13:17:23.176  3865  3865 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-07 13:17:23.177  3865  3865 I BluetoothServiceJni: cleanupNative: return from cleanup
09-07 13:17:23.177  3865  3865 I art     : --- WEIRD: removing null entry 246
09-07 13:17:23.177  3865  3865 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-07 13:17:23.177  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:23.177  3865  3865 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,09-07 13:17:23.178  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:23.179  6782  6782 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-07 13:17:23.180  6782  6782 D LGBluetoothEventManager: [BTUI] clear device connection state
09-07 13:17:23.180  1587  1587 D BluetoothAdapter: 952270950: getState() :  mService = null. Returning STATE_OFF
09-07 13:17:23.181  1587  1587 D BluetoothAdapter: 952270950: getState() :  mService = null. Returning STATE_OFF
09-07 13:17:23.181  6857  6857 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-07 13:17:23.183  3865  3865 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-07 13:17:23.183  6857  6857 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-07 13:17:23.184  6782  6782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 13:17:23.184  6857  6857 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-07 13:17:23.185  6857  6857 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-07 13:17:23.185  6857  6857 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-07 13:17:23.187  3865  3865 I art     : System.exit called, status: 0
09-07 13:17:23.187  3865  3865 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-07 13:17:23.187  6857  6857 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-07 13:17:23.194  6857  6857 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-07 13:17:23.200  6782  6782 D DockEventReceiver: finishStartingService: stopping service
09-07 13:17:23.208  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 13:17:23.211  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:23.214   312  1366 V AudioFlinger: 3865 died, releasing its sessions
09-07 13:17:23.214   312  1366 V AudioFlinger:  pid 1837 @ 0
09-07 13:17:23.214   312  1366 V AudioFlinger:  pid 3443 @ 1
09-07 13:17:23.214   312  1366 V AudioFlinger:  pid 3443 @ 2
09-07 13:17:23.214  6782  6782 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-07 13:17:23.323  1034  1836 I ActivityManager: Process com.android.bluetooth (pid 3865) has died
,09-07 13:17:23.326  1034  1836 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
09-07 13:17:23.336  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 13:17:23.339  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 13:17:23.342  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 13:17:23.348  6857  6857 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-07 13:17:23.352  6857  6857 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-07 13:17:23.354  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 13:17:23.354  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 13:17:23.354  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 13:17:23.363  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:23.375  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:23.381  6782  6782 D BluetoothPermissionRequest: onReceive
,09-07 13:17:23.383  6782  6782 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 13:17:23.384  6782  6782 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-07 13:17:23.387  6782  6782 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 13:17:23.468  1034  1944 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6909 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-07 13:17:23.481  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:23.483  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 13:17:23.486  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 13:17:23.489  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:23.493  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 13:17:23.493  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 13:17:23.493  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 13:17:23.493   335   335 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 25.751ms
09-07 13:17:23.496  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:23.512   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 368us total 17.576ms
09-07 13:17:23.515  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:23.521  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:23.521  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 13:17:23.525  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 13:17:23.529   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 357us total 16.429ms
09-07 13:17:23.530  6909  6909 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-07 13:17:23.530  6909  6909 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 13:17:23.531  6909  6909 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-07 13:17:23.531  6909  6909 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-07 13:17:23.547  6909  6909 D BluetoothAdapterApp: Loading JNI Library
,09-07 13:17:23.577  1034  1980 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6929 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-07 13:17:23.580  6909  6909 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2218fda4 Instance Count = 1
,09-07 13:17:23.587  6909  6909 D BluetoothAdapterApp: onCreate
09-07 13:17:23.617  6909  6909 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-07 13:17:23.617  6909  6909 D ProfileConfigQcom: Adding HeadsetService
09-07 13:17:23.617  6909  6909 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-07 13:17:23.617  6909  6909 D ProfileConfigQcom: Adding A2dpService
09-07 13:17:23.618  6909  6909 D ProfileConfigQcom: [BTUI] HidService is supported
09-07 13:17:23.618  6909  6909 D ProfileConfigQcom: Adding HidService
09-07 13:17:23.618  6909  6909 D ProfileConfigQcom: [BTUI] HealthService is supported
09-07 13:17:23.618  6909  6909 D ProfileConfigQcom: Adding HealthService
09-07 13:17:23.619  6909  6909 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-07 13:17:23.620  6909  6909 D ProfileConfigQcom: [BTUI] PanService is supported
09-07 13:17:23.620  6909  6909 D ProfileConfigQcom: Adding PanService
09-07 13:17:23.620  6909  6909 D ProfileConfigQcom: [BTUI] GattService is supported
09-07 13:17:23.621  6909  6909 D ProfileConfigQcom: Adding GattService
09-07 13:17:23.621  6909  6909 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-07 13:17:23.621  6909  6909 D ProfileConfigQcom: Adding BluetoothMapService
09-07 13:17:23.622  6909  6909 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-07 13:17:23.624  6909  6909 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-07 13:17:23.628  6782  6782 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-07 13:17:23.630  6909  6909 V LGMDMManagerInternal: Create singleton instance
09-07 13:17:23.658  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 13:17:23.661  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 13:17:23.667  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:23.684  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 13:17:23.684  6782  6782 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-07 13:17:23.684  6782  6782 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 13:17:23.684  6782  6782 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 13:17:23.686  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 13:17:23.693  6929  6949 W FormManager: Network not available. Please check & try again.
09-07 13:17:23.696  6782  6782 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 13:17:23.696  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 13:17:23.696  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 13:17:23.696  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 13:17:23.696  6782  6782 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 13:17:23.697  6782  6782 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-07 13:17:23.702  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-07 13:17:23.703  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 13:17:23.704  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:23.706  6929  6951 V FormManager: Network unavailable.
09-07 13:17:23.706  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:23.713  6929  6951 V FormManager: Network unavailable.
,09-07 13:17:23.720  6823  6823 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-07 13:17:23.720  4301  6953 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 13:17:23.720  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 13:17:23.720  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 13:17:23.722  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 13:17:23.724  6909  6909 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:23.725  4301  6954 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 13:17:23.725  4301  6954 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 13:17:23.729  6909  6909 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 13:17:23.730  6909  6909 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 13:17:23.730  6909  6909 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 13:17:23.732  6909  6909 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:23.732  6909  6909 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-07 13:17:23.735  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:23.743  6878  6878 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-07 13:17:23.746  1034  1890 I ActivityManager: Killing 6014:com.android.contacts/u0a19 (adj 15): empty #17
,09-07 13:17:23.784  1034  1998 W libprocessgroup: failed to open /acct/uid_10019/pid_6014/cgroup.procs: No such file or directory
,09-07 13:17:23.790  6929  6956 W FormManager: Network not available. Please check & try again.
09-07 13:17:23.799  6857  6857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-07 13:17:23.802  6929  6957 V FormManager: Network unavailable.
09-07 13:17:23.803  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-07 13:17:23.804  6857  6857 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-07 13:17:23.805  6929  6957 V FormManager: Network unavailable.
09-07 13:17:23.817  1034  1890 I ActivityManager: Killing 6450:com.lge.email/u0a23 (adj 15): empty #17
,09-07 13:17:23.857  6857  6857 D LgDataFeature: LgDataFeature() Constructor: none
09-07 13:17:23.858  6857  6857 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 13:17:23.867  6857  6857 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-07 13:17:23.868  6857  6857 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-07 13:17:23.868  6857  6857 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-07 13:17:23.868  6857  6857 V SoundPool: doLoad: loading sample sampleID=1
09-07 13:17:23.869  6857  6857 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-07 13:17:23.871  6857  6965 V SoundPool: Start decode
,09-07 13:17:23.871  6857  6965 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-07 13:17:23.872   312  1367 V MediaPlayerService: decode(23, 10857164, 17813)
09-07 13:17:23.872   312  1367 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-07 13:17:23.872   312  1367 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-07 13:17:23.872   312  1367 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-07 13:17:23.872   312  1367 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-07 13:17:23.872   312  1367 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-07 13:17:23.872   312  1367 V MediaPlayerService: player type = 3
09-07 13:17:23.872   312  1367 V AwesomePlayer: AwesomePlayer create()
09-07 13:17:23.873   312  1367 V AwesomePlayer: reset_l() 
09-07 13:17:23.873   312  1367 V AwesomePlayer: cancelPlayerEvents
09-07 13:17:23.873   312  1367 V AwesomePlayer: setAudioSink() 
09-07 13:17:23.873   312  1367 V AwesomePlayer: reset_l() 
09-07 13:17:23.873   312  1367 V AudioCache: notify(0xb14324c0, 8, 0, 0)
09-07 13:17:23.873   312  1367 V AudioCache: ignored
09-07 13:17:23.873   312  1367 V AwesomePlayer: cancelPlayerEvents
09-07 13:17:23.873   312  1367 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-07 13:17:23.873   312  1367 V AwesomePlayer: setDataSource_l dataSource
09-07 13:17:23.873   312  1367 V LGParserOSAL: SniffLGParser start
09-07 13:17:23.873   312  1367 V LGParserOSAL: MainType:5, SubType=0
09-07 13:17:23.873   312  1367 V LGParserOSAL: #### check Mime : application/ogg
09-07 13:17:23.873   312  1367 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-07 13:17:23.873   312  1367 E MediaExtractor: Use LGExtractor :application/ogg 
09-07 13:17:23.878  1034  1633 W libprocessgroup: failed to open /acct/uid_10023/pid_6450/cgroup.procs: No such file or directory
09-07 13:17:23.894  6578  6578 D UEI.SmartControl: QS Service created
09-07 13:17:23.895  6857  6857 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-07 13:17:23.902  6857  6857 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-07 13:17:23.903  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-07 13:17:23.920   312  1367 V LGParserOSAL: supported mime: application/ogg
,09-07 13:17:23.921   312  1367 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,09-07 13:17:23.921   312  1367 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-07 13:17:23.921   312  1367 V AwesomePlayer: mBitrate = -1 bits/sec
09-07 13:17:23.921   312  1367 V AwesomePlayer: AudioTrack Setting,
09-07 13:17:23.921   312  1367 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-07 13:17:23.921   312  1367 V AwesomePlayer: setAudioSource() 
09-07 13:17:23.921   312  1367 V MediaPlayerService: prepare
09-07 13:17:23.921   312  1367 V AwesomePlayer: prepareAsync_l() 
,09-07 13:17:23.921   312  1367 V MediaPlayerService: wait for prepare
09-07 13:17:23.922  6857  6857 V LGMDMManager: Create singleton instance
09-07 13:17:23.923   312  6966 V AwesomePlayer: onPrepareAsyncEvent() 
,09-07 13:17:23.923   312  6966 V AwesomePlayer: initAudioDecoder() 
09-07 13:17:23.923   312  6966 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
,09-07 13:17:23.923   312  6966 V AudioSystem: isOffloadSupported()
09-07 13:17:23.923   312  6966 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-07 13:17:23.923   312  6966 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false,
09-07 13:17:23.923   312  6966 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 13:17:23.923   312  6966 V AwesomePlayer: getUseOffload() = 0 
,09-07 13:17:23.923   312  6966 V OMXCodec: OMXCodec::Create
09-07 13:17:23.924   312  6966 V OMXCodec: findMatchingCodecs()
09-07 13:17:23.924   312  6966 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
,09-07 13:17:23.924   312  6966 V OMXCodec: matchingCodecs.size()=1
09-07 13:17:23.924   312  6966 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,09-07 13:17:23.928   312  6966 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-07 13:17:23.928   312  6966 V LGCodecAdapter: LG Codec Adapter start
09-07 13:17:23.928   312  6966 V OMXCodec: OMXCodec Createtor
09-07 13:17:23.928   312  6966 V OMXCodec: setComponentRole
09-07 13:17:23.928   312  6966 V OMXCodec: configureCodec protected=0
09-07 13:17:23.928   312  6966 V LGCodecAdapter: called getLGCodecSpecificData
09-07 13:17:23.928   312  6966 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-07 13:17:23.928   312  6966 V LGCodecOSAL: Called LGconfigureCodecMETA
09-07 13:17:23.928   312  6966 V LGCodecOSAL: Called LGconfigureCodecMSG
09-07 13:17:23.928   312  6966 V LGCodecOSAL: Not support LGCodec
09-07 13:17:23.928   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-07 13:17:23.928   312  6966 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-07 13:17:23.928   312  6966 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-07 13:17:23.928   312  6966 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-07 13:17:23.928  6578  6578 I UEI.SmartControl: Service initServices...
09-07 13:17:23.928   312  6966 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-07 13:17:23.928   312  6966 V AudioSystem: isOffloadSupported()
09-07 13:17:23.928   312  6966 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-07 13:17:23.928   312  6966 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-07 13:17:23.928   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-07 13:17:23.928   312  6966 V OMXCodec: init()
09-07 13:17:23.928   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-07 13:17:23.928   312  6966 V OMXCodec: allocateBuffers
09-07 13:17:23.928   312  6966 V OMXCodec: allocateBuffersOnPort portIndex=0
09-07 13:17:23.928   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-07 13:17:23.929  6578  6578 D UEI.SmartControl: QS start get config
09-07 13:17:23.929   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
09-07 13:17:23.929   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
09-07 13:17:23.929   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on input port
09-07 13:17:23.929   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on input port
09-07 13:17:23.929   312  6966 V OMXCodec: allocateBuffersOnPort portIndex=1
09-07 13:17:23.929   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-07 13:17:23.929   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
09-07 13:17:23.929   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
09-07 13:17:23.929   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434830 on output port
09-07 13:17:23.929   312  6966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434970 on output port
09-07 13:17:23.929   312  6966 V OMXCodec: init() mAsyncCompletion wait!!! 
09-07 13:17:23.931   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-07 13:17:23.931   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-07 13:17:23.931   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-07 13:17:23.931   312  6966 V OMXCodec: init() mAsyncCompletion wait!!! 
09-07 13:17:23.931   312  6968 V OMXCodec: [OMX.go,ogle.vorbis.decoder] onStateChange 3
09-07 13:17:23.931   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-07 13:17:23.931   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-07 13:17:23.931   312  6966 V OMXCodec: init() mAsyncCompletion wait free! 
09-07 13:17:23.931   312  6966 V AwesomePlayer: finishAsyncPrepare_l() 
09-07 13:17:23.931   312  6966 V AudioCache: notify(0xb14324c0, 5, 0, 0)
09-07 13:17:23.931   312  6966 V AudioCache: ignored
09-07 13:17:23.931   312  6966 V AudioCache: notify(0xb14324c0, 1, 0, 0)
09-07 13:17:23.931   312  6966 V AudioCache: prepared
09-07 13:17:23.931   312  1367 V AudioCache: wait - success
09-07 13:17:23.931   312  1367 V MediaPlayerService: start
09-07 13:17:23.931   312  1367 V AwesomePlayer: play_l() 
09-07 13:17:23.931   312  1367 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-07 13:17:23.931   312  1367 V AwesomePlayer: createAudioPlayer_l
09-07 13:17:23.931   312  1367 V AwesomePlayer: seekAudioIfNecessary_l() 
09-07 13:17:23.931   312  1367 V AwesomePlayer: startAudioPlayer_l() 
09-07 13:17:23.931   312  1367 D AudioPlayer: start of Playback, useOffload 0
09-07 13:17:23.931   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-07 13:17:23.932   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-07 13:17:23.935   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-07 13:17:23.935   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-07 13:17:23.935   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-07 13:17:23.935   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-07 13:17:23.935   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-07 13:17:23.935   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-07 13:17:23.935   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976064
09-07 13:17:23.935   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976304
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976624
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976944
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-07 13:17:23.936   312  6968 V OMXCodec: allocateBuffersOnPort portIndex=1
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434830 on output port
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
,09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
09-07 13:17:23.936   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15240b0 on output port
09-07 13:17:23.937   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-07 13:17:23.937   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-07 13:17:23.937   312  1367 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-07 13:17:23.937   312  1367 V AudioCache: notify(0xb14324c0, 6, 0, 0)
,09-07 13:17:23.938   312  1367 V AudioCache: ignored
,09-07 13:17:23.938   312  1367 V MediaPlayerService: wait for playback complete
,09-07 13:17:23.939   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.939   312  6969 V AudioCache: memcpy(0xab602000, 0xb124c000, 4096)
09-07 13:17:23.940   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.940   312  6969 V AudioCache: memcpy(0xab603000, 0xb124c000, 4096)
09-07 13:17:23.941   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.941   312  6969 V AudioCache: memcpy(0xab604000, 0xb124c000, 4096)
,09-07 13:17:23.942   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.942   312  6969 V AudioCache: memcpy(0xab605000, 0xb124c000, 4096)
09-07 13:17:23.942   312  6969 V AudioCache: write(0xb124c000, 4096)
,09-07 13:17:23.949   312  6969 V AudioCache: memcpy(0xab606000, 0xb124c000, 4096)
,09-07 13:17:23.949   312  6969 V AudioCache: write(0xb124c000, 4096)
,09-07 13:17:23.949   312  6969 V AudioCache: memcpy(0xab607000, 0xb124c000, 4096)
,09-07 13:17:23.950   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.950   312  6969 V AudioCache: memcpy(0xab608000, 0xb124c000, 4096)
,09-07 13:17:23.952   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.952   312  6969 V AudioCache: memcpy(0xab609000, 0xb124c000, 4096)
,09-07 13:17:23.952   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.952   312  6969 V AudioCache: memcpy(0xab60a000, 0xb124c000, 4096)
,09-07 13:17:23.953   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.953   312  6969 V AudioCache: memcpy(0xab60b000, 0xb124c000, 4096)
,09-07 13:17:23.954   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.954   312  6969 V AudioCache: memcpy(0xab60c000, 0xb124c000, 4096)
,09-07 13:17:23.954   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.954   312  6969 V AudioCache: memcpy(0xab60d000, 0xb124c000, 4096)
,09-07 13:17:23.955   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.955   312  6969 V AudioCache: memcpy(0xab60e000, 0xb124c000, 4096)
,09-07 13:17:23.956   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.956   312  6969 V AudioCache: memcpy(0xab60f000, 0xb124c000, 4096)
,09-07 13:17:23.956   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.956   312  6969 V AudioCache: memcpy(0xab610000, 0xb124c000, 4096)
,09-07 13:17:23.957   312  6969 V AudioCache: write(0xb124c000, 4096)
,09-07 13:17:23.957   312  6969 V AudioCache: memcpy(0xab611000, 0xb124c000, 4096)
09-07 13:17:23.958   312  6969 V AudioCache: write(0xb124c000, 4096)
,09-07 13:17:23.958   312  6969 V AudioCache: memcpy(0xab612000, 0xb124c000, 4096)
,09-07 13:17:23.958   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.958   312  6969 V AudioCache: memcpy(0xab613000, 0xb124c000, 4096)
,09-07 13:17:23.959   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.959   312  6969 V AudioCache: memcpy(0xab614000, 0xb124c000, 4096)
09-07 13:17:23.959   312  6969 V AudioCache: write(0xb124c000, 4096)
,09-07 13:17:23.959   312  6969 V AudioCache: memcpy(0xab615000, 0xb124c000, 4096)
09-07 13:17:23.960   312  6969 V AudioCache: write(0xb124c000, 4096)
,09-07 13:17:23.960   312  6969 V AudioCache: memcpy(0xab616000, 0xb124c000, 4096)
09-07 13:17:23.961   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.961   312  6969 V AudioCache: memcpy(0xab617000, 0xb124c000, 4096)
,09-07 13:17:23.961   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.961   312  6969 V AudioCache: memcpy(0xab618000, 0xb124c000, 4096)
,09-07 13:17:23.962   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.962   312  6969 V AudioCache: memcpy(0xab619000, 0xb124c000, 4096)
09-07 13:17:23.963   312  6969 V AudioCache: write(0xb124c000, 4096)
,09-07 13:17:23.963   312  6969 V AudioCache: memcpy(0xab61a000, 0xb124c000, 4096)
09-07 13:17:23.963   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.963   312  6969 V AudioCache: memcpy(0xab61b000, 0xb124c000, 4096)
,09-07 13:17:23.964   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.964   312  6969 V AudioCache: memcpy(0xab61c000, 0xb124c000, 4096)
09-07 13:17:23.965   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.965   312  6969 V AudioCache: memcpy(0xab61d000, 0xb124c000, 4096)
09-07 13:17:23.965   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.965   312  6969 V AudioCache: memcpy(0xab61e000, 0xb124c000, 4096)
09-07 13:17:23.966   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.966   312  6969 V AudioCache: memcpy(0xab61f000, 0xb124c000, 4096)
09-07 13:17:23.967   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.967   312  6969 V AudioCache: memcpy(0xab620000, 0xb124c000, 4096)
09-07 13:17:23.967   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.967   312  6969 V AudioCache: memcpy(0xab621000, 0xb124c000, 4096)
09-07 13:17:23.968   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.968   312  6969 V AudioCache: memcpy(0xab622000, 0xb124c000, 4096)
09-07 13:17:23.969   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.969   312  6969 V AudioCache: memcpy(0xab623000, 0xb124c000, 4096)
09-07 13:17:23.969   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.969   312  6969 V AudioCache: memcpy(0xab624000, 0xb124c000, 4096)
09-07 13:17:23.970   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.970   312  6969 V AudioCache: memcpy(0xab625000, 0xb124c000, 4096)
09-07 13:17:23.971   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.971   312  6969 V AudioCache: memcpy(0xab626000, 0xb124c000, 4096)
09-07 13:17:23.972   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.972   312  6969 V AudioCache: memcpy(0xab627000, 0xb124c000, 4096)
09-07 13:17:23.972   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.972   312  6969 V AudioCache: memcpy(0xab628000, 0xb124c000, 4096)
09-07 13:17:23.973   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.973   312  6969 V AudioCache: memcpy(0xab629000, 0xb124c000, 4096)
09-07 13:17:23.974   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.974   312  6969 V AudioCache: memcpy(0xab62a000, 0xb124c000, 4096)
09-07 13:17:23.974   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.974   312  6969 V AudioCache: memcpy(0xab62b000, 0xb124c000, 4096)
09-07 13:17:23.975   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.975   312  6969 V AudioCache: memcpy(0xab62c000, 0xb124c000, 4096)
09-07 13:17:23.976   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.976   312  6969 V AudioCache: memcpy(0xab62d000, 0xb124c000, 4096)
09-07 13:17:23.977   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.977   312  6969 V AudioCache: memcpy(0xab62e000, 0xb124c000, 4096)
09-07 13:17:23.977   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.977   312  6969 V AudioCache: memcpy(0xab62f000, 0xb124c000, 4096)
09-07 13:17:23.978   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.978   312  6969 V AudioCache: memcpy(0xab630000, 0xb124c000, 4096)
09-07 13:17:23.978   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.978   312  6969 V AudioCache: memcpy(0xab631000, 0xb124c000, 4096)
09-07 13:17:23.979   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.979   312  6969 V AudioCache: memcpy(0xab632000, 0xb124c000, 4096)
09-07 13:17:23.980   312  6969 V AudioCache: write(0xb124c000, 4096)
09-07 13:17:23.980   312  6969 V AudioCache: memcpy(0xab633000, 0xb124c000, 4096)
09-07 13:17:23.980   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-07 13:17:23.980   312  6969 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-07 13:17:23.980   312  6969 V AwesomePlayer: postAudioEOS() 
09-07 13:17:23.980   312  6969 V AudioCache: write(0xb124c000, 280)
09-07 13:17:23.980   312  6969 V AudioCache: memcpy(0xab,634000, 0xb124c000, 280)
09-07 13:17:23.983   312  6966 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-07 13:17:23.983   312  6966 V AwesomePlayer: onStreamDone
09-07 13:17:23.983   312  6966 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-07 13:17:23.983   312  6966 V AudioCache: notify(0xb14324c0, 2, 0, 0)
09-07 13:17:23.983   312  6966 V AudioCache: playback complete
09-07 13:17:23.983   312  6966 V AwesomePlayer: pause_l() 
09-07 13:17:23.983   312  6966 V AudioCache: notify(0xb14324c0, 7, 0, 0)
09-07 13:17:23.983   312  6966 V AudioCache: ignored
09-07 13:17:23.983   312  6966 V AwesomePlayer: cancelPlayerEvents
09-07 13:17:23.983   312  1367 V AudioCache: wait - success
09-07 13:17:23.983   312  1367 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-07 13:17:23.983   312  6966 D AudioPlayer: Pause Playback at 1068125
09-07 13:17:23.984   312  1367 V AwesomePlayer: reset_l() 
09-07 13:17:23.984   312  1367 V AudioCache: notify(0xb14324c0, 8, 0, 0)
09-07 13:17:23.984   312  1367 V AudioCache: ignored
09-07 13:17:23.984   312  1367 V AwesomePlayer: cancelPlayerEvents
09-07 13:17:23.984   312  1367 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-07 13:17:23.985   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-07 13:17:23.985   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-07 13:17:23.985   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-07 13:17:23.985   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 0
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 0
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb15240b0 on port 1
,09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 1
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-07 13:17:23.985   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 1
09-07 13:17:23.986   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1,
09-07 13:17:23.986   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434830 on port 1
09-07 13:17:23.986   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 13:17:23.986   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
,09-07 13:17:23.986   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-07 13:17:23.986   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-07 13:17:23.986   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-07 13:17:23.986   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.,
09-07 13:17:23.986   312  6968 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-07 13:17:23.986   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-07 13:17:23.986   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
,09-07 13:17:23.986   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-07 13:17:23.987   312  1367 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-07 13:17:23.987   312  1367 D AudioPlayer: AudioPlayer releasing audio source
09-07 13:17:23.987   312  1367 D AudioPlayer: AudioPlayer done releasing audio source,
09-07 13:17:23.987   312  1367 V AwesomePlayer: reset_l() 
09-07 13:17:23.987   312  1367 V AwesomePlayer: cancelPlayerEvents
09-07 13:17:23.987   312  1367 V AwesomePlayer: ~AwesomePlayer call
,09-07 13:17:23.988   312  1367 V AwesomePlayer: reset_l() 
09-07 13:17:23.988   312  1367 V AwesomePlayer: cancelPlayerEvents
09-07 13:17:23.988  6857  6965 V SoundPool: close(31)
,09-07 13:17:23.988  6857  6965 V SoundPool: pointer = 0xa003d000, size = 205080, sampleRate = 48000, numChannels = 2
,09-07 13:17:24.033  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-07 13:17:24.034  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-07 13:17:24.037  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7269
09-07 13:17:24.246  6578  6578 I UEI.SmartControl: Supports setup maps: true
09-07 13:17:24.249  6578  6578 D UEI.SmartControl: QS start statue = true Error code = 0
09-07 13:17:24.249  6578  6578 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-07 13:17:24.249  6578  6578 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-07 13:17:24.249  6578  6578 I UEI.SmartControl: ### init IR Blaster...
,09-07 13:17:24.253  6578  6578 D serial_port: Configuring serial port
,09-07 13:17:24.253  6578  6578 E UEI.SmartControl: UEIBLaster setting for 616
09-07 13:17:24.253  6578  6578 I UEI.SmartControl: Setting serial record hearder size = 2
09-07 13:17:24.253  6578  6578 I UEI.SmartControl: configuring settings for MAXQ616
09-07 13:17:24.253  6578  6578 I UEI.SmartControl: Get version...
09-07 13:17:24.269  6578  6971 D UEI.SmartControl: serial port data available: 21
,09-07 13:17:24.295  6578  6578 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-07 13:17:24.295  6578  6578 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-07 13:17:24.295  6578  6578 I UEI.SmartControl: QS saving settings...
09-07 13:17:24.295  6578  6578 D UEI.SmartControl: IR Blaster version: 25672567
,09-07 13:17:24.312  6578  6971 D UEI.SmartControl: serial port data available: 4
,09-07 13:17:24.346  6578  6578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-07 13:17:24.349  6578  6578 E UEI.SmartControl: Services init done
,09-07 13:17:24.349  6578  6578 D UEI.SmartControl: QS Service init finished
09-07 13:17:24.352  6578  6578 D UEI.SmartControl: QS Service version name: 2.1.91
09-07 13:17:24.353  6578  6578 D UEI.SmartControl: QS Service version code: 201091
,09-07 13:17:24.354  6578  6578 D UEI.SmartControl: Service requested: Control
09-07 13:17:24.354  6578  6980 I UEI.SmartControl: Device manager: loading config....
09-07 13:17:24.355  6578  6980 D UEI.SmartControl: ----------- loading internal config...
09-07 13:17:24.358  6578  6578 D UEI.SmartControl: Internal service binding...
09-07 13:17:24.359  6857  6857 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-07 13:17:24.361  6578  6594 I UEI.SmartControl: ------ IControl API: 11
09-07 13:17:24.362  6578  6594 D UEI.SmartControl: File observer start...
09-07 13:17:24.363  6578  6594 E UEI.SmartControl: IR Port is disabled: false
09-07 13:17:24.364  6578  6594 D UEI.SmartControl: Starting file observer...
,09-07 13:17:24.366  6578  6594 I UEI.SmartControl: Registering callback...
09-07 13:17:24.368  6578  6593 I UEI.SmartControl: ------ IControl API: 19
09-07 13:17:24.369  6578  6593 I UEI.SmartControl: Registering Services Ready callback...
09-07 13:17:24.371  6578  6980 E UEI.SmartControl: Loading SETTINGS...
09-07 13:17:24.375  6578  6980 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-07 13:17:24.386  6578  6979 I UEI.SmartControl: Notify AllClients services are ready: 0
09-07 13:17:24.387  6578  6979 D UEI.SmartControl: -----service ready thread exits
,09-07 13:17:24.387  6857  6873 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-07 13:17:24.388  6857  6963 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,09-07 13:17:24.388  6857  6963 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-07 13:17:24.389  6857  6857 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-07 13:17:24.390  6857  6857 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-07 13:17:24.390  6578  6594 I UEI.SmartControl: ------ IControl API: 8
09-07 13:17:24.392  6857  6857 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-07 13:17:24.392  6857  6857 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-07 13:17:24.393  6857  6857 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-07 13:17:24.393  6857  6857 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-07 13:17:24.394  6857  6857 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-07 13:17:24.394  6857  6857 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-07 13:17:24.396  6857  6857 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-07 13:17:24.398  6857  6857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-07 13:17:24.399  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-07 13:17:24.400  6857  6857 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-07 13:17:24.401  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-07 13:17:24.402  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-07 13:17:24.403  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-07 13:17:24.403  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-07 13:17:24.405  6857  6857 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473247044404]
09-07 13:17:24.409  6857  6857 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-07 13:17:24.411  1034  1057 I ActivityManager: Killing 6044:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-07 13:17:24.429  6857  6982 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-07 13:17:24.444  1034  1945 W libprocessgroup: failed to open /acct/uid_10027/pid_6044/cgroup.procs: No such file or directory
,09-07 13:17:24.453  6857  6857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-07 13:17:24.454  6857  6857 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-07 13:17:24.455  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-07 13:17:24.455  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-07 13:17:24.455  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-07 13:17:24.456  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-07 13:17:24.457  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,09-07 13:17:24.471  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-07 13:17:25.086  1034  1998 D WifiServiceImplEx: setWifiEnabled: true pid=6660, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 13:17:25.087  1034  1998 D WifiService: setWifiEnabled: true pid=6660, uid=10118
09-07 13:17:25.088  1034  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 13:17:25.113  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 13:17:25.113  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 13:17:25.113  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-07 13:17:25.115  1034  1522 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-07 13:17:25.115  1034  1522 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-07 13:17:25.118  1034  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-07 13:17:25.118  1034  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 13:17:25.118  1034  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-07 13:17:25.118  1034  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 13:17:25.118  1034  1522 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-07 13:17:25.118  1034  1522 E WifiHW  : unknown target_country: EU , set to default
09-07 13:17:25.118  1034  1522 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-07 13:17:25.118  1034  1522 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-07 13:17:25.118  1034  1522 I WifiUtil: gEnableBmps=1
09-07 13:17:25.128  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:17:25.135  1034  1117 D Tethering: MasterInitialState.processMessage what=3
09-07 13:17:25.143  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:17:25.148  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:25.149  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:25.154  1034  1117 D Tethering: MasterInitialState.processMessage what=3
09-07 13:17:25.162  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:17:25.166  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:25.167  1034  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:25.169  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 13:17:25.179  5739  5739 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-07 13:17:25.186  5739  5739 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-07 13:17:25.187  6356  6822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-07 13:17:25.212  2227  2227 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:17:25.250  1034  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:17:25.289  1034  2015 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7001 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-07 13:17:25.293  1034  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:25.294  1034  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 13:17:25.375  7001  7001 I AppUp4:AppBoxCP: onCreate
09-07 13:17:25.376  7001  7001 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-07 13:17:25.387  7001  7001 I AppUp4:DB:  setFingerPrint start
09-07 13:17:25.387  7001  7001 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-07 13:17:25.396  7001  7001 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-07 13:17:25.396  7001  7001 I AppUp4:DB:  SDK version = 21
09-07 13:17:25.396  7001  7001 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-07 13:17:25.399  7001  7001 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-07 13:17:25.401  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 13:17:25.401  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:25.403  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 13:17:25.404  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 13:17:25.412  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
,09-07 13:17:25.456  7001  7001 D LgDataFeature: LgDataFeature() Constructor: none
,09-07 13:17:25.456  7001  7001 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 13:17:25.466  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@f908d0e
09-07 13:17:25.466  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 13:17:25.467  7001  7001 D AppUp4:CustFacade: isPhone : true
09-07 13:17:25.467  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
09-07 13:17:25.468  7001  7001 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-07 13:17:25.468  7001  7001 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-07 13:17:25.469  7001  7020 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-07 13:17:25.469  7001  7020 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-07 13:17:25.470  7001  7020 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-07 13:17:25.474  1034  1633 I ActivityManager: Killing 6487:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-07 13:17:25.546  1034  1559 W libprocessgroup: failed to open /acct/uid_10061/pid_6487/cgroup.procs: No such file or directory
,09-07 13:17:25.548  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:25.549  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 13:17:25.553  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:25.558  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:25.566  4301  7025 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 13:17:25.571  4301  7026 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:25.571  4301  7026 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 13:17:25.630  1034  1872 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7030 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-07 13:17:25.717  7030  7030 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:17:25.718  7030  7030 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 13:17:25.721  7030  7030 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-07 13:17:25.722  7030  7030 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 13:17:25.815  7030  7030 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-07 13:17:25.844  1034  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-07 13:17:25.846  1034  1117 D Tethering: InitialState.processMessage what=4
09-07 13:17:25.848  1034  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 13:17:25.853   308   892 D SoftapController: Softap fwReload - Ok
09-07 13:17:25.855  1034  1522 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (731ms)
09-07 13:17:25.857  7030  7030 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-07 13:17:25.857   308   892 D CommandListener: Setting iface cfg
09-07 13:17:25.857   308   892 D CommandListener: Trying to bring down wlan0
09-07 13:17:25.859   308   892 D CommandListener: Clearing all IP addresses on wlan0
,09-07 13:17:25.863  1034  1522 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-07 13:17:25.854  7061  7061 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:25.854  7061  7061 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 13:17:25.892  7061  7061 I wpa_supplicant: Successfully initialized wpa_supplicant
09-07 13:17:25.901  7030  7030 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 13:17:25.927  7061  7061 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 13:17:25.927  7061  7061 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-07 13:17:25.937  7030  7030 D LgDataFeature: LgDataFeature() Constructor: none
09-07 13:17:25.937  7030  7030 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 13:17:25.963  1034  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 13:17:25.963  1034  1522 E WifiStateMachine: useWiFiOffloading() : false
09-07 13:17:25.963  1034  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 13:17:25.964  1034  1522 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-07 13:17:25.964  1034  1522 D WifiMonitor: connecting to supplicant
,09-07 13:17:25.966  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-07 13:17:25.969  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:25.972  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-07 13:17:25.972  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:25.973  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:17:26.013  7061  7061 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 13:17:26.045  7030  7030 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-07 13:17:26.068  7061  7061 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-07 13:17:26.071  3443  3443 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-07 13:17:26.071  3443  3443 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:26.071  3443  3443 I LgeMiscReceiver: networkInfo.isConnected() = false
09-07 13:17:26.078  1034  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-07 13:17:26.079  7061  7061 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-07 13:17:26.079  7061  7061 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-07 13:17:26.079  1034  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-07 13:17:26.080  1034  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-07 13:17:26.080  1034  7072 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-07 13:17:26.080  1034  1522 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-07 13:17:26.080  1034  7072 D WifiMonitor: Dropping event because (p2p0) is stopped
09-07 13:17:26.081  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-07 13:17:26.081  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-07 13:17:26.081  1034  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:26.081  1034  7072 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-07 13:17:26.081  1034  7072 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,09-07 13:17:26.081  1034  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:26.082  1034  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-07 13:17:26.083  1034  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-07 13:17:26.084  1034  1522 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-07 13:17:26.084  1034  1522 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-07 13:17:26.085  1034  1522 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-07 13:17:26.085  1034  1522 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-07 13:17:26.085  1034  1522 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-07 13:17:26.115  1034  1057 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7075 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-07 13:17:26.118  1034  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 13:17:26.118  1034  1522 E WifiStateMachine: useWiFiOffloading() : false
09-07 13:17:26.118  1034  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 13:17:26.118  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.118  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.118  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.118  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.118  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 13:17:26.119  1034  1522 D WifiNative-wlan0: doBoolean: SET update_config 1
09-07 13:17:26.120  1034  1522 D WifiNative-wlan0: SET update_config 1: returned true
09-07 13:17:26.120  1034  1522 D WifiConfigStore: Loading config and enabling all networks 
09-07 13:17:26.120  1034  1522 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-07 13:17:26.121  1034  1522 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-07 13:17:26.121  6929  7071 W FormManager: Network not available. Please check & try again.
09-07 13:17:26.123  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:26.123  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-07 13:17:26.124  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:26.124  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:26.124  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:26.124  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:26.124  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:26.124  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:26.124  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:26.124  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:26.124  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:17:26.124  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:26.124  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:26.124  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-07 13:17:26.125  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:26.125  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:26.125  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:26.125  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:26.125  6660  666,0 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:26.125  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:26.125  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:26.125  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:26.125  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:17:26.125  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:26.125  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:26.125  1927  1927 D WfdService: Waiting for WifiP2p enabling
09-07 13:17:26.128  6929  7073 V FormManager: Network unavailable.
09-07 13:17:26.131  6929  7073 V FormManager: Network unavailable.
,09-07 13:17:26.134  1034  1522 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-07 13:17:26.141  7030  7030 I HubEmail: JNI_OnLoad()
09-07 13:17:26.141  7030  7030 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 13:17:26.141  7030  7030 I HubEmail: registerNatives()
09-07 13:17:26.141  7030  7030 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 13:17:26.141  7030  7030 I HubEmail: registerNativeMethods()
09-07 13:17:26.141  7030  7030 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 13:17:26.142  7030  7030 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-07 13:17:26.145  1034  2015 I ActivityManager: Killing 6103:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-07 13:17:26.147  1034  1522 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-07 13:17:26.148  1034  1522 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-07 13:17:26.174  1034  1522 D WifiStateMachine: enableVerboseLogging : level 2
09-07 13:17:26.174  1034  1522 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-07 13:17:26.174  1034  1522 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-07 13:17:26.174  1034  1522 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-07 13:17:26.175  1034  1522 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-07 13:17:26.175  1034  1522 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-07 13:17:26.175  1034  1522 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-07 13:17:26.175  1034  1522 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-07 13:17:26.175  1034  1522 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-07 13:17:26.175  1034  1522 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-07 13:17:26.176  1034  1522 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-07 13:17:26.176  1034  1522 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-07 13:17:26.176  1034  1522 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-07 13:17:26.176  1034  1522 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-07 13:17:26.176  1034  1522 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-07 13:17:26.176  1034  1909 W libprocessgroup: failed to open /acct/uid_10080/pid_6103/cgroup.procs: No such file or directory
,09-07 13:17:26.179  1034  1522 D WifiStateMachine: Setting OUI to DA-A1-19
,09-07 13:17:26.179  1034  1522 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-07 13:17:26.180  1927  1927 D WfdsService: Supplicant Connection state is changed : true
09-07 13:17:26.180  1927  2285 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-07 13:17:26.180  1927  2285 D WfdsService: Set the WFDS Monitor: true
09-07 13:17:26.180  1927  2285 D WfdsMonitor: WfdsMonitorThread create
,09-07 13:17:26.180  1927  2285 D WfdsMonitor: WFDS Monitor is created and started
09-07 13:17:26.180  1927  2285 D WfdsService: WiFi: Supplicant connection re-established
09-07 13:17:26.180  1034  1522 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-07 13:17:26.180  1034  1522 D WifiNative-HAL: Setting external_sim to 1
09-07 13:17:26.180  1034  1522 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-07 13:17:26.181  1034  1522 D WifiNative-wlan0: SET external_sim 1: returned true
09-07 13:17:26.181  1034  1522 I WifiNative-HAL: startHal
09-07 13:17:26.181  1034  1522 D wifi    : setting scan oui 0xaf72c660
09-07 13:17:26.181  1034  1522 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 13:17:26.181  1034  1522 I WifiNative-HAL: startHal
,09-07 13:17:26.181  1034  1522 D wifi    : setting scan oui 0xaf72c660
09-07 13:17:26.181  1034  1522 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-07 13:17:26.181  1927  7094 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-07 13:17:26.182  1927  7094 E CtrlSupplicant: Succeed to open control connection
09-07 13:17:26.182  1927  7094 E CtrlSupplicant: Succeed to open monitor connection
09-07 13:17:26.182  1034  1522 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-07 13:17:26.182  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-07 13:17:26.182  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-07 13:17:26.182  7030  7093 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.182  1034  1522 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-07 13:17:26.183  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 13:17:26.183  1927  7094 D WfdsMonitor: Supplicant connection established
09-07 13:17:26.183  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 13:17:26.183  1927  2285 D WfdsService: Connected to the supplicant for wfds
09-07 13:17:26.183  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 13:17:26.183  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-07 13:17:26.183  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-07 13:17:26.183  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-07 13:17:26.183  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 13:17:26.184  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 13:17:26.184  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 13:17:26.184  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 13:17:26.184  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 13:17:26.184  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 13:17:26.184  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-07 13:17:26.184  7061  7061 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-07 13:17:26.184  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-07 13:17:26.185  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 13:17:26.185  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 13:17:26.185  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 13:17:26.186  1034  1522 E WifiNative: : [192,330,850 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-07 13:17:26.186  1034  1522 D WifiNative-wlan0: doBoolean: RECONNECT
09-07 13:17:26.186  1034  1522 D WifiNative-wlan0: RECONNECT: returned true
09-07 13:17:26.186  1034  1522 D WifiNative-wlan0: doString: [STATUS]
09-07 13:17:26.187  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-07 13:17:26.187  1034  1522 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 13:17:26.187  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-07 13:17:26.187  1034  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 13:17:26.187  1034  1522 D WifiNative-wlan0: SET ps 1: returned true
09-07 13:17:26.187  1034  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.187  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
09-07 13:17:26.188  1034  1034 D RttService: SCAN_AVAILABLE : 3
09-07 13:17:26.188  1034  1541 D RttService:, DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.188  1034  1540 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.188  1034  1540 I WifiNative-HAL: startHal
09-07 13:17:26.188  1034  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf72c660
09-07 13:17:26.188  1034  1540 D wifi    : failed to get capabilities : -3
09-07 13:17:26.188  1034  1540 E WifiScanningService: could not get scan capabilities
09-07 13:17:26.188  1034  1522 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-07 13:17:26.189   308   892 D CommandListener: Setting iface cfg
09-07 13:17:26.189   308   892 D CommandListener: Trying to bring up p2p0
09-07 13:17:26.189  1034  1522 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-07 13:17:26.189  1034  1522 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-07 13:17:26.189  1034  1522 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-07 13:17:26.190  1034  1522 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-07 13:17:26.190  1034  1522 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-07 13:17:26.190  1034  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 13:17:26.191  1034  1522 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-07 13:17:26.191  1034  1522 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-07 13:17:26.191  7061  7061 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-07 13:17:26.191  1034  1522 E WifiStateMachine:  DisconnectedState what:132096 -100 0
,09-07 13:17:26.192  1034  1522 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-07 13:17:26.192  1034  1522 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-07 13:17:26.192  1034  1522 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-07 13:17:26.192  7061  7061 E wpa_supplicant: disconnect_rssi_lvl: -100
09-07 13:17:26.193  1034  1521 D LGWifiP2pService: P2pEnablingState
09-07 13:17:26.193  1034  1521 D LGWifiP2pService: P2pEnablingState{ when=-2ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.193  1034  1521 D LGWifiP2pService: P2p socket connection successful
09-07 13:17:26.193  1034  1521 D LGWifiP2pService: P2pEnabledState
09-07 13:17:26.193  1034  1522 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 13:17:26.193  1034  1521 D LGWifiP2pService: sending p2p connection changed broadcast
09-07 13:17:26.193  1034  1522 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 13:17:26.194  1034  1522 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 13:17:26.194  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-07 13:17:26.194  1034  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-07 13:17:26.194  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-07 13:17:26.194  1927  1927 D WfdsService: WifiP2pState is changed : true
09-07 13:17:26.194  1927  2285 D WfdsService: Receive the WFDS_ENABLE Method
09-07 13:17:26.194  1927  2285 D WfdsService: Set the WFDS Monitor: true
09-07 13:17:26.194  1927  2285 D WfdsService: Connected to the supplicant for wfds
09-07 13:17:26.194  1927  2285 D WfdsJNI : doCommand: WFDS_SET TRUE
09-07 13:17:26.196  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 13:17:26.196  7061  7061 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:26.196  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 13:17:26.196  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:26.197  1034  7072 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:26.197  1034  7072 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:26.197  7061  7061 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 13:17:26.197  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-07 13:17:26.197  7061  7061 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-07 13:17:26.197  7061  7061 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.197  1927  2285 D WfdsService: selectPreferredScanChannel [36]
09-07 13:17:26.197  1927  2285 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-07 13:17:26.197  1927  7094 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:26.197  1034  7072 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:26.197  1927  1927 D WfdsService: isConnected: false
09-07 13:17:26.197  1034  7072 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.197  1034  7072 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.197  1034  7072 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.198  7061  7061 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.198  1927  7094 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:26.198  1034  7072 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:26.198  1034  7072 E WifiMonitor: WifiMonitor:p2p0 cnt=2,3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.198  1034  7072 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.198  1034  7072 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.199  1034  1522 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-07 13:17:26.200  1034  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-07 13:17:26.200  1034  1522 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-07 13:17:26.200  1034  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
09-07 13:17:26.200  1034  1522 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-07 13:17:26.200  1034  1521 D WifiNative-p2p0: SET device_name G3: returned true
09-07 13:17:26.200  1034  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-07 13:17:26.200  1034  1521 D LGWifiP2pService: before postfix = G3
09-07 13:17:26.200  1034  1521 D WifiServerServiceExt: postfix byte check : 2
09-07 13:17:26.200  1034  1521 D LGWifiP2pService: after postfix = G3
09-07 13:17:26.200  1034  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-07 13:17:26.200  1034  1522 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-07 13:17:26.200  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-07 13:17:26.201  1034  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-07 13:17:26.201  1034  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-07 13:17:26.201  1034  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-07 13:17:26.201  1034  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-07 13:17:26.201  1034  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-07 13:17:26.201  1034  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-07 13:17:26.202  1034  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-07 13:17:26.202  1034  1521 D WifiNative-HAL: p2pGetDeviceAddress
09-07 13:17:26.202  1034  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-07 13:17:26.203  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-07 13:17:26.203  7061  7061 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 13:17:26.204  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-07 13:17:26.204  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 13:17:26.204  1034  7072 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 13:17:26.204  1034  7072 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 13:17:26.204  1034  1522 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-07 13:17:26.204  1034  1522 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-07 13:17:26.205  1034  1522 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-07 13:17:26.205  1034  1522 D WifiNative-wlan0: doBoolean: SCAN
09-07 13:17:26.206  1034  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-07 13:17:26.206  1034  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,09-07 13:17:26.206  1034  1522 D WifiNative-wlan0: SCAN: returned false
09-07 13:17:26.207  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
09-07 13:17:26.207  1034  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=192352  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 13:17:26.207  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-07 13:17:26.207  1927  1927 D WfdsService: Update P2p Interface State: 3
09-07 13:17:26.208  1034  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
09-07 13:17:26.208  1034  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-07 13:17:26.208  1034  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-07 13:17:26.209  1034  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-07 13:17:26.209  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:26.209  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:26.209  1034  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-07 13:17:26.209  1034  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-07 13:17:26.210  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=192356  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 13:17:26.210  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:26.211  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.211  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.211  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 13:17:26.211  1034  1522 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 13:17:26.212  1034  1522 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 13:17:26.213  1034  1522 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 13:17:26.213  1034  1522 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 13:17:26.214  1034  1522 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 13:17:26.215  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:26.215  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
09-07 13:17:26.217  1034  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-07 13:17:26.217  1034  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-07 13:17:26.218  1034  1521 D LGWifiP2pService: InactiveState
09-07 13:17:26.218  1034  1521 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.218  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.218  1034  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-07 13:17:26.218  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-07 13:17:26.219  7061  7061 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:26.219  1927  7094 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 13:17:26.219  1034  7072 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 13:17:26.219  1034  7072 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:26.219  1034  7072 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:26.219  1034  7072 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:26.219  7061  7061 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 13:17:26.219  7061  7061 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.219  1034  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  7061  7061 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.221  1034  7072 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:26.221  1034  7072 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.221  1034  7072 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.221  1034  7072 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.221  1034  7072 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:26.221  1034  7072 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.221  1034  7072 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.221  1034  7072 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:26.,220  1927  7094 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:26.221  1927  7094 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:26.221  1927  2285 W WfdsService: DefaultState - msg [9441285] is not handled
09-07 13:17:26.220  1034  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.222  1034  1034 E WifiServerServiceExt: No p2p device connected
09-07 13:17:26.241  7075  7075 D LgDataFeature: LgDataFeature() Constructor: none
09-07 13:17:26.242  7075  7075 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 13:17:26.244  7075  7075 D PhoneMonitor: Register our PhoneStateListener
09-07 13:17:26.252  7075  7075 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 13:17:26.254  7075  7075 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-07 13:17:26.263  7075  7075 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-07 13:17:26.264  7075  7075 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-07 13:17:26.265  7075  7075 D TelephonyAutoProfiling: [parse] Load xml
,09-07 13:17:26.269  7075  7075 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-07 13:17:26.269  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-07 13:17:26.269  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-07 13:17:26.269  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-07 13:17:26.269  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-07 13:17:26.269  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-07 13:17:26.269  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-07 13:17:26.269  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-07 13:17:26.269  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-07 13:17:26.269  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-07 13:17:26.269  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-07 13:17:26.270  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-07 13:17:26.270  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-07 13:17:26.270  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-07 13:17:26.270  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-07 13:17:26.270  7075  7075 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-07 13:17:26.270  7075  7075 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-07 13:17:26.276  7075  7075 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-07 13:17:26.299  1034  1909 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7098 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 13:17:26.299  1034  1909 I ActivityManager: Killing 6132:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-07 13:17:26.364  1034  1058 W libprocessgroup: failed to open /acct/uid_10097/pid_6132/cgroup.procs: No such file or directory
,09-07 13:17:26.602  1034  2018 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7122 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-07 13:17:26.611  1034  2018 I ActivityManager: Killing 6540:com.lge.eula/1000 (adj 15): empty #17
,09-07 13:17:26.676  1034  1945 W libprocessgroup: failed to open /acct/uid_1000/pid_6540/cgroup.procs: No such file or directory
09-07 13:17:26.749  7061  7061 E wpa_supplicant: USIM:  scard_init function
09-07 13:17:26.750  7061  7061 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-07 13:17:26.758  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-07 13:17:26.758  1034  7072 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-07 13:17:26.758  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-07 13:17:26.758  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: WPS-AP-AVAILABLE 
09-07 13:17:26.758  1034  7072 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-07 13:17:26.759  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-07 13:17:26.759  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-07 13:17:26.761  1034  1522 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-07 13:17:26.762  1034  1522 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-07 13:17:26.765  1034  1522 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-07 13:17:26.766  1034  1522 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-07 13:17:26.766  1034  1522 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-07 13:17:26.777  1034  1944 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7139 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 13:17:26.779  1034  1944 I ActivityManager: Killing 6557:com.lge.bnr/1000 (adj 15): empty #17
09-07 13:17:26.846  1034  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=192991  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-07 13:17:26.847  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=192992  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-07 13:17:26.849  1034  1980 W libprocessgroup: failed to open /acct/uid_1000/pid_6557/cgroup.procs: No such file or directory
09-07 13:17:26.856  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:26.857  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:26.857  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.857  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.857  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 13:17:26.859  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.859  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.859  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-07 13:17:26.861  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:26.861  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-07 13:17:26.865  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:26.870  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 13:17:26.871  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:26.873  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:26.878  7061  7061 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-07 13:17:26.880  1034  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 13:17:26.881  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-07 13:17:26.881  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-07 13:17:26.881  1034  1522 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:26.882  1034  1522 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:26.882  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-07 13:17:26.882  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-07 13:17:26.882  1034  1522 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:26.882  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 13:17:26.883  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-07 13:17:26.884  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:26.884  1034  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:26.885  1034  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=193030  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 13:17:26.890  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=193031  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 13:17:26.890  7061  7061 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 13:17:26.890  7061  7061 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 13:17:26.891  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 13:17:26.891  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 13:17:26.891  1034  1522 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 32 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193037
09-07 13:17:26.891  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-07 13:17:26.892  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 13:17:26.892  1034  7072 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 13:17:26.892  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-07 13:17:26.892  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 13:17:26.892  1034  1522 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 32 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193037
09-07 13:17:26.892  1034  7072 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 13:17:26.892  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 13:17:26.892  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 13:17:26.892  1034  1522 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 32 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193038
09-07 13:17:26.894  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 32 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193040
,09-07 13:17:26.895  1034  1522 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 32 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193040
,09-07 13:17:26.896  1034  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=193041  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 13:17:26.898  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:26.898  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:26.900  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:26.900  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.900  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.900  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 13:17:26.901  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=193047  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 13:17:26.904  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.904  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.904  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-07 13:17:26.906  1034  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=193051  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 13:17:26.906  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=193052  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 13:17:26.907  1034  1522 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=193052
09-07 13:17:26.907  1034  1522 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=193053
09-07 13:17:26.908  1034  1522 D WifiNative-wlan0: doString: [STATUS]
09-07 13:17:26.908  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 13:17:26.909  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-07 13:17:26.909  1034  1522 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 13:17:26.911  1034  1522 I WifiServiceExtension: setVHTCapabilityType  : false
09-07 13:17:26.912  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:26.912  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-07 13:17:26.917  1034  1522 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-07 13:17:26.917  1034  1522 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-07 13:17:26.922  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:26.922  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:26.925  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:17:26.925  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.925  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 13:17:26.927  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.927  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.927  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 13:17:26.929  7139  7139 I art     : Almond Protected OAT
09-07 13:17:26.930  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:26.930  1034  1522 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-07 13:17:26.930  1034  1529 D ConnectivityService: Got NetworkAgent Messenger
09-07 13:17:26.930  1034  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 13:17:26.930  1034  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 13:17:26.930  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 13:17:26.930  1034  1529 D ConnectivityService: NetworkAgent connected
09-07 13:17:26.930  1034  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 13:17:26.930  1034  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 13:17:26.933  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:26.933  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:26.934  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:26.936  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:26.936  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:26.936  1034  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 13:17:26.936  1034  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 13:17:26.936  1034  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-07 13:17:26.937  1034  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 13:17:26.937  1034  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 13:17:26.937  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:26.940  1034  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 13:17:26.942   308   892 D CommandListener: Setting iface cfg
09-07 13:17:26.944  1034  1522 E WifiStateMachine: Start Dhcp Watchdog 2
09-07 13:17:26.944  1034  7169 D DhcpStateMachine: StoppedState
09-07 13:17:26.944  1034  7169 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.945  1034  7169 D DhcpStateMachine: WaitBeforeStartState
09-07 13:17:26.945  1034  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=193090  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 13:17:26.945  1034  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=193091  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 13:17:26.946  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=193091  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 13:17:26.947  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:26.947  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-07 13:17:26.948  1034  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=193093  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 13:17:26.948  1034  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=193093  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 13:17:26.949  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=193094  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-07 13:17:26.949  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:26.949  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-07 13:17:26.950  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:147298] from screen [on:0 period:73264422] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-07 13:17:26.951  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:73264423] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-07 13:17:26.951  1034  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-07 13:17:26.955  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:26.956  1034  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-07 13:17:26.956  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.957  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.957  1034  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.957  1034  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.958  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.958  1034  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.959  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 13:17:26.959  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=121,0,0
09-07 13:17:26.959  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=121,0,0
09-07 13:17:26.959  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-07 13:17:26.960  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-07 13:17:26.960  1034  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-07 13:17:26.960  1034  1522 D WifiNative-wlan0: doBoolean: SET ps 0
09-07 13:17:26.961  1034  1522 D WifiNative-wlan0: SET ps 0: returned true
09-07 13:17:26.961  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
,09-07 13:17:26.961  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-07 13:17:26.961  1034  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-07 13:17:26.962  1034  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@366ccd5d target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.962  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@366ccd5d target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.962  1034  7169 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.962  1034  7169 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-07 13:17:26.962  1034  1522 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-07 13:17:26.962  1034  1522 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 13:17:26.963  1034  1522 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 13:17:26.963   308   892 D CommandListener: Setting iface cfg
09-07 13:17:26.964   308   892 D CommandListener: Trying to bring up wlan0
09-07 13:17:26.964  1034  1522 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-07 13:17:26.965  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:26.965  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 13:17:26.965  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:26.965  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 13:17:26.966  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.966  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.967  1034  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.967  1034  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.968  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.968  1034  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:26.968  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 13:17:26.969  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 13:17:26.969  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 13:17:26.969  1034  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.969  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:26.969  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 13:17:26.970  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 13:17:26.970  1034  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 13:17:26.970  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-07 13:17:26.970  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-07 13:17:26.970  1034  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-07 13:17:26.970  1034  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 13:17:26.980  7139  7139 D WeatherApplication: removeAccount
,09-07 13:17:26.981  7139  7139 D WeatherApplication: Account.length = 0
09-07 13:17:26.981  7139  7139 E WeatherApplication: OPERATOR:OPEN
09-07 13:17:26.985  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:17:26
09-07 13:17:26.986  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 13:17:26.987  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
09-07 13:17:26.987  1034  1522 D WifiNative-wlan0: SET ps 1: returned true
09-07 13:17:26.987  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 13:17:26.988  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 13:17:26.988  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 13:17:26.988  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 13:17:26.988  1034  1522 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 13:17:26.988  1034  1529 D ConnectivityService: ignoring duplicate network state non-change
09-07 13:17:26.990  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:26.990  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:26.991  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:26.991  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.991  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.991  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 13:17:26.993  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 13:17:26.993  1034  1529 D ConnectivityService: Adding iface wlan0 to network 101
09-07 13:17:26.994  7139  7139 D WeatherAncestor: connectivity changed - connection : true
09-07 13:17:26.994  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.994  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.995  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 13:17:26.995  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-07 13:17:26.997  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 13:17:26.998  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-07 13:17:26.999  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.999  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:26.999  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 13:17:27.001  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 13:17:27.001  1034  1522 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 13:17:27.004  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:27.004  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:27.004  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 13:17:27.011  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:27.011  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-07 13:17:27.013  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:27.015  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 13:17:27.015  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 13:17:27.015  7139  7139 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-07 13:17:27.017  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:27.017  1034  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 13:17:27.017  1034  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-07 13:17:27.017  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 13:17:27.018  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:27.018  1034  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-07 13:17:27.019   308   892 E Netd    : netlink response contains error (File exists)
09-07 13:17:27.019  1034  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-07 13:17:27.020  1034  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-07 13:17:27.020  1034  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-07 13:17:27.020  1034  1529 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-07 13:17:27.021  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-07 13:17:27.021  1034  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-07 13:17:27.021  1034  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-07 13:17:27.022  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-07 13:17:27.022  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:27.022  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-07 13:17:27.022  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:17:27.022  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:27.022  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:27.022  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 13:17:27.022  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:27.022  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-07 13:17:27.022  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:27.022  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 13:17:27.022  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-07 13:17:27.022  1034  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-07 13:17:27.022  1034  152,9 D ConnectivityService:    accepting network in place of null
09-07 13:17:27.022  1034  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:27.022  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:27.023  1034  1522 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:27.024  1034  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:17:27.025  1034  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-07 13:17:27.026  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:27.026  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 13:17:27.026  1034  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 13:17:27.026  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 13:17:27.026  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:27.026  1034  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-07 13:17:27.026   308  7174 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-07 13:17:27.027  1034  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-07 13:17:27.028  1034  1529 D ConnectivityService: validation of new default Network = false
09-07 13:17:27.028  1034  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-07 13:17:27.028  1034  1529 D DSQN    : enableDataServiceNotify 
09-07 13:17:27.028  1034  1529 D DSQN    : start dsqn bin
,09-07 13:17:27.032  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 13:17:27.033  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:17:27
09-07 13:17:27.034  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-07 13:17:27.034  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 13:17:27.034  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 13:17:27.034  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 13:17:27.024  7175  7175 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:27.038  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-07 13:17:27.024  7175  7175 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:27.038  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:27.038  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:27.039  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:27.040  1587  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-07 13:17:27.050  7175  7175 E DSQN    : DSQN ssw
09-07 13:17:27.062  1034  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:27.062  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:27.062  1034  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 13:17:27.081  1034  2015 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7179 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 13:17:27.082  1034  2015 I ActivityManager: Killing 2158:com.lge.music/u0a34 (adj 15): empty #17
,09-07 13:17:27.082   308  7174 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-07 13:17:27.097   312  1365 V AudioFlinger: 2158 died, releasing its sessions
09-07 13:17:27.097   312  1365 V AudioFlinger:  pid 1837 @ 0
09-07 13:17:27.097   312  1365 V AudioFlinger:  pid 3443 @ 1
09-07 13:17:27.097   312  1365 V AudioFlinger:  pid 3443 @ 2
,09-07 13:17:27.117   308  7174 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-07 13:17:27.121  1034  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 13:17:27.122  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 13:17:27.122  1034  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 13:17:27.123  1034  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 13:17:27.123  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 13:17:27.123  1034  1522 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 13:17:27.144   308   891 D LGDataListener: argv[0]=dsqncommand
09-07 13:17:27.144   308   891 D LGDataListener: argv[1]=wlan0
09-07 13:17:27.144   308   891 D LGDataListener: argv[2]=1
09-07 13:17:27.144   308   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-07 13:17:27.144  1034  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-07 13:17:27.144  1034  1115 D DSQN    : start to monitor internet connection
,09-07 13:17:27.153  1034  1098 W ActivityManager: Failed to clear dns cache for: com.lge.music
09-07 13:17:27.157  1034  1944 W libprocessgroup: failed to open /acct/uid_10034/pid_2158/cgroup.procs: No such file or directory
,09-07 13:17:27.166  1034  7169 D DhcpStateMachine: DHCPV4 request on wlan0
09-07 13:17:27.166  1034  7169 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-07 13:17:27.166  1034  7169 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-07 13:17:27.167  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 11:17:27 GMT], X-Android-Received-Millis=[1473247047167], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473247047142]}
09-07 13:17:27.168  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-07 13:17:27.168  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-07 13:17:27.170  1034  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-07 13:17:27.170  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-07 13:17:27.170  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:17:27.170  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:27.170  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 13:17:27.170  1034  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-07 13:17:27.170  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-07 13:17:27.170  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:27.170  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:27.173  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:27.173  1034  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:27.173  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 13:17:27.173  1034  1522 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:27.173  1034  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:17:27.174  1587  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 13:17:27.175  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:27.175  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-07 13:17:27.154  7198  7198 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:27.154  7198  7198 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:27.179  7198  7198 I dhcpcd  : version 5.5.6 starting
09-07 13:17:27.181  7198  7198 E dhcpcd  : get_duid: m
09-07 13:17:27.181  7198  7198 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-07 13:17:27.181  7198  7198 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-07 13:17:27.196  1034  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-07 13:17:27.204  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 13:17:27.206  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:27.207  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 13:17:27.227  1800  7202 I CheckinService: active receiver: enabled
,09-07 13:17:27.240  1800  7202 I CheckinService: Preparing to send checkin request
09-07 13:17:27.241  1800  7202 I EventLogService: Accumulating logs since 1473246911502
09-07 13:17:27.242  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 13:17:27.243  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:27.244  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:27.244  7198  7198 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 13:17:27.245  7198  7198 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 13:17:27.245  7198  7198 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 13:17:27.245  7198  7198 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-07 13:17:27.245  7198  7198 D dhcpcd  : wlan0: sending REQUEST (xid 0x96660f99), next in 3.35 seconds
09-07 13:17:27.279  1800  7202 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 13:17:27.289   278   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 13:17:27.289   278   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-07 13:17:27.289   278   358 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 13:17:27.290  7198  7198 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-07 13:17:27.290  7179  7208 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-07 13:17:27.294   278   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 13:17:27.294   278   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-07 13:17:27.294   278   358 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 13:17:27.295  7179  7208 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-07 13:17:27.305   278   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 13:17:27.305   278   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-07 13:17:27.305   278   358 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 13:17:27.306  7179  7210 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-07 13:17:27.307   278   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 13:17:27.307   278   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-07 13:17:27.307   278   358 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 13:17:27.308  7179  7210 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-07 13:17:27.313  7198  7198 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-07 13:17:27.313  7198  7198 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-07 13:17:27.313  7198  7198 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-07 13:17:27.313  7198  7198 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-07 13:17:27.313  7198  7198 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 13:17:27.313  7198  7198 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-07 13:17:27.313  7198  7198 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 13:17:27.313  7198  7198 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-07 13:17:27.416  1034  1872 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7225 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-07 13:17:27.462  7225  7225 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-07 13:17:27.463  7225  7225 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-07 13:17:27.482  7225  7225 I MultiDex: VM with version 2.1.0 has multidex support
,09-07 13:17:27.483  7225  7225 I MultiDex: install
09-07 13:17:27.483  7225  7225 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-07 13:17:27.491  7225  7225 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-07 13:17:27.569  1034  7169 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-07 13:17:27.570  1034  7169 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-07 13:17:27.570  1034  7169 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 13:17:27.571  1034  7169 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-07 13:17:27.571  1034  7169 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-07 13:17:27.571  1034  7169 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 13:17:27.571  1034  7169 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-07 13:17:27.571  1034  7169 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-07 13:17:27.571  1034  7169 D DhcpStateMachine: RunningState
09-07 13:17:27.589  7179  7179 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-07 13:17:27.602  7179  7179 I LibraryLoader: Loading: webviewchromium
09-07 13:17:27.606  7179  7179 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3758-3763)
09-07 13:17:27.606  7179  7179 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 13:17:27.615  7179  7179 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3491a9b1}
,09-07 13:17:27.617  7179  7179 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 13:17:27.617  7179  7179 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 13:17:27.629  7179  7179 I BrowserStartupController: Initializing chromium process, renderers=0
09-07 13:17:27.631  7179  7179 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 13:17:27.651  7179  7179 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-07 13:17:27.652  7179  7179 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-07 13:17:27.652  7179  7179 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,09-07 13:17:27.658   312   312 V AudioPolicyService: registerClient() client 0xb14275e0, uid 10093
09-07 13:17:27.661  7179  7270 W AudioManagerAndroid: Requires BLUETOOTH permission
09-07 13:17:27.680  7179  7179 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 13:17:27.680  7179  7179 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 13:17:27.680  7179  7179 I Adreno-EGL: Build Date: 12/12/14 금
09-07 13:17:27.680  7179  7179 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 13:17:27.680  7179  7179 I Adreno-EGL: Remote Branch: 
09-07 13:17:27.680  7179  7179 I Adreno-EGL: Local Patches: 
09-07 13:17:27.680  7179  7179 I Adreno-EGL: Reconstruct Branch: 
,09-07 13:17:27.761  7179  7179 I NSApplication: Starting up...
,09-07 13:17:27.814  1034  1908 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7283 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-07 13:17:27.815  1034  1998 I ActivityManager: Killing 6064:com.android.vending/u0a44 (adj 15): empty #17
,09-07 13:17:27.895  1034  1057 W libprocessgroup: failed to open /acct/uid_10044/pid_6064/cgroup.procs: No such file or directory
,09-07 13:17:27.920  7300  7300 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-07 13:17:27.932  7283  7283 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 13:17:27.992  7300  7300 I dex2oat : dex2oat took 71.449ms (threads: 4)
,09-07 13:17:28.009  7225  7243 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 13:17:28.009  7225  7243 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 13:17:28.009  7225  7243 I Adreno-EGL: Build Date: 12/12/14 금
09-07 13:17:28.009  7225  7243 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 13:17:28.009  7225  7243 I Adreno-EGL: Remote Branch: 
09-07 13:17:28.009  7225  7243 I Adreno-EGL: Local Patches: 
09-07 13:17:28.009  7225  7243 I Adreno-EGL: Reconstruct Branch: 
09-07 13:17:28.034  1034  1522 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-07 13:17:28.034  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 13:17:28.035  1034  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 13:17:28.036  1034  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 13:17:28.037  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 13:17:28.037  1034  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 13:17:28.037  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-07 13:17:28.037  1034  1529 D ConnectivityService: identical MTU - not setting
09-07 13:17:28.038  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-07 13:17:28.038  1034  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-07 13:17:28.038  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:28.038  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:28.038  1034  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:28.039  1034  1529 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-07 13:17:28.039  1587  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-07 13:17:28.116  1034  1908 I art     : Explicit concurrent mark sweep GC freed 101672(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.656ms total 107.707ms
09-07 13:17:28.117  1034  1559 D WifiServiceImplEx: setWifiEnabled: false pid=6660, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-07 13:17:28.117  1034  1559 D WifiService: setWifiEnabled: false pid=6660, uid=10118
09-07 13:17:28.117  1034  1559 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 13:17:28.127  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 13:17:28.128  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 13:17:28.128  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-07 13:17:28.128  1034  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 13:17:28.129  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 13:17:28.129  1034  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-07 13:17:28.130  1034  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-07 13:17:28.130  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-07 13:17:28.130  1034  1522 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 13:17:28.130  1034  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 13:17:28.130  1034  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 13:17:28.130  1034  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 13:17:28.130  1034  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-07 13:17:28.136  1034  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 13:17:28.137  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 13:17:28.137  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 13:17:28.137  1034  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:28.137  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:28.137  1034  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 13:17:28.137  1034  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 13:17:28.137  1034  1522 D WifiNative-wlan0: SET ps 1: returned true
09-07 13:17:28.137   308   892 D CommandListener: Clearing all IP addresses on wlan0
09-07 13:17:28.137  1034  7169 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 13:17:28.151  7225  7243 D LgDataFeature: LgDataFeature() Constructor: none
09-07 13:17:28.151  7225  7243 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 13:17:28.170  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 13:17:28.170  1034  1529 D ConnectivityService: ignoring duplicate network state non-change
09-07 13:17:28.171  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-07 13:17:28.172  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-07 13:17:28.174  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:28.174  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:28.175  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-07 13:17:28.175  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:28.176  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:28.176  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:28.176  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 13:17:28.178  1034  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:28.178  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:28.178  1034  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:28.179  1034  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:28.179  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:28.180  1034  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:28.180  1034  1522 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 13:17:28.180  1034  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 13:17:28.180  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:28.180  1034  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@cf9605c
09-07 13:17:28.180  1034  1521 D LGWifiP2pService: P2pDisablingState
09-07 13:17:28.180  1034  1521 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:28.180  1034  1521 D LGWifiP2pService: p2p socket connection lost
09-07 13:17:28.180  1034  1521 D LGWifiP2pService: P2pDisabledState
09-07 13:17:28.181  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-07 13:17:28.183  1034  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-07 13:17:28.184  1034  1521 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:28.184  1034  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:28.184  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 13:17:28.184  7061  7061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 13:17:28.184  1034  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 13:17:28.184  1034  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 13:17:28.187  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:28.187  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:28.187  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 13:17:28.187  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 13:17:28.187  1034  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:28.188  1034  1034 D RttService: SCAN_AVAILABLE : 1
09-07 13:17:28.188  1034  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:28.189  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 13:17:28.190  1927  1927 D WfdsService: WifiP2pState is changed : false
09-07 13:17:28.190  1927  2285 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-07 13:17:28.190  1927  2285 D WfdsService: Set the WFDS Monitor: false
09-07 13:17:28.190  1927  2285 D WfdsMonitor: WFDS Monitor is stopped
09-07 13:17:28.190  1927  2285 D WfdsService: STATE : WfdsDisabledState - enter
09-07 13:17:28.190  1927  7094 D CtrlSupplicant: Received on exit socket, terminate
09-07 13:17:28.190  1927  7094 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-07 13:17:28.190  1927  7094 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-07 13:17:28.190  1927  7094 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-07 13:17:28.190  1034  1522 D WifiNative-wlan0: SET ps 1: returned true
09-07 13:17:28.191  1927  2287 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-07 13:17:28.191  1927  2285 W WfdsService: DefaultState - msg [9445378] is not handled
09-07 13:17:28.194  7225  7243 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 13:17:28.194  7225  7243 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 13:17:28.194  7225  7243 I Adreno-EGL: Build Date: 12/12/14 금
09-07 13:17:28.194  7225  7243 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 13:17:28.194  7225  7243 I Adreno-EGL: Remote Branch: 
09-07 13:17:28.194  7225  7243 I Adreno-EGL: Local Patches: 
09-07 13:17:28.194  7225  7,243 I Adreno-EGL: Reconstruct Branch: 
09-07 13:17:28.197  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:28.197  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:28.198  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:28.224   308   892 D CommandListener: Clearing all IP addresses on wlan0
09-07 13:17:28.224  1034  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-07 13:17:28.224  1034  1529 D DSQN    : disableDataServiceNotify
09-07 13:17:28.224  1034  1529 D DSQN    : stop dsqn bin
,09-07 13:17:28.225  1034  1522 D WifiNative-p2p0: doBoolean: TERMINATE
09-07 13:17:28.227  1034  1034 D WifiHS20: hidePasspointNotification off =false
09-07 13:17:28.227  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:28.227  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:28.227  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 13:17:28.228  1034  1522 D WifiNative-p2p0: TERMINATE: returned true
09-07 13:17:28.228  1034  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 13:17:28.228  1034  1522 E WifiStateMachine: useWiFiOffloading() : false
09-07 13:17:28.228  1034  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 13:17:28.230  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-07 13:17:28.230  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-07 13:17:28.231  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:28.231  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-07 13:17:28.231  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:28.231  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:28.231  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:28.231  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:28.231  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:28.231  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:28.231  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:28.231  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:28.231  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:28.231  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:28.231  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:28.232  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:28.232  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:28.232  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:28.232  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:28.232  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:28.232  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:28.232  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:28.232  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:28.232  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:28.232  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advert,isement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:28.232  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:28.232  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 13:17:28.232  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:28.232  1034  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-07 13:17:28.232  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:28.233  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:28.233  1034  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:28.233  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-07 13:17:28.233  1034  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-07 13:17:28.233  1034  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 13:17:28.233  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 13:17:28.234  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:28.234  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 13:17:28.234  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:28.234  1034  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:28.234  1034  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:28.234  1034  1529 D NetworkManagementService: Removing idletimer
09-07 13:17:28.234  1034  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:28.234  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:28.234  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 13:17:28.235  1587  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 13:17:28.235  1034  7168 D NetworkMonitor NetworkAgentInfo [WIF,I () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:28.235  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:28.235  1034  7168 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-07 13:17:28.236  1034  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 13:17:28.236  1034  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 13:17:28.238  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 13:17:28.238  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 13:17:28.239  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 13:17:28.239  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 13:17:28.239  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 13:17:28.239  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 13:17:28.239  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 13:17:28.239  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 13:17:28.243  1034  1522 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:28.243  1034  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:17:28.243  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:28.245  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:28.246  7225  7243 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 13:17:28.246  7225  7243 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 13:17:28.246  7225  7243 I Adreno-EGL: Build Date: 12/12/14 금
09-07 13:17:28.246  7225  7243 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 13:17:28.246  7225  7243 I Adreno-EGL: Remote Branch: 
09-07 13:17:28.246  7225  7243 I Adreno-EGL: Local Patches: 
09-07 13:17:28.246  7225  7243 I Adreno-EGL: Reconstruct Branch: 
09-07 13:17:28.266  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-07 13:17:28.266  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:28.267  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 13:17:28.280  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 13:17:28.281  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:28.281  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:28.305  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-07 13:17:28.308  6356  6822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 13:17:28.315  2227  2227 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:28.322  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-07 13:17:28.322  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:28.323  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 13:17:28.323  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 13:17:28.324  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
09-07 13:17:28.327  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@f908d0e
09-07 13:17:28.327  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 13:17:28.327  7001  7001 D AppUp4:CustFacade: isPhone : true
09-07 13:17:28.327  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
09-07 13:17:28.327  7001  7001 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 13:17:28.330  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:28.330  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 13:17:28.331  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:28.332  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:28.336  7061  7061 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-07 13:17:28.336  7061  7061 I wpa_supplicant: monitor socket send errors count : 1
09-07 13:17:28.336  7061  7061 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-4\x00 that cannot receive messages
09-07 13:17:28.338  1034  7072 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-07 13:17:28.338  1034  7072 D WifiMonitor: Dropping event because (p2p0) is stopped
09-07 13:17:28.338  7030  7030 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-07 13:17:28.340  4301  7321 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 13:17:28.341  4301  7322 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:28.341  4301  7322 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 13:17:28.354  1034  7169 D DhcpStateMachine: StoppedState
09-07 13:17:28.356  1034  7169 D DhcpStateMachine: StoppedState{ when=-165ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 13:17:28.358  7030  7323 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:28.359  1034  1522 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-07 13:17:28.359  1034  1522 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-07 13:17:28.364  3443  3443 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 13:17:28.364  3443  3443 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:28.364  3443  3443 I LgeMiscReceiver: networkInfo.isConnected() = false
09-07 13:17:28.367  7061  7061 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 13:17:28.367  7061  7061 W wpa_supplicant: USIM:  scard_deinit function
09-07 13:17:28.368  1034  1117 D Tethering: InitialState.processMessage what=4
,09-07 13:17:28.369  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,09-07 13:17:28.369  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 13:17:28.369  1034  7072 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 13:17:28.370  1034  7072 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-07 13:17:28.370  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 13:17:28.370  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 13:17:28.370  1034  1522 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=194515
09-07 13:17:28.370  1034  1522 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=194516
09-07 13:17:28.371  1034  1522 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=194516  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 13:17:28.371  7075  7075 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 13:17:28.371  7075  7075 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 13:17:28.371  1034  1522 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=194517  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 13:17:28.371  1034  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 13:17:28.372  1034  1522 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:28.372  1034  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:28.377  6929  7325 W FormManager: Network not available. Please check & try again.
09-07 13:17:28.380  6929  7326 V FormManager: Network unavailable.
,09-07 13:17:28.383  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:17:28
09-07 13:17:28.385  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 13:17:28.385  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
09-07 13:17:28.385  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 13:17:28.385  6929  7326 V FormManager: Network unavailable.
09-07 13:17:28.385  7139  7139 D WeatherAncestor: connectivity changed - connection : true
09-07 13:17:28.385  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@9dc5d3c
09-07 13:17:28.386  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 13:17:28.386  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 13:17:28.386  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 13:17:28.386  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 13:17:28.387  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:17:28
09-07 13:17:28.391   308  7332 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-07 13:17:28.392  1800  7202 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-07 13:17:28.392  1034  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-07 13:17:28.393  6929  7324 W art     : No such thread id for suspend: 15
,09-07 13:17:28.401  1800  7202 I CheckinService: active receiver: disabled
,09-07 13:17:28.413  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 13:17:28.414  6782  6782 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 13:17:28.414  6782  6782 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 13:17:28.414  6782  6782 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 13:17:28.414  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 13:17:28.414  6782  6782 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 13:17:28.414  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 13:17:28.415  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 13:17:28.415  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 13:17:28.415  6782  6782 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 13:17:28.415  6782  6782 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 13:17:28.419  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 13:17:28.421  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:17:28.424  6929  7334 W FormManager: Network not available. Please check & try again.
09-07 13:17:28.427  6929  7335 V FormManager: Network unavailable.
09-07 13:17:28.427  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:28.433  7061  7061 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-07 13:17:28.433  1034  7072 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-07 13:17:28.434  1034  7072 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-TERMINATING 
09-07 13:17:28.434  6929  7335 V FormManager: Network unavailable.
09-07 13:17:28.434  1034  7072 D WifiMonitor: Disconnecting from the supplicant, no more events
09-07 13:17:28.434  1034  1522 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 41 0
,09-07 13:17:28.446  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 13:17:28.449  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:17:28.451  6929  7337 W FormManager: Network not available. Please check & try again.
09-07 13:17:28.452  6929  7338 V FormManager: Network unavailable.
09-07 13:17:28.454  6929  7338 V FormManager: Network unavailable.
09-07 13:17:28.454  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:28.466  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 13:17:28.466  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 13:17:28.467  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 13:17:28.468  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:28.473  4301  7339 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 13:17:28.473  4301  7340 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 13:17:28.473  4301  7340 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 13:17:28.509  1034  1057 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7341 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-07 13:17:28.525   335   335 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 13.332ms
,09-07 13:17:28.536  1034  1522 D WifiOffDelayIfNotUsed: stopMonitoring
09-07 13:17:28.536  1034  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 13:17:28.536  1034  1522 E WifiStateMachine: useWiFiOffloading() : false
09-07 13:17:28.536  1034  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 13:17:28.536  1927  1927 D WfdsService: Supplicant Connection state is changed : false
09-07 13:17:28.537  1927  2285 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-07 13:17:28.537  1927  2285 D WfdsService: Set the WFDS Monitor: false
09-07 13:17:28.537  1927  2285 D WfdsMonitor: WFDS Monitor is stopped
09-07 13:17:28.538  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:28.538  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,09-07 13:17:28.540   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 253us total 12.770ms
09-07 13:17:28.541  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:28.541  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:28.541  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:28.541  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:28.541  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:28.541  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:28.541  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:28.541  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:28.541  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:17:28.541  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-07 13:17:28.542  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-07 13:17:28.542  2484  2484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:28.542  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 13:17:28.543  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:28.543  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:28.543  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:28.543  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:28.543  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:28.543  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:28.543  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:28.543  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:28.543  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:17:28.551   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 224us total 11.052ms
,09-07 13:17:28.611  7341  7341 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 13:17:28.611  7341  7341 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-07 13:17:28.618  7341  7341 V [BNRBootReceiver]: Boot Receiver Return
09-07 13:17:28.619  7341  7341 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 13:17:28.628  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 13:17:28.646  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:28.652  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:28.670  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:28.670  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:28.672  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 13:17:28.676  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-07 13:17:28.679  6782  6782 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-07 13:17:28.682  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 13:17:28.698  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:28.705  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:28.713  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 13:17:28.714  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:28.718  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 13:17:28.723  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:28.734  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:28.742  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:28.755  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:28.755  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 13:17:28.757  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 13:17:28.762  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:28.769  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:28.778  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:28.789  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:28.789  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 13:17:28.789  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 13:17:28.797  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:28.811  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:28.819  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:28.828  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 13:17:28.829  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:28.830  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 13:17:28.838  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:28.854  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:28.864  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 13:17:28.879  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:28.880  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 13:17:28.881  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 13:17:28.889  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:28.902  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:28.911  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 13:17:28.920  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:28.921  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:28.922  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 13:17:28.936  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 13:17:28.960  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:28.974  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 13:17:28.988  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 13:17:28.989  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:28.998  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 13:17:29.007  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 13:17:29.027  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:29.039  1034  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1065966058, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,09-07 13:17:29.044  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:29.056  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:29.057  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 13:17:29.057  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 13:17:29.067  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:29.080  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-07 13:17:29.096  2575  2575 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 13:17:29.118  1034  1528 D WifiService: New client listening to asynchronous messages
,09-07 13:17:29.120  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 13:17:29.126  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:29.134  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:29.143  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 13:17:29.143  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:29.144  6857  6857 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 13:17:29.145  6857  6857 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-07 13:17:29.146  6857  6857 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 13:17:29.153  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:29.157  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-07 13:17:29.159  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 13:17:29.163  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 13:17:29.169  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:29.176  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:29.177  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:29.178  6857  6857 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-07 13:17:29.178  6857  6857 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 13:17:29.179  6857  6857 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 13:17:29.182  1034  2037 I ActivityManager: Killing 6803:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-07 13:17:29.280  1034  1058 W libprocessgroup: failed to open /acct/uid_10037/pid_6803/cgroup.procs: No such file or directory
,09-07 13:17:29.290  2227  2227 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-07 13:17:29.311  2227  2227 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-07 13:17:29.313  2227  2227 D c       : Getting all permits...
09-07 13:17:29.313  2227  2227 D a       : Opening database...
09-07 13:17:29.324  2227  2227 D a       : Opening database auth.proximity.permit_store...
,09-07 13:17:29.328  1034  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{26319fe2 type 2 when 195472 com.google.android.gms} when 195472
09-07 13:17:29.329  2227  2227 D a       : Closing database...
09-07 13:17:29.345  6578  6981 D UEI.SmartControl: Internal timer expired: 2
09-07 13:17:29.345  6578  6981 D UEI.SmartControl: unbind internal service
,09-07 13:17:29.356  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:29.367  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 13:17:29.367  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-07 13:17:29.367  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 13:17:29.379  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:29.396  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:29.415  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 13:17:29.416  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 13:17:29.421  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 13:17:29.430  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 13:17:29.437  6578  6975 D serial_port: close(fd = 24)
,09-07 13:17:29.442  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 13:17:29.443  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 13:17:29.443  6578  6975 I UEI.SmartControl: Serial port is closed.
09-07 13:17:29.444  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 13:17:29.448  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:29.455  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 13:17:29.468  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 13:17:29.469  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 13:17:29.473  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 13:17:29.482  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:29.490  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 13:17:29.490  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 13:17:29.490  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 13:17:29.494  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 13:17:29.500  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:29.513  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:29.514  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 13:17:29.517  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 13:17:29.540  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 13:17:29.553  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:17:29.565  6929  7372 W FormManager: Network not available. Please check & try again.
09-07 13:17:29.568  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 13:17:29.574  6929  7373 V FormManager: Network unavailable.
09-07 13:17:29.579  6929  7373 V FormManager: Network unavailable.
,09-07 13:17:29.608  2227  2227 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-07 13:17:29.629  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-07 13:17:29.630  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 13:17:29.634  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:29.637  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:29.658  6823  6823 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-07 13:17:29.658  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 13:17:29.658  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 13:17:29.659  4301  7378 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 13:17:29.660  4301  7378 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 13:17:29.661  4301  7377 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 13:17:29.670  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:17:29.678  6929  7380 W FormManager: Network not available. Please check & try again.
09-07 13:17:29.680  6929  7381 V FormManager: Network unavailable.
09-07 13:17:29.683  6929  7381 V FormManager: Network unavailable.
09-07 13:17:29.684  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:29.700  6857  6857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,09-07 13:17:29.701  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7269
09-07 13:17:29.705  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1065966058 [*alarm*], flags=0x0
09-07 13:17:29.707   308  7383 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-07 13:17:29.708  1034  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-07 13:17:29.957  1034  1522 E WifiStateMachine:  InitialState CMD_RSSI_POLL 5 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:73267429] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 13:17:29.958  1034  1522 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 5 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:73267430] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-07 13:17:30.028  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:17:30.042  1034  1117 D Tethering: MasterInitialState.processMessage what=3
09-07 13:17:30.058  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:17:30.064  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-07 13:17:30.067  1034  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:30.070  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 13:17:30.072  6356  6822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-07 13:17:30.087  5739  5739 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-07 13:17:30.112  2227  2227 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:17:30.142  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 13:17:30.142  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:30.142  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 13:17:30.142  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-07 13:17:30.149  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
09-07 13:17:30.152  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@f908d0e
09-07 13:17:30.153  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 13:17:30.153  7001  7001 D AppUp4:CustFacade: isPhone : true
09-07 13:17:30.153  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
09-07 13:17:30.153  7001  7001 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 13:17:30.159  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:30.159  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 13:17:30.160  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 13:17:30.167  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:30.178  7030  7030 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-07 13:17:30.210  3443  3443 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 13:17:30.210  3443  3443 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:30.210  3443  3443 I LgeMiscReceiver: networkInfo.isConnected() = true
09-07 13:17:30.210  3443  3443 D PhoneState: setPdpRejectCasuse : false
,09-07 13:17:30.218  7075  7075 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 13:17:30.218  7075  7075 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 13:17:30.244  4301  7405 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 13:17:30.248  4301  7409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:30.249  4301  7409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 13:17:30.250  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:17:30
09-07 13:17:30.255  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-07 13:17:30.255  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
09-07 13:17:30.255  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 13:17:30.255  7139  7139 D WeatherAncestor: connectivity changed - connection : true
09-07 13:17:30.255  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@9dc5d3c
09-07 13:17:30.257  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 13:17:30.257  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 13:17:30.257  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 13:17:30.257  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 13:17:30.258  6929  7406 W FormManager: Network not available. Please check & try again.
09-07 13:17:30.259  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:17:30
09-07 13:17:30.259  7030  7391 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:17:30.267  1034  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:30.278  6929  7411 V FormManager: Network unavailable.
,09-07 13:17:30.286  6929  7411 V FormManager: Network unavailable.
,09-07 13:17:31.128  1034  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:31.129  1034  2037 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-07 13:17:31.159  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 13:17:31.159  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 13:17:31.160  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,09-07 13:17:31.163  1034  1117 D BluetoothManagerService: Message: 1
09-07 13:17:31.163  1034  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-07 13:17:31.189  1034  1117 D BluetoothManagerService: Message: 20
09-07 13:17:31.189  1034  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3fd3cb63:true
,09-07 13:17:31.192  6909  6909 D BluetoothAdapterState: make
09-07 13:17:31.197  6909  6909 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-07 13:17:31.197  6909  6909 I bluedroid-qcom: init
09-07 13:17:31.199  6909  7424 I BluetoothAdapterState: Entering OffState
09-07 13:17:31.199  6909  6909 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 13:17:31.199  6909  6909 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 13:17:31.199  6909  6909 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 13:17:31.200  6909  6909 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 13:17:31.200  6909  6909 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-07 13:17:31.201  6909  6909 I bluedroid-qcom: get_profile_interface socket
09-07 13:17:31.202  6909  6909 I bluedroid-qcom: get_profile_interface map_client
,09-07 13:17:31.194  7427  7427 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:31.208  6909  7428 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-07 13:17:31.210  6909  7428 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-07 13:17:31.194  7427  7427 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:31.216  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 13:17:31.216  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,09-07 13:17:31.223  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-07 13:17:31.224  1034  1117 D BluetoothManagerService: Message: 40
09-07 13:17:31.224  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-07 13:17:31.225  6909  6927 I bluedroid-qcom: config_hci_snoop_log
09-07 13:17:31.227  7427  7427 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-07 13:17:31.227  7427  7427 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-07 13:17:31.227  7427  7427 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-07 13:17:31.228  1034  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-07 13:17:31.228  1034  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-07 13:17:31.230  7427  7427 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-07 13:17:31.236  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:31.237  7427  7427 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-07 13:17:31.237  7427  7427 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-07 13:17:31.250  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:17:31.253  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:31.254  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:31.265  6909  7424 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-07 13:17:31.267  1034  1117 D Tethering: MasterInitialState.processMessage what=3
09-07 13:17:31.268  1034  1117 D Tethering: MasterInitialState.processMessage what=3
09-07 13:17:31.268  6909  7428 D BluetoothAdapterProperties: Name is: G3
09-07 13:17:31.270  6909  7424 D BluetoothAdapterProperties: Setting state to 11
09-07 13:17:31.270  6909  7424 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 13:17:31.272  1034  1117 D BluetoothManagerService: Message: 60
09-07 13:17:31.272  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-07 13:17:31.272  1034  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-07 13:17:31.273  6909  7424 I LGBluetoothServiceJni: classInitNative: succeeds
09-07 13:17:31.279  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:17:31.285  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:31.291  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-07 13:17:31.294  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:17:31.306  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:31.306  6782  6782 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-07 13:17:31.310  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:31.311  6909  7424 D BluetoothBondStateMachine: make
,09-07 13:17:31.316  6909  6909 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 13:17:31.317  6909  6909 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:31.318  6909  6909 V BluetoothPbapReceiver: ***********state = 11
09-07 13:17:31.321  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 13:17:31.322  6356  6822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 13:17:31.324  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 13:17:31.328  6909  7444 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 13:17:31.330  6909  7424 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:31.330  6909  7424 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-07 13:17:31.330  6909  7424 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:31.330  6909  7424 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-07 13:17:31.332  6909  7424 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-07 13:17:31.336  6909  7424 E BluetoothAdapterService: File transfer profiles supported!!
09-07 13:17:31.375  1034  1559 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7447 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-07 13:17:31.380  6909  7424 E BluetoothAdapterService: File transfer profiles supported!!
09-07 13:17:31.383  6909  6909 D HeadsetService: Received start request. Starting profile...
09-07 13:17:31.384  6909  6909 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 13:17:31.384  6909  6909 D LGBluetoothHfpAdapter: Version 1.6
09-07 13:17:31.387  6909  6909 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-07 13:17:31.388  6909  7424 E BluetoothAdapterService: File transfer profiles supported!!
09-07 13:17:31.388  6909  6909 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 13:17:31.389  6909  6909 D HeadsetStateMachine: make
09-07 13:17:31.393  5739  5739 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-07 13:17:31.394  6909  7424 E BluetoothAdapterService: File transfer profiles supported!!
09-07 13:17:31.400  6909  7424 E BluetoothAdapterService: File transfer profiles supported!!
09-07 13:17:31.404  6909  7424 E BluetoothAdapterService: File transfer profiles supported!!
09-07 13:17:31.407  6909  7424 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 13:17:31.418  6909  7424 V LGMDMManager: Create singleton instance
09-07 13:17:31.419  6909  7424 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-07 13:17:31.419  5739  5739 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-07 13:17:31.429  6909  6909 D LgDataFeature: LgDataFeature() Constructor: none
09-07 13:17:31.429  6909  6909 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 13:17:31.435  6909  6909 D HeadsetStateMachine: max_hf_connections = 1
09-07 13:17:31.435  6909  6909 I bluedroid-qcom: get_profile_interface handsfree
09-07 13:17:31.438  6909  6909 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-07 13:17:31.438   312  1365 V AudioPolicyService: registerClient() client 0xb1427400, uid 1002
09-07 13:17:31.439   312   312 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-07 13:17:31.439   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,09-07 13:17:31.439   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 13:17:31.439  6909  6909 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-07 13:17:31.439   312  1366 V AudioFlinger: registerClient() client 0xb55817a8, pid 6909
09-07 13:17:31.439   312  1361 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:31.439   312  1361 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 13:17:31.440  6909  6909 V ToneGenerator: Create Track: 0xb4929480
09-07 13:17:31.440  6909  6909 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-07 13:17:31.440  6909  6909 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-07 13:17:31.440   312  1360 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 13:17:31.440   312  1360 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 13:17:31.440   312  1365 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 13:17:31.440  1034  2018 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:31.440  1034  2018 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 13:17:31.440   312  1365 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-07 13:17:31.440   312  1365 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 13:17:31.440   312  1365 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 13:17:31.440  1034  2018 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 13:17:31.440  1034  2018 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 13:17:31.440  6909  6909 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-07 13:17:31.440  6909  6927 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:31.440  6909  6927 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-07 13:17:31.440  6909  6927 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 13:17:31.440  6909  6927 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-07 13:17:31.441  1587  2090 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:31.441  1587  2090 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 13:17:31.441  1587  2090 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 13:17:31.441  1587  2090 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 13:17:31.443   312  1367 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 13:17:31.443  1837  2708 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:31.443  1837  2708 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 13:17:31.443  1837  2708 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 13:17:31.443  1837  2708 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 13:17:31.443  3443  3458 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:31.443  3443  3458 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 13:17:31.443  3443  3458 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 13:17:31.443  3443  3458 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 13:17:31.444  2227  2227 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:17:31.446   312  1366 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 13:17:31.446   312  1366 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-07 13:17:31.446   312  1366 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 13:17:31.446   312  1366 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 13:17:31.446  6909  6909 V AudioSystem: getLatency() output 2, latency 50
09-07 13:17:31.446  6909  6909 V AudioSystem: getFrameCount() output 2, frameCount 960
09-07 13:17:31.446  6909  6909 V AudioTrack: createTrack_l() output 2 afLatency 50
09-07 13:17:31.446   312  1365 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 13:17:31.446   312  1365 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 13:17:31.447   312  1365 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 13:17:31.447   312  1365 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 13:17:31.447   312  1365 V AudioFlinger: createTrack() lSessionId: 22
09-07 13:17:31.447  6909  6909 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-07 13:17:31.448   312   312 V AudioFlinger: acquiring 22 from 6909, for 6909
09-07 13:17:31.448   312   312 V AudioFlinger:  added new entry for 22
09-07 13:17:31.448  6909  6909 V ToneGenerator: ToneGenerator INIT OK, time: 197605
09-07 13:17:31.448  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:31.449  6909  7459 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-07 13:17:31.449  6909  7459 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 13:17:31.449  6909  7459 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 13:17:31.449  6909  7459 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-07 13:17:31.449   312  1367 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6909
09-07 13:17:31.450   312  1367 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-07 13:17:31.450   312  1367 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-07 13:17:31.450   312  1367 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-07 13:17:31.450   312  1367 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 13:17:31.450   312  1367 V voice   : voice_set_parameters: exit with code(0)
09-07 13:17:31.450   312  1367 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-07 13:17:31.450   312  1367 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-07 13:17:31.450   312  1367 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 13:17:31.450   312  1367 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 13:17:31.450   312  1367 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-07 13:17:31.450   312  1367 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-07 13:17:31.450  6909  7459 V ToneGenerator: ToneGenerator destructor
09-07 13:17:31.450  6909  7459 V ToneGenerator: stopTone
09-07 13:17:31.450  6909  7459 V ToneGenerator: Delete Track: 0xb4929480
09-07 13:17:31.450  6909  7459 V AudioTrack: ~AudioTrack, releasing session id from 6909 on behalf of 6909
09-07 13:17:31.451   312   312 V AudioFlinger: releasing 22 from 6909 for 6909
09-07 13:17:31.451   312   312 V AudioFlinger:  decremented refcount to 0
09-07 13:17:31.451   312   312 V AudioFlinger: purging stale effects
09-07 13:17:31.451   312   312 V AudioPolicyService: AudioCommandThread() adding release output 2
09-07 13:17:31.451   312   312 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-07 13:17:31.451   31,2   312 V AudioFlinger: PlaybackThread::Track destructor
09-07 13:17:31.451   312   312 V AudioFlinger: removeClient_l() pid 6909, calling pid 312
09-07 13:17:31.451   312  1272 V AudioPolicyService: AudioCommandThread() waking up
09-07 13:17:31.451   312  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
09-07 13:17:31.451   312  1272 V AudioPolicyManager: releaseOutput() 2
09-07 13:17:31.451   312  1272 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 13:17:31.451  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:31.454  6909  6909 D A2dpService: Received start request. Starting profile...
09-07 13:17:31.454  6909  6909 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 13:17:31.454  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 13:17:31.454  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:31.454  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 13:17:31.454  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 13:17:31.455  6909  6909 V Avrcp   : make
09-07 13:17:31.455  6909  6909 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-07 13:17:31.455  6909  6909 I bluedroid-qcom: get_profile_interface avrcp
09-07 13:17:31.456  1034  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:31.457  1034  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:31.457  1034  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:31.457  1034  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:31.459  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
09-07 13:17:31.463  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@f908d0e
09-07 13:17:31.463  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 13:17:31.463  7001  7001 D AppUp4:CustFacade: isPhone : true
09-07 13:17:31.463  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
09-07 13:17:31.463  6909  6909 V AudioManager: registerRemoteController: size of Media player list: 0
09-07 13:17:31.463  7001  7001 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 13:17:31.466  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:31.466  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 13:17:31.466  6909  6909 E AudioManager: No RCC entry present to update
09-07 13:17:31.466  6909  6909 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 13:17:31.467  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:31.468  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:31.470  6909  6909 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-07 13:17:31.471  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-07 13:17:31.471  6909  6909 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-07 13:17:31.474  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-07 13:17:31.474  7030  7030 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-07 13:17:31.476  4301  7471 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 13:17:31.480  4301  7474 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:31.481  4301  7474 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 13:17:31.506  7447  7447 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-07 13:17:31.507  7447  7447 W LG Account v2.2: No ProfileInfo entries
09-07 13:17:31.507  7447  7447 I LG Account v2.2: isEnabled: false
09-07 13:17:31.507  7447  7447 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-07 13:17:31.507  7447  7447 I Feature : [Lifetracker]Country: EU
09-07 13:17:31.507  7447  7447 I Feature : [Lifetracker]Operator: OPEN
09-07 13:17:31.507  7447  7447 I Feature : [Lifetracker]Ranking support: false
09-07 13:17:31.507  7447  7447 I Feature : [Lifetracker]Comfort support: false
09-07 13:17:31.507  7447  7447 I Feature : [Lifetracker]Accessory: true
09-07 13:17:31.507  7447  7447 I Feature : [Lifetracker]Health device: true
09-07 13:17:31.507  7447  7447 I Feature : [Lifetracker]Extra Pedometer: false
09-07 13:17:31.507  7447  7447 I Feature : [Lifetracker]Blood glucose device: false
09-07 13:17:31.508  7447  7447 I Feature : [Lifetracker]Device Number: 3
09-07 13:17:31.528  6782  6782 D BluetoothPermissionRequest: onReceive
,09-07 13:17:31.529  7030  7475 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:17:31.536  6929  7477 W FormManager: Network not available. Please check & try again.
09-07 13:17:31.541  6782  6782 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-07 13:17:31.544  6929  7478 V FormManager: Network unavailable.
09-07 13:17:31.547  3443  3443 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 13:17:31.548  3443  3443 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:31.549  3443  3443 I LgeMiscReceiver: networkInfo.isConnected() = false
09-07 13:17:31.555  7075  7075 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 13:17:31.555  7075  7075 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-07 13:17:31.557  1034  2015 V SIM_STK : Menu title from STK is T-Mobile
09-07 13:17:31.557  1034  2015 V SIM_STK : Menu title from STK is T-Mobile
09-07 13:17:31.562  6929  7478 V FormManager: Network unavailable.
09-07 13:17:31.579  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:17:31
,09-07 13:17:31.583  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 13:17:31.583  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
09-07 13:17:31.584  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 13:17:31.584  7139  7139 D WeatherAncestor: connectivity changed - connection : true
09-07 13:17:31.584  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@9dc5d3c
09-07 13:17:31.585  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 13:17:31.586  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 13:17:31.586  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 13:17:31.586  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 13:17:31.586  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:17:31
09-07 13:17:31.611  6356  6356 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-07 13:17:31.615  6356  6822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 13:17:31.634  2227  2227 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:17:31.649  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 13:17:31.649  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:17:31.649  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 13:17:31.650  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 13:17:31.654  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
09-07 13:17:31.656  1034  1998 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-07 13:17:31.659  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@f908d0e
09-07 13:17:31.659  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 13:17:31.659  7001  7001 D AppUp4:CustFacade: isPhone : true
09-07 13:17:31.659  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
09-07 13:17:31.660  7001  7001 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 13:17:31.664  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:31.665  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-07 13:17:31.665  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-07 13:17:31.669  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:31.671  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-07 13:17:31.672  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-07 13:17:31.672  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 13:17:31.672  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 13:17:31.672  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:31.672  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 13:17:31.672  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 13:17:31.672  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 13:17:31.672  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-07 13:17:31.673  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 13:17:31.674  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 13:17:31.674  6909  6909 I BluetoothA2dpServiceJni: classInitNative
09-07 13:17:31.675  6909  6909 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 13:17:31.675  6909  6909 D A2dpStateMachine: make
09-07 13:17:31.677  6909  6909 I bluedroid-qcom: get_profile_interface a2dp
09-07 13:17:31.677  6909  7482 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-07 13:17:31.680  6909  6909 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-07 13:17:31.680  6909  6909 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-07 13:17:31.682  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:31.682  6909  7481 D A2dpStateMachine: Enter Disconnected: -2
09-07 13:17:31.683  6909  6909 I BluetoothHidServiceJni: classInitNative: succeeds
09-07 13:17:31.686  4301  7484 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 13:17:31.686  6909  6909 D HidService: Received start request. Starting profile...
09-07 13:17:31.686  6909  6909 I bluedroid-qcom: get_profile_interface hidhost
09-07 13:17:31.686  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:31.687  6909  6909 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 13:17:31.688  7030  7030 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-07 13:17:31.690  6909  6909 D HealthService: Received start request. Starting profile...
09-07 13:17:31.692  6909  6909 I bluedroid-qcom: get_profile_interface health
09-07 13:17:31.692  4301  7485 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:31.692  6909  6909 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-07 13:17:31.692  4301  7485 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 13:17:31.692  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
,09-07 13:17:31.695  6909  6909 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 13:17:31.697  6909  6909 D PanService: Received start request. Starting profile...
09-07 13:17:31.697  6909  6909 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 13:17:31.697  6909  6909 I bluedroid-qcom: get_profile_interface pan
09-07 13:17:31.705  6909  6909 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-07 13:17:31.705  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:31.706  6909  6909 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-07 13:17:31.711  6909  6909 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 13:17:31.712  6909  6909 D BtGatt.GattService: Received start request. Starting profile...
09-07 13:17:31.712  6909  6909 D BtGatt.GattService: start()
09-07 13:17:31.712  6909  6909 I bluedroid-qcom: get_profile_interface gatt
09-07 13:17:31.713  6909  6909 D BtGatt.AdvertiseManager: advertise manager created
,09-07 13:17:31.723  7030  7489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:31.723  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:31.725  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
,09-07 13:17:31.725  6909  6909 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-07 13:17:31.726  6909  6909 V BluetoothMapService: BluetoothMapBinder()
09-07 13:17:31.727  6909  6909 D BluetoothMapService: Received start request. Starting profile...
09-07 13:17:31.727  6909  6909 D BluetoothMapService: start()
09-07 13:17:31.728  3443  3443 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 13:17:31.728  3443  3443 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:31.728  3443  3443 I LgeMiscReceiver: networkInfo.isConnected() = false
09-07 13:17:31.731  6929  7492 W FormManager: Network not available. Please check & try again.
09-07 13:17:31.732  6909  6909 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-07 13:17:31.732  6909  6909 D BluetoothMapEmailAppObserver: createReceiver()
09-07 13:17:31.734  7075  7075 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 13:17:31.735  7075  7075 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 13:17:31.736  6909  6909 D BluetoothMapEmailAppObserver: initObservers()
09-07 13:17:31.736  6909  6909 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-07 13:17:31.744  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:17:31
09-07 13:17:31.744  6929  7493 V FormManager: Network unavailable.
09-07 13:17:31.745  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 13:17:31.745  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
09-07 13:17:31.746  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:31.746  6909  6909 D HeadsetStateMachine: Proxy object connected
,09-07 13:17:31.746  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 13:17:31.747  6909  6909 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-07 13:17:31.747  7139  7139 D WeatherAncestor: connectivity changed - connection : true
09-07 13:17:31.747  6909  6909 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-07 13:17:31.747  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@9dc5d3c
09-07 13:17:31.747  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 13:17:31.748  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 13:17:31.748  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 13:17:31.748  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 13:17:31.748  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:17:31
09-07 13:17:31.748  6909  7459 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 13:17:31.748  6929  7493 V FormManager: Network unavailable.
,09-07 13:17:31.749  6909  7459 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 13:17:31.749  6909  7459 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-07 13:17:31.753  6909  6909 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 13:17:31.756  6909  6909 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 13:17:31.758  6909  6909 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 13:17:31.761  6909  6909 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-07 13:17:31.764  6909  6909 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 13:17:31.765  6909  6909 V PanService: [BTUI] SIM Extra State :ABSENT
09-07 13:17:31.767  6909  6909 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-07 13:17:31.767  6909  6909 V BluetoothMapService: Handler(): got msg=1
09-07 13:17:31.768  6909  7424 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-07 13:17:31.768  6909  7424 I bluedroid-qcom: enable
09-07 13:17:31.769  6909  7496 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-07 13:17:31.769  6909  7424 I bt_hci_bdroid: init
09-07 13:17:31.769  6909  7496 I bt-btu  : btu_task pending for preload complete event
09-07 13:17:31.770  6909  6909 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:31.770  6909  7424 I bt_vendor: bt-vendor : init
09-07 13:17:31.770  6909  7424 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 13:17:31.770  6909  7424 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 13:17:31.770  6909  7424 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-07 13:17:31.770  6909  7424 D bt_userial_mct: userial_init
09-07 13:17:31.771  6909  7424 D bt_hci_bdroid: set_power 1
09-07 13:17:31.771  6909  7424 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-07 13:17:31.771  6909  7424 I bt_vendor: Starting hciattach daemon
09-07 13:17:31.771  6909  7424 I bt_vendor: try to set true
09-07 13:17:31.764  7499  7499 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 13:17:31.764  7499  7499 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:31.775  6909  6909 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 13:17:31.775  6909  6909 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 13:17:31.775  6909  6909 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 13:17:31.775  6909  6909 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:31.775  6909  6909 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-07 13:17:31.790  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-07 13:17:31.877  7506  7506 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-07 13:17:31.896  7507  7507 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 13:17:31.924  7509  7509 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 13:17:31.945  7510  7510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-07 13:17:31.958  7511  7511 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 13:17:31.971  7512  7512 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-07 13:17:31.996  7514  7514 I libmdmdetect: ESOC framework not supported
,09-07 13:17:32.000  7514  7514 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-07 13:17:32.008  7514  7514 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-07 13:17:32.008  7514  7514 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-07 13:17:32.008  7514  7514 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-07 13:17:32.008  7514  7514 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-07 13:17:32.008  7514  7514 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-07 13:17:32.008  7514  7514 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-07 13:17:32.008  7514  7514 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-07 13:17:32.048  7514  7515 E QC-QMI  : qmi_client [7514] 14: failed to locate client data
,09-07 13:17:32.053   473   473 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-07 13:17:32.053   473   473 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-07 13:17:32.145  7522  7522 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-07 13:17:32.173  7526  7526 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 13:17:32.227  6909  7424 I bt_vendor: bluetooth satus is on
09-07 13:17:32.227  6909  7424 D bt_hci_bdroid: preload
,09-07 13:17:32.229  6909  7498 D bt_userial_mct: userial_open(port:0)
09-07 13:17:32.229  6909  7498 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-07 13:17:32.233  6909  7498 I bt_vendor: Done intiailizing UART
09-07 13:17:32.234  6909  7498 I bt_vendor: Done intiailizing UART
09-07 13:17:32.234  6909  7498 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-07 13:17:32.234  6909  7498 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-07 13:17:32.234  6909  7496 I bt-btu  : btu_task received preload complete event
09-07 13:17:32.235  6909  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-07 13:17:32.235  6909  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-07 13:17:32.237  6909  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-07 13:17:32.239  6909  7528 D bt_userial_mct: Entering userial_read_thread()
,09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 13:17:32.245  6909  7496 I         : BTE_InitTraceLevels -- TRC_BTIF
09-07 13:17:32.293  6909  7496 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-07 13:17:32.293  6909  7496 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c6061 
09-07 13:17:32.293  6909  7496 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c6061 
,09-07 13:17:32.318  6909  7428 E bt-btif : Calling BTA_HhEnable
09-07 13:17:32.318  6909  7428 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-07 13:17:32.319  6909  7428 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-07 13:17:32.325  6909  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-07 13:17:32.325  6909  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-07 13:17:32.325  6909  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-07 13:17:32.325  6909  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-07 13:17:32.325  6909  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-07 13:17:32.328  6909  7428 D BluetoothAdapterProperties: Name is: G3
09-07 13:17:32.331  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 13:17:32.333  6909  7428 D BluetoothAdapterProperties: Scan Mode:20
09-07 13:17:32.333  6909  7428 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 13:17:32.333  6909  7428 D bt_hci_bdroid: postload
09-07 13:17:32.334  6909  7498 D bt_hci_bdroid: Used up Tx Cmd credits
,09-07 13:17:32.336  6909  7496 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 13:17:32.337  6909  7496 W bt-smp  : Plain text(LSB ~ MSB) = 44 29 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 13:17:32.337  6909  7496 W bt-smp  : Encrypted text(LSB ~ MSB) = 26 2d 4a 6f 60 bb 0c a1 e1 9d b3 1a b8 eb 17 d0 
09-07 13:17:32.337  6909  7498 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 13:17:32.337  6909  7496 W bt-btm  : Stopping oneshot timer
09-07 13:17:32.338  6909  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-07 13:17:32.338  6909  7428 D bte_conf: Device ID record 1 : primary
09-07 13:17:32.338  6909  7428 D bte_conf:   vendorId            = 00c4
09-07 13:17:32.338  6909  7428 D bte_conf:   vendorIdSource      = 0001
09-07 13:17:32.338  6909  7428 D bte_conf:   product             = 13a1
09-07 13:17:32.338  6909  7428 D bte_conf:   version             = 1000
09-07 13:17:32.339  6909  7428 D bte_conf:   clientExecutableURL = 
09-07 13:17:32.339  6909  7428 D bte_conf:   serviceDescription  = 
09-07 13:17:32.339  6909  7428 D bte_conf:   documentationURL    = 
09-07 13:17:32.339  6909  7428 D bte_conf: bte_load_did_conf no section named DID2.
09-07 13:17:32.340  6909  7498 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 13:17:32.340  6909  7498 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 13:17:32.341  6909  7498 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 13:17:32.343  6909  7528 E bt_mct  : hci lib postload completed
09-07 13:17:32.334  7531  7531 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:32.347  6909  7424 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 13:17:32.348  6909  7424 D BluetoothAdapterProperties: ScanMode =  20
09-07 13:17:32.348  6909  7424 D BluetoothAdapterProperties: State =  11
09-07 13:17:32.348  6909  7424 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-07 13:17:32.348  6909  7424 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-07 13:17:32.348  6909  7424 D BluetoothAdapterProperties: Setting state to 12
09-07 13:17:32.348  6909  7424 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 13:17:32.352  6909  7428 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 13:17:32.352  6909  7428 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 13:17:32.344  7531  7531 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:32.356  1034  1117 D BluetoothManagerService: Message: 60
09-07 13:17:32.356  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-07 13:17:32.356  1034  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-07 13:17:32.373  6909  7424 I BluetoothAdapterState: Entering On State
,09-07 13:17:32.391  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,09-07 13:17:32.394  6909  7428 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 13:17:32.395  6909  7428 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-07 13:17:32.404  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:32.404  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:32.404  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:32.404  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:32.404  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:32.404  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:32.404  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:32.404  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:17:32.414  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:32.420  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:32.420  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:32.420  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:32.420  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:32.420  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:32.420  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:32.420  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:32.420  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:17:32.429  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:32.455  6782  6801 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 13:17:32.463  6909  7424 D LGBluetoothServiceAdapter: [BTUI] OnState
09-07 13:17:32.463  6909  7424 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-07 13:17:32.463  6909  7424 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-07 13:17:32.467  6909  7424 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-07 13:17:32.468  6909  7424 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-07 13:17:32.469  7548  7548 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-07 13:17:32.475  6782  6802 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 13:17:32.479  1837  2691 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:17:32.480  7179  7211 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-07 13:17:32.481  6782  6801 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 13:17:32.483  1837  1837 D BluetoothHeadset: Proxy object connected
09-07 13:17:32.484  6782  6802 D BluetoothPan: onBluetoothStateChange on: true
09-07 13:17:32.484  6782  6802 D BluetoothPan: onBluetoothStateChange call bindService
09-07 13:17:32.485  6782  6782 D BluetoothMap: Proxy object connected
09-07 13:17:32.485  6782  6782 D MapProfile: Bluetooth service connected
09-07 13:17:32.485  6782  6782 D BluetoothMap: getConnectedDevices()
09-07 13:17:32.486  6909  6927 V BluetoothMapService: getConnectedDevices()
09-07 13:17:32.487  6782  6782 D BluetoothInputDevice: Proxy object connected
,09-07 13:17:32.487  6782  6782 D HidProfile: Bluetooth service connected
09-07 13:17:32.488  1837  2708 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:17:32.489  6782  6782 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 13:17:32.489  6782  6782 D PanProfile: Bluetooth service connected
09-07 13:17:32.489  1837  1837 D BluetoothHeadset: Proxy object connected
09-07 13:17:32.489  1837  2691 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:17:32.491  1837  1837 D BluetoothHeadset: Proxy object connected
09-07 13:17:32.491  1034  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 13:17:32.497  1034  1034 D BluetoothA2dp: Proxy object connected
09-07 13:17:32.499  1034  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:17:32.500  1034  1034 D BluetoothHeadset: Proxy object connected
09-07 13:17:32.503  1034  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-07 13:17:32.503  1034  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-07 13:17:32.507  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-07 13:17:32.507  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:32.508  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 13:17:32.508  1927  2089 D LGBluetoothAPIService: Message: 1
09-07 13:17:32.508  1927  2089 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-07 13:17:32.512  6660  6660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 13:17:32.515  1034  1117 D BluetoothManagerService: Message: 40
09-07 13:17:32.515  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-07 13:17:32.518  1927  2089 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-07 13:17:32.518  6909  6909 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:17:32.518  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:32.518  6909  6909 D BluetoothMapService: STATE_ON
09-07 13:17:32.521  6909  6909 D LGBluetoothAPIServer: [BTUI] onCreate()
09-07 13:17:32.521  6909  6909 D LGBluetoothAPIServer: [BTUI] onBind()
09-07 13:17:32.522  6909  6909 V BluetoothMapService: Handler(): got msg=1
09-07 13:17:32.522  6782  6782 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 13:17:32.523  6909  6909 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-07 13:17:32.524  6909  7557 D BluetoothMapMasInstance: MAS initSocket()
09-07 13:17:32.525  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-07 13:17:32.525  6909  7557 D BluetoothMapMasInstance:   masId = 00
09-07 13:17:32.525  6909  7557 D BluetoothMapMasInstance:   msgTypes = 0e
09-07 13:17:32.525  6909  7557 D BluetoothMapMasInstance:   masName = SMS/MMS
09-07 13:17:32.525  6909  7557 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-07 13:17:32.525  1927  2089 D LGBluetoothAPIService: Message: 100
09-07 13:17:32.525  1927  2089 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-07 13:17:32.527  1034  1117 D BluetoothManagerService: Message: 30
09-07 13:17:32.527  1034  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:32.529  6782  6782 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-07 13:17:32.533  1034  1117 D BluetoothManagerService: Message: 30
,09-07 13:17:32.535  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:32.538  6909  7557 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:17:32.539  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:32.540  6909  6909 V BluetoothPbapService: Pbap Service onCreate
09-07 13:17:32.540  6909  6909 V BluetoothPbapService: Starting PBAP service
09-07 13:17:32.540  6909  7428 D BluetoothAdapterProperties: Scan Mode:21
09-07 13:17:32.541  6909  7428 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-07 13:17:32.541  6909  6909 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-07 13:17:32.542  6909  7557 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-07 13:17:32.542  6909  6909 V BluetoothPbapService: Pbap Service onBind
09-07 13:17:32.542  6909  7557 V BluetoothMapMasInstance: Succeed to create listening socket 
09-07 13:17:32.542  6909  7557 D BluetoothMapMasInstance: Accepting socket connection...
09-07 13:17:32.543  6909  6909 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:32.543  6909  6909 V BluetoothPbapService: state: 12
09-07 13:17:32.543  6909  6909 V BluetoothPbapService: Handler(): got msg=1
09-07 13:17:32.543  6782  6782 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-07 13:17:32.543  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:32.543  6909  6909 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-07 13:17:32.545  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:32.545  6909  7558 V BluetoothPbapService: Pbap Service initSocket
09-07 13:17:32.545  6782  6782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-07 13:17:32.551  1034  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 13:17:32.551  6782  6782 D BluetoothA2dp: Proxy object connected
09-07 13:17:32.552  6909  7558 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:17:32.552  6782  6782 D A2dpProfile: Bluetooth service connected
09-07 13:17:32.553  6909  6909 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 13:17:32.553  6909  6909 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:32.553  6909  6909 V BluetoothPbapReceiver: ***********state = 12
09-07 13:17:32.554  6909  7558 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-07 13:17:32.554  6909  7558 V BluetoothPbapService: Succeed to create listening socket 
09-07 13:17:32.554  6909  7558 V BluetoothPbapService: Accepting socket connection...
09-07 13:17:32.556  6782  6782 D BluetoothHeadset: Proxy object connected
09-07 13:17:32.556  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 13:17:32.556  2227  2227 D c       : Getting all permits...
09-07 13:17:32.557  2227  2227 D a       : Opening database...
09-07 13:17:32.557  6782  6782 D HeadsetProfile: Bluetooth service connected
,09-07 13:17:32.559  6782  6782 D BluetoothPbap: Proxy object connected
09-07 13:17:32.560  6782  6782 D PbapServerProfile: Bluetooth service connected
09-07 13:17:32.561  2227  2227 D a       : Opening database auth.proximity.permit_store...
09-07 13:17:32.562  2227  2227 D a       : Closing database...
09-07 13:17:32.566  6782  6782 D DockEventReceiver: finishStartingService: stopping service
09-07 13:17:32.574  6782  6782 D BluetoothPermissionRequest: onReceive
,09-07 13:17:32.575  6782  6782 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-07 13:17:32.577  6782  6782 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 13:17:32.580  6909  6909 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-07 13:17:32.582  6909  6909 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-07 13:17:32.588  6909  6909 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-07 13:17:32.608  6909  6909 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-07 13:17:32.608  6909  6909 V BtOppService: onCreate
,09-07 13:17:32.613  6909  6909 V BluetoothOppNotification: send message
,09-07 13:17:32.620  6909  6909 V BtOppService: Starting RfcommListener
09-07 13:17:32.626  6909  7563 V BtOppService: Deleted complete outbound shares, number =  0
09-07 13:17:32.628  6909  6909 D BluetoothOppPreference: Dumping Names:  
09-07 13:17:32.628  6909  6909 D BluetoothOppPreference: {}
,09-07 13:17:32.628  6909  6909 D BluetoothOppPreference: Dumping Channels:  
09-07 13:17:32.628  6909  6909 D BluetoothOppPreference: {}
09-07 13:17:32.629  6909  6909 V BtOppService: onStartCommand
09-07 13:17:32.631  6909  7566 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 13:17:32.632  6909  7563 V BtOppService: Deleted complete inbound failed shares, number = 0
09-07 13:17:32.634  6909  7563 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-07 13:17:32.634  6909  7566 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 13:17:32.635  6909  6909 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:32.635  6909  6909 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 13:17:32.635  6909  7563 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ba1d491 on behalf of 
09-07 13:17:32.638  6909  6909 V BluetoothOppNotification: new notify threadi!
09-07 13:17:32.640  6909  7566 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bd1dff6 on behalf of 
09-07 13:17:32.640  6909  6909 V BluetoothOppNotification: send delay message
,09-07 13:17:32.641  6909  6909 V BtOppService: start RfcommListener
09-07 13:17:32.642  6909  7567 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-07 13:17:32.644  6909  6909 V BtOppService: RfcommListener started
09-07 13:17:32.645  6909  6909 V BtOppService: ContentObserver received notification
09-07 13:17:32.645  6909  6909 V BtOppService: ContentObserver received notification
09-07 13:17:32.647  6909  7568 V BtOppRfcommListener: Starting RFCOMM listener....
09-07 13:17:32.648  1034  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 13:17:32.650  6909  7568 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:17:32.652  6909  7568 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
,09-07 13:17:32.653  6909  7568 V BtOppRfcommListener: Started RFCOMM listener....
09-07 13:17:32.653  6909  7568 I BtOppRfcommListener: Accept thread started.
09-07 13:17:32.653  6909  7568 V BtOppRfcommListener: Accepting connection...
09-07 13:17:32.654  6909  7567 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28dd7ff7 on behalf of 
09-07 13:17:32.655  6909  7566 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 13:17:32.655  6909  7567 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-07 13:17:32.655  6909  7566 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 13:17:32.657  6909  7567 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 13:17:32.658  6909  7567 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3dfe28cd on behalf of 
09-07 13:17:32.658  6909  7566 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1356ee64 on behalf of 
09-07 13:17:32.659  6909  7567 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 13:17:32.659  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:32.659  6909  6909 V BluetoothFtpService: Ftp Service onCreate
09-07 13:17:32.659  6909  6909 I BluetoothFtpService: Ftp Service onCreate
09-07 13:17:32.660  6909  6909 V BluetoothFtpService: Ftp Service onStartCommand
09-07 13:17:32.660  6909  6909 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:32.660  6909  6909 V BluetoothFtpService: Starting Listening on sockets
09-07 13:17:32.660  6909  6909 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 13:17:32.660  6909  6909 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 13:17:32.660  6909  6909 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 13:17:32.660  6909  6909 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:32.660  6909  6909 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-07 13:17:32.660  6909  6909 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 13:17:32.661  6909  7566 V BluetoothOppNotification: update too frequent, put in queue
09-07 13:17:32.661  6909  7567 V BluetoothOppNotification: outbound notification was removed.
09-07 13:17:32.662  6909  7567 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 13:17:32.663  6909  6909 V BluetoothFtpService: Handler(): got msg=1
09-07 13:17:32.665  6909  6909 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-07 13:17:32.665  6909  6909 V BluetoothFtpService: Ftp Service initSocket
09-07 13:17:32.666  6909  7566 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-07 13:17:32.668  6909  7567 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11602493 on behalf of 
09-07 13:17:32.669  6909  7567 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-07 13:17:32.671  6909  7567 V BluetoothOppNotification: inbound notification was removed.
09-07 13:17:32.671  1034  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:32.671  6909  7567 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 13:17:32.673  6909  6909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 13:17:32.674  6909  7567 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dc68cd0 on behalf of 
09-07 13:17:32.675  6909  6909 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
,09-07 13:17:32.675  6909  6909 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-07 13:17:32.678  6909  7569 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-07 13:17:32.699  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:32.699  6909  6909 V BluetoothSapService: Sap Service onCreate
,09-07 13:17:32.701  6909  6909 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:17:32.701  6909  6909 V BluetoothSapService: state: 12
09-07 13:17:32.701  6909  6909 V BluetoothSapService: Starting SAP server process
09-07 13:17:32.694  7570  7570 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:32.704  6909  6909 V BluetoothSapService: SAP Service startRfcommListenerThread
09-07 13:17:32.694  7570  7570 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:32.706  6909  7571 V BluetoothSapService: Sap Service initRfcommSocket
09-07 13:17:32.707  1034  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:32.708  6909  7571 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:17:32.709  6909  7571 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-07 13:17:32.709  6909  7571 V BluetoothSapService: Succeed to create listening socket 
09-07 13:17:32.709  6909  7571 V BluetoothSapService: Accepting socket connection...
09-07 13:17:32.729  7570  7570 V BT_SAP  : Event pipe created
09-07 13:17:32.729  7570  7570 V BT_SAP  : create_server_socket qcom.sap.server
09-07 13:17:32.729  7570  7570 V BT_SAP  : created socket fd 6
,09-07 13:17:33.185  1034  1521 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 13:17:33.185  1034  1521 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 13:17:33.233  1034  1522 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-07 13:17:33.234  1034  1522 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-07 13:17:33.330  1034  1890 I ActivityManager: Killing 7341:com.lge.bnr/1000 (adj 15): empty #17
,09-07 13:17:33.364  1034  1058 W libprocessgroup: failed to open /acct/uid_1000/pid_7341/cgroup.procs: No such file or directory
,09-07 13:17:33.375  1034  1944 I ActivityManager: Killing 6823:com.lge.sync/1000 (adj 15): empty #17
09-07 13:17:33.391  1034  1528 D WifiService: Client connection lost with reason: 4
,09-07 13:17:33.416  1034  1633 W libprocessgroup: failed to open /acct/uid_1000/pid_6823/cgroup.procs: No such file or directory
,09-07 13:17:33.641  6909  6909 V BluetoothOppNotification: new notify threadi!
,09-07 13:17:33.641  6909  6909 V BluetoothOppNotification: send delay message
,09-07 13:17:33.655  6909  7581 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-07 13:17:33.663  6909  7581 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d4fa5fc on behalf of 
09-07 13:17:33.665  6909  7581 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-07 13:17:33.674  6909  7581 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 13:17:33.676  6909  7581 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c64a485 on behalf of 
09-07 13:17:33.677  6909  7581 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 13:17:33.679  6909  7581 V BluetoothOppNotification: outbound notification was removed.
09-07 13:17:33.679  6909  7581 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 13:17:33.680  6909  7581 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14d8c2da on behalf of 
09-07 13:17:33.680  6909  7581 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-07 13:17:33.684  6909  7581 V BluetoothOppNotification: inbound notification was removed.
,09-07 13:17:33.684  6909  7581 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 13:17:33.686  6909  7581 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a45930b on behalf of 
09-07 13:17:34.177  1034  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:34.177  1034  1559 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@153a685f mBinding = false
,09-07 13:17:34.204  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 13:17:34.204  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 13:17:34.204  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,09-07 13:17:34.207  1034  1117 D BluetoothManagerService: Message: 2
09-07 13:17:34.208  1034  1117 D BluetoothManagerService: Sending off request.
09-07 13:17:34.209  6909  6927 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-07 13:17:34.210  6909  7424 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-07 13:17:34.210  6909  7424 D BluetoothAdapterProperties: Setting state to 13
09-07 13:17:34.210  6909  7424 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 13:17:34.211  6909  7424 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 13:17:34.211  6909  7424 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-07 13:17:34.213  6909  7428 D BluetoothAdapterProperties: Scan Mode:20
09-07 13:17:34.214  6909  7424 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 13:17:34.216  6909  7557 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-07 13:17:34.216  6909  7557 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 13:17:34.216  6909  7557 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-07 13:17:34.216  6909  7557 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-07 13:17:34.216  6909  7557 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-07 13:17:34.216  6909  7557 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-07 13:17:34.216  6909  7557 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-07 13:17:34.216  6909  7557 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-07 13:17:34.218  6909  7558 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 13:17:34.221  6909  7568 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 13:17:34.221  6909  7569 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 13:17:34.222  6909  7424 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 13:17:34.224  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-07 13:17:34.224  6909  7496 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-07 13:17:34.227  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 13:17:34.227  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 13:17:34.227  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 13:17:34.227  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 13:17:34.227  6909  7496 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:17:34.227  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 13:17:34.228  6909  7496 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:17:34.228  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 13:17:34.228  6909  7496 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:17:34.228  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-07 13:17:34.228  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-07 13:17:34.228  6909  7496 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 13:17:34.237  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:34.237  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:34.237  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:34.237  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:34.237  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:34.237  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:34.237  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:34.237  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:34.237  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:17:34.243  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:34.243  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:34.246  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:34.246  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:34.246  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:34.246  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:34.246  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:34.246  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:17:34.246  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:34.246  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:34.246  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:17:34.247  6660  6660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:17:34.247  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:34.248  1034  1117 D BluetoothManagerService: Message: 60
09-07 13:17:34.248  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-07 13:17:34.248  1034  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-07 13:17:34.254  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:34.256  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 13:17:34.260  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:34.262  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:34.265  6909  6909 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:34.266  6909  6909 D BluetoothMapService: STATE_TURNING_OFF
09-07 13:17:34.266  6909  6909 V BluetoothMapService: Handler(): got msg=4
09-07 13:17:34.266  6909  6909 D BluetoothMapService: MAP Service closeService in
09-07 13:17:34.266  6909  6909 D BluetoothMapMasInstance: MAP Service shutdown
09-07 13:17:34.266  6909  6909 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 13:17:34.266  6909  6909 V BluetoothMapService: MAP Service closeService out
,09-07 13:17:34.270  6909  6909 V BtOppService: Receiver DISABLED_ACTION 
09-07 13:17:34.270  6909  6909 I BtOppRfcommListener: stopping Accept Thread
09-07 13:17:34.270  6909  6909 V BtOppRfcommListener: close mBtServerSocket
09-07 13:17:34.271  6909  7568 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 13:17:34.271  6909  6909 V BtOppRfcommListener: waiting for thread to terminate
09-07 13:17:34.271  6909  6909 V BtOppRfcommListener: done waiting for thread to terminate
09-07 13:17:34.278  6782  6782 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-07 13:17:34.283  6909  7571 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 13:17:34.287  6782  6782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 13:17:34.288  6909  6909 V BtOppService: onDestroy
09-07 13:17:34.290  6909  6909 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-07 13:17:34.294  6909  6909 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 13:17:34.294  6909  6909 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:34.295  6909  6909 V BluetoothPbapReceiver: ***********state = 13
,09-07 13:17:34.299  6909  6909 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-07 13:17:34.302  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 13:17:34.305  6909  6909 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:34.305  6909  6909 V BluetoothPbapService: state: 13
09-07 13:17:34.305  6909  6909 V BluetoothPbapService: Pbap Service closeService in
09-07 13:17:34.308  6909  6909 V BluetoothPbapService: successfully stopped pbap service
09-07 13:17:34.308  6909  6909 V BluetoothPbapService: Pbap Service closeService out
,09-07 13:17:34.312  6909  6909 V BluetoothPbapService: Pbap Service onDestroy
09-07 13:17:34.312  6909  6909 V BluetoothPbapService: Pbap Service closeService in
09-07 13:17:34.312  6909  6909 V BluetoothPbapService: Pbap Service closeService out
09-07 13:17:34.312  6909  6909 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-07 13:17:34.325  6782  6782 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:17:34.330  6782  6782 D BluetoothPbap: Proxy object disconnected
09-07 13:17:34.330  6782  6782 D PbapServerProfile: Bluetooth service disconnected
,09-07 13:17:34.350  6782  6782 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-07 13:17:34.355  6782  6782 D BluetoothPermissionRequest: onReceive
09-07 13:17:34.356  6782  6782 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-07 13:17:34.362  6782  6782 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-07 13:17:34.366  6909  6909 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-07 13:17:34.366  6909  6909 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-07 13:17:34.367  6909  6909 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-07 13:17:34.371  6909  6909 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:34.371  6909  6909 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 13:17:34.372  6909  6909 V BluetoothFtpService: Ftp Service onStartCommand
09-07 13:17:34.372  6909  6909 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:17:34.372  6909  6909 V BluetoothFtpService: Ftp Service closeService
09-07 13:17:34.373  6909  6909 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-07 13:17:34.374  6909  6909 V BluetoothFtpService: successfully stopped ftp service
09-07 13:17:34.375  6909  6909 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 13:17:34.375  6909  6909 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 13:17:34.375  6909  6909 V BluetoothSapReceiver: SapReceiver onReceive 
,09-07 13:17:34.375  6909  6909 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:17:34.375  6909  6909 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-07 13:17:34.375  6909  6909 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 13:17:34.376  6909  6909 V BluetoothFtpService: Ftp Service onDestroy
09-07 13:17:34.376  6909  6909 V BluetoothFtpService: Ftp Service closeService
09-07 13:17:34.380  6909  6909 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:34.380  6909  6909 V BluetoothSapService: state: 13
09-07 13:17:34.380  6909  6909 V BluetoothSapService: Stopping SAP server process
,09-07 13:17:34.381  6909  6909 V BluetoothSapService: Sap Service closeSapService in,
09-07 13:17:34.382  6909  6909 V BluetoothSapService: Close listen Socket : 
09-07 13:17:34.382  6909  6909 V BluetoothSapService: Close rfcomm Socket : 
09-07 13:17:34.382  6909  6909 V BluetoothSapService: Close sapd  Socket : 
09-07 13:17:34.385  6909  6909 V BluetoothSapService: Sap Service closeSapService out
09-07 13:17:34.385  6909  6909 V BluetoothSapService: Sap Service onDestroy
,09-07 13:17:34.385  6909  6909 V BluetoothSapService: Sap Service closeSapService in
09-07 13:17:34.385  6909  6909 V BluetoothSapService: Close listen Socket : 
09-07 13:17:34.385  6909  6909 V BluetoothSapService: Close rfcomm Socket : 
09-07 13:17:34.385  6909  6909 V BluetoothSapService: Close sapd  Socket : 
09-07 13:17:34.385  6909  6909 V BluetoothSapService: Sap Service closeSapService out
09-07 13:17:35.134  6909  7428 D bt_hci_bdroid: cleanup
,09-07 13:17:35.147  6909  7498 I bt_lpm  : LPM is already off!!!
09-07 13:17:35.147  6909  7528 I bt_userial_mct: exiting userial_read_thread
09-07 13:17:35.147  6909  7528 D bt_userial_mct: Leaving userial_evt_read_thread()
09-07 13:17:35.148  6909  7496 W bt-btif : ag scb idx 1 not allocated
09-07 13:17:35.148  6909  7496 E bt-btif : BTA AG is already disabled, ignoring ...
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 13:17:35.148  6909  7496 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:17:35.148  6909  7496 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 13:17:35.150  6909  7428 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 13:17:35.150  6909  7498 I bt_vendor: hw_epilog_process
09-07 13:17:35.151  6909  7428 D bt_hci_bdroid: cleanup Finalizing cleanup
09-07 13:17:35.151  6909  7428 D bt_userial_mct: userial_close
09-07 13:17:35.151  6909  7428 E bt_userial_mct: pthread_join() FAILED result:3
09-07 13:17:35.151  6909  7428 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-07 13:17:35.153  6909  7428 D bt_hci_bdroid: set_power 0
09-07 13:17:35.153  6909  7428 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 13:17:35.153  6909  7428 I bt_vendor: bluetooth satus is on
09-07 13:17:35.153  6909  7428 I bt_vendor: bt-vendor : resetting BT status
09-07 13:17:35.153  6909  7428 I bt_vendor: Starting hciattach daemon
09-07 13:17:35.153  6909  7428 I bt_vendor: try to set false
09-07 13:17:35.155  6909  7428 I bt_vendor: Starting hciattach daemon
09-07 13:17:35.155  6909  7428 I bt_vendor: try to set false
09-07 13:17:35.156  6909  7428 I bt_vendor: cleanup
,09-07 13:17:35.161  6909  7496 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-07 13:17:35.163  6909  7428 I GKI_LINUX: GKI_exit_task 0 done
09-07 13:17:35.163  6909  7428 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-07 13:17:35.165  6909  7424 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-07 13:17:35.171  6909  6909 D HeadsetService: Received stop request...Stopping profile...
,09-07 13:17:35.175  6909  6909 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 13:17:35.175  6909  6909 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 13:17:35.175  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:35.176  6909  7459 D HeadsetStateMachine: Exit Disconnected: -1
09-07 13:17:35.180  1034  1034 D BluetoothHeadset: Proxy object disconnected
09-07 13:17:35.180  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-07 13:17:35.181  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-07 13:17:35.181  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-07 13:17:35.181  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-07 13:17:35.182  6909  7424 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 13:17:35.183  6909  6909 D A2dpService: Received stop request...Stopping profile...
,09-07 13:17:35.186  6909  7481 D A2dpStateMachine: Exit Disconnected: -1
09-07 13:17:35.188  6909  6909 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-07 13:17:35.190  6909  6909 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-07 13:17:35.190  6909  6909 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 13:17:35.190  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:35.192  1034  1034 D BluetoothA2dp: Proxy object disconnected
09-07 13:17:35.192  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-07 13:17:35.193  6909  6909 D HidService: Received stop request...Stopping profile...
09-07 13:17:35.193  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:35.195  6909  6909 D HealthService: Received stop request...Stopping profile...
09-07 13:17:35.195  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
,09-07 13:17:35.200  6909  6909 D PanService: Received stop request...Stopping profile...
09-07 13:17:35.201  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:35.202  6909  6909 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 13:17:35.203  6909  6909 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 13:17:35.203  6909  6909 D BtGatt.GattService: stop()
09-07 13:17:35.203  6909  6909 D BtGatt.AdvertiseManager: advertise clients cleared
09-07 13:17:35.204  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:35.205  6909  6909 D HeadsetStateMachine: Unbinding service...
09-07 13:17:35.207  6909  6909 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 13:17:35.208  6909  6909 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 13:17:35.208  6909  6909 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 13:17:35.208  6909  6909 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 13:17:35.208  6909  6909 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 13:17:35.208  6909  6909 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 13:17:35.208  6909  6909 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-07 13:17:35.211  6909  6909 D BluetoothMapService: Received stop request...Stopping profile...
09-07 13:17:35.211  6909  6909 D BluetoothMapService: stop()
09-07 13:17:35.213  6909  6909 D BluetoothMapEmailAppObserver: deinitObservers()
09-07 13:17:35.213  6909  6909 D BluetoothMapEmailAppObserver: removeReceiver()
09-07 13:17:35.214  6909  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9dc5d3c
09-07 13:17:35.215  6909  6909 I BluetoothA2dpServiceJni: cleanupNative
09-07 13:17:35.215  6909  7482 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-07 13:17:35.216  6909  6909 I GKI_LINUX: GKI_exit_task 2 done
09-07 13:17:35.216  6909  6909 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 13:17:35.216  6909  6909 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 13:17:35.216  6909  6909 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 13:17:35.216  6909  6909 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 13:17:35.217  6909  6909 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-07 13:17:35.217  6909  6909 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 13:17:35.217  6909  6909 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 13:17:35.217  6909  6909 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 13:17:35.220  6909  6909 V BluetoothMapService: Handler(): got msg=4
09-07 13:17:35.220  6909  6909 D BluetoothMapService: MAP Service closeService in
09-07 13:17:35.220  6909  6909 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 13:17:35.220  6909  6909 V BluetoothMapService: MAP Service closeService out
,09-07 13:17:35.224  6909  7424 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-07 13:17:35.224  6909  7424 D BluetoothAdapterProperties: Setting state to 10
09-07 13:17:35.224  6909  7424 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 13:17:35.226  6909  6909 D BluetoothMapService: cleanup()
09-07 13:17:35.226  6909  6909 D BluetoothMapService: MAP Service closeService in
09-07 13:17:35.226  6909  6909 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 13:17:35.226  6909  6909 V BluetoothMapService: MAP Service closeService out
09-07 13:17:35.227  1034  1117 D BluetoothManagerService: Message: 60
09-07 13:17:35.227  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-07 13:17:35.227  1034  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-07 13:17:35.228  6909  7424 I BluetoothAdapterState: Entering OffState
09-07 13:17:35.228  6782  6802 D BluetoothMap: onBluetoothStateChange: up=false
09-07 13:17:35.228  6782  6802 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:17:35.229  6782  6802 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 13:17:35.232  1837  2708 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 13:17:35.235  6782  6802 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 13:17:35.236  6782  6802 D BluetoothPan: onBluetoothStateChange on: false
09-07 13:17:35.237  1837  2691 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:17:35.238  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:17:35.238  1034  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 13:17:35.239  6782  6802 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 13:17:35.239  1034  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:17:35.240  1034  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-07 13:17:35.240  1034  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-07 13:17:35.242  1034  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-07 13:17:35.242  1034  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-07 13:17:35.242  1034  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@153a685f mBinding = false
09-07 13:17:35.243  1034  1117 D BluetoothManagerService: Sending unbind request.
09-07 13:17:35.248  6909  7428 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-07 13:17:35.251  6909  6909 I GKI_LINUX: GKI_exit_task 1 done
09-07 13:17:35.251  6909  6909 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-07 13:17:35.251  6909  6909 I BluetoothServiceJni: cleanupNative: return from cleanup
09-07 13:17:35.252  6909  6909 I art     : --- WEIRD: removing null entry 248
09-07 13:17:35.252  6909  6909 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-07 13:17:35.252  6909  6909 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-07 13:17:35.253  6909  6909 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-07 13:17:35.254  1034  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-07 13:17:35.256  6909  6909 I art     : System.exit called, status: 0
09-07 13:17:35.256  6909  6909 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-07 13:17:35.276   312   312 V AudioFlinger: 6909 died, releasing its sessions
09-07 13:17:35.276   312   312 V AudioFlinger:  pid 1837 @ 0
09-07 13:17:35.276   312   312 V AudioFlinger:  pid 3443 @ 1
09-07 13:17:35.276   312   312 V AudioFlinger:  pid 3443 @ 2
,09-07 13:17:35.280  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-07 13:17:35.280  1927  2089 D LGBluetoothAPIService: Message: 101
09-07 13:17:35.280  1927  2089 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-07 13:17:35.280  1927  2089 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-07 13:17:35.280  1927  2089 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-07 13:17:35.285  6782  6782 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-07 13:17:35.323  1034  2018 I ActivityManager: Process com.android.bluetooth (pid 6909) has died
,09-07 13:17:35.324  1034  2018 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-07 13:17:35.324  1034  2018 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
09-07 13:17:35.333  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:35.333  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 13:17:35.334  1927  2089 D LGBluetoothAPIService: Message: 2
09-07 13:17:35.334  1927  2089 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-07 13:17:35.340  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:17:35.343  6782  6782 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-07 13:17:35.343  6782  6782 D LGBluetoothEventManager: [BTUI] clear device connection state
09-07 13:17:35.347  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:35.347  6782  6782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 13:17:35.350  1587  1587 D BluetoothAdapter: 952270950: getState() :  mService = null. Returning STATE_OFF
09-07 13:17:35.350  1587  1587 D BluetoothAdapter: 952270950: getState() :  mService = null. Returning STATE_OFF
09-07 13:17:35.406  1034  1944 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7630 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-07 13:17:35.408  6782  6782 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:17:35.606  1034  1633 I art     : Explicit concurrent mark sweep GC freed 94778(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.549ms total 152.399ms
,09-07 13:17:35.628  7630  7630 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-07 13:17:35.629  7630  7630 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 13:17:35.629  7630  7630 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-07 13:17:35.630  7630  7630 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 13:17:35.652  7630  7630 D BluetoothAdapterApp: Loading JNI Library
,09-07 13:17:35.689  7630  7630 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2218fda4 Instance Count = 1
,09-07 13:17:35.697  7630  7630 D BluetoothAdapterApp: onCreate
09-07 13:17:35.724  7630  7630 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-07 13:17:35.724  7630  7630 D ProfileConfigQcom: Adding HeadsetService
09-07 13:17:35.724  7630  7630 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-07 13:17:35.725  7630  7630 D ProfileConfigQcom: Adding A2dpService
09-07 13:17:35.725  7630  7630 D ProfileConfigQcom: [BTUI] HidService is supported
09-07 13:17:35.725  7630  7630 D ProfileConfigQcom: Adding HidService
09-07 13:17:35.725  7630  7630 D ProfileConfigQcom: [BTUI] HealthService is supported
09-07 13:17:35.726  7630  7630 D ProfileConfigQcom: Adding HealthService
09-07 13:17:35.726  7630  7630 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-07 13:17:35.727  7630  7630 D ProfileConfigQcom: [BTUI] PanService is supported
09-07 13:17:35.727  7630  7630 D ProfileConfigQcom: Adding PanService
09-07 13:17:35.727  7630  7630 D ProfileConfigQcom: [BTUI] GattService is supported
09-07 13:17:35.728  7630  7630 D ProfileConfigQcom: Adding GattService
09-07 13:17:35.728  7630  7630 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-07 13:17:35.728  7630  7630 D ProfileConfigQcom: Adding BluetoothMapService
09-07 13:17:35.729  7630  7630 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-07 13:17:35.730  7630  7630 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-07 13:17:35.731  7630  7630 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED,
09-07 13:17:35.731  7630  7630 V BluetoothPbapReceiver: ***********state = 10
09-07 13:17:35.733  7630  7630 V LGMDMManagerInternal: Create singleton instance
,09-07 13:17:35.829  7630  7630 D LGBluetoothAPIServer: [BTUI] onCreate()
09-07 13:17:35.829  7630  7630 D LGBluetoothAPIServer: [BTUI] onBind()
,09-07 13:17:35.838  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 13:17:35.840  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-07 13:17:35.841  1927  2089 D LGBluetoothAPIService: Message: 100
09-07 13:17:35.841  1927  2089 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-07 13:17:35.845  6782  6782 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-07 13:17:35.861  6782  6782 D BluetoothPermissionRequest: onReceive
,09-07 13:17:35.864  6782  6782 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 13:17:35.864  6782  6782 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-07 13:17:35.867  6782  6782 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 13:17:35.873  7630  7630 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-07 13:17:35.877  7630  7630 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:17:35.882  7630  7630 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 13:17:35.882  7630  7630 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 13:17:35.883  7630  7630 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 13:17:35.884  7630  7630 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:35.884  7630  7630 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-07 13:17:35.887  6878  6878 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-07 13:17:37.283  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:37.284  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:17:37.320  1587  1587 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-07 13:17:37.386  1034  1446 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 13:17:37.426  1034  1098 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7658 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-07 13:17:37.430  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-07 13:17:37.443  1034  1034 D administrator: Handling package changes for user 0
09-07 13:17:37.446  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-07 13:17:37.447  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-07 13:17:37.469  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-07 13:17:37.518  7658  7658 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-07 13:17:37.575  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-07 13:17:37.575  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-07 13:17:37.616  7658  7658 D LgDataFeature: LgDataFeature() Constructor: none
09-07 13:17:37.617  7658  7658 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 13:17:37.635  1034  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 13:17:37.643  1034  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-07 13:17:37.654  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-07 13:17:37.656  2484  2484 V GmsNetworkLocationProvi: DISABLE
09-07 13:17:37.687  1034  1097 D LocationProviderProxy: applying state to connected service
,09-07 13:17:37.692  2484  2484 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-07 13:17:37.759  7658  7704 I Babel   : MmsConfig: mnc/mcc: 0/0
09-07 13:17:37.759  7658  7704 I Babel   : MmsConfig.loadMmsSettings
09-07 13:17:37.765  7658  7704 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-07 13:17:37.766  7658  7704 I Babel   : MmsConfig.loadFromDatabase
,09-07 13:17:37.796  7658  7704 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-07 13:17:37.796  7658  7704 I Babel   : MmsConfig.loadFromResources
09-07 13:17:37.798  7658  7704 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-07 13:17:37.799  7658  7704 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-07 13:17:37.810  7658  7702 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 13:17:37.813  7658  7658 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:37.814  7658  7702 W AudioCapabilities: Unsupported mime audio/qcelp
09-07 13:17:37.820  7658  7702 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 13:17:37.833  7658  7702 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-07 13:17:37.835  7658  7702 W AudioCapabilities: Unsupported mime audio/qcelp
09-07 13:17:37.836  7658  7702 W AudioCapabilities: Unsupported mime audio/evrc
09-07 13:17:37.844  1800  7706 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-07 13:17:37.844  1800  7706 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-07 13:17:37.848  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
,09-07 13:17:37.854  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@f908d0e
09-07 13:17:37.854  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 13:17:37.854  7001  7001 D AppUp4:CustFacade: isPhone : true
09-07 13:17:37.855  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
09-07 13:17:37.855  7001  7001 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-07 13:17:37.859  1800  4768 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-07 13:17:37.867  7658  7702 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-07 13:17:37.872  7658  7702 W VideoCapabilities: Unsupported mime video/divx
09-07 13:17:37.879  7658  7702 W VideoCapabilities: Unsupported mime video/divx311
09-07 13:17:37.882  7658  7702 W VideoCapabilities: Unsupported mime video/divx4
09-07 13:17:37.890  1034  1057 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7709 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-07 13:17:37.895  1034  1890 I ActivityManager: Killing 6578:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-07 13:17:37.895  7658  7702 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-07 13:17:37.911  6857  6857 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-07 13:17:37.913  6857  6857 W System.err: android.os.DeadObjectException
09-07 13:17:37.913  6857  6857 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 13:17:37.913  6857  6857 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 13:17:37.913  6857  6857 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-07 13:17:37.913  6857  6857 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-07 13:17:37.913  6857  6857 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-07 13:17:37.913  6857  6857 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-07 13:17:37.913  6857  6857 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 13:17:37.913  6857  6857 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 13:17:37.913  6857  6857 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 13:17:37.913  6857  6857 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 13:17:37.913  6857  6857 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:17:37.913  6857  6857 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:17:37.913  6857  6857 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 13:17:37.913  6857  6857 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 13:17:37.914  6857  6857 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-07 13:17:37.914  6857  6857 W System.err: android.os.DeadObjectException
09-07 13:17:37.914  6857  6857 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 13:17:37.914  6857  6857 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 13:17:37.914  6857  6857 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-07 13:17:37.914  6857  6857 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-07 13:17:37.914  6857  6857 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-07 13:17:37.914  6857  6857 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-07 13:17:37.914  6857  6857 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 13:17:37.914  6857  6857 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 13:17:37.914  6857  6857 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 13:17:37.914  6857  6857 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 13:17:37.914  6857  6857 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:17:37.915  6857  6857 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:17:37.915  6857  6857 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 13:17:37.915  6857  6857 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 13:17:37.915  6857  6857 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-07 13:17:37.915  6857  6857 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-07 13:17:37.924  7658  7702 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-07 13:17:37.930  7658  7702 W AudioCapabilities: Unsupported mime audio/eac3
09-07 13:17:37.930  7658  7702 W AudioCapabilities: Unsupported mime audio/ac3
09-07 13:17:37.931  7658  7702 W AudioCapabilities: Unsupported mime audio/g726
09-07 13:17:37.932  7658  7702 W AudioCapabilities: Unsupported mime audio/wma-voice
09-07 13:17:37.932  7658  7702 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-07 13:17:37.934  7658  7702 W AudioCapabilities: Unsupported mime audio/adpcm
,09-07 13:17:37.936  7658  7702 W VideoCapabilities: Unsupported mime video/theora
09-07 13:17:37.937  7658  7702 W VideoCapabilities: Unsupported mime video/mjpg
09-07 13:17:38.159  1034  2015 W libprocessgroup: failed to open /acct/uid_1000/pid_6578/cgroup.procs: No such file or directory
,09-07 13:17:38.159  1034  2015 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-07 13:17:38.178  6857  6857 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-07 13:17:38.178  6857  6857 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-07 13:17:38.199  7709  7709 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 13:17:38.199  7709  7709 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 13:17:38.200  7709  7709 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-07 13:17:38.201  7709  7709 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-07 13:17:38.201  7709  7709 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 13:17:38.240  1034  1529 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-07 13:17:38.256  1034  1945 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7729 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 13:17:38.258  6857  6857 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-07 13:17:38.308  7709  7709 I SystemConfig: BUILD Country: EU
09-07 13:17:38.309  7709  7709 I SystemConfig: BUILD Operator: OPEN
,09-07 13:17:38.326  7729  7729 D UEI.SmartControl: Quickset Services start...
,09-07 13:17:38.328  7729  7729 I UEI.SmartControl: Manufacture = LGE
09-07 13:17:38.328  7729  7729 D UEI.SmartControl: Id = LGNevo
09-07 13:17:38.330  7729  7729 D UEI.SmartControl: File observer start...
09-07 13:17:38.331  7729  7729 E UEI.SmartControl: IR Port is disabled: false
09-07 13:17:38.331  7729  7729 D UEI.SmartControl: Starting file observer...
09-07 13:17:38.331  7729  7729 D UEI.SmartControl: Extracting JNI libs...
09-07 13:17:38.331  7729  7729 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-07 13:17:38.374  1034  1890 I ActivityManager: Killing 6857:com.lge.qremote/u0a112 (adj 15): empty #17
,09-07 13:17:38.435  7729  7729 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-07 13:17:38.436  7729  7729 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-07 13:17:38.436  7729  7729 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-07 13:17:38.466  1034  2037 W libprocessgroup: failed to open /acct/uid_10112/pid_6857/cgroup.procs: No such file or directory
,09-07 13:17:38.482  7729  7729 I UEI.SmartControl: --- Selecting new region: 6
09-07 13:17:38.486  7729  7729 I UEI.SmartControl: Model = LG-D855
,09-07 13:17:38.487  7729  7729 D UEI.SmartControl: QS Service created
09-07 13:17:38.485  7709  7748 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-07 13:17:38.488  7709  7748 I SystemConfig: existFile = false
09-07 13:17:38.488  7709  7748 I SystemConfig: canReadFile = false
09-07 13:17:38.488  7709  7748 I SystemConfig: systemFeature RCS result false
09-07 13:17:38.488  7709  7748 D SystemConfig: refreshRcsSupport() :false
09-07 13:17:38.509  1034  1836 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7750 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-07 13:17:38.529  7729  7729 I UEI.SmartControl: Service initServices...
09-07 13:17:38.532  7729  7729 D UEI.SmartControl: QS start get config
,09-07 13:17:38.567  7729  7729 D UEI.SmartControl: Loading JNI Libs...
,09-07 13:17:38.575  7750  7750 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:17:38.575  7750  7750 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 13:17:38.576  7750  7750 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-07 13:17:38.576  7750  7750 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 13:17:38.658  7750  7750 I AppConfig: Total System Memory = 2995761152
,09-07 13:17:38.667  7750  7750 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-07 13:17:38.755  1034  2015 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7769 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 13:17:38.756  1034  2015 I ActivityManager: Killing 7030:com.lge.email/u0a23 (adj 15): empty #17
,09-07 13:17:38.874  1034  2037 W libprocessgroup: failed to open /acct/uid_10023/pid_7030/cgroup.procs: No such file or directory
,09-07 13:17:38.979  7729  7729 I UEI.SmartControl: Supports setup maps: true
,09-07 13:17:38.991  7729  7729 D UEI.SmartControl: QS start statue = true Error code = 0
09-07 13:17:38.992  7729  7729 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-07 13:17:38.992  7729  7729 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-07 13:17:38.995  7729  7729 I UEI.SmartControl: ### init IR Blaster...
,09-07 13:17:39.004  7729  7729 D serial_port: Configuring serial port
09-07 13:17:39.014  7729  7729 E UEI.SmartControl: UEIBLaster setting for 616
09-07 13:17:39.014  7729  7729 I UEI.SmartControl: Setting serial record hearder size = 2
09-07 13:17:39.015  7729  7729 I UEI.SmartControl: configuring settings for MAXQ616
09-07 13:17:39.015  7729  7729 I UEI.SmartControl: Get version...
,09-07 13:17:39.031  7729  7790 D UEI.SmartControl: serial port data available: 21
,09-07 13:17:39.057  7769  7769 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-07 13:17:39.059  7729  7729 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-07 13:17:39.059  7729  7729 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-07 13:17:39.059  7729  7729 I UEI.SmartControl: QS saving settings...
09-07 13:17:39.060  7729  7729 D UEI.SmartControl: IR Blaster version: 25672567
09-07 13:17:39.076  7729  7790 D UEI.SmartControl: serial port data available: 4
,09-07 13:17:39.116  7729  7805 I UEI.SmartControl: Device manager: loading config....
,09-07 13:17:39.116  7729  7805 D UEI.SmartControl: ----------- loading internal config...
09-07 13:17:39.121  7729  7729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-07 13:17:39.124  7729  7729 E UEI.SmartControl: Services init done
09-07 13:17:39.124  7729  7729 D UEI.SmartControl: QS Service init finished
09-07 13:17:39.125  7729  7729 D UEI.SmartControl: QS Service version name: 2.1.91
09-07 13:17:39.125  7729  7729 D UEI.SmartControl: QS Service version code: 201091
09-07 13:17:39.126  7729  7729 D UEI.SmartControl: Service requested: Control
09-07 13:17:39.131  7729  7805 E UEI.SmartControl: Loading SETTINGS...
09-07 13:17:39.131  7729  7729 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-07 13:17:39.133  7729  7729 D UEI.SmartControl: Service.onUnbind: IControl
09-07 13:17:39.135  7729  7729 D UEI.SmartControl: Service.onDestroy
09-07 13:17:39.135  7729  7729 D UEI.SmartControl: Lock is in USE false
09-07 13:17:39.135  7729  7729 D UEI.SmartControl: unbind internal service
,09-07 13:17:39.137  7729  7729 D serial_port: close(fd = 25)
09-07 13:17:39.140  7769  7769 D LgDataFeature: LgDataFeature() Constructor: none
09-07 13:17:39.140  7769  7769 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 13:17:39.140  7729  7729 I UEI.SmartControl: Serial port is closed.
09-07 13:17:39.140  7729  7729 I UEI.SmartControl: Serial port is closed.
09-07 13:17:39.140  7729  7729 D UEI.SmartControl: Blaster closed
09-07 13:17:39.141  7729  7729 D UEI.SmartControl: Shut down QS...
09-07 13:17:39.141  7729  7729 D UEI.SmartControl: Stopping QS lib
09-07 13:17:39.141  7729  7729 D UEI.SmartControl: QS lib stop result = true
09-07 13:17:39.141  7729  7729 D UEI.SmartControl: Stopped QS lib
09-07 13:17:39.141  7729  7729 D UEI.SmartControl: Stopped file observer...
09-07 13:17:39.142  7729  7729 D UEI.SmartControl: QS shutdown complete
09-07 13:17:39.143  7729  7729 D UEI.SmartControl: QS Service created
09-07 13:17:39.150  7729  7805 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-07 13:17:39.153  7729  7804 I UEI.SmartControl: Notify AllClients services are ready: 11
09-07 13:17:39.153  7729  7804 D UEI.SmartControl: -----service ready thread exits
,09-07 13:17:39.157  7729  7729 I UEI.SmartControl: Service initServices...
09-07 13:17:39.157  7729  7729 D UEI.SmartControl: QS start get config
,09-07 13:17:39.194  7769  7769 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-07 13:17:39.214  7769  7769 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-07 13:17:39.215  7769  7769 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 13:17:39.237  7769  7769 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 13:17:39.237  7769  7769 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-07 13:17:39.259  1034  1872 I ActivityManager: Killing 6929:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-07 13:17:39.351  1034  1633 W libprocessgroup: failed to open /acct/uid_10026/pid_6929/cgroup.procs: No such file or directory
,09-07 13:17:39.358  3525  3580 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-07 13:17:39.361  3525  3580 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@14703d2 on behalf of 7769
09-07 13:17:39.369  4612  7812 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-07 13:17:39.393  1034  1998 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7813 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-07 13:17:39.414  7769  7769 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-07 13:17:39.433  7769  7769 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-07 13:17:39.471  7813  7813 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-07 13:17:39.485  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-07 13:17:39.486  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-07 13:17:39.486  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-07 13:17:39.486  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-07 13:17:39.486  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-07 13:17:39.486  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-07 13:17:39.508  1034  1058 I ActivityManager: Killing 6356:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-07 13:17:39.535  7729  7729 I UEI.SmartControl: Supports setup maps: true
,09-07 13:17:39.540  7729  7729 D UEI.SmartControl: QS start statue = true Error code = 0
09-07 13:17:39.540  7729  7729 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-07 13:17:39.540  7729  7729 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-07 13:17:39.540  7729  7729 I UEI.SmartControl: ### init IR Blaster...
09-07 13:17:39.545  7729  7729 D serial_port: Configuring serial port
09-07 13:17:39.546  7729  7729 E UEI.SmartControl: UEIBLaster setting for 616
09-07 13:17:39.546  7729  7729 I UEI.SmartControl: Setting serial record hearder size = 2
09-07 13:17:39.546  7729  7729 I UEI.SmartControl: configuring settings for MAXQ616
,09-07 13:17:39.546  7729  7729 I UEI.SmartControl: Get version...
09-07 13:17:39.564  7729  7840 D UEI.SmartControl: serial port data available: 21
,09-07 13:17:39.590  7729  7729 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-07 13:17:39.590  7729  7729 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-07 13:17:39.590  7729  7729 I UEI.SmartControl: QS saving settings...
09-07 13:17:39.592  7729  7729 D UEI.SmartControl: IR Blaster version: 25672567
,09-07 13:17:39.600  1034  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_6356/cgroup.procs: No such file or directory
09-07 13:17:39.613  7729  7840 D UEI.SmartControl: serial port data available: 4
,09-07 13:17:39.646  7729  7843 I UEI.SmartControl: Device manager: loading config....
09-07 13:17:39.646  7729  7843 D UEI.SmartControl: ----------- loading internal config...
,09-07 13:17:39.647  7729  7729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-07 13:17:39.651  7729  7729 E UEI.SmartControl: Services init done
09-07 13:17:39.651  7729  7729 D UEI.SmartControl: QS Service init finished
09-07 13:17:39.652  7729  7729 D UEI.SmartControl: QS Service version name: 2.1.91
09-07 13:17:39.652  7729  7729 D UEI.SmartControl: QS Service version code: 201091
09-07 13:17:39.653  7729  7729 D UEI.SmartControl: Service requested: Control
09-07 13:17:39.659  7729  7843 E UEI.SmartControl: Loading SETTINGS...
09-07 13:17:39.662  7729  7729 D UEI.SmartControl: Request IControl service: devices are loaded...
09-07 13:17:39.664  1034  1559 I ActivityManager: Killing 7075:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-07 13:17:39.670  7729  7843 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-07 13:17:39.686  7729  7842 I UEI.SmartControl: Notify AllClients services are ready: 0
09-07 13:17:39.686  7729  7842 D UEI.SmartControl: -----service ready thread exits
,09-07 13:17:39.797  1034  2018 W libprocessgroup: failed to open /acct/uid_10046/pid_7075/cgroup.procs: No such file or directory
09-07 13:17:39.799  7729  7729 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@274c6c1a that was originally bound here
09-07 13:17:39.799  7729  7729 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@274c6c1a that was originally bound here
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 13:17:39.799  7729  7729 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-07 13:17:39.807  7729  7729 D UEI.SmartControl: Internal service binding...
09-07 13:17:40.034  1034  1890 V SIM_STK : Menu title from STK is T-Mobile
,09-07 13:17:40.057  4612  7812 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 688 ms] updated apps [took 688 ms] 
,09-07 13:17:40.135  7729  7807 D UEI.SmartControl: Internal timer expired: 2
,09-07 13:17:40.290  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 13:17:40.290  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@569aa70 added. We now have 6 listener(s)
09-07 13:17:40.290  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:17:40.296  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:40.296  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28be1e9 added. We now have 7 listener(s)
09-07 13:17:40.296  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:40.297  6660  6739 I System.out: IsBluetoothEnabled
09-07 13:17:40.299  1034  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:40.299  1034  1980 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-07 13:17:40.299  1034  1117 D BluetoothManagerService: Message: 2
09-07 13:17:40.302  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:40.303  1034  1633 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:40.303  1034  1633 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-07 13:17:40.328  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 13:17:40.328  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 13:17:40.329  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,09-07 13:17:40.332  1034  1117 D BluetoothManagerService: Message: 1
09-07 13:17:40.332  1034  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-07 13:17:40.360  1034  1117 D BluetoothManagerService: Message: 20
09-07 13:17:40.360  1034  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@640df56:true
,09-07 13:17:40.363  7630  7630 D BluetoothAdapterState: make
09-07 13:17:40.368  7630  7630 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-07 13:17:40.368  7630  7630 I bluedroid-qcom: init
09-07 13:17:40.369  7630  7857 I BluetoothAdapterState: Entering OffState
09-07 13:17:40.369  7630  7630 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 13:17:40.370  7630  7630 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 13:17:40.370  7630  7630 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 13:17:40.370  7630  7630 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 13:17:40.370  7630  7630 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-07 13:17:40.372  7630  7630 I bluedroid-qcom: get_profile_interface socket
09-07 13:17:40.372  7630  7630 I bluedroid-qcom: get_profile_interface map_client
,09-07 13:17:40.375  7630  7861 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-07 13:17:40.364  7860  7860 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:40.380  7630  7861 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-07 13:17:40.364  7860  7860 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:40.389  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-07 13:17:40.389  7860  7860 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-07 13:17:40.389  7860  7860 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-07 13:17:40.394  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 13:17:40.394  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-07 13:17:40.396  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-07 13:17:40.396  1034  1117 D BluetoothManagerService: Message: 40
09-07 13:17:40.396  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-07 13:17:40.397  7630  7645 I bluedroid-qcom: config_hci_snoop_log
09-07 13:17:40.399  1034  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-07 13:17:40.399  1034  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-07 13:17:40.400  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-07 13:17:40.402  7630  7861 D BluetoothAdapterProperties: Name is: G3
,09-07 13:17:40.408  7630  7857 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-07 13:17:40.409  7630  7857 D BluetoothAdapterProperties: Setting state to 11
09-07 13:17:40.409  7630  7857 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 13:17:40.411  7630  7857 I LGBluetoothServiceJni: classInitNative: succeeds
09-07 13:17:40.413  1034  1117 D BluetoothManagerService: Message: 60
09-07 13:17:40.413  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-07 13:17:40.413  1034  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-07 13:17:40.417  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:17:40.420  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 13:17:40.421  7860  7860 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-07 13:17:40.421  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-07 13:17:40.425  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:40.429  6782  6782 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-07 13:17:40.437  7630  7630 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 13:17:40.438  7630  7630 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:40.438  7630  7630 V BluetoothPbapReceiver: ***********state = 11
09-07 13:17:40.442  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 13:17:40.467  7630  7857 D BluetoothBondStateMachine: make
,09-07 13:17:40.473  7630  7857 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
,09-07 13:17:40.473  7630  7857 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
,09-07 13:17:40.474  7630  7857 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
09-07 13:17:40.474  7630  7857 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-07 13:17:40.474  6782  6782 D BluetoothPermissionRequest: onReceive
09-07 13:17:40.474  7630  7857 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-07 13:17:40.476  7630  7872 I BluetoothBondStateMachine: StableState(): Entering Off State
09-07 13:17:40.478  6782  6782 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 13:17:40.478  7630  7857 E BluetoothAdapterService: File transfer profiles supported!!
09-07 13:17:40.490  7630  7630 D HeadsetService: Received start request. Starting profile...
09-07 13:17:40.490  7630  7630 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 13:17:40.490  7630  7630 D LGBluetoothHfpAdapter: Version 1.6
,09-07 13:17:40.495  7630  7630 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 13:17:40.496  7630  7630 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 13:17:40.497  7630  7630 D HeadsetStateMachine: make
09-07 13:17:40.497  7630  7857 E BluetoothAdapterService: File transfer profiles supported!!
09-07 13:17:40.506  7630  7857 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 13:17:40.514  7630  7857 E BluetoothAdapterService: File transfer profiles supported!!
09-07 13:17:40.521  7630  7857 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 13:17:40.528  7630  7857 E BluetoothAdapterService: File transfer profiles supported!!
09-07 13:17:40.534  7630  7857 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 13:17:40.540  7630  7630 D LgDataFeature: LgDataFeature() Constructor: none
09-07 13:17:40.541  7630  7630 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 13:17:40.547  7630  7630 D HeadsetStateMachine: max_hf_connections = 1
09-07 13:17:40.547  7630  7630 I bluedroid-qcom: get_profile_interface handsfree
09-07 13:17:40.550  7630  7630 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,09-07 13:17:40.550   312  1366 V AudioPolicyService: registerClient() client 0xb14276a0, uid 1002
09-07 13:17:40.551   312  1367 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-07 13:17:40.551   312  1367 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 13:17:40.551   312  1367 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 13:17:40.551  7630  7630 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-07 13:17:40.551   312  1365 V AudioFlinger: registerClient() client 0xb1433040, pid 7630
09-07 13:17:40.552   312  1360 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 13:17:40.552   312  1360 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 13:17:40.552  1587  1605 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 13:17:40.552  3443  3459 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 13:17:40.552  3443  3459 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 13:17:40.552  1587  1605 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 13:17:40.552  1837  1853 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,09-07 13:17:40.552  1837  1853 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 13:17:40.553  7630  7645 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 13:17:40.553  7630  7645 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-07 13:17:40.553  1034  1998 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 13:17:40.553   312  1361 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:40.553  1034  1998 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 13:17:40.553   312  1361 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 13:17:40.554  1034  2037 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:40.554  1034  2037 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 13:17:40.554  1587  1603 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:40.554  1587  1603 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 13:17:40.554  7630  7646 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:40.554  7630  7646 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-07 13:17:40.554  7630  7630 V ToneGenerator: Create Track: 0xb4928a80
09-07 13:17:40.554  7630  7630 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-07 13:17:40.554  7630  7630 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-07 13:17:40.555  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:40.555  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 13:17:40.555  3443  3458 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 13:17:40.555  3443  3458 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 13:17:40.555   312  1367 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 13:17:40.555   312  1367 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-07 13:17:40.555   312  1367 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 13:17:40.555   312  1367 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 13:17:40.555   312  1366 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 13:17:40.556   312  1365 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 13:17:40.556   312  1365 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-07 13:17:40.556   312  1365 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,09-07 13:17:40.556   312  1365 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 13:17:40.556  7630  7630 V AudioSystem: getLatency() output 2, latency 50
09-07 13:17:40.556  7630  7630 V AudioSystem: getFrameCount() output 2, frameCount 960
09-07 13:17:40.556  7630  7630 V AudioTrack: createTrack_l() output 2 afLatency 50
09-07 13:17:40.556   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 13:17:40.556   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 13:17:40.556   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 13:17:40.556   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 13:17:40.556   312   312 V AudioFlinger: createTrack() lSessionId: 23
,09-07 13:17:40.558  7630  7630 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-07 13:17:40.558   312  1367 V AudioFlinger: acquiring 23 from 7630, for 7630
09-07 13:17:40.558   312  1367 V AudioFlinger:  added new entry for 23
09-07 13:17:40.558  7630  7630 V ToneGenerator: ToneGenerator INIT OK, time: 206715
09-07 13:17:40.558  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
09-07 13:17:40.559  7630  7880 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-07 13:17:40.560  7630  7880 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 13:17:40.560  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
09-07 13:17:40.560  7630  7880 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 13:17:40.561  7630  7880 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-07 13:17:40.561   312  1366 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7630
09-07 13:17:40.562   312  1366 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
,09-07 13:17:40.562   312  1366 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-07 13:17:40.562   312  1366 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-07 13:17:40.562   312  1366 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 13:17:40.562   312  1366 V voice   : voice_set_parameters: exit with code(0)
09-07 13:17:40.562   312  1366 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-07 13:17:40.562   312  1366 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-07 13:17:40.562   312  1366 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 13:17:40.562   312  1366 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 13:17:40.562   312  1366 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-07 13:17:40.562   312  1366 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-07 13:17:40.563  7630  7880 V ToneGenerator: ToneGenerator destructor
09-07 13:17:40.563  7630  7880 V ToneGenerator: stopTone
09-07 13:17:40.563  7630  7880 V ToneGenerator: Delete Track: 0xb4928a80
,09-07 13:17:40.563  7630  7880 V AudioTrack: ~AudioTrack, releasing session id from 7630 on behalf of 7630
09-07 13:17:40.564   312  1365 V AudioFlinger: releasing 23 from 7630 for 7630
09-07 13:17:40.564   312  1365 V AudioFlinger:  decremented refcount to 0
09-07 13:17:40.564   312  1365 V AudioFlinger: purging stale effects
09-07 13:17:40.564   312  1365 V AudioPolicyService: AudioCommandThread() adding release output 2
09-07 13:17:40.564   312  1365 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-07 13:17:40.564   312  1272 V AudioPolicyService: AudioCommandThread() waking up
09-07 13:17:40.564   312  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
09-07 13:17:40.564   312  1272 V AudioPolicyManager: releaseOutput() 2
09-07 13:17:40.564   312  1272 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 13:17:40.564   312  1365 V AudioFlinger: PlaybackThread::Track destructor
09-07 13:17:40.564   312  1365 V AudioFlinger: removeClient_l() pid 7630, calling pid 312
,09-07 13:17:40.565  7630  7630 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:40.566  7630  7857 V LGMDMManager: Create singleton instance
09-07 13:17:40.570  7630  7630 D A2dpService: Received start request. Starting profile...
09-07 13:17:40.571  7630  7857 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-07 13:17:40.571  7630  7630 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 13:17:40.574  7630  7630 V Avrcp   : make
09-07 13:17:40.574  7630  7630 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-07 13:17:40.574  7630  7630 I bluedroid-qcom: get_profile_interface avrcp
09-07 13:17:40.585  7630  7630 V AudioManager: registerRemoteController: size of Media player list: 0
,09-07 13:17:40.586  7630  7630 E AudioManager: No RCC entry present to update
,09-07 13:17:40.587  7630  7630 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 13:17:40.591  7630  7630 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-07 13:17:40.592  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-07 13:17:40.592  7630  7630 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-07 13:17:40.598  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-07 13:17:40.706  1034  1944 V SIM_STK : Menu title from STK is T-Mobile
09-07 13:17:40.706  1034  1944 V SIM_STK : Menu title from STK is T-Mobile
,09-07 13:17:40.780  1034  2037 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-07 13:17:40.789  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-07 13:17:40.793  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-07 13:17:40.794  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,09-07 13:17:40.794  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 13:17:40.794  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 13:17:40.794  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,09-07 13:17:40.794  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 13:17:40.794  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 13:17:40.794  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-07 13:17:40.794  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 13:17:40.794  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 13:17:40.795  7630  7630 I BluetoothA2dpServiceJni: classInitNative
09-07 13:17:40.795  7630  7630 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 13:17:40.795  7630  7630 D A2dpStateMachine: make
09-07 13:17:40.798  7630  7630 I bluedroid-qcom: get_profile_interface a2dp
09-07 13:17:40.798  7630  7888 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-07 13:17:40.801  7630  7630 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-07 13:17:40.801  7630  7630 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-07 13:17:40.802  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
09-07 13:17:40.803  7630  7630 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 13:17:40.803  7630  7887 D A2dpStateMachine: Enter Disconnected: -2
09-07 13:17:40.804  7630  7630 D HidService: Received start request. Starting profile...
09-07 13:17:40.804  7630  7630 I bluedroid-qcom: get_profile_interface hidhost
09-07 13:17:40.804  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
09-07 13:17:40.804  7630  7630 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 13:17:40.806  7630  7630 D HealthService: Received start request. Starting profile...
09-07 13:17:40.809  7630  7630 I bluedroid-qcom: get_profile_interface health
09-07 13:17:40.809  7630  7630 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-07 13:17:40.809  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
09-07 13:17:40.810  7630  7630 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 13:17:40.811  7630  7630 D PanService: Received start request. Starting profile...
09-07 13:17:40.811  7630  7630 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 13:17:40.811  7630  7630 I bluedroid-qcom: get_profile_interface pan
,09-07 13:17:40.818  7630  7630 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-07 13:17:40.819  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
09-07 13:17:40.820  7630  7630 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-07 13:17:40.823  7630  7630 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 13:17:40.824  7630  7630 D BtGatt.GattService: Received start request. Starting profile...
09-07 13:17:40.824  7630  7630 D BtGatt.GattService: start()
09-07 13:17:40.824  7630  7630 I bluedroid-qcom: get_profile_interface gatt
09-07 13:17:40.824  7630  7630 D BtGatt.AdvertiseManager: advertise manager created
09-07 13:17:40.833  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
,09-07 13:17:40.834  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
09-07 13:17:40.834  7630  7630 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-07 13:17:40.835  7630  7630 V BluetoothMapService: BluetoothMapBinder()
09-07 13:17:40.835  7630  7630 D BluetoothMapService: Received start request. Starting profile...
09-07 13:17:40.835  7630  7630 D BluetoothMapService: start()
09-07 13:17:40.837  7630  7630 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-07 13:17:40.837  7630  7630 D BluetoothMapEmailAppObserver: createReceiver()
09-07 13:17:40.838  7630  7630 D BluetoothMapEmailAppObserver: initObservers()
,09-07 13:17:40.838  7630  7630 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-07 13:17:40.843  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
09-07 13:17:40.843  7630  7630 D HeadsetStateMachine: Proxy object connected
09-07 13:17:40.844  7630  7630 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-07 13:17:40.844  7630  7630 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-07 13:17:40.852  7630  7630 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 13:17:40.854  7630  7630 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 13:17:40.854  7630  7880 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 13:17:40.854  7630  7630 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 13:17:40.854  7630  7630 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 13:17:40.854  7630  7630 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:40.855  7630  7630 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-07 13:17:40.855  7630  7880 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 13:17:40.859  7630  7880 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-07 13:17:40.868  7630  7630 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 13:17:40.876  7630  7630 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-07 13:17:40.882  7630  7630 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 13:17:40.886  7630  7630 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 13:17:40.887  7630  7630 V PanService: [BTUI] SIM Extra State :ABSENT
,09-07 13:17:40.891  7630  7630 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-07 13:17:40.891  7630  7630 V BluetoothMapService: Handler(): got msg=1
09-07 13:17:40.892  7630  7857 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-07 13:17:40.892  7630  7857 I bluedroid-qcom: enable
,09-07 13:17:40.893  7630  7857 I bt_hci_bdroid: init
09-07 13:17:40.896  7630  7857 I bt_vendor: bt-vendor : init
09-07 13:17:40.896  7630  7857 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 13:17:40.896  7630  7857 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 13:17:40.896  7630  7857 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-07 13:17:40.896  7630  7857 D bt_userial_mct: userial_init
09-07 13:17:40.898  7630  7857 D bt_hci_bdroid: set_power 1
09-07 13:17:40.898  7630  7857 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-07 13:17:40.898  7630  7857 I bt_vendor: Starting hciattach daemon
09-07 13:17:40.898  7630  7898 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-07 13:17:40.898  7630  7857 I bt_vendor: try to set true
09-07 13:17:40.898  7630  7898 I bt-btu  : btu_task pending for preload complete event
09-07 13:17:40.884  7901  7901 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:40.894  7901  7901 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 13:17:40.938  7902  7902 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-07 13:17:41.063  7908  7908 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-07 13:17:41.078  7909  7909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 13:17:41.121  7911  7911 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 13:17:41.139  7912  7912 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-07 13:17:41.165  7913  7913 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 13:17:41.178  7917  7917 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-07 13:17:41.198  7919  7919 I libmdmdetect: ESOC framework not supported
09-07 13:17:41.199  7919  7919 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-07 13:17:41.209  7919  7919 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-07 13:17:41.209  7919  7919 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-07 13:17:41.209  7919  7919 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-07 13:17:41.209  7919  7919 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-07 13:17:41.209  7919  7919 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-07 13:17:41.209  7919  7919 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-07 13:17:41.209  7919  7919 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-07 13:17:41.249  7919  7920 E QC-QMI  : qmi_client [7919] 15: failed to locate client data
09-07 13:17:41.255   473   473 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-07 13:17:41.255   473   473 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-07 13:17:41.285  7921  7921 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-07 13:17:41.312  7922  7922 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 13:17:41.353  7630  7857 I bt_vendor: bluetooth satus is on
09-07 13:17:41.353  7630  7857 D bt_hci_bdroid: preload
09-07 13:17:41.356  7630  7900 D bt_userial_mct: userial_open(port:0)
09-07 13:17:41.356  7630  7900 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-07 13:17:41.359  7630  7900 I bt_vendor: Done intiailizing UART
09-07 13:17:41.360  7630  7900 I bt_vendor: Done intiailizing UART
09-07 13:17:41.360  7630  7900 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-07 13:17:41.360  7630  7900 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-07 13:17:41.360  7630  7898 I bt-btu  : btu_task received preload complete event
09-07 13:17:41.361  7630  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-07 13:17:41.361  7630  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-07 13:17:41.363  7630  7924 D bt_userial_mct: Entering userial_read_thread()
09-07 13:17:41.363  7630  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 13:17:41.367  7630  7898 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 13:17:41.368  7630  7898 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 13:17:41.368  7630  7898 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 13:17:41.368  7630  7898 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 13:17:41.368  7630  7898 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 13:17:41.456  7630  7898 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-07 13:17:41.456  7630  7898 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c6061 
09-07 13:17:41.456  7630  7898 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c6061 
,09-07 13:17:41.488  7630  7861 E bt-btif : Calling BTA_HhEnable
09-07 13:17:41.488  7630  7861 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-07 13:17:41.489  7630  7861 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-07 13:17:41.493  7630  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-07 13:17:41.493  7630  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-07 13:17:41.493  7630  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-07 13:17:41.493  7630  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-07 13:17:41.493  7630  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-07 13:17:41.495  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 13:17:41.495  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
09-07 13:17:41.495  7630  7861 D BluetoothAdapterProperties: Name is: G3
09-07 13:17:41.498  7630  7861 D BluetoothAdapterProperties: Scan Mode:20
09-07 13:17:41.498  7630  7861 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 13:17:41.498  7630  7861 D bt_hci_bdroid: postload
09-07 13:17:41.498  7630  7900 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 13:17:41.499  7630  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-07 13:17:41.500  7630  7861 D bte_conf: Device ID record 1 : primary
09-07 13:17:41.500  7630  7861 D bte_conf:   vendorId            = 00c4
09-07 13:17:41.500  7630  7861 D bte_conf:   vendorIdSource      = 0001
09-07 13:17:41.500  7630  7861 D bte_conf:   product             = 13a1
09-07 13:17:41.500  7630  7861 D bte_conf:   version             = 1000
09-07 13:17:41.500  7630  7861 D bte_conf:   clientExecutableURL = 
09-07 13:17:41.500  7630  7861 D bte_conf:   serviceDescription  = 
09-07 13:17:41.500  7630  7861 D bte_conf:   documentationURL    = 
09-07 13:17:41.500  7630  7861 D bte_conf: bte_load_did_conf no section named DID2.
09-07 13:17:41.501  7630  7900 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 13:17:41.502  7630  7900 D bt_hci_bdroid: Used up Tx Cmd credits
,09-07 13:17:41.508  7630  7898 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 13:17:41.508  7630  7898 W bt-smp  : Plain text(LSB ~ MSB) = 6d 16 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 13:17:41.508  7630  7898 W bt-smp  : Encrypted text(LSB ~ MSB) = 16 e6 22 70 47 d6 4d ab 42 3b b1 c2 37 79 18 4a 
09-07 13:17:41.509  7630  7900 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 13:17:41.509  7630  7898 W bt-btm  : Stopping oneshot timer
09-07 13:17:41.509  7630  7857 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 13:17:41.510  7630  7857 D BluetoothAdapterProperties: ScanMode =  20
09-07 13:17:41.510  7630  7857 D BluetoothAdapterProperties: State =  11
09-07 13:17:41.510  7630  7857 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-07 13:17:41.510  7630  7857 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-07 13:17:41.510  7630  7857 D BluetoothAdapterProperties: Setting state to 12
09-07 13:17:41.510  7630  7857 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 13:17:41.511  7630  7861 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 13:17:41.511  7630  7924 E bt_mct  : hci lib postload completed
09-07 13:17:41.504  7929  7929 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:41.504  7929  7929 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:41.523  1034  1117 D BluetoothManagerService: Message: 60
09-07 13:17:41.523  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-07 13:17:41.523  1034  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-07 13:17:41.528  7630  7861 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 13:17:41.550  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:41.550  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:41.550  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:41.550  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:41.550  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:41.550  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:41.550  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:41.550  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:17:41.556  7630  7898 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 13:17:41.556  7630  7898 W bt-smp  : Plain text(LSB ~ MSB) = 2f 08 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 13:17:41.556  7630  7898 W bt-smp  : Encrypted text(LSB ~ MSB) = 0c 10 9f 53 bc 46 0f f3 01 b2 3b 86 15 23 71 70 
09-07 13:17:41.556  7630  7898 W bt-btm  : Stopping oneshot timer
09-07 13:17:41.562  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:17:41.566  7630  7898 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 13:17:41.566  7630  7898 W bt-smp  : Plain text(LSB ~ MSB) = e7 2f 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 13:17:41.566  7630  7898 W bt-smp  : Encrypted text(LSB ~ MSB) = 28 8c 07 0f 15 38 ca 82 cc 66 68 7c cb b4 19 b5 
09-07 13:17:41.567  7630  7898 W bt-btm  : Stopping oneshot timer
09-07 13:17:41.567  7630  7857 I BluetoothAdapterState: Entering On State
09-07 13:17:41.581  7630  7857 D LGBluetoothServiceAdapter: [BTUI] OnState
09-07 13:17:41.581  7630  7857 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-07 13:17:41.581  7630  7857 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-07 13:17:41.585  7630  7857 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-07 13:17:41.585  6782  7552 D BluetoothMap: onBluetoothStateChange: up=true
09-07 13:17:41.591  7630  7898 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 13:17:41.591  7630  7898 W bt-smp  : Plain text(LSB ~ MSB) = 4a cf 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 13:17:41.591  7630  7898 W bt-smp  : Encrypted text(LSB ~ MSB) = 6f e6 88 c2 09 64 86 55 d4 42 f7 d4 9b fe d4 6c 
09-07 13:17:41.591  7630  7898 W bt-btm  : Stopping oneshot timer
09-07 13:17:41.603  6782  7552 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 13:17:41.612  7630  7898 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 13:17:41.612  7630  7898 W bt-smp  : Plain text(LSB ~ MSB) = 19 4b 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 13:17:41.612  7630  7898 W bt-smp  : Encrypted text(LSB ~ MSB) = 8a 62 3f aa 7a 10 b9 db 8c 5c 38 ab f4 b0 8b 01 
09-07 13:17:41.612  7630  7898 W bt-btm  : Stopping oneshot timer
09-07 13:17:41.621  7630  7857 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-07 13:17:41.632  6782  6802 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 13:17:41.656  7934  7934 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-07 13:17:41.659  1837  2691 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:17:41.667  1837  1837 D BluetoothHeadset: Proxy object connected
09-07 13:17:41.667  6782  7552 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 13:17:41.670  6782  6782 D BluetoothMap: Proxy object connected
09-07 13:17:41.670  6782  6782 D MapProfile: Bluetooth service connected
09-07 13:17:41.670  6782  6782 D BluetoothMap: getConnectedDevices()
09-07 13:17:41.672  6782  6802 D BluetoothPan: onBluetoothStateChange on: true
09-07 13:17:41.672  6782  6802 D BluetoothPan: onBluetoothStateChange call bindService
,09-07 13:17:41.675  7630  7862 V BluetoothMapService: getConnectedDevices()
09-07 13:17:41.676  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:17:41.678  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:17:41.679  1837  1837 D BluetoothHeadset: Proxy object connected
09-07 13:17:41.679  6782  6782 D BluetoothHeadset: Proxy object connected
09-07 13:17:41.679  6782  6782 D HeadsetProfile: Bluetooth service connected
09-07 13:17:41.681  6782  6782 D BluetoothInputDevice: Proxy object connected
09-07 13:17:41.681  6782  6782 D HidProfile: Bluetooth service connected
09-07 13:17:41.683  6782  6782 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 13:17:41.683  1837  1837 D BluetoothHeadset: Proxy object connected
09-07 13:17:41.683  6782  6782 D PanProfile: Bluetooth service connected
,09-07 13:17:41.686  1034  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 13:17:41.687  6782  6801 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 13:17:41.688  1034  1034 D BluetoothA2dp: Proxy object connected
09-07 13:17:41.695  1034  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:17:41.696  1034  1034 D BluetoothHeadset: Proxy object connected
09-07 13:17:41.696  6782  6782 D BluetoothA2dp: Proxy object connected
09-07 13:17:41.696  6782  6782 D A2dpProfile: Bluetooth service connected
,09-07 13:17:41.699  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-07 13:17:41.700  1034  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-07 13:17:41.700  1034  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-07 13:17:41.700  7630  7861 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 13:17:41.700  7630  7861 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-07 13:17:41.701  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:41.702  1927  2089 D LGBluetoothAPIService: Message: 1
09-07 13:17:41.702  1927  2089 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-07 13:17:41.702  1927  2089 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-07 13:17:41.702  1927  2089 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-07 13:17:41.702  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 13:17:41.703  1034  1117 D BluetoothManagerService: Message: 40
09-07 13:17:41.703  1034  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-07 13:17:41.706  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:41.707  7630  7630 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:41.707  7630  7630 D BluetoothMapService: STATE_ON
09-07 13:17:41.708  6782  6782 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-07 13:17:41.710  6782  6782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-07 13:17:41.716  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
09-07 13:17:41.716  7630  7630 V BluetoothPbapService: Pbap Service onCreate
09-07 13:17:41.716  7630  7630 V BluetoothPbapService: Starting PBAP service
09-07 13:17:41.717  6782  6782 D DockEventReceiver: finishStartingService: stopping service
09-07 13:17:41.717  7630  7630 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-07 13:17:41.717  7630  7630 V BluetoothPbapService: Pbap Service onBind
09-07 13:17:41.718  7630  7630 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:41.718  7630  7630 V BluetoothPbapService: state: 12
09-07 13:17:41.718  7630  7630 V BluetoothMapService: Handler(): got msg=1
09-07 13:17:41.719  7630  7630 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-07 13:17:41.719  7630  7630 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 13:17:41.719  7630  7630 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:41.719  7630  7630 V BluetoothPbapReceiver: ***********state = 12
09-07 13:17:41.720  7630  7952 D BluetoothMapMasInstance: MAS initSocket()
09-07 13:17:41.721  6782  6782 D BluetoothPbap: Proxy object connected
09-07 13:17:41.721  7630  7952 D BluetoothMapMasInstance:   masId = 00
09-07 13:17:41.721  7630  7952 D BluetoothMapMasInstance:   msgTypes = 0e
09-07 13:17:41.721  7630  7952 D BluetoothMapMasInstance:   masName = SMS/MMS
09-07 13:17:41.721  7630  7952 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-07 13:17:41.721  6782  6782 D PbapServerProfile: Bluetooth service connected
09-07 13:17:41.721  7630  7630 V BluetoothPbapService: Handler(): got msg=1
09-07 13:17:41.722  7630  7630 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-07 13:17:41.722  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 13:17:41.723  1034  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:41.723  2227  2227 D c       : Getting all permits...
09-07 13:17:41.723  2227  2227 D a       : Opening database...
09-07 13:17:41.723  7630  7953 V BluetoothPbapService: Pbap Service initSocket
09-07 13:17:41.723  1034  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:41.726  2227  2227 D a       : Opening database auth.proximity.permit_store...
,09-07 13:17:41.727  2227  2227 D a       : Closing database...
09-07 13:17:41.731  7630  7953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:17:41.731  7630  7952 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:17:41.734  7630  7952 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-07 13:17:41.735  7630  7952 V BluetoothMapMasInstance: Succeed to create listening socket 
09-07 13:17:41.735  7630  7952 D BluetoothMapMasInstance: Accepting socket connection...
09-07 13:17:41.736  7630  7953 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-07 13:17:41.736  7630  7953 V BluetoothPbapService: Succeed to create listening socket 
09-07 13:17:41.736  7630  7953 V BluetoothPbapService: Accepting socket connection...
09-07 13:17:41.736  7630  7861 D BluetoothAdapterProperties: Scan Mode:21
09-07 13:17:41.736  7630  7861 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-07 13:17:41.738  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:17:41.740  6782  6782 D BluetoothPermissionRequest: onReceive
09-07 13:17:41.745  6782  6782 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 13:17:41.746  6782  6782 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 13:17:41.747  7630  7630 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-07 13:17:41.748  7630  7630 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-07 13:17:41.753  7630  7630 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-07 13:17:41.766  7630  7630 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 13:17:41.766  7630  7630 V BtOppService: onCreate
,09-07 13:17:41.769  7630  7630 V BluetoothOppNotification: send message
09-07 13:17:41.771  7630  7630 V BtOppService: Starting RfcommListener
09-07 13:17:41.786  7630  7630 D BluetoothOppPreference: Dumping Names:  
09-07 13:17:41.786  7630  7630 D BluetoothOppPreference: {}
,09-07 13:17:41.786  7630  7630 D BluetoothOppPreference: Dumping Channels:  
09-07 13:17:41.786  7630  7630 D BluetoothOppPreference: {}
09-07 13:17:41.788  7630  7630 V BtOppService: onStartCommand
09-07 13:17:41.789  7630  7957 V BtOppService: Deleted complete outbound shares, number =  0
09-07 13:17:41.791  7630  7630 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:41.791  7630  7957 V BtOppService: Deleted complete inbound failed shares, number = 0
09-07 13:17:41.793  7630  7957 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-07 13:17:41.793  7630  7630 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 13:17:41.794  7630  7960 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 13:17:41.794  7630  7960 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 13:17:41.794  7630  7957 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ba1d491 on behalf of 
09-07 13:17:41.796  7630  7630 V BluetoothOppNotification: new notify threadi!
09-07 13:17:41.796  7630  7630 V BluetoothOppNotification: send delay message
09-07 13:17:41.797  7630  7630 V BtOppService: start RfcommListener
09-07 13:17:41.798  7630  7960 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bd1dff6 on behalf of 
,09-07 13:17:41.799  7630  7630 V BtOppService: RfcommListener started
09-07 13:17:41.800  7630  7630 V BtOppService: ContentObserver received notification
09-07 13:17:41.800  7630  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-07 13:17:41.800  7630  7630 V BtOppService: ContentObserver received notification
09-07 13:17:41.805  7630  7962 V BtOppRfcommListener: Starting RFCOMM listener....
09-07 13:17:41.805  1034  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:41.806  7630  7962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:17:41.806  7630  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28dd7ff7 on behalf of 
09-07 13:17:41.807  7630  7962 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
09-07 13:17:41.807  7630  7961 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-07 13:17:41.807  7630  7962 V BtOppRfcommListener: Started RFCOMM listener....
09-07 13:17:41.807  7630  7962 I BtOppRfcommListener: Accept thread started.
09-07 13:17:41.807  7630  7962 V BtOppRfcommListener: Accepting connection...
09-07 13:17:41.808  7630  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 13:17:41.813  7630  7960 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 13:17:41.813  7630  7960 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-07 13:17:41.823  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
09-07 13:17:41.824  7630  7630 V BluetoothFtpService: Ftp Service onCreate
09-07 13:17:41.824  7630  7630 I BluetoothFtpService: Ftp Service onCreate
,09-07 13:17:41.824  7630  7630 V BluetoothFtpService: Ftp Service onStartCommand
09-07 13:17:41.824  7630  7630 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:41.825  7630  7630 V BluetoothFtpService: Starting Listening on sockets
09-07 13:17:41.825  7630  7630 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 13:17:41.825  7630  7630 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 13:17:41.825  7630  7630 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 13:17:41.825  7630  7630 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:41.826  7630  7630 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-07 13:17:41.826  7630  7630 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-07 13:17:41.830  7630  7630 V BluetoothFtpService: Handler(): got msg=1
09-07 13:17:41.831  7630  7630 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-07 13:17:41.831  7630  7630 V BluetoothFtpService: Ftp Service initSocket
09-07 13:17:41.834  1034  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:41.835  7630  7630 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:17:41.837  7630  7630 V BluetoothFtpService: Succeed to create listening socket on channel 20
,09-07 13:17:41.843  7630  7963 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-07 13:17:41.867  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa42ac5
,09-07 13:17:41.867  7630  7630 V BluetoothSapService: Sap Service onCreate
09-07 13:17:41.869  7630  7630 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:17:41.869  7630  7630 V BluetoothSapService: state: 12
09-07 13:17:41.869  7630  7630 V BluetoothSapService: Starting SAP server process
09-07 13:17:41.870  7630  7630 V BluetoothSapService: SAP Service startRfcommListenerThread
09-07 13:17:41.854  7965  7965 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:41.854  7965  7965 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:41.872  7630  7966 V BluetoothSapService: Sap Service initRfcommSocket
09-07 13:17:41.872  1034  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:41.873  7630  7966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:17:41.874  7630  7966 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-07 13:17:41.874  7630  7966 V BluetoothSapService: Succeed to create listening socket 
09-07 13:17:41.874  7630  7966 V BluetoothSapService: Accepting socket connection...
09-07 13:17:41.879  7965  7965 V BT_SAP  : Event pipe created
09-07 13:17:41.879  7965  7965 V BT_SAP  : create_server_socket qcom.sap.server
09-07 13:17:41.879  7965  7965 V BT_SAP  : created socket fd 6
09-07 13:17:41.936  1034  1559 I art     : Explicit concurrent mark sweep GC freed 25615(1263KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.408ms total 124.971ms
09-07 13:17:41.938  7630  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dc68cd0 on behalf of 
09-07 13:17:41.938  7630  7960 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@155184c9 on behalf of 
,09-07 13:17:41.938  7630  7961 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 13:17:41.939  7630  7960 V BluetoothOppNotification: update too frequent, put in queue
09-07 13:17:41.942  7630  7961 V BluetoothOppNotification: outbound notification was removed.
09-07 13:17:41.942  7630  7960 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-07 13:17:41.942  7630  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 13:17:41.946  7630  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26a0f7ce on behalf of 
09-07 13:17:41.948  7630  7961 V BluetoothOppNotification: inbound: succ-0  fail-0
09-07 13:17:41.950  7630  7961 V BluetoothOppNotification: inbound notification was removed.
09-07 13:17:41.950  7630  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-07 13:17:41.953  7630  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@355e76ef on behalf of 
,09-07 13:17:42.364  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:42.364  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:42.364  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:42.364  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:17:42.364  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:42.364  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:42.364  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:42.364  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:17:42.378  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:42.380  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:42.380  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@179a5e6e added. We now have 8 listener(s)
09-07 13:17:42.380  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:42.385  1034  1998 D WifiServiceImplEx: setWifiEnabled: false pid=6660, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 13:17:42.385  1034  1998 D WifiService: setWifiEnabled: false pid=6660, uid=10118
09-07 13:17:42.385  1034  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 13:17:42.393  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:42.396  1034  2015 D WifiServiceImplEx: setWifiEnabled: true pid=6660, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 13:17:42.396  1034  2015 D WifiService: setWifiEnabled: true pid=6660, uid=10118
09-07 13:17:42.396  1034  2015 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 13:17:42.416  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-07 13:17:42.416  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 13:17:42.416  1034  1034 D Ulp_jni : JNI:system_update. Event-4
09-07 13:17:42.418  1034  1522 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-07 13:17:42.418  1034  1522 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-07 13:17:42.420  1034  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-07 13:17:42.420  1034  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-07 13:17:42.420  1034  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin],
09-07 13:17:42.421  1034  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-07 13:17:42.421  1034  1522 I WifiUtil: Intf0MacAddress=C49A027FFB5D,
09-07 13:17:42.421  1034  1522 E WifiHW  : unknown target_country: EU , set to default
,09-07 13:17:42.421  1034  1522 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-07 13:17:42.421  1034  1522 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,09-07 13:17:42.421  1034  1522 I WifiUtil: gEnableBmps=1
09-07 13:17:42.799  7630  7630 V BluetoothOppNotification: new notify threadi!
,09-07 13:17:42.800  7630  7630 V BluetoothOppNotification: send delay message
,09-07 13:17:42.822  7630  7979 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-07 13:17:42.826  7630  7979 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d4fa5fc on behalf of 
,09-07 13:17:42.827  7630  7979 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-07 13:17:42.834  7630  7979 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 13:17:42.837  7630  7979 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c64a485 on behalf of 
09-07 13:17:42.838  7630  7979 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 13:17:42.840  7630  7979 V BluetoothOppNotification: outbound notification was removed.
09-07 13:17:42.840  7630  7979 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 13:17:42.841  7630  7979 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14d8c2da on behalf of 
09-07 13:17:42.841  7630  7979 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-07 13:17:42.845  7630  7979 V BluetoothOppNotification: inbound notification was removed.
09-07 13:17:42.846  7630  7979 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 13:17:42.847  7630  7979 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a45930b on behalf of 
09-07 13:17:43.073   308   892 D SoftapController: Softap fwReload - Ok
,09-07 13:17:43.153  1034  1522 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (728ms)
,09-07 13:17:43.195   308   892 D CommandListener: Setting iface cfg
09-07 13:17:43.195   308   892 D CommandListener: Trying to bring down wlan0
,09-07 13:17:43.199   308   892 D CommandListener: Clearing all IP addresses on wlan0
09-07 13:17:43.203  1034  1522 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-07 13:17:43.203  1034  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 13:17:43.205  1034  1117 D Tethering: InitialState.processMessage what=4
09-07 13:17:43.205  1034  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 13:17:43.205  1034  1522 E WifiStateMachine: useWiFiOffloading() : false
09-07 13:17:43.205  1034  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 13:17:43.207  1034  1522 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-07 13:17:43.208  1034  1522 D WifiMonitor: connecting to supplicant
09-07 13:17:43.194  8002  8002 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:43.194  8002  8002 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:43.211  1034  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 13:17:43.212  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:43.213  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-07 13:17:43.214  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-07 13:17:43.214  6782  6782 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 13:17:43.214  6782  6782 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 13:17:43.214  6782  6782 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 13:17:43.218  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-07 13:17:43.221  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:43.230  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 13:17:43.230  6782  6782 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 13:17:43.231  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 13:17:43.231  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 13:17:43.231  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 13:17:43.231  6782  6782 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 13:17:43.231  6782  6782 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 13:17:43.260  8002  8002 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-07 13:17:43.271  1034  1836 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8004 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-07 13:17:43.302  8002  8002 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 13:17:43.302  8002  8002 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-07 13:17:43.324  7729  7740 E UEI.SmartControl: file observer is disposed!
,09-07 13:17:43.373  8002  8002 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 13:17:43.395  1034  2018 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8027 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 13:17:43.401  8004  8024 W FormManager: Network not available. Please check & try again.
09-07 13:17:43.406  8002  8002 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-07 13:17:43.413  8004  8025 V FormManager: Network unavailable.
09-07 13:17:43.414  1034  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-07 13:17:43.414  1034  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-07 13:17:43.415  1034  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-07 13:17:43.416  1034  1522 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-07 13:17:43.416  1034  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:43.417  1034  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:43.417  1034  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:43.417  8004  8025 V FormManager: Network unavailable.
09-07 13:17:43.417  1034  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:43.418  1034  1522 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-07 13:17:43.418  1034  1522 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-07 13:17:43.419  1034  1522 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-07 13:17:43.419  1034  1522 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-07 13:17:43.419  1034  1522 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-07 13:17:43.420  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:43.420  1034  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 13:17:43.420  1034  1522 E WifiStateMachine: useWiFiOffloading() : false
09-07 13:17:43.420  1034  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 13:17:43.420  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:43.420  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:43.420  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:43.420  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 13:17:43.422  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-07 13:17:43.423  1034  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-07 13:17:43.423  1927  1927 D WfdService: Waiting for WifiP2p enabling
09-07 13:17:43.424  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:43.425  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:43.425  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:43.425  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:43.425  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:43.425  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:43.425  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:43.425  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:43.425  6660  6660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:17:43.429  6660  6660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:17:43.431  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:17:43.431  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:43.431  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:43.431  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is W,i-Fi enabled: true
09-07 13:17:43.431  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:43.431  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:17:43.431  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:17:43.431  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:17:43.432  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:17:43.434  1034  1522 D WifiNative-wlan0: doBoolean: SET update_config 1
09-07 13:17:43.434  1034  1522 D WifiNative-wlan0: SET update_config 1: returned true
09-07 13:17:43.434  1034  1522 D WifiConfigStore: Loading config and enabling all networks 
09-07 13:17:43.435  1034  1522 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-07 13:17:43.436  1034  1522 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-07 13:17:43.439  6660  6739 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-07 13:17:43.440  6660  6739 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-07 13:17:43.441  1034  1633 I ActivityManager: Killing 7098:com.android.chrome/u0a57 (adj 15): empty #17
09-07 13:17:43.442  6660  6739 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1149dd40 Bundle[{}]
09-07 13:17:43.443  6660  6739 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 13:17:43.443  6660  6739 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-07 13:17:43.444  8002  8002 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-07 13:17:43.444  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-07 13:17:43.444  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-07 13:17:43.444  6660  6739 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-07 13:17:43.444  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-07 13:17:43.444  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-07 13:17:43.444  1034  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-07 13:17:43.444  1034  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-07 13:17:43.445  6660  6739 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 13:17:43.446  6660  6739 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-07 13:17:43.446  6660  6739 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-07 13:17:43.449  1034  1522 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-07 13:17:43.453  6660  6739 I System.out: Running OutgoingSocketThread
,09-07 13:17:43.455  6660  8046 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 856)
09-07 13:17:43.456  6660  8046 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55701
09-07 13:17:43.456  6660  8046 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-07 13:17:43.458  1034  1522 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-07 13:17:43.458  1034  1522 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 13:17:43.550  1034  2015 W libprocessgroup: failed to open /acct/uid_10057/pid_7098/cgroup.procs: No such file or directory
09-07 13:17:43.550  1034  1522 D WifiStateMachine: enableVerboseLogging : level 2
09-07 13:17:43.550  1034  1522 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-07 13:17:43.555  1034  1522 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-07 13:17:43.555  1034  1522 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,09-07 13:17:43.558  1034  1522 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-07 13:17:43.558  1034  1522 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-07 13:17:43.559  1034  1522 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-07 13:17:43.559  1034  1522 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-07 13:17:43.560  1034  1522 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-07 13:17:43.560  1034  1522 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-07 13:17:43.561  1034  1522 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-07 13:17:43.561  1034  1522 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-07 13:17:43.563  1034  1522 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-07 13:17:43.563  1034  1522 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-07 13:17:43.564  1034  1522 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-07 13:17:43.564  1034  1522 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 13:17:43.564  1034  1522 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-07 13:17:43.565  1034  1522 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-07 13:17:43.565  1034  1522 D WifiNative-HAL: Setting external_sim to 1
09-07 13:17:43.565  1034  1522 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-07 13:17:43.565  1034  1522 D WifiNative-wlan0: SET external_sim 1: returned true
09-07 13:17:43.565  1034  1522 I WifiNative-HAL: startHal
,09-07 13:17:43.565  1034  1522 D wifi    : setting scan oui 0xaf72c660
09-07 13:17:43.565  1927  1927 D WfdsService: Supplicant Connection state is changed : true
09-07 13:17:43.566  1927  2285 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-07 13:17:43.566  1034  1522 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 13:17:43.566  1927  2285 D WfdsService: Set the WFDS Monitor: true
09-07 13:17:43.566  1034  1522 I WifiNative-HAL: startHal
09-07 13:17:43.566  1927  2285 D WfdsMonitor: WfdsMonitorThread create
09-07 13:17:43.566  1034  1522 D wifi    : setting scan oui 0xaf72c660
09-07 13:17:43.566  1927  2285 D WfdsMonitor: WFDS Monitor is created and started
09-07 13:17:43.566  1034  1522 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-07 13:17:43.566  1927  2285 D WfdsService: WiFi: Supplicant connection re-established
09-07 13:17:43.566  7658  7658 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:17:43.566  1034  1522 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-07 13:17:43.566  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-07 13:17:43.567  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-07 13:17:43.567  1034  1522 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-07 13:17:43.567  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 13:17:43.567  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 13:17:43.567  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 13:17:43.568  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-07 13:17:43.568  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-07 13:17:43.568  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-07 13:17:43.568  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START,
09-07 13:17:43.568  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 13:17:43.568  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 13:17:43.568  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 13:17:43.569  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,09-07 13:17:43.569  1927  8047 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-07 13:17:43.570  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 13:17:43.570  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-07 13:17:43.570  8002  8002 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,09-07 13:17:43.571  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-07 13:17:43.571  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 13:17:43.571  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 13:17:43.571  1034  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 13:17:43.573  1034  1522 E WifiNative: : [209,717,465 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-07 13:17:43.573  1034  1522 D WifiNative-wlan0: doBoolean: RECONNECT
09-07 13:17:43.573  1034  1522 D WifiNative-wlan0: RECONNECT: returned true
09-07 13:17:43.573  1034  1522 D WifiNative-wlan0: doString: [STATUS]
09-07 13:17:43.574  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-07 13:17:43.574  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-07 13:17:43.574  1034  1522 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 13:17:43.574  1034  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 13:17:43.575  1034  1522 D WifiNative-wlan0: SET ps 1: returned true
09-07 13:17:43.575  1034  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 13:17:43.576  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
09-07 13:17:43.576  1034  1034 D RttService: SCAN_AVAILABLE : 3
09-07 13:17:43.576  1034  1522 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-07 13:17:43.576  1927  8047 E CtrlSupplicant: Succeed to open control connection
09-07 13:17:43.576  1034  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.576  1034  1540 I WifiNative-HAL: startHal
09-07 13:17:43.577  1034  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf72c660
09-07 13:17:43.577  1927  8047 E CtrlSupplicant: Succeed to open monitor connection
09-07 13:17:43.577  1034  1540 D wifi    : failed to get capabilities : -3
09-07 13:17:43.577  1034  1540 E WifiScanningService: could not get scan capabilities
09-07 13:17:43.577  1034  1541 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.578  1034  1522 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-07 13:17:43.578  1927  8047 D WfdsMonitor: Supplicant connection established
09-07 13:17:43.578  1927  2285 D WfdsService: Connected to the supplicant for wfds
09-07 13:17:43.578  1034  1522 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-07 13:17:43.578  1034  1522 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-07 13:17:43.579   308   892 D CommandListener: Setting iface cfg
09-07 13:17:43.579   308   892 D CommandListener: Trying to bring up p2p0
09-07 13:17:43.579  1034  1522 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-07 13:17:43.579  1034  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 13:17:43.579  1034  1521 D LGWifiP2pService: P2pEnablingState
09-07 13:17:43.579  1034  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.579  1034  1521 D LGWifiP2pService: P2p socket connection successful
09-07 13:17:43.579  1034  1522 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-07 13:17:43.579  1034  1521 D LGWifiP2pService: P2pEnabledState
09-07 13:17:43.580  1034  1522 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-07 13:17:43.580  1034  1522 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-07 13:17:43.580  8002  8002 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-07 13:17:43.581  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-07 13:17:43.581  1034  1522 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-07 13:17:43.581  1927  1927 D WfdsService: WifiP2pState is changed : true
09-07 13:17:43.581  1927  2285 D WfdsService: Receive the WFDS_ENABLE Method
09-07 13:17:43.581  1927  2285 D WfdsService: Set the WFDS Monitor: true
09-07 13:17:43.581  1927  2285 D WfdsService: Connected to the supplicant for wfds
09-07 13:17:43.581  1927  2285 D WfdsJNI : doCommand: WFDS_SET TRUE
09-07 13:17:43.582  8002  8002 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-07 13:17:43.582  1927  2285 D WfdsService: selectPreferredScanChannel [36]
09-07 13:17:43.582  1034  1522 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-07 13:17:43.582  1927  2285 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-07 13:17:43.582  1034  1522 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-07 13:17:43.582  1034  1522 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-07 13:17:43.582  8002  8002 E wpa_supplicant: disconnect_rssi_lvl: -100
09-07 13:17:43.583  1034  1521 D LGWifiP2pService: sending p2p connection changed broadcast
09-07 13:17:43.583  1034  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=209729  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-07 13:17:43.585  1034  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-07 13:17:43.586  1034  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-07 13:17:43.586  1034  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
09-07 13:17:43.586  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=209732  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 13:17:43.587  1034  1522 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 13:17:43.587  1034  1522 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 13:17:43.587  1034  1521 D WifiNative-p2p0: SET device_name G3: returned true
09-07 13:17:43.587  1034  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-07 13:17:43.587  1034  1521 D LGWifiP2pService: before postfix = G3
,09-07 13:17:43.587  1034  1521 D WifiServerServiceExt: postfix byte check : 2
09-07 13:17:43.587  1034  1521 D LGWifiP2pService: after postfix = G3
09-07 13:17:43.587  1034  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-07 13:17:43.587  1034  1522 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 13:17:43.587  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-07 13:17:43.588  1034  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-07 13:17:43.588  1034  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-07 13:17:43.588  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-07 13:17:43.588  1034  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-07 13:17:43.588  1034  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-07 13:17:43.588  1927  1927 D WfdsService: isConnected: false
09-07 13:17:43.589  1034  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-07 13:17:43.589  1034  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-07 13:17:43.589  1034  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-07 13:17:43.589  1034  1521 D WifiNative-HAL: p2pGetDeviceAddress
09-07 13:17:43.589  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:43.589  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:43.589  1034  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-07 13:17:43.590  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 13:17:43.591  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:43.591  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:43.591  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-07 13:17:43.591  8002  8002 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:43.591  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 13:17:43.591  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:43.591  1034  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ,
09-07 13:17:43.591  1034  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-07 13:17:43.591  1034  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:43.591  1034  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-07 13:17:43.592  8002  8002 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 13:17:43.592  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:43.592  8002  8002 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.592  1034  8044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:43.592  1034  8044 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.592  1034  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD,
09-07 13:17:43.592  1034  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.593  1927  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:43.593  1034  1522 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-07 13:17:43.593  1034  1522 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-07 13:17:43.593  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
09-07 13:17:43.593  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-07 13:17:43.594  1927  1927 D WfdsService: Update P2p Interface State: 3
09-07 13:17:43.594  1034  1522 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-07 13:17:43.594  1034  1522 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-07 13:17:43.594  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-07 13:17:43.596  8002  8002 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.596  1927  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:43.597  1034  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
,09-07 13:17:43.597  1034  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-07 13:17:43.597  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-07 13:17:43.597  8002  8002 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 13:17:43.599  1034  8044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:43.599  1034  8044 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.599  1034  1522 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-07 13:17:43.599  1034  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.599  1034  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.599  1034  1522 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,09-07 13:17:43.599  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-07 13:17:43.599  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 13:17:43.599  1034  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 13:17:43.599  1034  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 13:17:43.599  1034  1522 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-07 13:17:43.599  1034  1522 D WifiNative-wlan0: doBoolean: SCAN
09-07 13:17:43.599  1034  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-07 13:17:43.600  1034  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-07 13:17:43.600  1034  1522 D WifiNative-wlan0: SCAN: returned false
09-07 13:17:43.600  1034  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=209746  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-07 13:17:43.601  1034  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-07 13:17:43.601  1034  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,09-07 13:17:43.604  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=209750  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 13:17:43.605  1034  1522 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 13:17:43.606  1034  1522 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 13:17:43.607  1034  1522 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 13:17:43.608  1034  1522 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 13:17:43.608  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:43.608  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:43.608  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 13:17:43.609  1034  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-07 13:17:43.609  1034  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-07 13:17:43.609  1034  1521 D LGWifiP2pService: InactiveState
09-07 13:17:43.609  1034  1521 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.609  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.609  1034  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-07 13:17:43.610  1034  1522 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 13:17:43.610  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 13:17:43.610  8002  8002 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:43.611  8002  8002 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 13:17:43.611  8002  8002 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.612  8002  8002 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.612  1927  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 13:17:43.612  1927  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:43.613  1034  8044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 13:17:43.613  1034  8044 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:43.613  1034  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:43.613  1034  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 13:17:43.613  1034  8044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:43.613  1034  8044 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-07 13:17:43.613  1034  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.613  1034  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.613  1034  8044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:43.613  1034  8044 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.613  1034  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.613  1034  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 13:17:43.613  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:43.613  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:43.614  1927  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 13:17:43.614  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:43.614  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
09-07 13:17:43.615  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:43.615  1034  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-07 13:17:43.615  1034  1521 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.615  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.615  1034  1521 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.615  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.615  1034  1521 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.616  1034  1521 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.616  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.616  1034  1521 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.616  1927  2285 W WfdsService: DefaultState - msg [9441285] is not handled
09-07 13:17:43.616  1034  1521 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.617  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.617  1034  1521 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.617  1034  1521 D LGWifiP2pService: InactiveState{ when=-8ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.617  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.617  1034  1521 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:43.617  1034  1034 E WifiServerServiceExt: No p2p device connected
09-07 13:17:43.618  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:43.618  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
09-07 13:17:43.626  8027  8027 D PCSuite :, [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 13:17:43.629  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:17:43.634  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:43.635  1034  1633 I ActivityManager: Killing 7122:com.lge.drmservice/u0a62 (adj 15): empty #17
09-07 13:17:43.655  1034  1872 W libprocessgroup: failed to open /acct/uid_10062/pid_7122/cgroup.procs: No such file or directory
,09-07 13:17:43.665  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 13:17:43.665  6782  6782 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 13:17:43.666  6782  6782 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 13:17:43.666  6782  6782 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-07 13:17:43.666  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-07 13:17:43.667  6782  6782 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 13:17:43.667  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 13:17:43.667  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 13:17:43.667  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 13:17:43.668  6782  6782 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 13:17:43.668  6782  6782 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 13:17:43.675  8027  8027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 13:17:43.678  8004  8051 W FormManager: Network not available. Please check & try again.
09-07 13:17:43.680  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:17:43.685  8004  8052 V FormManager: Network unavailable.
09-07 13:17:43.688  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:43.688  8004  8052 V FormManager: Network unavailable.
09-07 13:17:43.706  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 13:17:43.706  4301  4301 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-07 13:17:43.711  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 13:17:43.716  4301  4301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 13:17:43.726  4301  8053 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 13:17:43.734  4301  8054 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-07 13:17:43.734  4301  8054 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 13:17:43.799  1034  1058 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8055 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-07 13:17:43.822   335   335 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 21.055ms
,09-07 13:17:43.841   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 373us total 18.405ms
,09-07 13:17:43.858   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 16.183ms
09-07 13:17:43.908  8055  8055 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 13:17:43.908  8055  8055 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-07 13:17:43.916  8055  8055 V [BNRBootReceiver]: Boot Receiver Return
09-07 13:17:43.920  8055  8055 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-07 13:17:43.985  1034  2018 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8073 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-07 13:17:43.986  1034  2018 I ActivityManager: Killing 7139:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-07 13:17:44.044  1034  1890 W libprocessgroup: failed to open /acct/uid_10085/pid_7139/cgroup.procs: No such file or directory
,09-07 13:17:44.072  8073  8073 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 13:17:44.099  8073  8073 D PluginManager: init()
,09-07 13:17:44.106  8002  8002 E wpa_supplicant: USIM:  scard_init function
09-07 13:17:44.108  8002  8002 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-07 13:17:44.112  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-07 13:17:44.112  1034  8044 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-07 13:17:44.112  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-07 13:17:44.113  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: WPS-AP-AVAILABLE 
09-07 13:17:44.113  1034  8044 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-07 13:17:44.113  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,09-07 13:17:44.113  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-07 13:17:44.115  1034  1522 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-07 13:17:44.116  1034  1522 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-07 13:17:44.117  1034  1522 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-07 13:17:44.118  1034  1522 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-07 13:17:44.119  1034  1522 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-07 13:17:44.133  1034  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=210279  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-07 13:17:44.136  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=210281  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-07 13:17:44.137  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.137  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.137  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 13:17:44.138  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:44.138  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,09-07 13:17:44.138  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:44.138  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:44.140  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 13:17:44.234  8002  8002 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 13:17:44.239  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-07 13:17:44.239  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-07 13:17:44.239  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-07 13:17:44.239  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-07 13:17:44.241  1034  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 13:17:44.244  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 13:17:44.244  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 13:17:44.244  1034  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=210387  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 13:17:44.245  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=210390  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 13:17:44.246  1034  1522 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:44.246  1034  1522 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:44.247  1034  1522 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:44.248  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 13:17:44.249  1034  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-07 13:17:44.249  1034  1522 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210395
09-07 13:17:44.250  1034  1522 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210395
09-07 13:17:44.251  1034  1522 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210396
09-07 13:17:44.251  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210397
09-07 13:17:44.252  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 13:17:44.252  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 13:17:44.253  8002  8002 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 13:17:44.254  8002  8002 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-07 13:17:44.256  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-07 13:17:44.258  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 13:17:44.258  1034  8044 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 13:17:44.258  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-07 13:17:44.258  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 13:17:44.258  1034  8044 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 13:17:44.259  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 13:17:44.259  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 13:17:44.260  1034  1522 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210405
09-07 13:17:44.260  1034  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=210406  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 13:17:44.263  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:44.263  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:44.263  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.263  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.263  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 13:17:44.264  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:44.266  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.266  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.267  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-07 13:17:44.268  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=210413  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-07 13:17:44.270  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:44.270  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-07 13:17:44.271  1034  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=210416  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 13:17:44.272  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=210417  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 13:17:44.273  1034  1522 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=210419
09-07 13:17:44.274  1034  1522 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=210419
09-07 13:17:44.274  1034  1522 D WifiNative-wlan0: doString: [STATUS]
09-07 13:17:44.275  1034  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 13:17:44.275  1034  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 13:17:44.275  1034  1522 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 13:17:44.277  1034  1522 I WifiServiceExtension: setVHTCapabilityType  : false
09-07 13:17:44.285  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:44.285  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-07 13:17:44.286  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:44.288  1034  1522 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-07 13:17:44.288  1034  1522 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-07 13:17:44.293  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.293  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.293  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 13:17:44.295  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.296  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.296  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 13:17:44.303  1034  1522 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-07 13:17:44.303  1034  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 13:17:44.304  1034  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 13:17:44.304  1034  1529 D ConnectivityService: Got NetworkAgent Messenger
09-07 13:17:44.304  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 13:17:44.304  1034  1529 D ConnectivityService: NetworkAgent connected
,09-07 13:17:44.306  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:44.306  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:44.307  1034  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 13:17:44.307  1034  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 13:17:44.307  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:44.308  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:44.308  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:44.309  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:44.312  1034  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 13:17:44.312  1034  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 13:17:44.312  1034  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 13:17:44.313  1034  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 13:17:44.313  1034  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 13:17:44.319  1034  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-07 13:17:44.321   308   892 D CommandListener: Setting iface cfg
09-07 13:17:44.325  1034  1522 E WifiStateMachine: Start Dhcp Watchdog 3
09-07 13:17:44.325  1034  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=210470  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 13:17:44.326  1034  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=210471  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 13:17:44.326  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=210471  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 13:17:44.327  1034  8098 D DhcpStateMachine: StoppedState
09-07 13:17:44.327  1034  8098 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:44.327  1034  8098 D DhcpStateMachine: WaitBeforeStartState
09-07 13:17:44.327  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:44.327  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-07 13:17:44.328  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:44.328  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-07 13:17:44.328  1034  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=210474  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 13:17:44.329  1034  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=210474  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 13:17:44.329  1034  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=210474  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 13:17:44.330  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14372] from screen [on:0 period:73281802] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 13:17:44.331  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:73281803] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 13:17:44.331  1034  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-07 13:17:44.335  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 13:17:44.336  1034  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-07 13:17:44.336  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:44.337  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:44.337  1034  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:44.337  1034  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:44.338  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:44.338  1034  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:44.339  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-07 13:17:44.340  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:44.340  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 13:17:44.340  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=131,0,0
09-07 13:17:44.341  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=131,0,0
09-07 13:17:44.341  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-07 13:17:44.341  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-07 13:17:44.341  1034  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-07 13:17:44.341  1034  1522 D WifiNative-wlan0: doBoolean: SET ps 0
09-07 13:17:44.342  1034  1522 D WifiNative-wlan0: SET ps 0: returned true
09-07 13:17:44.342  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-07 13:17:44.342  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-07 13:17:44.342  1034  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-07 13:17:44.342  1034  1522 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-07 13:17:44.342  1034  1522 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 13:17:44.342  1034  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1f47775f target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:44.342  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1f47775f target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:44.343  1034  1522 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 13:17:44.343  1034  8098 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:44.343  1034  8098 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-07 13:17:44.343   308   892 D CommandListener: Setting iface cfg
09-07 13:17:44.343   308   892 D CommandListener: Trying to bring up wlan0
09-07 13:17:44.345  1034  1522 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-07 13:17:44.345  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 13:17:44.345  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 13:17:44.346  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:44.346  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:44.347  1034  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:44.347  1034  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:44.348  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 13:17:44.348  1034  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTI,ES 0 0
09-07 13:17:44.349  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-07 13:17:44.349  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 13:17:44.349  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,09-07 13:17:44.350  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2,
09-07 13:17:44.350  1034  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:44.350  1034  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:44.350  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2,
09-07 13:17:44.350  1034  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 13:17:44.350  1034  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1,
09-07 13:17:44.351  8002  8002 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-07 13:17:44.351  1034  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,09-07 13:17:44.351  1034  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 13:17:44.370  1034  1522 D WifiNative-wlan0: SET ps 1: returned true
09-07 13:17:44.371  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-07 13:17:44.372  1034  1522 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,09-07 13:17:44.372  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 13:17:44.372  1034  1522 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 13:17:44.373  1034  1529 D ConnectivityService: ignoring duplicate network state non-change,
,09-07 13:17:44.375  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:44.376  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:44.377  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.377  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.377  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 13:17:44.381  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:17:44.381  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.381  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 13:17:44.381  1034  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-07 13:17:44.382  1034  1529 D ConnectivityService: Adding iface wlan0 to network 102
09-07 13:17:44.382  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:44.385  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:44.385  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 13:17:44.386  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 13:17:44.387  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 13:17:44.390  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-07 13:17:44.396  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.396  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.397  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 13:17:44.400  1034  1522 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 13:17:44.402  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-07 13:17:44.409  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.409  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 13:17:44.409  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 13:17:44.409  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:44.409  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 13:17:44.410  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:44.411  1034  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 13:17:44.411  1034  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-07 13:17:44.413  1034  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-07 13:17:44.413  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:17:44.413  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 13:17:44.414  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:44.414   308   892 E Netd    : netlink response contains error (File exists)
09-07 13:17:44.414  1034  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-07 13:17:44.415  1034  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-07 13:17:44.415  1034  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-07 13:17:44.415  1034  1529 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-07 13:17:44.416  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-07 13:17:44.416  1034  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-07 13:17:44.416  1034  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-07 13:17:44.416  1034  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-07 13:17:44.416  1034  8093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:44.416  1034  8093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-07 13:17:44.416  1034  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:17:44.417  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:44.417  1034  8093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:17:44.417  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 13:17:44.417  1034  8093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-07 13:17:44.417  1034  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:44.417  1034  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, l,egacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-07 13:17:44.417  1034  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-07 13:17:44.417  1034  1529 D ConnectivityService:    accepting network in place of null
09-07 13:17:44.417  1034  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:44.419   308  8104 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-07 13:17:44.419  1034  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-07 13:17:44.419  1034  1522 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:44.419  1034  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-07 13:17:44.419  1034  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:17:44.419  1034  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 13:17:44.419   308  8104 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-07 13:17:44.420   308  8104 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
09-07 13:17:44.420   308  8104 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
09-07 13:17:44.421  1034  8093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-07 13:17:44.422  1034  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-07 13:17:44.423  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:44.424  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 13:17:44.427  1034  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 13:17:44.427  1034  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-07 13:17:44.428  1034  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-07 13:17:44.429  1034  1529 D ConnectivityService: validation of new default Network = false
09-07 13:17:44.429  1034  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-07 13:17:44.429  1034  1529 D DSQN    : enableDataServiceNotify 
09-07 13:17:44.429  1034  1529 D DSQN    : start dsqn bin
09-07 13:17:44.429  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-07 13:17:44.429  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 13:17:44.429  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 13:17:44.429  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 13:17:44.432  1034  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,09-07 13:17:44.432  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:17:44.432  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:44.433  1034  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:44.436  1587  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 13:17:44.424  8105  8105 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:44.424  8105  8105 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:44.445  1034  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-07 13:17:44.448  8105  8105 E DSQN    : DSQN ssw
09-07 13:17:44.455  6660  6739 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 857)
09-07 13:17:44.455  6660  6739 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 857)
,09-07 13:17:44.458  6660  6739 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 862)
,09-07 13:17:44.459  6660  6739 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-07 13:17:44.459  6660  6739 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 863)
09-07 13:17:44.460  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 13:17:44.461  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:44.462  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 13:17:44.463  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:17:44.463  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c93e90f added. We now have 2 listener(s)
,09-07 13:17:44.463  1034  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:44.465  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 13:17:44.465  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:44.465  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:17:44.465  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:44.465  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c96fd9c added. We now have 9 listener(s)
09-07 13:17:44.465  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:44.465  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 13:17:44.467  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:44.470  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:44.470  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:44.470  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:44.470  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:44.470  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:44.470  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:44.470  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:44.470  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:44.471  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:44.471  6660  6739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:17:44.471  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:17:44.471  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3711f37a added. We now have 3 listener(s)
09-07 13:17:44.471  1034  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 13:17:44.473  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 13:17:44.473  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:44.473  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:17:44.473  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:44.473  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3530072b added. We now have 10 listener(s)
09-07 13:17:44.473  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:44.473  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:44.473  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:44.473  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:44.473  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:44.473  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:44.474  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.474  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:44.474  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:17:44.474  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c93e90f removed from the list
09-07 13:17:44.474  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.474  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c96fd9c removed from the list
09-07 13:17:44.475  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:44.475  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:44.475  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.476  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.476  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.476  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:44.476  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:44.476  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.476  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c96fd9c not in the list
09-07 13:17:44.476  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listen,er does not exist in the list - probably already removed
09-07 13:17:44.476  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.477  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:44.477  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:44.477  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.477  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3530072b removed from the list
09-07 13:17:44.477  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:44.477  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.477  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.477  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:17:44.477  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3711f37a removed from the list
09-07 13:17:44.478  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:17:44.478  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3de45788 added. We now have 2 listener(s)
09-07 13:17:44.478  1034  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:44.480  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 13:17:44.480  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:44.480  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:17:44.480  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:44.480  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2814e521 added. We now have 9 listener(s)
09-07 13:17:44.480  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:44.480  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 13:17:44.483  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:17:44.488  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:44.488  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:44.488  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:44.488  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:44.488  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:44.488  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:44.488  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:44.488  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:17:44.490  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:44.490  6660  6739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:17:44.490  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:17:44.490  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1725eb07 added. We now have 3 listener(s)
09-07 13:17:44.490  1034  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:44.491  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:44.493  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:44.493  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 13:17:44.493  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:44.493  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:17:44.493  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:44.493  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@372b6434 added. We now have 10 listener(s)
09-07 13:17:44.493  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:44.493  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:17:44.493  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:17:44.493  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:17:44.493  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:44.493  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 13:17:44.496  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 13:17:44.496  1034  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 13:17:44.500  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 13:17:44.500  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 13:17:44.502  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 13:17:44.502  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:44.503  6660  6739 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 13:17:44.503  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:44.503  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:44.505  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:44.505  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:44.505  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:44.505  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:44.505  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.505  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:44.505  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:17:44.505  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3de45788 removed from the list
09-07 13:17:44.505  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.505  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2814e521 removed from the list
09-07 13:17:44.505  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:44.505  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.506  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.506  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.506  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:44.506  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:44.506  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.506  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2814e521 not in the list
09-07 13:17:44.506  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.506  6660  6739 D org.thaliproject.p2p.btconn,ectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.507  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:44.507  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:44.507  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:44.508  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:44.508  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.508  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@372b6434 removed from the list
09-07 13:17:44.508  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:44.508  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.508  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.508  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:17:44.508  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1725eb07 removed from the list
09-07 13:17:44.508  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:17:44.508  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33ac30a3 added. We now have 2 listener(s)
09-07 13:17:44.509  1034  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 13:17:44.511  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 13:17:44.511  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:44.511  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:17:44.511  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:44.511  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38348fa0 added. We now have 9 listener(s)
09-07 13:17:44.511  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:44.511  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 13:17:44.513  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:44.516  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:44.516  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:44.516  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:44.516  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:44.516  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:44.516  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:44.516  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:44.516  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:44.517  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:44.517  6660  6739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:17:44.517  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:17:44.517  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23113f1e added. We now have 3 listener(s)
09-07 13:17:44.518  1034  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:44.519  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:44.520  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:44.521  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 13:17:44.521  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:44.521  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:17:44.521  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:44.521  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thali,project.p2p.btconnectorlib.DiscoveryManager@1ec733ff added. We now have 10 listener(s)
09-07 13:17:44.521  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:44.521  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:17:44.522  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:17:44.522  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:17:44.522  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:17:44.522  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:44.522  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 13:17:44.525  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 13:17:44.525  1034  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:44.528  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 13:17:44.529  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 13:17:44.530  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 13:17:44.531  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:44.532  6660  6739 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 13:17:44.532  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:44.532  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:44.532  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:44.533  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:44.533  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.533  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:44.533  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:17:44.533  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33ac30a3 removed from the list
09-07 13:17:44.533  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.533  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38348fa0 removed from the list
09-07 13:17:44.533  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:44.533  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.533  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.533  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.534  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:44.534  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:44.534  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.534  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38348fa0 not in the list
09-07 13:17:44.534  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.534  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.535  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 13:17:44.535  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:44.535  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:44.535  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:44.535  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.536  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec733ff removed from the list
09-07 13:17:44.536  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:44.536  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.536  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.536  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:17:44.536  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23113f1e removed from the list
09-07 13:17:44.536  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:17:44.536  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178e2f2a added. We now have 2 listener(s)
09-07 13:17:44.537  1034  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:44.539  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 13:17:44.539  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:44.539  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:17:44.539  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:44.539  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e65111b added. We now have 9 listener(s)
09-07 13:17:44.539  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:44.539  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 13:17:44.541  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:44.544  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:44.544  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:44.544  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:44.544  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:44.544  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:44.544  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:44.544  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:44.544  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network ,type is Wi-Fi: true
09-07 13:17:44.546  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:44.546  6660  6739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:17:44.547  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:17:44.547  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b05891 added. We now have 3 listener(s)
,09-07 13:17:44.547  1034  8098 D DhcpStateMachine: DHCPV4 request on wlan0
09-07 13:17:44.547  1034  1633 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:44.548  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:44.549  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:44.551  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 13:17:44.551  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:44.551  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:17:44.551  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:44.551  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@173813f6 added. We now have 10 listener(s)
09-07 13:17:44.551  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:44.551  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:17:44.551  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:17:44.551  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:17:44.551  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:17:44.551  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 13:17:44.552  1034  8098 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-07 13:17:44.552  1034  8098 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-07 13:17:44.553  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 13:17:44.554  1034  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:44.544  8109  8109 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:44.544  8109  8109 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 13:17:44.557  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 13:17:44.559  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 13:17:44.561  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 13:17:44.561  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:44.563  6660  6739 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 13:17:44.564  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:44.564  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:44.564  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:17:44.565  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:44.565  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.565  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:44.565  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:17:44.565  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178e2f2a removed from the list
09-07 13:17:44.565  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.565  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e65111b removed from the list
09-07 13:17:44.565  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:44.565  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.566  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.566  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.567  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:44.567  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:44.567  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.567  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e65111b not in the list
09-07 13:17:44.567  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.567  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.568  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:44.568  8109  8109 I dhcpcd  : version 5.5.6 starting
09-07 13:17:44.568  6660  6739 D BluetoothLeScanner: could not find callback wrapper
09-07 13:17:44.568  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:17:44.568  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:44.568  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.568  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.,btconnectorlib.DiscoveryManager@173813f6 removed from the list
09-07 13:17:44.568  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:44.568  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:17:44.568  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.568  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:17:44.568  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b05891 removed from the list
09-07 13:17:44.569  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-07 13:17:44.569  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f70eccd added. We now have 2 listener(s)
09-07 13:17:44.569  1034  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:44.570  8109  8109 E dhcpcd  : get_duid: m
,09-07 13:17:44.570  8109  8109 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-07 13:17:44.570  8109  8109 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-07 13:17:44.572  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-07 13:17:44.572  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:44.572  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-07 13:17:44.572  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:44.572  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec97982 added. We now have 9 listener(s)
09-07 13:17:44.572  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:44.572  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 13:17:44.574  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:17:44.577  6660  6739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:17:44.577  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:17:44.577  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 13:17:44.577  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:17:44.577  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:17:44.577  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:44.577  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:17:44.577  6660  6739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:17:44.579  6660  6739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:17:44.579  6660  6739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:17:44.579  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:17:44.579  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdb20d0 added. We now have 3 listener(s)
09-07 13:17:44.580  1034  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 13:17:44.581  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:44.584  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:17:44.586  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 13:17:44.586  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:17:44.586  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:17:44.586  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:17:44.586  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@352c88c9 added. We now have 10 listener(s)
09-07 13:17:44.586  6660  6739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:17:44.587  6660  6739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:17:44.587  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:44.587  6660  6739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 13:17:44.589  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:44.589  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.589  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:17:44.589  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:17:44.589  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f70eccd removed from the list
09-07 13:17:44.589  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.589  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec97982 removed from the list
09-07 13:17:44.589  6660  6739 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:17:44.589  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.590  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.590  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.590  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:44.590  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:44.590  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.590  6660  6739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec97982 not in the list
09-07 13:17:44.590  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.590  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.591  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:17:44.591  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:17:44.591  6660  6739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:17:44.591  6660  6739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@352c88c9 removed from the list
09-07 13:17:44.591  6660  6739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:17:44.591  6660  6739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:17:44.591  6660  6739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:17:44.591  6660  6739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:17:44.591  6660  6739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdb20d0 removed from the list
09-07 13:17:44.592  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 13:17:44.592  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: tru,e - Start operation: Should start/stop everything
09-07 13:17:44.592  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 13:17:44.593  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:17:44.593  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 13:17:44.593  6660  6739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 13:17:44.601  6660  8114 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: My test thread name)
09-07 13:17:44.602  6660  8114 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: My test thread name)
09-07 13:17:44.602  6660  8114 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 13:17:44.602  8073  8073 W ExternalStrings: load override strings
09-07 13:17:44.602  8073  8073 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 13:17:44.602  8073  8073 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-07 13:17:44.604  8073  8073 D StatusProvider: onCreate
09-07 13:17:44.604  6660  8115 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 872, name: My test thread name)
09-07 13:17:44.604  6660  8115 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 872, thread name: My test thread name)
09-07 13:17:44.604  6660  8115 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 872, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 13:17:44.606  6660  6739 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-07 13:17:44.606  6660  6739 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-07 13:17:44.606  6660  6739 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-07 13:17:44.606  6660  6739 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 13:17:44.606  6660  6739 D com.test.thalitest.ThaliTestRunner: Total duration: 22827 ms
09-07 13:17:44.607  6660  6739 I jxcore-log: *Native tests were executed*
09-07 13:17:44.607  6660  6739 I jxcore-log: 
09-07 13:17:44.608  6660  6739 I jxcore-log: Total number of executed tests:  80
09-07 13:17:44.608  6660  6739 I jxcore-log: 
09-07 13:17:44.608  6660  6739 I jxcore-log: Number of passed tests:  80
09-07 13:17:44.608  6660  6739 I jxcore-log: 
09-07 13:17:44.608  6660  6739 I jxcore-log: Number of failed tests:  0
09-07 13:17:44.608  6660  6739 I jxcore-log: 
09-07 13:17:44.608  6660  6739 I jxcore-log: Number of ignored tests:  0
09-07 13:17:44.608  6660  6739 I jxcore-log: 
09-07 13:17:44.609  6660  6739 I jxcore-log: Total duration:  22827
09-07 13:17:44.609  6660  6739 I jxcore-log: 
09-07 13:17:44.609  6660  6739 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 13:17:44.609  6660  6739 I jxcore-log: 
09-07 13:17:44.611  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:17:44.611  6660  6739 I jxcore-log: 
09-07 13:17:44.615  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:17:44.615  6660  6739 I jxcore-log: 
09-07 13:17:44.616  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:17:44.616  6660  6739 I jxcore-log: 
09-07 13:17:44.617  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:17:44.617  6660  6739 I jxcore-log: 
09-07 13:17:44.618  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:17:44.618  6660  6739 I jxcore-log: 
,09-07 13:17:44.619  6660  6660 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 13:17:44.620  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:17:44.620  6660  6739 I jxcore-log: 
09-07 13:17:44.623  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 13:17:44.623  6660  6739 I jxcore-log: 
09-07 13:17:44.624  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 13:17:44.624  6660  6739 I jxcore-log: 
09-07 13:17:44.625  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 13:17:44.625  6660  6739 I jxcore-log: 
09-07 13:17:44.626  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 13:17:44.626  6660  6739 I jxcore-log: 
09-07 13:17:44.626  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 13:17:44.626  6660  6739 I jxcore-log: 
09-07 13:17:44.628  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 13:17:44.628  6660  6739 I jxcore-log: 
09-07 13:17:44.628  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 13:17:44.628  6660  6739 I jxcore-log: 
09-07 13:17:44.629  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 13:17:44.629  6660  6739 I jxcore-log: 
09-07 13:17:44.629  8109  8109 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 13:17:44.629  8109  8109 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 13:17:44.629  8109  8109 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 13:17:44.630  8109  8109 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-07 13:17:44.630  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 13:17:44.630  6660  6739 I jxcore-log: 
09-07 13:17:44.630  8109  8109 D dhcpcd  : wlan0: sending REQUEST (xid 0x1b6e11f6), next in 3.17 seconds
09-07 13:17:44.630  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 13:17:44.630  6660  6739 I jxcore-log: 
09-07 13:17:44.631  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 13:17:44.631  6660  6739 I jxcore-log: 
09-07 13:17:44.631  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 13:17:44.631  6660  6739 I jxcore-log: 
09-07 13:17:44.632  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 13:17:44.632  6660  6739 I jxcore-log: 
09-07 13:17:44.632  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 13:17:44.,632  6660  6739 I jxcore-log: 
09-07 13:17:44.633  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 13:17:44.633  6660  6739 I jxcore-log: 
09-07 13:17:44.633  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 13:17:44.633  6660  6739 I jxcore-log: 
09-07 13:17:44.634  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 13:17:44.634  6660  6739 I jxcore-log: 
09-07 13:17:44.634  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:17:44.634  6660  6739 I jxcore-log: 
09-07 13:17:44.635  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:17:44.635  6660  6739 I jxcore-log: 
09-07 13:17:44.636  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:17:44.636  6660  6739 I jxcore-log: 
09-07 13:17:44.636  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:17:44.636  6660  6739 I jxcore-log: 
09-07 13:17:44.637  6660  6739 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:17:44.637  6660  6739 I jxcore-log: 
,09-07 13:17:44.647  7729  7844 D UEI.SmartControl: Internal timer expired: 3
09-07 13:17:44.647  7729  7844 D UEI.SmartControl: unbind internal service
09-07 13:17:44.649  7729  7729 D UEI.SmartControl: Service.onUnbind: IControl
,09-07 13:17:44.649  7729  7729 D UEI.SmartControl: Service.onDestroy
09-07 13:17:44.649  7729  7729 D UEI.SmartControl: Lock is in USE false
09-07 13:17:44.650  7729  7729 D UEI.SmartControl: unbind internal service
09-07 13:17:44.650  7729  7729 D serial_port: close(fd = 24)
09-07 13:17:44.655  7729  7729 I UEI.SmartControl: Serial port is closed.
09-07 13:17:44.655  7729  7729 I UEI.SmartControl: Serial port is closed.
09-07 13:17:44.655  7729  7729 D UEI.SmartControl: Blaster closed
09-07 13:17:44.655  7729  7729 D UEI.SmartControl: Shut down QS...
09-07 13:17:44.655  7729  7729 D UEI.SmartControl: Stopping QS lib
09-07 13:17:44.656  7729  7729 D UEI.SmartControl: QS lib stop result = true
09-07 13:17:44.656  7729  7729 D UEI.SmartControl: Stopped QS lib
09-07 13:17:44.656  7729  7729 D UEI.SmartControl: QS shutdown complete
09-07 13:17:44.659  8073  8073 V Signer  : override build config not found
09-07 13:17:44.659  8073  8073 D Signer  : value of property debug is false
,09-07 13:17:44.684  8109  8109 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-07 13:17:44.719  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,09-07 13:17:44.720  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-07 13:17:44.721  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-07 13:17:44.722  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-07 13:17:44.723  8109  8109 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-07 13:17:44.723  8109  8109 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-07 13:17:44.723  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-07 13:17:44.723  8109  8109 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-07 13:17:44.723  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-07 13:17:44.724  8109  8109 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-07 13:17:44.724  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-07 13:17:44.724  8109  8109 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 13:17:44.724  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-07 13:17:44.724  8109  8109 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 13:17:44.724  8109  8109 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 13:17:44.724  8109  8109 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-07 13:17:44.724  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-07 13:17:44.725  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-07 13:17:44.725  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-07 13:17:44.725  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-07 13:17:44.725  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-07 13:17:44.741  8073  8073 V LGMDMManager: Create singleton instance
,09-07 13:17:44.815  8073  8073 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-07 13:17:44.873  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 13:17:44.876  8073  8136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 13:17:44.889  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:44.895  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:44.921  1034  1836 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8145 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-07 13:17:44.921  1034  1836 I ActivityManager: Killing 7179:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-07 13:17:44.946  8118  8118 D AndroidRuntime: 
09-07 13:17:44.946  8118  8118 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-07 13:17:44.950  8118  8118 D AndroidRuntime: CheckJNI is OFF
09-07 13:17:44.957  1034  8098 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-07 13:17:44.958  1034  8098 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-07 13:17:44.958  1034  8098 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 13:17:44.958  1034  8098 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-07 13:17:44.958  1034  8098 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-07 13:17:44.958  1034  8098 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 13:17:44.958  1034  8098 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-07 13:17:44.958  1034  8098 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-07 13:17:44.958  1034  8098 D DhcpStateMachine: RunningState
,09-07 13:17:45.034  8073  8135 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-07 13:17:45.144  8118  8118 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 13:17:45.158  1034  1057 W libprocessgroup: failed to open /acct/uid_10093/pid_7179/cgroup.procs: No such file or directory
,09-07 13:17:45.166  1034  1098 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-07 13:17:45.168  1034  1098 I ActivityManager: Killing 6660:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-07 13:17:45.234  1034  2015 I WindowState: WIN DEATH: Window{9e307f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 13:17:45.235  1034  1528 D WifiService: Client connection lost with reason: 4
,09-07 13:17:45.242  1034  2015 D InputDispatcher: Window went away: Window{9e307f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 13:17:45.270  8145  8145 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 13:17:45.383  1034  1098 I ActivityManager:   Force finishing activity ActivityRecord{3fa4f645 u0 com.test.thalitest/.MainActivity t6}
,09-07 13:17:45.409   331   345 E GBMv2   : DFP En is all cleared set to be enabled
09-07 13:17:45.410  1034  1909 W ActivityManager: Spurious death for ProcessRecord{24597fe0 6660:com.test.thalitest/u0a118}, curProc for 6660: null
09-07 13:17:45.411  1034  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-07 13:17:45.416  1034  1123 I ActivityManager:   Force finishing activity ActivityRecord{3fa4f645 u0 com.test.thalitest/.MainActivity t6 f}
09-07 13:17:45.416  1034  1123 W ActivityManager: Duplicate finish request for ActivityRecord{3fa4f645 u0 com.test.thalitest/.MainActivity t6 f}
,09-07 13:17:45.477  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,09-07 13:17:45.477  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b71d5d5 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-07 13:17:45.480  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-07 13:17:45.480  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{165d21ea co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-07 13:17:45.490  2019  2019 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-07 13:17:45.492  2019  2019 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,09-07 13:17:45.495  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-07 13:17:45.496  2019  2088 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-07 13:17:45.498  8145  8145 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-07 13:17:45.500  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-07 13:17:45.502  2732  2732 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-07 13:17:45.502  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-07 13:17:45.503  7630  7630 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-07 13:17:45.503  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-07 13:17:45.509  2484  2622 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 13:17:45.510  4504  4504 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-07 13:17:45.510  4504  4504 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-07 13:17:45.510  4504  4504 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-07 13:17:45.510  4504  4504 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-07 13:17:45.510  4504  4504 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 13:17:45.510  4504  4504 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 13:17:45.510  4504  4504 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 13:17:45.511  4504  4504 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 13:17:45.511  4504  4504 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:17:45.511  4504  4504 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:17:45.511  4504  4504 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 13:17:45.511  4504  4504 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-07 13:17:45.526  1034  1446 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 13:17:45.530  4612  4612 I art     : Explicit concurrent mark sweep GC freed 8198(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 450us total 48.991ms
,09-07 13:17:45.543  1034  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-07 13:17:45.553  1034  1909 V SIM_STK : Menu title from STK is T-Mobile
09-07 13:17:45.589  1034  1034 D administrator: Handling package changes for user 0
,09-07 13:17:45.598  1891  1891 D ActionManagerService: notifyUserLog: 1000003
09-07 13:17:45.598  2732  4476 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-07 13:17:45.599  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-07 13:17:45.611  2019  2019 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,09-07 13:17:45.622  2019  2019 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-07 13:17:45.628  1587  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 13:17:45.628  1587  1646 D KeyguardModel: createShortcutInfo...
,09-07 13:17:45.642  8145  8145 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-07 13:17:45.642  8145  8145 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-07 13:17:45.642  8145  8145 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,09-07 13:17:45.643  8145  8145 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-07 13:17:45.643  8145  8145 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-07 13:17:45.644  8145  8145 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-07 13:17:45.649  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-07 13:17:45.649  2019  2019 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-07 13:17:45.651  1587  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 13:17:45.651  1587  1646 D KeyguardModel: createShortcutInfo...
09-07 13:17:45.654  1891  1891 D ActionManagerService: notifyUserLog: 1000004
09-07 13:17:45.654  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-07 13:17:45.655  2732  4476 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-07 13:17:45.656  2732  2757 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262123
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , expire_time: 0
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , display: false
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , animation: false }
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262287
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , expire_time: 0
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , display: false
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , animation: false }
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , create_time: 1472828323917
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , expire_time: 0
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , display: false
09-07 13:17:45.658  2019  2019 I GBoardWebViewUtils: , animation: false }
09-07 13:17:45.660  8145  8145 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-07 13:17:45.663  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-07 13:17:45.664  1854  1854 D SplitUIService: removed split : 
09-07 13:17:45.666  2019  8195 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-07 13:17:45.666  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-07 13:17:45.668  1587  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 13:17:45.668  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-07 13:17:45.669  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-07 13:17:45.674  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 13:17:45.674  1587  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 13:17:45.676  1587  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 13:17:45.676  1587  1646 D KeyguardModel: createShortcutInfo...
09-07 13:17:45.680  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-07 13:17:45.680  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 13:17:45.681  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 13:17:45.681  1587  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 13:17:45.682  1587  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 13:17:45.682  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 13:17:45.682  1587  1646 D KeyguardModel: createShortcutInfo...
09-07 13:17:45.683  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-07 13:17:45.683  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-07 13:17:45.683  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-07 13:17:45.686  1587  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:17:45.687  1587  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 13:17:45.687  8073  8135 D LgDataFeature: LgDataFeature() Constructor: none
09-07 13:17:45.687  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-07 13:17:45.687  8073  8135 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 13:17:45.687  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 13:17:45.690  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 13:17:45.690  1587  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 13:17:45.693  1587  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 13:17:45.693  1587  1646 D KeyguardModel: createShortcutInfo...
,09-07 13:17:45.708  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-07 13:17:45.708  1854  1854 I SplitUIService: split app #11
09-07 13:17:45.708  1034  1998 V SIM_STK : Menu title from STK is T-Mobile
09-07 13:17:45.708  1034  1998 V SIM_STK : Menu title from STK is T-Mobile
,09-07 13:17:45.710  1587  1587 D KeyguardModel: handleShortcutListChanged...
09-07 13:17:45.710  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-07 13:17:45.714  1587  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 13:17:45.714  1587  1646 D KeyguardModel: createShortcutInfo...
09-07 13:17:45.718  8145  8145 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 13:17:45.719  8145  8145 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:45.728  1587  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 13:17:45.728  1587  1646 D KeyguardModel: createShortcutInfo...
09-07 13:17:45.730  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 13:17:45.730  1587  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 13:17:45.731  1587  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 13:17:45.731  1587  1646 D KeyguardModel: createShortcutInfo...
09-07 13:17:45.732  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 13:17:45.733  1587  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 13:17:45.738  1587  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 13:17:45.738  1587  1646 D KeyguardModel: createShortcutInfo...
,09-07 13:17:45.755  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 13:17:45.755  1587  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-07 13:17:45.757  1587  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 13:17:45.757  1587  1646 D KeyguardModel: createShortcutInfo...
09-07 13:17:45.758  1034  1836 V SIM_STK : Menu title from STK is T-Mobile
09-07 13:17:45.760  1034  2037 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-07 13:17:45.760  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-07 13:17:45.760  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-07 13:17:45.760  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-07 13:17:45.760  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 13:17:45.760  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 13:17:45.760  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 13:17:45.760  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 13:17:45.760  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 13:17:45.760  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-07 13:17:45.760  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 13:17:45.760  7630  7630 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 13:17:45.763  8145  8145 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 13:17:45.764  8145  8145 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-07 13:17:45.765  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:45.765  8073  8136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 13:17:45.767  8145  8145 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-07 13:17:45.773  2019  2019 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,09-07 13:17:45.783  1587  1587 D KeyguardModel: handleShortcutListChanged...
09-07 13:17:45.783  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-07 13:17:45.795  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:45.808  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-07 13:17:45.808  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 13:17:45.808  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 13:17:45.813  1034  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,09-07 13:17:45.829  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:45.843  8145  8145 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 13:17:45.845  8145  8145 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:45.849  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-07 13:17:45.851  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 13:17:45.852  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-07 13:17:45.854  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-07 13:17:45.854  8145  8145 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 13:17:45.855  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-07 13:17:45.856  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-07 13:17:45.860  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-07 13:17:45.862  6782  6782 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-07 13:17:45.864  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:45.865  8073  8136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-07 13:17:45.869  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 13:17:45.872  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-07 13:17:45.872  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 13:17:45.878   325   410 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-07 13:17:45.879  3211  8203 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-07 13:17:45.880  2019  2143 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-07 13:17:45.880  2019  2143 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,09-07 13:17:45.881  1034  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3541d53e u0 com.lge.launcher2/.Launcher t5} time:212038
09-07 13:17:45.889  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-07 13:17:45.890  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-07 13:17:45.890  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 13:17:45.891  1034  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 13:17:45.894  1034  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-07 13:17:45.897  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:45.898  2019  2019 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-07 13:17:45.899  2575  2575 D [Concierge]Service: onStartCommand(). Type : 8
09-07 13:17:45.899  2575  2575 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-07 13:17:45.901  2575  2575 D [Concierge]Service: Update widget ID : 11
09-07 13:17:45.901  8145  8145 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:45.901  8145  8145 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:45.901  2019  2019 D [Concierge]WidgetView: change position of spinner
09-07 13:17:45.901  8145  8145 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 13:17:45.903  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 13:17:45.903  6782  6782 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 13:17:45.903  6782  6782 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 13:17:45.904  6782  6782 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 13:17:45.904  1034  1522 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-07 13:17:45.904  1034  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 13:17:45.904  1034  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 13:17:45.905  1034  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 13:17:45.905  1034  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 13:17:45.906  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 13:17:45.906  2019  2019 I [Concierge]WidgetView: initWebView(). Time : 1473247065906
09-07 13:17:45.906  2575  2575 D [Concierge]Service: onStartCommand(). Type : 0
09-07 13:17:45.906  1034  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 13:17:45.907  8073  8135 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-07 13:17:45.907  1034  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-07 13:17:45.907  1034  1529 D ConnectivityService: identical MTU - not setting
09-07 13:17:45.907  1034  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-07 13:17:45.907  1034  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-07 13:17:45.907  6782  6782 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 13:17:45.907  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 13:17:45.907  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-07 13:17:45.907  1034  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:45.907  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 13:17:45.907  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 13:17:45.907  6782  6782 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 13:17:45.907  6782  6782 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-07 13:17:45.907  1034  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 13:17:45.907  6782  6782 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 13:17:45.909  1587  1817 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-07 13:17:45.909  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:45.911  8073  8136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 13:17:45.912  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 13:17:45.915  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 13:17:45.921  8145  8145 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:45.921  8145  8145 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:45.921  8145  8145 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 13:17:45.923  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:45.923  8073  8136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 13:17:45.924  8073  8135 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-07 13:17:45.928  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:45.930  2019  2019 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 385527309
09-07 13:17:45.930  2019  2019 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-07 13:17:45.931  8073  8135 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-07 13:17:45.931  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-07 13:17:45.931  8073  8135 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-07 13:17:45.933  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:45.933  8073  8135 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-07 13:17:45.933  8073  8135 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-07 13:17:45.934  8073  8135 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-07 13:17:45.934  2019  2019 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@16f11151
09-07 13:17:45.934  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-07 13:17:45.935  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-07 13:17:45.935  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 13:17:45.937  8073  8135 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-07 13:17:45.937  8145  8145 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:45.937  8145  8145 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:45.937  8145  8145 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 13:17:45.938  8073  8135 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-07 13:17:45.939  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:45.939  8073  8136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 13:17:45.940  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,09-07 13:17:45.940  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-07 13:17:45.942  2019  2019 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-07 13:17:45.942  2019  2019 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-07 13:17:45.944  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 13:17:45.946  1034  1123 I art     : Explicit concurrent mark sweep GC freed 80315(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.717ms total 295.165ms
09-07 13:17:45.946  2019  2019 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473246882087, New one : 1473247065906
09-07 13:17:45.946  2019  2019 D [Concierge]WidgetView: Unregister all receivers
09-07 13:17:45.946  2019  2019 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-07 13:17:45.947  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 13:17:45.948  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-07 13:17:45.949  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:45.949  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,09-07 13:17:45.950  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-07 13:17:45.952  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-07 13:17:45.953  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-07 13:17:45.953  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 13:17:45.954  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 13:17:45.961  8145  8145 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:45.961  8145  8145 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:45.962  8145  8145 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 13:17:45.963  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 13:17:45.964  8073  8136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-07 13:17:46.002  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-07 13:17:46.006  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 13:17:46.012  2019  2019 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-07 13:17:46.012  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-07 13:17:46.014  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 13:17:46.016  8118  8118 D AndroidRuntime: Shutting down VM
,09-07 13:17:46.022  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 13:17:46.029  8145  8145 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:46.029  8145  8145 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 13:17:46.029  8145  8145 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 13:17:46.034  2019  2019 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d20f07e time:212191
09-07 13:17:46.036  8073  8136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 13:17:46.037  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:46.045  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:46.050  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:46.054  8145  8145 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:46.054  8145  8145 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:46.058  8145  8145 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 13:17:46.060  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:46.077  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 13:17:46.081  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 13:17:46.085  8145  8145 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:46.085  8145  8145 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:46.086  8145  8145 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 13:17:46.087  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:46.090  8027  8027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-07 13:17:46.092  8027  8027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-07 13:17:46.094  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 13:17:46.097  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 13:17:46.100  8145  8145 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:46.101  8145  8145 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:46.101  8145  8145 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 13:17:46.101  8145  8145 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 13:17:46.102  8145  8145 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-07 13:17:46.105  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:46.107  8027  8027 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-07 13:17:46.107  8027  8027 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-07 13:17:46.109  6782  6782 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 13:17:46.112  6782  6782 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 13:17:46.116  8145  8145 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 13:17:46.116  8145  8145 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 13:17:46.117  8145  8145 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 13:17:46.117  8145  8145 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 13:17:46.117  8145  8145 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 13:17:46.119  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 13:17:46.120  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-07 13:17:46.122  1800  1800 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-07 13:17:46.126  2227  2227 I ConfigService: onCreate
09-07 13:17:46.126  2227  2227 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-07 13:17:46.128  1800  1800 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-07 13:17:46.130  2227  2227 I ConfigService: onBind returning update interface
09-07 13:17:46.131  2227  2227 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 13:17:46.131  2227  2227 I ConfigService: onBind returning config service
09-07 13:17:46.147  2227  2227 I ConfigService: onDestroy
,09-07 13:17:46.149  1800  8212 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-07 13:17:46.156  2019  2019 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-07 13:17:46.164  1800  8219 I PeopleContactsSync: CP2 sync disabled
,09-07 13:17:46.166  5920  8218 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-07 13:17:46.168  1800  4768 I Icing   : doRemovePackageData com.test.thalitest
09-07 13:17:46.185  1800  8217 W GmsApplication: Using Auth Proxy for data requests.
,09-07 13:17:46.188  1800  8217 W GmsApplication: Using Auth Proxy for data requests.
,09-07 13:17:46.213  2019  2862 I GBoardtInterface: onReloaded()
,09-07 13:17:46.215  2019  2019 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-07 13:17:46.216  2732  2776 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 13:17:46.218  2732  2759 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 13:17:46.224  1891  1891 D ActionManagerService: notifyUserLog: 1000001
09-07 13:17:46.225  2732  4476 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,09-07 13:17:46.225  2732  4476 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,09-07 13:17:46.228  1891  1891 D ActionManagerService: notifyUserLog: 1000001
09-07 13:17:46.229  2732  4476 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-07 13:17:46.229  2732  4476 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-07 13:17:46.229  2732  4476 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-07 13:17:46.229  2732  4476 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-07 13:17:46.230  2732  2759 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 13:17:46.234  7001  7001 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-07 13:17:46.251  2227  2351 I art     : Explicit concurrent mark sweep GC freed 6139(368KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 873us total 16.950ms
,09-07 13:17:46.266  1034  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8222 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-07 13:17:46.273  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-07 13:17:46.273  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-07 13:17:46.275  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-07 13:17:46.275  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-07 13:17:46.278  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
,09-07 13:17:46.279  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,09-07 13:17:46.280  2332  8238 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-07 13:17:46.297  1034  1944 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8241 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-07 13:17:46.339  1034  1836 I ActivityManager: Killing 7225:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-07 13:17:46.346  8241  8241 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:17:46.346  8241  8241 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 13:17:46.347  8241  8241 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 13:17:46.347  8241  8241 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.jav,a:372)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 13:17:46.383  8241  8241 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 13:17:46.384  8241  8241 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:17:46.384  8241  8241 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
,09-07 13:17:46.384  8241  8241 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 13:17:46.384  8241  8241 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 13:17:46.384  8241  8241 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 13:17:46.384  8241  8241 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:17:46.384  8241  8241 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:17:46.384  8241  8241 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 13:17:46.384  8241  8241 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-07 13:17:46.388  8241  8241 E SQLite,Database: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 13:17:46.388  8241  8241 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 13:17:46.388  8241  8241 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-07 13:17:46.389  8241  8241 E AndroidRuntime: FATAL EXCEPTION: main
09-07 13:17:46.389  8241  8241 E AndroidRuntime: Process: com.lge.email, PID: 8241
09-07 13:17:46.389  8241  8241 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: Caused by: an,droid.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-07 13:17:46.389  8241  8241 E AndroidRuntime: 	... 11 more
09-07 13:17:46.393  1034  1980 W libprocessgroup: failed to open /acct/uid_10005/pid_7225/cgroup.procs: No such file or directory
09-07 13:17:46.399  1034  2015 I ActivityManager: Killing 7658:com.google.android.talk/u0a72 (adj 15): empty #17

```
