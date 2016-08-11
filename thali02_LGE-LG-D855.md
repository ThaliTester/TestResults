#### Test 8091287736177d0_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-11 09:35:00.106  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-11 09:35:00.107  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 09:35:00.107  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-11 09:35:00.108  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,08-11 09:35:00.122  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 09:35:00.122  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
08-11 09:35:00.125  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
08-11 09:35:00.126  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
08-11 09:35:00.429  6766  6766 D AndroidRuntime: 
08-11 09:35:00.429  6766  6766 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 09:35:00.437  6766  6766 D AndroidRuntime: CheckJNI is OFF
08-11 09:35:00.638  6766  6766 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 09:35:00.649  1034  1928 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 09:35:00.664  1967  3453 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-11 09:35:00.669  1034  1928 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-11 09:35:00.671  1034  1928 D ActivityManager: setTaskToReturnTo : TaskRecord{a7e510f #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 09:35:00.671  1034  1928 D ActivityManager: setTaskToReturnTo : TaskRecord{a7e510f #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 09:35:00.673  1034  1928 D WindowStateEx: AppWindowTokenEx init.. 
08-11 09:35:00.674   349   365 E GBMv2   : DFP En is all cleared set to be enabled
08-11 09:35:00.702  1034  1928 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6781 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 09:35:00.704  6766  6766 D AndroidRuntime: Shutting down VM
08-11 09:35:00.774  1967  3453 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-11 09:35:00.775  1967  3453 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3e27fec5 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 09:35:00.776  1967  1983 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-11 09:35:00.776  1967  1983 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3805b01a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
,08-11 09:35:00.835  6781  6781 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-11 09:35:00.929  6781  6781 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-11 09:35:00.938  6781  6781 I LibraryLoader: Loading: webviewchromium
08-11 09:35:00.941  6781  6781 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1596-1600)
,08-11 09:35:00.941  6781  6781 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 09:35:00.957  6781  6781 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3ace9bb}
,08-11 09:35:00.959  6781  6781 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 09:35:00.959  6781  6781 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 09:35:00.969  6781  6781 I BrowserStartupController: Initializing chromium process, renderers=0
,08-11 09:35:00.970  6781  6781 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:35:00.980  6781  6781 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-11 09:35:00.981  6781  6781 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46780 len=2953
,08-11 09:35:00.983  6781  6781 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:32 off:229536 len:643667
08-11 09:35:00.987   323  1384 V AudioPolicyService: registerClient() client 0xb558a860, uid 10118
08-11 09:35:00.991  1034  1110 D BluetoothManagerService: Message: 20
08-11 09:35:00.992  1034  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a6c0d21:true
08-11 09:35:01.001  6781  6781 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 09:35:01.001  6781  6781 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 09:35:01.001  6781  6781 I Adreno-EGL: Build Date: 12/12/14 금
08-11 09:35:01.001  6781  6781 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 09:35:01.001  6781  6781 I Adreno-EGL: Remote Branch: 
08-11 09:35:01.001  6781  6781 I Adreno-EGL: Local Patches: 
08-11 09:35:01.001  6781  6781 I Adreno-EGL: Reconstruct Branch: 
,08-11 09:35:01.071  6781  6816 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-11 09:35:01.077  6781  6781 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-11 09:35:01.096  6781  6781 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 09:35:01.102  6781  6781 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-11 09:35:01.105  6781  6781 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-11 09:35:01.109  6781  6781 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 09:35:01.109  6781  6781 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-11 09:35:01.125  6781  6781 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-11 09:35:01.132  6781  6781 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:35:01.132  6781  6781 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 09:35:01.163  6781  6828 D OpenGLRenderer: Render dirty regions requested: true
08-11 09:35:01.163  6781  6828 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 09:35:01.171  6781  6828 D OpenGLRenderer: Enabling debug mode 0
,08-11 09:35:01.184  6781  6781 D Atlas   : Validating map...
,08-11 09:35:01.188  1034  2058 D SplitWindow: check instance of lgWin Window{28027093 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:35:01.225  6781  6826 D LgDataFeature: LgDataFeature() Constructor: none
08-11 09:35:01.226  6781  6826 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 09:35:01.320  1034  1111 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +546ms (total +645ms)
08-11 09:35:01.321  1034  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3515459c u0 com.test.thalitest/.MainActivity t6} time:181980
,08-11 09:35:01.324  6781  6781 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@39b997c6 time:181983
08-11 09:35:01.419  6781  6781 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 09:35:01.524  6781  6826 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-11 09:35:01.524  6781  6826 I chromium: 
,08-11 09:35:01.660  6781  6839 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-11 09:35:01.675  6781  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 09:35:01.675  6781  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 09:35:01.675  6781  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 09:35:01.675  6781  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 09:35:01.675  6781  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 09:35:01.675  6781  6839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f19f1aa added. We now have 1 listener(s)
08-11 09:35:01.681  1034  1966 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 09:35:01.685  6781  6781 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-11 09:35:01.685  6781  6781 I chromium: 
08-11 09:35:01.687  6781  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-11 09:35:01.693  6781  6839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 09:35:01.696  6781  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 09:35:01.697  6781  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-11 09:35:01.712  6781  6839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6dd11 added. We now have 1 listener(s)
08-11 09:35:01.713  6781  6839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 09:35:01.719  1034  1546 D WifiService: New client listening to asynchronous messages
08-11 09:35:01.723  6781  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 09:35:01.723  6781  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 09:35:01.726  6781  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 09:35:01.726  6781  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 09:35:01.726  6781  6839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-11 09:35:01.733  6781  6839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 09:35:01.734  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 09:35:01.735  6781  6839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-11 09:35:01.743  6781  6839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-11 09:35:01.743  6781  6839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:35:01.743  6781  6839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:35:01.743  6781  6839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 09:35:01.743  6781  6839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:35:01.743  6781  6839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:35:01.743  6781  6839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:35:01.743  6781  6839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:35:01.743  6781  6839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 09:35:01.743  6781  6839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 09:35:01.744  6781  6839 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 09:35:01.747  6781  6781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 09:35:01.749  6781  6781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 09:35:01.750  6781  6839 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 09:35:01.786  6781  6781 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 09:35:02.112   349   367 E GBMv2   : DFP En is all cleared set to be enabled
08-11 09:35:02.113   349   367 E GBMv2   : Set value is all cleared set the max
08-11 09:35:02.113   349   367 I GBMv2   : DFP Enabled. Ignore VFP set
,08-11 09:35:02.523  6781  6842 W jxcore-log: Initializing JXcore engine
08-11 09:35:02.523  6781  6842 W jxcore-log: JXcore engine is ready
,08-11 09:35:02.558  6842  6842 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8532]" dev="sockfs" ino=8532 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 09:35:02.558  6842  6842 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-11 09:35:02.558  6842  6842 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10327]" dev="sockfs" ino=10327 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 09:35:02.558  6842  6842 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-11 09:35:02.558  6842  6842 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32018]" dev="sockfs" ino=32018 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-11 09:35:02.572  6781  6842 W jxcore-log: Starting JXcore engine
,08-11 09:35:02.648  6781  6842 W jxcore-log: Platform android
08-11 09:35:02.648  6781  6842 W jxcore-log: 
,08-11 09:35:02.648  6781  6842 W jxcore-log: Process ARCH arm
08-11 09:35:02.648  6781  6842 W jxcore-log: 
08-11 09:35:02.814  6781  6842 I jxcore-log: JXcore Cordova bridge is ready!
08-11 09:35:02.814  6781  6842 I jxcore-log: 
08-11 09:35:02.814  6781  6842 W jxcore-log: JXcore engine is started
,08-11 09:35:02.822  6781  6839 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-11 09:35:02.825  6781  6781 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 09:35:12.690  6781  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 09:35:12.690  6781  6842 I jxcore-log: 
,08-11 09:35:12.693  6781  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 09:35:12.693  6781  6842 I jxcore-log: 
08-11 09:35:12.698  6781  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:35:12.698  6781  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:35:12.698  6781  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 09:35:12.698  6781  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:35:12.698  6781  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:35:12.698  6781  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:35:12.698  6781  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:35:12.698  6781  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 09:35:12.701  6781  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 09:35:12.704  6781  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 09:35:12.704  6781  6842 I jxcore-log: 
08-11 09:35:12.706  6781  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 09:35:12.706  6781  6842 I jxcore-log: 
,08-11 09:35:13.030  6781  6842 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-11 09:35:13.030  6781  6842 I jxcore-log: Failed to execute UT.
08-11 09:35:13.030  6781  6842 I jxcore-log: 
08-11 09:35:13.031  6781  6842 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 09:35:13.031  6781  6842 I jxcore-log: 
,08-11 09:35:13.039  6781  6842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 09:35:13.039  6781  6842 I jxcore-log: 
08-11 09:35:13.039  6781  6781 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-11 09:35:13.362  6843  6843 D AndroidRuntime: 
08-11 09:35:13.362  6843  6843 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-11 09:35:13.366  6843  6843 D AndroidRuntime: CheckJNI is OFF
08-11 09:35:13.519  6843  6843 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 09:35:13.535  1034  1095 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-11 09:35:13.536  1034  1095 I ActivityManager: Killing 6781:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-11 09:35:13.596  1034  1966 I WindowState: WIN DEATH: Window{28027093 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:35:13.597  1034  1546 D WifiService: Client connection lost with reason: 4
08-11 09:35:13.603  1034  1966 D InputDispatcher: Window went away: Window{28027093 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 09:35:13.652  1034  1095 I ActivityManager:   Force finishing activity ActivityRecord{3515459c u0 com.test.thalitest/.MainActivity t6}
,08-11 09:35:13.677   349   365 E GBMv2   : DFP En is all cleared set to be enabled
08-11 09:35:13.686  1034  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-11 09:35:13.698  1034  1123 I ActivityManager:   Force finishing activity ActivityRecord{3515459c u0 com.test.thalitest/.MainActivity t6 f}
08-11 09:35:13.698  1034  1123 W ActivityManager: Duplicate finish request for ActivityRecord{3515459c u0 com.test.thalitest/.MainActivity t6 f}
,08-11 09:35:13.741  1034  1965 W ActivityManager: Spurious death for ProcessRecord{3c92b001 6781:com.test.thalitest/u0a118}, curProc for 6781: null
08-11 09:35:13.742  2078  2078 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-11 09:35:13.742  1967  1983 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-11 09:35:13.742  1967  1983 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2430174b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 09:35:13.743  1967  1982 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-11 09:35:13.743  2078  2078 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-11 09:35:13.744  1967  1982 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1e94f528 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 09:35:13.747  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-11 09:35:13.751  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-11 09:35:13.752  2078  2194 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-11 09:35:13.758  1034  1461 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-11 09:35:13.765  2021  2021 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-11 09:35:13.767  3835  3835 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-11 09:35:13.770  3891  3891 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-11 09:35:13.770  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-11 09:35:13.775  2506  2608 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 09:35:13.797  4487  4487 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 09:35:13.798  4487  4487 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-11 09:35:13.798  4487  4487 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-11 09:35:13.798  4487  4487 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-11 09:35:13.798  4487  4487 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 09:35:13.798  4487  4487 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 09:35:13.798  4487  4487 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 09:35:13.798  4487  4487 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 09:35:13.798  4487  4487 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 09:35:13.798  4487  4487 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 09:35:13.798  4487  4487 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 09:35:13.798  4487  4487 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-11 09:35:13.827  1930  1930 D ActionManagerService: notifyUserLog: 1000003
08-11 09:35:13.827  2078  2078 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-11 09:35:13.828  3835  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-11 09:35:13.829  2078  2078 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-11 09:35:13.831  2078  2078 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-11 09:35:13.832  2078  2078 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-11 09:35:13.834  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-11 09:35:13.835  1034  1092 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-11 09:35:13.869  4598  4598 I art     : Explicit concurrent mark sweep GC freed 476(32KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 460us total 135.653ms
,08-11 09:35:13.887  1606  1606 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-11 09:35:13.893  1034  2058 V SIM_STK : Menu title from STK is T-Mobile
08-11 09:35:13.922  1606  1606 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 09:35:13.922  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-11 09:35:13.923  1894  1894 D SplitUIManager: split_name #11 / not available #0
08-11 09:35:13.924  1894  1894 D SplitUIService: removed split : 
08-11 09:35:13.931  1034  1034 I art     : Explicit concurrent mark sweep GC freed 38595(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 5.105ms total 202.928ms
08-11 09:35:13.932  1034  2002 I art     : WaitForGcToComplete blocked for 98.819ms for cause Explicit
08-11 09:35:13.975  1894  1894 D SplitUIManager: split_name #11 / not available #0
08-11 09:35:13.975  1894  1894 I SplitUIService: split app #11
,08-11 09:35:13.976  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-11 09:35:13.976  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-11 09:35:14.000  1034  1034 D administrator: Handling package changes for user 0
,08-11 09:35:14.031  1034  2002 I art     : Explicit concurrent mark sweep GC freed 4184(264KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.568ms total 99.210ms
08-11 09:35:14.032  1034  1123 I art     : WaitForGcToComplete blocked for 144.483ms for cause Explicit
,08-11 09:35:14.037  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-11 09:35:14.046  1034  2044 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-11 09:35:14.046  1606  1657 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-11 09:35:14.046  1606  1657 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.047  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-11 09:35:14.047  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-11 09:35:14.047  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-11 09:35:14.047  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-11 09:35:14.047  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-11 09:35:14.047  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 09:35:14.048  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-11 09:35:14.048  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-11 09:35:14.048  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-11 09:35:14.048  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 09:35:14.048  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-11 09:35:14.048  2078  2078 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-11 09:35:14.049  1930  1930 D ActionManagerService: notifyUserLog: 1000004
08-11 09:35:14.050  3835  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-11 09:35:14.051  3835  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 09:35:14.053  1606  1657 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 09:35:14.053  1606  1657 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.054  2226  2226 I ConfigService: onCreate
08-11 09:35:14.055  2226  2226 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-11 09:35:14.062  1606  1657 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 09:35:14.062  1606  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 09:35:14.063  1606  1657 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-11 09:35:14.064  1606  1657 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 09:35:14.065  1606  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:35:14.065  1606  1657 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 09:35:14.065  2226  2226 I ConfigService: onBind returning update interface
08-11 09:35:14.066  1606  1657 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 09:35:14.066  1606  1657 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , create_time: 1430832262123
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , expire_time: 0
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , display: false
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , animation: false }
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , create_time: 1430832262287
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , expire_time: 0
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , display: false
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , animation: false }
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , create_time: 1470393743569
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , expire_time: 0
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , display: false
08-11 09:35:14.069  2078  2078 I GBoardWebViewUtils: , animation: false }
08-11 09:35:14.070  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-11 09:35:14.071  2226  2226 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-11 09:35:14.071  2226  2226 I ConfigService: onBind returning config service
08-11 09:35:14.074  1606  1657 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 09:35:14.076  1606  1657 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 09:35:14.078  1818  1818 I ConfigFetchService: service connected
08-11 09:35:14.078  1818  1818 I ConfigClient: service connected
08-11 09:35:14.078  1606  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:35:14.078  1606  1657 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 09:35:14.080  2078  6872 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-11 09:35:14.083  1606  1657 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 09:35:14.083  1606  1657 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.091  2226  2226 I ConfigService: onDestroy
08-11 09:35:14.091  1606  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 09:35:14.091  1606  1657 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-11 09:35:14.091  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 09:35:14.091  1606  1657 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-11 09:35:14.091  1606  1657 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 09:35:14.091  2078  2078 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-11 09:35:14.093  1606  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:35:14.093  1606  1657 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-11 09:35:14.094  1818  6874 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-11 09:35:14.097  1606  1657 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 09:35:14.098  1606  1657 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.105  1606  1606 D KeyguardModel: handleShortcutListChanged...
08-11 09:35:14.105  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-11 09:35:14.133  1606  1657 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 09:35:14.133  1606  1657 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.134  1034  1755 V SIM_STK : Menu title from STK is T-Mobile
,08-11 09:35:14.143  1606  1657 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 09:35:14.143  1606  1657 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.144  1606  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:35:14.144  1606  1657 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 09:35:14.146  1606  1657 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 09:35:14.146  1606  1657 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.146  1606  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:35:14.146  1606  1657 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-11 09:35:14.147  1606  1657 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 09:35:14.147  1606  1657 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.148  1606  1657 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:35:14.148  1606  1657 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 09:35:14.149  1606  1657 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 09:35:14.149  1606  1657 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.153  1818  6881 I PeopleContactsSync: CP2 sync disabled
08-11 09:35:14.164  1606  1606 D KeyguardModel: handleShortcutListChanged...
08-11 09:35:14.164  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-11 09:35:14.175  2078  2078 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-11 09:35:14.176  1818  6880 W GmsApplication: Using Auth Proxy for data requests.
,08-11 09:35:14.182  1818  6880 W GmsApplication: Using Auth Proxy for data requests.
08-11 09:35:14.183  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-11 09:35:14.183  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 09:35:14.184  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 09:35:14.190  1818  4744 I Icing   : doRemovePackageData com.test.thalitest
08-11 09:35:14.190  1034  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-11 09:35:14.191  5919  6879 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-11 09:35:14.192  5992  5992 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-11 09:35:14.215  6552  6552 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-11 09:35:14.222  2326  6884 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-11 09:35:14.234  2021  2021 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-11 09:35:14.234  2021  2021 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-11 09:35:14.236  2021  2021 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-11 09:35:14.238  6455  6455 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-11 09:35:14.264  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-11 09:35:14.267  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:35:14.269  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-11 09:35:14.271  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-11 09:35:14.272  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-11 09:35:14.273  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-11 09:35:14.282  1034  2044 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6886 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-11 09:35:14.289  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-11 09:35:14.289  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:35:14.289  1034  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{27d69a91 u0 com.lge.launcher2/.Launcher t5} time:194949
08-11 09:35:14.289  2078  2298 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-11 09:35:14.289  2078  2298 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-11 09:35:14.303  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-11 09:35:14.304  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 09:35:14.304  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-11 09:35:14.312  2078  2078 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-11 09:35:14.313  2670  2670 D [Concierge]Service: onStartCommand(). Type : 8
08-11 09:35:14.313  2670  2670 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-11 09:35:14.313  2670  2670 D [Concierge]Service: Update widget ID : 11
08-11 09:35:14.315  2078  2078 D [Concierge]WidgetView: change position of spinner
08-11 09:35:14.316  2078  2078 I [Concierge]WidgetView: initWebView(). Time : 1470900914316
08-11 09:35:14.316  2670  2670 D [Concierge]Service: onStartCommand(). Type : 0
,08-11 09:35:14.336  2078  2078 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 887721890
,08-11 09:35:14.336  2078  2078 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-11 09:35:14.336  2078  2078 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-11 09:35:14.339  2078  2078 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@b2c2f79
08-11 09:35:14.339  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-11 09:35:14.341  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 09:35:14.341  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:35:14.345  1034  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 09:35:14.347  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-11 09:35:14.348  2078  2078 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-11 09:35:14.348  2078  2078 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 09:35:14.348  2078  2078 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470900747680, New one : 1470900914316
08-11 09:35:14.348  2078  2078 D [Concierge]WidgetView: Unregister all receivers
08-11 09:35:14.349  2078  2078 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 09:35:14.349  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:35:14.351  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-11 09:35:14.352  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-11 09:35:14.354  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-11 09:35:14.354  1034  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-11 09:35:14.355  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-11 09:35:14.357  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-11 09:35:14.357  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:35:14.358  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:35:14.361  1034  1123 I art     : Explicit concurrent mark sweep GC freed 8962(481KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.656ms total 328.452ms
08-11 09:35:14.363  6886  6886 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-11 09:35:14.363  6886  6886 W LG Account v2.2: No ProfileInfo entries
08-11 09:35:14.363  6886  6886 I LG Account v2.2: isEnabled: false
08-11 09:35:14.363  6886  6886 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-11 09:35:14.364  6886  6886 I Feature : [Lifetracker]Country: EU
08-11 09:35:14.364  6886  6886 I Feature : [Lifetracker]Operator: OPEN
08-11 09:35:14.364  6886  6886 I Feature : [Lifetracker]Ranking support: false
08-11 09:35:14.364  6886  6886 I Feature : [Lifetracker]Comfort support: false
08-11 09:35:14.364  6886  6886 I Feature : [Lifetracker]Accessory: true
08-11 09:35:14.364  6886  6886 I Feature : [Lifetracker]Health device: true
08-11 09:35:14.364  6886  6886 I Feature : [Lifetracker]Extra Pedometer: false
08-11 09:35:14.364  6886  6886 I Feature : [Lifetracker]Blood glucose device: false
08-11 09:35:14.364  6886  6886 I Feature : [Lifetracker]Device Number: 3
08-11 09:35:14.365  6886  6886 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-11 09:35:14.391  2078  2078 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-11 09:35:14.397  1034  1049 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6908 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-11 09:35:14.398  1034  1049 I ActivityManager: Killing 6231:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-11 09:35:14.403  2078  2078 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-11 09:35:14.403  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-11 09:35:14.405  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-11 09:35:14.424  2078  2078 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25f2876b time:195084
,08-11 09:35:14.451  6843  6843 D AndroidRuntime: Shutting down VM
,08-11 09:35:14.461  1034  2070 W libprocessgroup: failed to open /acct/uid_10014/pid_6231/cgroup.procs: No such file or directory
,08-11 09:35:14.467  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-11 09:35:14.482  6908  6908 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 09:35:14.482  6908  6908 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-11 09:35:14.483  6908  6908 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 09:35:14.483  6908  6908 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-11 09:35:14.484  6908  6908 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 09:35:14.485  6908  6908 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-11 09:35:14.550  2078  2078 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-11 09:35:14.588  2078  2953 I GBoardtInterface: onReloaded()
,08-11 09:35:14.590  2078  2078 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-11 09:35:14.592  3835  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 09:35:14.597  6908  6908 D PackageIntentReceiver: Not supported Hotkey customization function 
08-11 09:35:14.597  3835  3850 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 09:35:14.607  1930  1930 D ActionManagerService: notifyUserLog: 1000001
08-11 09:35:14.608  6908  6908 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-11 09:35:14.609  6908  6908 D HideNavigationAppsReceiver: replacing : false
08-11 09:35:14.609  3835  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-11 09:35:14.609  3835  4477 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-11 09:35:14.612  1930  1930 D ActionManagerService: notifyUserLog: 1000001
08-11 09:35:14.612  6908  6908 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-11 09:35:14.614  3835  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-11 09:35:14.614  3835  4477 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-11 09:35:14.614  3835  4477 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-11 09:35:14.616  3835  4477 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-11 09:35:14.616  6908  6908 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-11 09:35:14.617  6908  6908 D ButtonCombinationReceiver: replacing : false
08-11 09:35:14.620  3835  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 09:35:14.623  1034  2070 I ActivityManager: Killing 6509:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-11 09:35:14.713  1034  2044 W libprocessgroup: failed to open /acct/uid_10008/pid_6509/cgroup.procs: No such file or directory
,08-11 09:35:14.731  2078  2078 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-11 09:35:14.731  2078  2078 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-11 09:35:14.731  4598  6930 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-11 09:35:14.736  2078  2078 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-11 09:35:14.736  2078  2078 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 09:35:14.739  2078  2078 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-11 09:35:14.739  2078  2078 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-11 09:35:14.775  1034  1928 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6931 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 09:35:14.786  1034  1605 V SIM_STK : Menu title from STK is T-Mobile
08-11 09:35:14.803  4598  6930 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
08-11 09:35:14.814  4598  6930 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-11 09:35:14.814  4598  6930 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4598
08-11 09:35:14.814  4598  6930 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at csx.d(PG:186)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at cun.g(PG:594)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at cuy.ub(PG:301)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-11 09:35:14.814  4598  6930 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 09:35:14.824  1034  6952 E DropBoxManagerService: Can't write: system_app_crash
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-11 09:35:14.824  1034  6952 E DropBoxManagerService: 	... 5 more
08-11 09:35:14.825  4598  6930 I Process : Sending signal. PID: 4598 SIG: 9
08-11 09:35:14.841  6931  6931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
,08-11 09:35:14.852  6126  6126 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-11 09:35:14.852  6126  6126 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-11 09:35:14.852  6126  6126 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-11 09:35:14.852  6126  6126 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,08-11 09:35:14.852  6126  6126 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-11 09:35:14.852  6126  6126 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-11 09:35:14.860  1034  1546 D WifiService: Client connection lost with reason: 4
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-11 09:35:14.875  6931  6954 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 09:35:14.875  6931  6954 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-11 09:35:14.875  6931  6954 E AndroidRuntime: Process: com.android.keychain, PID: 6931
08-11 09:35:14.875  6931  6954 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-11 09:35:14.875  6931  6954 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 09:35:14.930  1034  2071 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 4598) has died
08-11 09:35:14.931  1034  2071 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
08-11 09:35:14.931  1034  2071 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
,08-11 09:35:14.940  6656  6656 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.test.thalitest
08-11 09:35:14.942  6931  6954 I Process : Sending signal. PID: 6931 SIG: 9
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: Can't write: system_app_crash
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-11 09:35:14.944  1034  6960 E DropBoxManagerService: 	... 5 more
,08-11 09:35:15.008  1034  1050 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6961 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-11 09:35:15.017   353   353 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 315us total 13.568ms
08-11 09:35:15.030   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 259us total 12.688ms
,08-11 09:35:15.041  1034  2020 I ActivityManager: Process com.android.keychain (pid 6931) has died
08-11 09:35:15.041  1034  2020 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10891ms
,08-11 09:35:15.042   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 226us total 11.557ms
08-11 09:35:15.064  6961  6961 I art     : Almond Protected OAT
,08-11 09:35:15.074  2078  2953 I GBoardtInterface: exportHTML()
08-11 09:35:15.094  6961  6961 D WeatherApplication: removeAccount
,08-11 09:35:15.095  6961  6961 D WeatherApplication: Account.length = 0
08-11 09:35:15.095  6961  6961 E WeatherApplication: OPERATOR:OPEN
08-11 09:35:15.098  6961  6961 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 9:35:15
08-11 09:35:15.100  6961  6961 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-11 09:35:15.100  6961  6961 D Weather.Utils: 2 : All the weather widget is gone.
08-11 09:35:15.101  6961  6961 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-11 09:35:15.103  6961  6961 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-11 09:35:15.103  6961  6961 D Weather.Utils: 2 : All the weather widget is gone.
08-11 09:35:15.103  6961  6961 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 9:35:15
08-11 09:35:15.105  6908  6908 D PackageIntentReceiver: Not supported Hotkey customization function 
08-11 09:35:15.105  2078  2953 I GBoardtInterface: exportHTML()
,08-11 09:35:15.115   349   367 E GBMv2   : DFP En is all cleared set to be enabled
08-11 09:35:15.115   349   367 E GBMv2   : Set value is all cleared set the max
08-11 09:35:15.115   349   367 I GBMv2   : DFP Enabled. Ignore VFP set
08-11 09:35:15.128  2078  2953 I GBoardtInterface: exportHTML()

```
